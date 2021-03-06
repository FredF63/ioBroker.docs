---
translatedFrom: en
translatedWarning: Wenn Sie dieses Dokument bearbeiten möchten, löschen Sie bitte das Feld "translationsFrom". Andernfalls wird dieses Dokument automatisch erneut übersetzt
editLink: https://github.com/ioBroker/ioBroker.docs/edit/master/docs/de/adapterref/iobroker.logparser/README.md
title: ioBroker.logparser
hash: ifv1iQUi4BEJcBOYxOUWRM3ZGbwpOTmRqWNoxbsg+KI=
---
![Logo](../../../en/adapterref/iobroker.logparser/admin/logparser.png)

![NPM-Version](http://img.shields.io/npm/v/iobroker.logparser.svg)
![Downloads](https://img.shields.io/npm/dm/iobroker.logparser.svg)
![Anzahl der Installationen (aktuell)](http://iobroker.live/badges/logparser-installed.svg)
![Anzahl der Installationen (stabil)](http://iobroker.live/badges/logparser-stable.svg)
![Abhängigkeitsstatus](https://img.shields.io/david/Mic-M/iobroker.logparser.svg)
![Bekannte Sicherheitslücken](https://snyk.io/test/github/Mic-M/ioBroker.logparser/badge.svg)
![NPM](https://nodei.co/npm/iobroker.logparser.png?downloads=true)
![Travis-CI](http://img.shields.io/travis/Mic-M/ioBroker.logparser/master.svg)

# IoBroker.logparser
## Log Parser für alle ioBroker-Adapter
Dieser Adapter analysiert (filtert) alle Protokolle von ioBroker-Adaptern und liefert die Ergebnisse als JSON in Status für jeden Filter, wie in den Einstellungen konfiguriert.
Das resultierende JSON kann dann in VIS zur Visualisierung verwendet werden. Es werden auch Zustände zum Leeren (Löschen) alter Protokolle bereitgestellt (wie `logparser.0.filters.Homematic.emptyJson` oder `logparser.0.emptyAllJson`, um alle zu leeren.)

![Zustände](../../../en/adapterref/iobroker.logparser/docs/en/img/states.png)

## Installation
Installieren Sie den Adapter einfach regelmäßig über die ioBroker-Administrationsoberfläche. Der Adapter befindet sich sowohl im neuesten als auch im stabilen Repository.

## Anleitung
Ich habe alle Anweisungen direkt in die Admin-Einstellungen dieses Adapters aufgenommen.

Die meisten dieser Anweisungen können Sie auch hier lesen:

* [** Grundlegende Adapteranweisungen **] (https://github.com/Mic-M/ioBroker.logparser/blob/master/admin/doc-md/start_en.md) - für Deutsch [hier klicken (Deutsch) ] (https://github.com/Mic-M/ioBroker.logparser/blob/master/admin/doc-md/start_de.md)
* [** Parser-Regeln (Filter) **] (https://github.com/Mic-M/ioBroker.logparser/blob/master/admin/doc-md/table-parser-rules_en.md) - für Deutsch [hier klicken (Deutsch)] (https://github.com/Mic-M/ioBroker.logparser/blob/master/admin/doc-md/table-parser-rules_de.md)
* [** Globale Blacklist **] (https://github.com/Mic-M/ioBroker.logparser/blob/master/admin/doc-md/table-global-blacklist_en.md) - für Deutsch [hier klicken (Deutsch)] (https://github.com/Mic-M/ioBroker.logparser/blob/master/admin/doc-md/table-global-blacklist_de.md)

## Visualisierungsbeispiel (animiertes GIF)
![Vis](../../../en/adapterref/iobroker.logparser/docs/de/img/visintro.gif)

## Screenshots der Adapteroptionen
Bitte beachten Sie, dass diese Screenshots eine Momentaufnahme sind und nicht die neuesten Adapteroptionen widerspiegeln.
Dies dient nur dazu, Ihnen einen Überblick über die Adapteroptionen zu geben.

![Parser-Optionen protokollieren](../../../en/adapterref/iobroker.logparser/admin/img/option-screenshots/tab-start.png)

![Parser-Optionen protokollieren](../../../en/adapterref/iobroker.logparser/admin/img/option-screenshots/tab-parser-rules.png)

![Parser-Optionen protokollieren](../../../en/adapterref/iobroker.logparser/admin/img/option-screenshots/tab-further-settings.png)

![Parser-Optionen protokollieren](../../../en/adapterref/iobroker.logparser/admin/img/option-screenshots/tab-vis.png)

![Parser-Optionen protokollieren](../../../en/adapterref/iobroker.logparser/admin/img/option-screenshots/tab-global-blacklist.png)

![Parser-Optionen protokollieren](../../../en/adapterref/iobroker.logparser/admin/img/option-screenshots/tab-expert-settings.png)

## Links und Ressourcen
* [** Link zum Log Parser ioBroker-Forum (Begrüßungsseite) **] (https://forum.iobroker.net/topic/37793/log-parser-adapter-splash-page)

## Anmerkungen
* Dieser Adapter verwendet Sentry-Bibliotheken, um Ausnahmen und Codefehler automatisch anonym an die Adapterentwickler zu melden. Weitere Details und Informationen zum Deaktivieren dieser Fehlerberichterstattung finden Sie unter [Sentry-Plugin-Dokumentation] (https://github.com/ioBroker/plugin-sentry#plugin-sentry). Sentry Reporting wird ab js-controller 3.0 verwendet.

## Changelog

### 1.1.0
* (Mic-M) Fixed issue [#15](https://github.com/Mic-M/ioBroker.logparser/issues/15) regarding regex for tab "Parser Rules", column "Blacklist"
* (Mic-M) Enhancement [#16](https://github.com/Mic-M/ioBroker.logparser/issues/16) - add specific CSS classes to any element of the JSON log per adapter option.
* (Mic-M) Major improvement: Implemented entire documentation into adapter itself to significantly improve usability.
* (Mic-M) A few improvements under the hood.


### 1.0.4
* (Mic-M) Fixed 'Today/Yesterday' updating issue - https://forum.iobroker.net/post/469757. Thanks to (Kuddel) for reporting and (Glasfaser) for further debugging.

### 1.0.3
* (Mic-M) Added [Sentry](https://github.com/ioBroker/plugin-sentry)

### 1.0.2
* (Mic-M) Added debug logging for callAtMidnight() and updateTodayYesterday()

### 1.0.1
* (Mic-M) Updated lodash dependency from 4.17.15 to 4.17.19

### 1.0.0
* (Mic-M) No changes - just prepare versioning to add adapter to stable repository per [Adapter dev docu](https://github.com/ioBroker/ioBroker.docs/blob/master/docs/en/dev/adapterdev.md#versioning)

### 0.4.11
* (Mic-M) Adapter is now in latest repository.
* (Mic-M) Removed unused adapter features 'extra tab' and 'custom state options'
* (Mic-M) Removed unused subscription to object changes

### 0.4.10
* (Mic-M) Fixed reference to 'visualization.table' for adapter instances other than instance 0.
* (Mic-M) Cleanup code.

### 0.4.9
* (Mic-M) Add option to remove script.js.Script_Name, update documentation

### 0.4.8
* (Mic-M) Fixed npm issue

### 0.4.7
* (Mic-M) Fixed translations, disabled 'supportCustoms', improved admin settings

### 0.4.6
* (Mic-M) Added error handling for invalid regex provided by user
* (Mic-M) A few other fixes/improvements under the hood

### 0.4.5
* (Mic-M) Fixed issue with merge option and other filter settings by now cloning input logObject prior to handling
* (Mic-M) Allow wildcard * for 'Whitelist AND' and 'Whitelist OR' to indicate matching all

### 0.4.4
* (Mic-M) Translations added, adapter instructions added, optimized admin interface

### 0.4.3
* (Mic-M) Fix multiple regex/string config values separated by comma

### 0.4.2
* (Mic-M) Fix issue #12 ('state is missing the required property val')
* (Mic-M) Fix issue with visualization.tableX.json and .selection. See https://forum.iobroker.net/post/408513

### 0.4.1
* (Mic-M) Fix 'Yesterday' for date, 2. Fix multiple filters, 3. Add description to settings page

### 0.4.0
* (Mic-M) Add new option "maxLength" to limit the length of each log message

### 0.3.0
* (Mic-M) initial public release

## License
MIT License

Copyright (c) 2020 Mic-M

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.