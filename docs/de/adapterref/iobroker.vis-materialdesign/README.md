---
translatedFrom: en
translatedWarning: Wenn Sie dieses Dokument bearbeiten möchten, löschen Sie bitte das Feld "translationsFrom". Andernfalls wird dieses Dokument automatisch erneut übersetzt
editLink: https://github.com/ioBroker/ioBroker.docs/edit/master/docs/de/adapterref/iobroker.vis-materialdesign/README.md
title: Material Design Widgets für ioBroker VIS
hash: STkC4jUrj13PgxyXCjHtZZL44zY9Atc892hDUI3Tx/M=
---
![Logo](../../../en/adapterref/iobroker.vis-materialdesign/admin/vis-materialdesign.png) <! - in toc weglassen ->

![stabile Version](http://iobroker.live/badges/vis-materialdesign.svg)
![NPM-Version](http://img.shields.io/npm/v/iobroker.vis-materialdesign.svg)
![Anzahl der Installationen](http://iobroker.live/badges/vis-materialdesign-installed.svg)
![Downloads](https://img.shields.io/npm/dm/iobroker.vis-materialdesign.svg)
![NPM](https://nodei.co/npm/iobroker.vis-materialdesign.png?downloads=true)

## IoBroker.vis-materialdesign
<! - in toc weglassen ->

# Material Design Widgets für ioBroker VIS [![paypal] (https://www.paypalobjects.com/en_US/i/btn/btn_donateCC_LG.gif)](https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=VWAXSTS634G88&source=url)
ioBroker Material Design Widgets basieren auf [Richtlinien für das Materialdesign von Google](https://material.io/design/)

<br>

<! - in toc weglassen ->

## Inhaltsverzeichnis
- [Allgemein] (# Allgemein)
- [Online-Beispielprojekt] (# Online-Beispielprojekt)
- [Praktische Beispiele] (# praktische Beispiele)
- [Fragen und Antworten zu den Widgets] (# Fragen und Antworten zu den Widgets)
- [Unterstützter Browser] (# unterstützter Browser)
- [Unterstützte Browser-Funktion zum Vibrieren auf Mobilgeräten] (# Unterstützte Browser-Funktion zum Vibrieren auf Mobilgeräten)
- [ioBroker VIS App] (# iobroker-vis-app)
- [Adaptereinstellungen] (# Adaptereinstellungen)
- [Allgemein] (# allgemein-1)
- [Theme Editor] (# Theme-Editor)
- [Farbthema] (# Farben-Thema)
- [Schriftarten-Thema] (# Schriftarten-Thema)
- [Schriftgrößen-Thema] (# Schriftgrößen-Thema)
- [Widgets] (# Widgets)
- [Material Design Icons und Bilder] (# Material Design Icons und Bilder)
- [Tasten] (# Tasten)
- [Schaltflächen vertikal] (# Schaltflächen-vertikal)
- [Buttons Icon] (# Buttons-Icon)
- [Karte] (# Karte)
- [Liste] (# Liste)
- [IconList] (# iconlist)
- [Editoreinstellungen] (# Editoreinstellungen)
- [JSON-Eigenschaften] (# json-properties)
- [Fortschritt] (# Fortschritt)
- [Fortschrittsrundschreiben] (# Fortschrittsrundschreiben)
- [Slider] (# Slider)
- [Slider-Runde] (# Slider-Runde)
- [Checkbox] (# Checkbox)
- [Schalter] (# Schalter)
- [Eingabe] (# Eingabe)
- [Texteingabe] (# Texteingabe)
- [Auswählen] (# Auswählen)
- [Autocomplete] (# Autocomplete)
- [Top App Bar] (# Top-App-Leiste)
- [Untermenü] (# Untermenü)
- [JSON-Eigenschaften] (# json-properties-1)
- [Charts] (# Charts)
- [Balkendiagramm] (# Balkendiagramm)
- [Editoreinstellungen] (# editor-settings-1)
- [JSON-Eigenschaften] (# json-properties-2)
- [Kreisdiagramm] (# Kreisdiagramm)
- [Editoreinstellungen] (# editor-settings-2)
- [JSON-Eigenschaften] (# json-properties-3)
- [Linienverlaufsdiagramm:] (# Linienverlaufsdiagramm)
- [Editoreinstellungen] (# editor-settings-3)
- [JSON-Diagramm] (# json-Diagramm)
- [JSON-Eigenschaften] (# json-properties-4)
- [Tabelle] (# Tabelle)
- [Eingabedaten] (# Eingabedaten)
- [Steuerelemente] (# Steuerelemente)
- [Editoreinstellungen] (# editor-settings-4)
- [Responsive Layout] (# Responsive-Layout)
- [Mauerwerksansichten] (# Mauerwerksansichten)
- [Rasteransichten] (# Rasteransichten)
- [Warnungen] (# Warnungen)
- [Kalender] (# Kalender)
- [HTML-Elemente] (# HTML-Elemente)
- [gebrauchte Bibliotheken] (# gebrauchte Bibliotheken)
- [Changelog] (# changelog)
- [Lizenz] (# Lizenz)

# Allgemeines
## Online-Beispielprojekt
bereitgestellt von [iobroker.click](https://iobroker.click/index.html), dank bluefox und iobroker.

* <a href="https://iobroker.click/vis/index.html?Material%20Design%20Widgets" target="_blank">VIS Runtime</a> ( <a href="http://iobroker.click:8082/vis/index.html?Material%20Design%20Widgets" target="_blank">alternativ</a> )
* <a href="https://iobroker.click/vis/edit.html?Material%20Design%20Widgets" target="_blank">VIS Editor</a> ( <a href="http://iobroker.click:8082/vis/edit.html?Material%20Design%20Widgets" target="_blank">alternativ</a> )

## Praktische Beispiele
* [Wetteransicht] (https://forum.iobroker.net/topic/32232/material-design-widgets-wetter-view)
* [Skriptstatus] (https://forum.iobroker.net/topic/30662/material-design-widgets-skript-status)
* [Adapterstatus] (https://forum.iobroker.net/topic/30661/material-design-widgets-adapter-status)
* [UniFi-Netzwerkstatus] (https://github.com/Scrounger/ioBroker.vis-materialdesign/tree/master/examples/UnifiNetworkState)

## Fragen und Antworten zu den Widgets
Wenn Sie Fragen zu den einzelnen Widgets haben, schauen Sie sich zunächst die Themen der einzelnen Widgets an

* [Deutsche Threads] (https://forum.iobroker.net/search?term=Material%20Design%20Widgets%3A&in=titles&matchWords=all&by%5B%5D=Scrounger&categories%5B%5D=7&sortBy=topic.title=s& Themen)

## Unterstützter Browser
Ich unterstütze offiziell die letzten beiden Versionen aller gängigen Browser. Insbesondere teste ich auf den folgenden Browsern:

* Firefox unter Windows und Linux
* Chrome unter Android, Windows und Linux

## Unterstützter Browser zum Vibrieren auf Mobilgeräten
https://developer.mozilla.org/en-US/docs/Web/API/Navigator/vibrate

## IoBroker VIS App
Die neueste Version muss von der App implementiert werden (siehe https://github.com/ioBroker/ioBroker.vis.cordova).
Ich benutze die App nicht und teste sie auch nicht

# Adaptereinstellungen
Ab Version 0.4.0 gibt es eine Einstellungsseite für den Adapter. Sie finden es unter Instanzen in der Benutzeroberfläche des Admin-Adapters

## Allgemeines
![Logo](../../../en/adapterref/iobroker.vis-materialdesign/doc/en/media/settings_general.png)

| Einstellung | Beschreibung |
| ---------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Dokumentation | Links zur Dokumentation zur Konfiguration der Widgets |
| Globales Skript generieren | Erstellen Sie ein globales Skript für die [Javascript Script Engine](https://github.com/ioBroker/ioBroker.javascript) mit allen Themendatenpunkten. Dies ermöglicht die bequeme Verwendung von Farben, Schriftarten und Schriftgrößen in Skripten. |
| Wachposten | Verwenden Sie Sentry-Bibliotheken, um Ausnahmen und Codefehler automatisch anonym an die Entwickler zu melden. Weitere Details und Informationen zum Deaktivieren der Fehlerberichterstattung finden Sie unter [Sentry-Plugin-Dokumentation] (https://github.com/ioBroker/plugin-sentry#plugin-sentry)! |

## Themeneditor
Mit Hilfe des Design-Editors können Sie Farben, Schriftarten und Schriftgrößen für alle Widgets über die Adaptereinstellungen zentral einstellen. Dies wird mit Hilfe der [Bindungen des VIS-Adapters](https://github.com/ioBroker/ioBroker.vis#bindings-of-objects) realisiert. Für jedes Widget werden Datenpunkte (siehe Abbildung unten) mit den festgelegten Werten erstellt. Dies ermöglicht die Verwendung dieser Einstellungen in anderen Widgets (nicht Material Design Widgets) über Bindungen.

##### Datenpunktstruktur
![Logo](../../../en/adapterref/iobroker.vis-materialdesign/doc/en/media/settings_datapoints.png)

##### VIS Editor (Alte Widgets wiederherstellen / aktualisieren)
![Logo](../../../en/adapterref/iobroker.vis-materialdesign/doc/en/media/vis_editor_theme_restore.gif)

Im VIS-Editor finden Sie für jedes Widget eine Schaltfläche `use theme`. Mit dieser Schaltfläche können Sie die Widgets auf die Verwendung der Themen zurücksetzen. Das heißt, wenn Sie Farben, Schriftarten oder Schriftgrößen geändert haben, können Sie diese mit dieser Schaltfläche zurücksetzen.

Mit Hilfe dieser Schaltfläche ist es auch möglich, Ihre Widgets von Versionen vor 0.4.0 zu aktualisieren, um die Themen zu verwenden.

##### Bindung für Nicht-Material-Design-Widgets verwenden
![Logo](../../../en/adapterref/iobroker.vis-materialdesign/doc/en/media/settings_binding.gif)

In den Adaptereinstellungen können Sie den Bindungsbefehl in die Zwischenablage kopieren, indem Sie auf den Standardtext oder die ID in den Tabellen klicken. Diese Bindung kann dann auch für Nicht-Material-Design-Widgets durch Kopieren und Einfügen verwendet werden.

### Farbthema
Für Farben gibt es zwei Themen - helles Thema und dunkles Thema. Mit dem Datenpunkt `vis-materialdesign.0.colors.darkTheme` können Sie zwischen den beiden Themen wechseln.

![Logo](../../../en/adapterref/iobroker.vis-materialdesign/doc/en/media/settings_colors_light.png)

![Logo](../../../en/adapterref/iobroker.vis-materialdesign/doc/en/media/settings_colors_dark.png)

Im oberen Bereich können Standardfarben definiert werden. Diese Standardfarben können dann über die Schaltflächen in der Tabelle den einzelnen Widgets zugewiesen werden. Wenn Sie die Standardfarbe ändern, ändert sich dies auch für alle Widgets, die diese Farbe verwenden.
Darüber hinaus ist es möglich, den Widgets unabhängig von den Standardfarben eigene Farben zuzuweisen.

### Schriftart-Thema
![Logo](../../../en/adapterref/iobroker.vis-materialdesign/doc/en/media/settings_fonts.png)

Standardschriftarten können im oberen Bereich definiert werden. Diese Standardschriftarten können dann über die Schaltflächen in der Tabelle den einzelnen Widgets zugewiesen werden. Wenn Sie die Standardfarbe ändern, ändert sich dies auch für alle Widgets, die diese Farbe verwenden.
Darüber hinaus können Sie den Widgets unabhängig von den Standardfarben eigene Schriftarten zuweisen.

### Schriftgrößen-Thema
![Logo](../../../en/adapterref/iobroker.vis-materialdesign/doc/en/media/settings_fontSizes.png)

Standardschriftgrößen können im oberen Bereich definiert werden. Diese Standardschriftgrößen können dann über die Schaltflächen in der Tabelle den einzelnen Widgets zugewiesen werden. Wenn Sie die Standardfarbe ändern, ändert sich dies auch für alle Widgets, die diese Farbe verwenden.
Darüber hinaus können Sie den Widgets unabhängig von den Standardfarben Ihre eigenen Schriftgrößen zuweisen.

# Widgets
## Material Design Icons und Bilder
<table><thead><tr><th>Bildschirmfoto</th><th> Beschreibung</th></tr></thead><tbody><tr><td rowspan=6><img src="doc/en/media/material-icons.png"></td><td> Einige der Widgets unterstützen die <a href="https://materialdesignicons.com/" target="_blank">Material Design Icons-</a> Bibliothek. Sie können ein Symbol aus der obigen Liste auswählen oder die Bildauswahl öffnen, indem Sie auf die Schaltfläche rechts neben dem Eingabefeld klicken.<br><br> <b>Bildfarben gelten nur für die Materialdesignsymbole, nicht für ein Bild!</b></td></tr></tbody></table>

## Tasten
##### Eigenschaften der Schaltflächenverknüpfung
Die folgenden Eigenschaften können als [Steuerelement in einer Tabelle] (# Steuerelemente) oder als [HTML-Element](#html-elements) verwendet werden

<details><table><thead><tr><th>Eigentum</th><th> Beschreibung</th><th> Art</th><th> Werte</th></tr></thead><tbody><tr><td> Art</td><td> Widget-Typ</td><td> Zeichenfolge</td><td> link_default</td></tr><tr><td> debuggen</td><td> Debug-Modus</td><td> Boolescher Wert</td><td> false | wahr</td></tr><tr><td colspan="4" style="background: #44739e; color: white; border-color: #44739e;"> <i><b>Verbreitet</b></i></td></tr><tr><td> buttonStyle</td><td> Tastenstil</td><td> Zeichenfolge</td><td> Text | angehoben | nicht erhöht | umrissen</tr><tr><td> href</td><td> Verknüpfung</td><td> URL</td><td></tr><tr><td> openNewWindow</td><td> in neuem Fenster öffnen</td><td> Boolescher Wert</td><td> false | wahr</tr><tr><td> vibrateOnMobilDevices</td><td> vibrieren auf mobilen Geräten [s]</td><td> Nummer</td><td></tr><tr><td> generateHtmlControl</td><td> HTML-Element generieren</td><td> Zeichenfolge</td><td></tr><tr><td colspan="4" style="background: #44739e; color: white; border-color: #44739e;"><i><b>Beschriftung</b></i></td></tr><tr><td> Schaltflächentext</td><td> Schaltflächentext</td><td> Zeichenfolge</td><td></tr><tr><td> textFontFamily</td><td> Schriftart</td><td> Zeichenfolge</td><td></tr><tr><td> textFontSize</td><td> Textgröße</td><td> Nummer</td><td></tr><tr><td> labelWidth</td><td> Textbreite</td><td> Nummer</td><td></tr><tr><td colspan="4" style="background: #44739e; color: white; border-color: #44739e;"><i><b>Farben</b></i></td></tr><tr><td> mdwButtonPrimaryColor</td><td> Primärfarbe</td><td> Zeichenfolge</td><td> hex (# 44739e), rgb (20, 50, 200), rgba (20, 50, 200, 0,5)</tr><tr><td> mdwButtonSecondaryColor</td><td> sekundäre Farbe</td><td> Zeichenfolge</td><td> hex (# 44739e), rgb (20, 50, 200), rgba (20, 50, 200, 0,5)</tr><tr><td> mdwButtonColorPress</td><td> Farbe gedrückt</td><td> Zeichenfolge</td><td> hex (# 44739e), rgb (20, 50, 200), rgba (20, 50, 200, 0,5)</tr><tr><td colspan="4" style="background: #44739e; color: white; border-color: #44739e;"> <i><b>Symbol</b></i></td></tr><tr><td> Bild</td><td> Bild</td><td> Zeichenfolge</td><td></tr><tr><td> imageColor</td><td> Bildfarbe</td><td> Zeichenfolge</td><td> hex (# 44739e), rgb (20, 50, 200), rgba (20, 50, 200, 0,5)</tr><tr><td> iconPosition</td><td> Bildposition</td><td> Zeichenfolge</td><td> links | Recht</tr><tr><td> iconHeight</td><td> Bildhöhe</td><td> Nummer</td><td></tr></tbody></table></details>

##### Eigenschaften des Schaltflächenstatus
Die folgenden Eigenschaften können als [Steuerelement in einer Tabelle] (# Steuerelemente) oder als [HTML-Element](#html-elements) verwendet werden

<details><table><thead><tr><th>Eigentum</th><th> Beschreibung</th><th> Art</th><th> Werte</th></tr></thead><tbody><tr><td> Art</td><td> Widget-Typ</td><td> Zeichenfolge</td><td> state_default</td></tr><tr><td> debuggen</td><td> Debug-Modus</td><td> Boolescher Wert</td><td> false | wahr</td></tr><tr><td colspan="4" style="background: #44739e; color: white; border-color: #44739e;"> <i><b>Verbreitet</b></i></td></tr><tr><td> oid</td><td> Objekt Identifikation</td><td> Zeichenfolge</td><td></tr><tr><td> buttonStyle</td><td> Tastenstil</td><td> Zeichenfolge</td><td> Text | angehoben | nicht erhöht | umrissen</tr><tr><td> Wert</td><td> Wert</td><td> Zeichenfolge</td><td></tr><tr><td> vibrateOnMobilDevices</td><td> vibrieren auf mobilen Geräten [s]</td><td> Nummer</td><td></tr><tr><td> generateHtmlControl</td><td> HTML-Element generieren</td><td> Zeichenfolge</td><td></tr><tr><td colspan="4" style="background: #44739e; color: white; border-color: #44739e;"><i><b>Beschriftung</b></i></td></tr><tr><td> Schaltflächentext</td><td> Schaltflächentext</td><td> Zeichenfolge</td><td></tr><tr><td> textFontFamily</td><td> Schriftart</td><td> Zeichenfolge</td><td></tr><tr><td> textFontSize</td><td> Textgröße</td><td> Nummer</td><td></tr><tr><td> labelWidth</td><td> Textbreite</td><td> Nummer</td><td></tr><tr><td colspan="4" style="background: #44739e; color: white; border-color: #44739e;"><i><b>Farben</b></i></td></tr><tr><td> mdwButtonPrimaryColor</td><td> Primärfarbe</td><td> Zeichenfolge</td><td> hex (# 44739e), rgb (20, 50, 200), rgba (20, 50, 200, 0,5)</tr><tr><td> mdwButtonSecondaryColor</td><td> sekundäre Farbe</td><td> Zeichenfolge</td><td> hex (# 44739e), rgb (20, 50, 200), rgba (20, 50, 200, 0,5)</tr><tr><td> mdwButtonColorPress</td><td> Farbe gedrückt</td><td> Zeichenfolge</td><td> hex (# 44739e), rgb (20, 50, 200), rgba (20, 50, 200, 0,5)</tr><tr><td colspan="4" style="background: #44739e; color: white; border-color: #44739e;"> <i><b>Symbol</b></i></td></tr><tr><td> Bild</td><td> Bild</td><td> Zeichenfolge</td><td></tr><tr><td> imageColor</td><td> Bildfarbe</td><td> Zeichenfolge</td><td> hex (# 44739e), rgb (20, 50, 200), rgba (20, 50, 200, 0,5)</tr><tr><td> iconPosition</td><td> Bildposition</td><td> Zeichenfolge</td><td> links | Recht</tr><tr><td> iconHeight</td><td> Bildhöhe</td><td> Nummer</td><td></tr><tr><td colspan="4" style="background: #44739e; color: white; border-color: #44739e;"><i><b>Verriegeln</b></i></td></tr><tr><td> lockEnabled</td><td> Sperren aktivieren</td><td> Boolescher Wert</td><td> false | wahr</tr><tr><td> autoLockAfter</td><td> automatische Sperre nach [s]</td><td> Nummer</td><td></tr><tr><td> lockIcon</td><td> Symbol</td><td> Zeichenfolge</td><td></tr><tr><td> lockIconSize</td><td> Symbolgröße</td><td> Nummer</td><td></tr><tr><td> lockIconColor</td><td> Symbolfarbe</td><td> Zeichenfolge</td><td> hex (# 44739e), rgb (20, 50, 200), rgba (20, 50, 200, 0,5)</tr><tr><td> lockFilterGrayscale</td><td> Graufilter, wenn gesperrt</td><td> Nummer</td><td></tr></tbody></table></details>

##### Schaltfläche Eigenschaften umschalten
Die folgenden Eigenschaften können als [Steuerelement in einer Tabelle] (# Steuerelemente) oder als [HTML-Element](#html-elements) verwendet werden

<details><table><thead><tr><th>Eigentum</th><th> Beschreibung</th><th> Art</th><th> Werte</th></tr></thead><tbody><tr><td> Art</td><td> Widget-Typ</td><td> Zeichenfolge</td><td> toggle_default</td></tr><tr><td> debuggen</td><td> Debug-Modus</td><td> Boolescher Wert</td><td> false | wahr</td></tr><tr><td colspan="4" style="background: #44739e; color: white; border-color: #44739e;"> <i><b>Verbreitet</b></i></td></tr><tr><td> oid</td><td> Objekt Identifikation</td><td> Zeichenfolge</td><td></tr><tr><td> buttonStyle</td><td> Tastenstil</td><td> Zeichenfolge</td><td> Text | angehoben | nicht erhöht | umrissen</tr><tr><td> schreibgeschützt</td><td> schreibgeschützt</td><td> Boolescher Wert</td><td> false | wahr</tr><tr><td> toggleType</td><td> Art des Umschalters</td><td> Zeichenfolge</td><td> boolean | Wert</tr><tr><td> Druckknopf</td><td> Druckknopf</td><td> Boolescher Wert</td><td> false | wahr</tr><tr><td> valueOff</td><td> Wert für aus</td><td> Zeichenfolge</td><td></tr><tr><td> valueOn</td><td> Wert für auf</td><td> Zeichenfolge</td><td></tr><tr><td> stateIfNotTrueValue</td><td> Geben Sie an, ob der Wert nicht der Bedingung &quot;Ein&quot; entspricht</td><td> Zeichenfolge</td><td> am | aus</tr><tr><td> vibrateOnMobilDevices</td><td> vibrieren auf mobilen Geräten [s]</td><td> Nummer</td><td></tr><tr><td> generateHtmlControl</td><td> HTML-Element generieren</td><td> Zeichenfolge</td><td></tr><tr><td colspan="4" style="background: #44739e; color: white; border-color: #44739e;"><i><b>Beschriftung</b></i></td></tr><tr><td> Schaltflächentext</td><td> Schaltflächentext</td><td> Zeichenfolge</td><td></tr><tr><td> labelTrue</td><td> Beschriften Sie true</td><td> Zeichenfolge</td><td></tr><tr><td> labelColorFalse</td><td> Etikettenfarbe</td><td> Zeichenfolge</td><td> hex (# 44739e), rgb (20, 50, 200), rgba (20, 50, 200, 0,5)</tr><tr><td> labelColorTrue</td><td> aktive Etikettenfarbe</td><td> Zeichenfolge</td><td> hex (# 44739e), rgb (20, 50, 200), rgba (20, 50, 200, 0,5)</tr><tr><td> textFontFamily</td><td> Schriftart</td><td> Zeichenfolge</td><td></tr><tr><td> textFontSize</td><td> Textgröße</td><td> Nummer</td><td></tr><tr><td> labelWidth</td><td> Textbreite</td><td> Nummer</td><td></tr><tr><td colspan="4" style="background: #44739e; color: white; border-color: #44739e;"><i><b>Farben</b></i></td></tr><tr><td> mdwButtonPrimaryColor</td><td> Primärfarbe</td><td> Zeichenfolge</td><td> hex (# 44739e), rgb (20, 50, 200), rgba (20, 50, 200, 0,5)</tr><tr><td> mdwButtonSecondaryColor</td><td> sekundäre Farbe</td><td> Zeichenfolge</td><td> hex (# 44739e), rgb (20, 50, 200), rgba (20, 50, 200, 0,5)</tr><tr><td> mdwButtonColorPress</td><td> Farbe gedrückt</td><td> Zeichenfolge</td><td> hex (# 44739e), rgb (20, 50, 200), rgba (20, 50, 200, 0,5)</tr><tr><td> colorBgFalse</td><td> Hintergrund</td><td> Zeichenfolge</td><td> hex (# 44739e), rgb (20, 50, 200), rgba (20, 50, 200, 0,5)</tr><tr><td> colorBgTrue</td><td> aktiver Hintergrund</td><td> Zeichenfolge</td><td> hex (# 44739e), rgb (20, 50, 200), rgba (20, 50, 200, 0,5)</tr><tr><td colspan="4" style="background: #44739e; color: white; border-color: #44739e;"> <i><b>Symbol</b></i></td></tr><tr><td> Bild</td><td> Bild</td><td> Zeichenfolge</td><td></tr><tr><td> imageColor</td><td> Bildfarbe</td><td> Zeichenfolge</td><td> hex (# 44739e), rgb (20, 50, 200), rgba (20, 50, 200, 0,5)</tr><tr><td> imageTrue</td><td> aktives Bild</td><td> Zeichenfolge</td><td></tr><tr><td> imageTrueColor</td><td> aktive Bildfarbe</td><td> Zeichenfolge</td><td> hex (# 44739e), rgb (20, 50, 200), rgba (20, 50, 200, 0,5)</tr><tr><td> iconPosition</td><td> Bildposition</td><td> Zeichenfolge</td><td> links | Recht</tr><tr><td> iconHeight</td><td> Bildhöhe</td><td> Nummer</td><td></tr><tr><td colspan="4" style="background: #44739e; color: white; border-color: #44739e;"><i><b>Verriegeln</b></i></td></tr><tr><td> lockEnabled</td><td> Sperren aktivieren</td><td> Boolescher Wert</td><td> false | wahr</tr><tr><td> autoLockAfter</td><td> automatische Sperre nach [s]</td><td> Nummer</td><td></tr><tr><td> lockIcon</td><td> Symbol</td><td> Zeichenfolge</td><td></tr><tr><td> lockIconSize</td><td> Symbolgröße</td><td> Nummer</td><td></tr><tr><td> lockIconColor</td><td> Symbolfarbe</td><td> Zeichenfolge</td><td> hex (# 44739e), rgb (20, 50, 200), rgba (20, 50, 200, 0,5)</tr><tr><td> lockFilterGrayscale</td><td> Graufilter, wenn gesperrt</td><td> Nummer</td><td></tr></tbody></table></details>

## Schaltflächen vertikal
![Logo](../../../en/adapterref/iobroker.vis-materialdesign/doc/en/media/buttons.gif)

##### Schaltfläche Vertikale Verknüpfungseigenschaften
Die folgenden Eigenschaften können als [Steuerelement in einer Tabelle] (# Steuerelemente) oder als [HTML-Element](#html-elements) verwendet werden

<details><table><thead><tr><th>Eigentum</th><th> Beschreibung</th><th> Art</th><th> Werte</th></tr></thead><tbody><tr><td> Art</td><td> Widget-Typ</td><td> Zeichenfolge</td><td> link_vertical</td></tr><tr><td> debuggen</td><td> Debug-Modus</td><td> Boolescher Wert</td><td> false | wahr</td></tr><tr><td colspan="4" style="background: #44739e; color: white; border-color: #44739e;"> <i><b>Verbreitet</b></i></td></tr><tr><td> buttonStyle</td><td> Tastenstil</td><td> Zeichenfolge</td><td> Text | angehoben | nicht erhöht | umrissen</tr><tr><td> href</td><td> Verknüpfung</td><td> URL</td><td></tr><tr><td> openNewWindow</td><td> in neuem Fenster öffnen</td><td> Boolescher Wert</td><td> false | wahr</tr><tr><td> vibrateOnMobilDevices</td><td> vibrieren auf mobilen Geräten [s]</td><td> Nummer</td><td></tr><tr><td> generateHtmlControl</td><td> HTML-Element generieren</td><td> Zeichenfolge</td><td></tr><tr><td colspan="4" style="background: #44739e; color: white; border-color: #44739e;"><i><b>Beschriftung</b></i></td></tr><tr><td> Schaltflächentext</td><td> Schaltflächentext</td><td> Zeichenfolge</td><td></tr><tr><td> textFontFamily</td><td> Schriftart</td><td> Zeichenfolge</td><td></tr><tr><td> textFontSize</td><td> Textgröße</td><td> Nummer</td><td></tr><tr><td> Ausrichtung</td><td> Ausrichtung</td><td> Zeichenfolge</td><td> Flex-Start | Mitte | Flex-End</tr><tr><td> distanceBetweenTextAndImage</td><td> Abstand zwischen Text und Bild</td><td> Nummer</td><td></tr><tr><td colspan="4" style="background: #44739e; color: white; border-color: #44739e;"><i><b>Farben</b></i></td></tr><tr><td> mdwButtonPrimaryColor</td><td> Primärfarbe</td><td> Zeichenfolge</td><td> hex (# 44739e), rgb (20, 50, 200), rgba (20, 50, 200, 0,5)</tr><tr><td> mdwButtonSecondaryColor</td><td> sekundäre Farbe</td><td> Zeichenfolge</td><td> hex (# 44739e), rgb (20, 50, 200), rgba (20, 50, 200, 0,5)</tr><tr><td> mdwButtonColorPress</td><td> Farbe gedrückt</td><td> Zeichenfolge</td><td> hex (# 44739e), rgb (20, 50, 200), rgba (20, 50, 200, 0,5)</tr><tr><td colspan="4" style="background: #44739e; color: white; border-color: #44739e;"> <i><b>Symbol</b></i></td></tr><tr><td> Bild</td><td> Bild</td><td> Zeichenfolge</td><td></tr><tr><td> imageColor</td><td> Bildfarbe</td><td> Zeichenfolge</td><td> hex (# 44739e), rgb (20, 50, 200), rgba (20, 50, 200, 0,5)</tr><tr><td> iconPosition</td><td> Bildposition</td><td> Zeichenfolge</td><td> Nach oben | Unterseite</tr><tr><td> iconHeight</td><td> Bildhöhe</td><td> Nummer</td><td></tr></tbody></table></details>

##### Eigenschaften des vertikalen Status der Schaltfläche
Die folgenden Eigenschaften können als [Steuerelement in einer Tabelle] (# Steuerelemente) oder als [HTML-Element](#html-elements) verwendet werden

<details><table><thead><tr><th>Eigentum</th><th> Beschreibung</th><th> Art</th><th> Werte</th></tr></thead><tbody><tr><td> Art</td><td> Widget-Typ</td><td> Zeichenfolge</td><td> state_vertical</td></tr><tr><td> debuggen</td><td> Debug-Modus</td><td> Boolescher Wert</td><td> false | wahr</td></tr><tr><td colspan="4" style="background: #44739e; color: white; border-color: #44739e;"> <i><b>Verbreitet</b></i></td></tr><tr><td> oid</td><td> Objekt Identifikation</td><td> Zeichenfolge</td><td></tr><tr><td> buttonStyle</td><td> Tastenstil</td><td> Zeichenfolge</td><td> Text | angehoben | nicht erhöht | umrissen</tr><tr><td> Wert</td><td> Wert</td><td> Zeichenfolge</td><td></tr><tr><td> vibrateOnMobilDevices</td><td> vibrieren auf mobilen Geräten [s]</td><td> Nummer</td><td></tr><tr><td> generateHtmlControl</td><td> HTML-Element generieren</td><td> Zeichenfolge</td><td></tr><tr><td colspan="4" style="background: #44739e; color: white; border-color: #44739e;"><i><b>Beschriftung</b></i></td></tr><tr><td> Schaltflächentext</td><td> Schaltflächentext</td><td> Zeichenfolge</td><td></tr><tr><td> textFontFamily</td><td> Schriftart</td><td> Zeichenfolge</td><td></tr><tr><td> textFontSize</td><td> Textgröße</td><td> Nummer</td><td></tr><tr><td> Ausrichtung</td><td> Ausrichtung</td><td> Zeichenfolge</td><td> Flex-Start | Mitte | Flex-End</tr><tr><td> distanceBetweenTextAndImage</td><td> Abstand zwischen Text und Bild</td><td> Nummer</td><td></tr><tr><td colspan="4" style="background: #44739e; color: white; border-color: #44739e;"><i><b>Farben</b></i></td></tr><tr><td> mdwButtonPrimaryColor</td><td> Primärfarbe</td><td> Zeichenfolge</td><td> hex (# 44739e), rgb (20, 50, 200), rgba (20, 50, 200, 0,5)</tr><tr><td> mdwButtonSecondaryColor</td><td> sekundäre Farbe</td><td> Zeichenfolge</td><td> hex (# 44739e), rgb (20, 50, 200), rgba (20, 50, 200, 0,5)</tr><tr><td> mdwButtonColorPress</td><td> Farbe gedrückt</td><td> Zeichenfolge</td><td> hex (# 44739e), rgb (20, 50, 200), rgba (20, 50, 200, 0,5)</tr><tr><td colspan="4" style="background: #44739e; color: white; border-color: #44739e;"> <i><b>Symbol</b></i></td></tr><tr><td> Bild</td><td> Bild</td><td> Zeichenfolge</td><td></tr><tr><td> imageColor</td><td> Bildfarbe</td><td> Zeichenfolge</td><td> hex (# 44739e), rgb (20, 50, 200), rgba (20, 50, 200, 0,5)</tr><tr><td> iconPosition</td><td> Bildposition</td><td> Zeichenfolge</td><td> Nach oben | Unterseite</tr><tr><td> iconHeight</td><td> Bildhöhe</td><td> Nummer</td><td></tr><tr><td colspan="4" style="background: #44739e; color: white; border-color: #44739e;"><i><b>Verriegeln</b></i></td></tr><tr><td> lockEnabled</td><td> Sperren aktivieren</td><td> Boolescher Wert</td><td> false | wahr</tr><tr><td> autoLockAfter</td><td> automatische Sperre nach [s]</td><td> Nummer</td><td></tr><tr><td> lockIcon</td><td> Symbol</td><td> Zeichenfolge</td><td></tr><tr><td> lockIconTop</td><td> Symbolabstand von oben [%]</td><td> Nummer</td><td></tr><tr><td> lockIconLeft</td><td> Symbolabstand von links [%]</td><td> Nummer</td><td></tr><tr><td> lockIconSize</td><td> Symbolgröße</td><td> Nummer</td><td></tr><tr><td> lockIconColor</td><td> Symbolfarbe</td><td> Zeichenfolge</td><td> hex (# 44739e), rgb (20, 50, 200), rgba (20, 50, 200, 0,5)</tr><tr><td> lockFilterGrayscale</td><td> Graufilter, wenn gesperrt</td><td> Nummer</td><td></tr></tbody></table></details>

##### Schaltfläche Vertikale Umschalteigenschaften
Die folgenden Eigenschaften können als [Steuerelement in einer Tabelle] (# Steuerelemente) oder als [HTML-Element](#html-elements) verwendet werden

<details><table><thead><tr><th>Eigentum</th><th> Beschreibung</th><th> Art</th><th> Werte</th></tr></thead><tbody><tr><td> Art</td><td> Widget-Typ</td><td> Zeichenfolge</td><td> toggle_vertical</td></tr><tr><td> debuggen</td><td> Debug-Modus</td><td> Boolescher Wert</td><td> false | wahr</td></tr><tr><td colspan="4" style="background: #44739e; color: white; border-color: #44739e;"> <i><b>Verbreitet</b></i></td></tr><tr><td> oid</td><td> Objekt Identifikation</td><td> Zeichenfolge</td><td></tr><tr><td> buttonStyle</td><td> Tastenstil</td><td> Zeichenfolge</td><td> Text | angehoben | nicht erhöht | umrissen</tr><tr><td> schreibgeschützt</td><td> schreibgeschützt</td><td> Boolescher Wert</td><td> false | wahr</tr><tr><td> toggleType</td><td> Art des Umschalters</td><td> Zeichenfolge</td><td> boolean | Wert</tr><tr><td> Druckknopf</td><td> Druckknopf</td><td> Boolescher Wert</td><td> false | wahr</tr><tr><td> valueOff</td><td> Wert für aus</td><td> Zeichenfolge</td><td></tr><tr><td> valueOn</td><td> Wert für auf</td><td> Zeichenfolge</td><td></tr><tr><td> stateIfNotTrueValue</td><td> Geben Sie an, ob der Wert nicht der Bedingung &quot;Ein&quot; entspricht</td><td> Zeichenfolge</td><td> am | aus</tr><tr><td> vibrateOnMobilDevices</td><td> vibrieren auf mobilen Geräten [s]</td><td> Nummer</td><td></tr><tr><td> generateHtmlControl</td><td> HTML-Element generieren</td><td> Zeichenfolge</td><td></tr><tr><td colspan="4" style="background: #44739e; color: white; border-color: #44739e;"><i><b>Beschriftung</b></i></td></tr><tr><td> Schaltflächentext</td><td> Schaltflächentext</td><td> Zeichenfolge</td><td></tr><tr><td> labelTrue</td><td> Beschriften Sie true</td><td> Zeichenfolge</td><td></tr><tr><td> labelColorFalse</td><td> Etikettenfarbe</td><td> Zeichenfolge</td><td> hex (# 44739e), rgb (20, 50, 200), rgba (20, 50, 200, 0,5)</tr><tr><td> labelColorTrue</td><td> aktive Etikettenfarbe</td><td> Zeichenfolge</td><td> hex (# 44739e), rgb (20, 50, 200), rgba (20, 50, 200, 0,5)</tr><tr><td> textFontFamily</td><td> Schriftart</td><td> Zeichenfolge</td><td></tr><tr><td> textFontSize</td><td> Textgröße</td><td> Nummer</td><td></tr><tr><td> Ausrichtung</td><td> Ausrichtung</td><td> Zeichenfolge</td><td> Flex-Start | Mitte | Flex-End</tr><tr><td> distanceBetweenTextAndImage</td><td> Abstand zwischen Text und Bild</td><td> Nummer</td><td></tr><tr><td colspan="4" style="background: #44739e; color: white; border-color: #44739e;"><i><b>Farben</b></i></td></tr><tr><td> mdwButtonPrimaryColor</td><td> Primärfarbe</td><td> Zeichenfolge</td><td> hex (# 44739e), rgb (20, 50, 200), rgba (20, 50, 200, 0,5)</tr><tr><td> mdwButtonSecondaryColor</td><td> sekundäre Farbe</td><td> Zeichenfolge</td><td> hex (# 44739e), rgb (20, 50, 200), rgba (20, 50, 200, 0,5)</tr><tr><td> colorBgFalse</td><td> Hintergrund</td><td> Zeichenfolge</td><td> hex (# 44739e), rgb (20, 50, 200), rgba (20, 50, 200, 0,5)</tr><tr><td> colorBgTrue</td><td> aktiver Hintergrund</td><td> Zeichenfolge</td><td> hex (# 44739e), rgb (20, 50, 200), rgba (20, 50, 200, 0,5)</tr><tr><td colspan="4" style="background: #44739e; color: white; border-color: #44739e;"> <i><b>Symbol</b></i></td></tr><tr><td> Bild</td><td> Bild</td><td> Zeichenfolge</td><td></tr><tr><td> imageColor</td><td> Bildfarbe</td><td> Zeichenfolge</td><td> hex (# 44739e), rgb (20, 50, 200), rgba (20, 50, 200, 0,5)</tr><tr><td> imageTrue</td><td> aktives Bild</td><td> Zeichenfolge</td><td></tr><tr><td> imageTrueColor</td><td> aktive Bildfarbe</td><td> Zeichenfolge</td><td> hex (# 44739e), rgb (20, 50, 200), rgba (20, 50, 200, 0,5)</tr><tr><td> iconPosition</td><td> Bildposition</td><td> Zeichenfolge</td><td> Nach oben | Unterseite</tr><tr><td> iconHeight</td><td> Bildhöhe</td><td> Nummer</td><td></tr><tr><td colspan="4" style="background: #44739e; color: white; border-color: #44739e;"><i><b>Verriegeln</b></i></td></tr><tr><td> lockEnabled</td><td> Sperren aktivieren</td><td> Boolescher Wert</td><td> false | wahr</tr><tr><td> autoLockAfter</td><td> automatische Sperre nach [s]</td><td> Nummer</td><td></tr><tr><td> lockIcon</td><td> Symbol</td><td> Zeichenfolge</td><td></tr><tr><td> lockIconTop</td><td> Symbolabstand von oben [%]</td><td> Nummer</td><td></tr><tr><td> lockIconLeft</td><td> Symbolabstand von links [%]</td><td> Nummer</td><td></tr><tr><td> lockIconSize</td><td> Symbolgröße</td><td> Nummer</td><td></tr><tr><td> lockIconColor</td><td> Symbolfarbe</td><td> Zeichenfolge</td><td> hex (# 44739e), rgb (20, 50, 200), rgba (20, 50, 200, 0,5)</tr><tr><td> lockFilterGrayscale</td><td> Graufilter, wenn gesperrt</td><td> Nummer</td><td></tr></tbody></table></details>

## Schaltflächensymbol
![Logo](../../../en/adapterref/iobroker.vis-materialdesign/doc/en/media/icon-button.gif)

##### Eigenschaften des Schaltflächensymbols
Die folgenden Eigenschaften können als [Steuerelement in einer Tabelle] (# Steuerelemente) oder als [HTML-Element](#html-elements) verwendet werden

<details><table><thead><tr><th>Eigentum</th><th> Beschreibung</th><th> Art</th><th> Werte</th></tr></thead><tbody><tr><td> Art</td><td> Widget-Typ</td><td> Zeichenfolge</td><td> link_icon</td></tr><tr><td> debuggen</td><td> Debug-Modus</td><td> Boolescher Wert</td><td> false | wahr</td></tr><tr><td colspan="4" style="background: #44739e; color: white; border-color: #44739e;"> <i><b>Verbreitet</b></i></td></tr><tr><td> href</td><td> Verknüpfung</td><td> URL</td><td></tr><tr><td> openNewWindow</td><td> in neuem Fenster öffnen</td><td> Boolescher Wert</td><td> false | wahr</tr><tr><td> vibrateOnMobilDevices</td><td> vibrieren auf mobilen Geräten [s]</td><td> Nummer</td><td></tr><tr><td> generateHtmlControl</td><td> HTML-Element generieren</td><td> Zeichenfolge</td><td></tr><tr><td colspan="4" style="background: #44739e; color: white; border-color: #44739e;"><i><b>Symbol</b></i></td></tr><tr><td> Bild</td><td> Bild</td><td> Zeichenfolge</td><td></tr><tr><td> imageColor</td><td> Bildfarbe</td><td> Zeichenfolge</td><td> hex (# 44739e), rgb (20, 50, 200), rgba (20, 50, 200, 0,5)</tr><tr><td> iconHeight</td><td> Bildhöhe</td><td> Nummer</td><td></tr><tr><td colspan="4" style="background: #44739e; color: white; border-color: #44739e;"><i><b>Farben</b></i></td></tr><tr><td> colorBgFalse</td><td> Hintergrund</td><td> Zeichenfolge</td><td> hex (# 44739e), rgb (20, 50, 200), rgba (20, 50, 200, 0,5)</tr><tr><td> colorPress</td><td> Farbe gedrückt</td><td> Zeichenfolge</td><td> hex (# 44739e), rgb (20, 50, 200), rgba (20, 50, 200, 0,5)</tr></tbody></table></details>

##### Eigenschaften des Schaltflächensymbolstatus
Die folgenden Eigenschaften können als [Steuerelement in einer Tabelle] (# Steuerelemente) oder als [HTML-Element](#html-elements) verwendet werden

<details><table><thead><tr><th>Eigentum</th><th> Beschreibung</th><th> Art</th><th> Werte</th></tr></thead><tbody><tr><td> Art</td><td> Widget-Typ</td><td> Zeichenfolge</td><td> state_icon</td></tr><tr><td> debuggen</td><td> Debug-Modus</td><td> Boolescher Wert</td><td> false | wahr</td></tr><tr><td colspan="4" style="background: #44739e; color: white; border-color: #44739e;"> <i><b>Verbreitet</b></i></td></tr><tr><td> oid</td><td> Objekt Identifikation</td><td> Zeichenfolge</td><td></tr><tr><td> Wert</td><td> Wert</td><td> Zeichenfolge</td><td></tr><tr><td> vibrateOnMobilDevices</td><td> vibrieren auf mobilen Geräten [s]</td><td> Nummer</td><td></tr><tr><td> generateHtmlControl</td><td> HTML-Element generieren</td><td> Zeichenfolge</td><td></tr><tr><td colspan="4" style="background: #44739e; color: white; border-color: #44739e;"><i><b>Symbol</b></i></td></tr><tr><td> Bild</td><td> Bild</td><td> Zeichenfolge</td><td></tr><tr><td> imageColor</td><td> Bildfarbe</td><td> Zeichenfolge</td><td> hex (# 44739e), rgb (20, 50, 200), rgba (20, 50, 200, 0,5)</tr><tr><td> iconHeight</td><td> Bildhöhe</td><td> Nummer</td><td></tr><tr><td colspan="4" style="background: #44739e; color: white; border-color: #44739e;"><i><b>Farben</b></i></td></tr><tr><td> colorBgFalse</td><td> Hintergrund</td><td> Zeichenfolge</td><td> hex (# 44739e), rgb (20, 50, 200), rgba (20, 50, 200, 0,5)</tr><tr><td> colorPress</td><td> Farbe gedrückt</td><td> Zeichenfolge</td><td> hex (# 44739e), rgb (20, 50, 200), rgba (20, 50, 200, 0,5)</tr><tr><td colspan="4" style="background: #44739e; color: white; border-color: #44739e;"> <i><b>Verriegeln</b></i></td></tr><tr><td> lockEnabled</td><td> Sperren aktivieren</td><td> Boolescher Wert</td><td> false | wahr</tr><tr><td> autoLockAfter</td><td> automatische Sperre nach [s]</td><td> Nummer</td><td></tr><tr><td> lockIcon</td><td> Symbol</td><td> Zeichenfolge</td><td></tr><tr><td> lockIconTop</td><td> Symbolabstand von oben [%]</td><td> Nummer</td><td></tr><tr><td> lockIconLeft</td><td> Symbolabstand von links [%]</td><td> Nummer</td><td></tr><tr><td> lockIconSize</td><td> Symbolgröße</td><td> Nummer</td><td></tr><tr><td> lockIconColor</td><td> Symbolfarbe</td><td> Zeichenfolge</td><td> hex (# 44739e), rgb (20, 50, 200), rgba (20, 50, 200, 0,5)</tr><tr><td> lockIconBackground</td><td> lockIconBackground</td><td> Zeichenfolge</td><td> hex (# 44739e), rgb (20, 50, 200), rgba (20, 50, 200, 0,5)</tr><tr><td> lockBackgroundSizeFactor</td><td> lockBackgroundSizeFactor</td><td> Nummer</td><td></tr><tr><td> lockFilterGrayscale</td><td> Graufilter, wenn gesperrt</td><td> Nummer</td><td></tr></tbody></table></details>

##### Button Icon Eigenschaften umschalten
Die folgenden Eigenschaften können als [Steuerelement in einer Tabelle] (# Steuerelemente) oder als [HTML-Element](#html-elements) verwendet werden

<details><table><thead><tr><th>Eigentum</th><th> Beschreibung</th><th> Art</th><th> Werte</th></tr><thead><tbody><tr><td> Art</td><td> Widget-Typ</td><td> Zeichenfolge</td><td> toggle_icon</td></tr><tr><td> debuggen</td><td> Debug-Modus</td><td> Boolescher Wert</td><td> false | wahr</td></tr><tr><td colspan="4" style="background: #44739e; color: white; border-color: #44739e;"> <i><b>Verbreitet</b></i></td></tr><tr><td> oid</td><td> Objekt Identifikation</td><td> Zeichenfolge</td><td></tr><tr><td> schreibgeschützt</td><td> schreibgeschützt</td><td> Boolescher Wert</td><td> false | wahr</tr><tr><td> toggleType</td><td> Art des Umschalters</td><td> Zeichenfolge</td><td> boolean | Wert</tr><tr><td> Druckknopf</td><td> Druckknopf</td><td> Boolescher Wert</td><td> false | wahr</tr><tr><td> valueOff</td><td> Wert für aus</td><td> Zeichenfolge</td><td></tr><tr><td> valueOn</td><td> Wert für auf</td><td> Zeichenfolge</td><td></tr><tr><td> stateIfNotTrueValue</td><td> Geben Sie an, ob der Wert nicht der Bedingung &quot;Ein&quot; entspricht</td><td> Zeichenfolge</td><td> am | aus</tr><tr><td> vibrateOnMobilDevices</td><td> vibrieren auf mobilen Geräten [s]</td><td> Nummer</td><td></tr><tr><td> generateHtmlControl</td><td> HTML-Element generieren</td><td> Zeichenfolge</td><td></tr><tr><td colspan="4" style="background: #44739e; color: white; border-color: #44739e;"><i><b>Symbol</b></i></td></tr><tr><td> Bild</td><td> Bild</td><td> Zeichenfolge</td><td></tr><tr><td> imageColor</td><td> Bildfarbe</td><td> Zeichenfolge</td><td> hex (# 44739e), rgb (20, 50, 200), rgba (20, 50, 200, 0,5)</tr><tr><td> imageTrue</td><td> aktives Bild</td><td> Zeichenfolge</td><td></tr><tr><td> imageTrueColor</td><td> aktive Bildfarbe</td><td> Zeichenfolge</td><td> hex (# 44739e), rgb (20, 50, 200), rgba (20, 50, 200, 0,5)</tr><tr><td> iconHeight</td><td> Bildhöhe</td><td> Nummer</td><td></tr><tr><td colspan="4" style="background: #44739e; color: white; border-color: #44739e;"><i><b>Farben</b></i></td></tr><tr><td> colorBgFalse</td><td> Hintergrund</td><td> Zeichenfolge</td><td> hex (# 44739e), rgb (20, 50, 200), rgba (20, 50, 200, 0,5)</tr><tr><td> colorBgTrue</td><td> aktiver Hintergrund</td><td> Zeichenfolge</td><td> hex (# 44739e), rgb (20, 50, 200), rgba (20, 50, 200, 0,5)</tr><tr><td> colorPress</td><td> Farbe gedrückt</td><td> Zeichenfolge</td><td> hex (# 44739e), rgb (20, 50, 200), rgba (20, 50, 200, 0,5)</tr><tr><td colspan="4" style="background: #44739e; color: white; border-color: #44739e;"> <i><b>Verriegeln</b></i></td></tr><tr><td> lockEnabled</td><td> Sperren aktivieren</td><td> Boolescher Wert</td><td> false | wahr</tr><tr><td> autoLockAfter</td><td> automatische Sperre nach [s]</td><td> Nummer</td><td></tr><tr><td> lockIcon</td><td> Symbol</td><td> Zeichenfolge</td><td></tr><tr><td> lockIconTop</td><td> Symbolabstand von oben [%]</td><td> Nummer</td><td></tr><tr><td> lockIconLeft</td><td> Symbolabstand von links [%]</td><td> Nummer</td><td></tr><tr><td> lockIconSize</td><td> Symbolgröße</td><td> Nummer</td><td></tr><tr><td> lockIconColor</td><td> Symbolfarbe</td><td> Zeichenfolge</td><td> hex (# 44739e), rgb (20, 50, 200), rgba (20, 50, 200, 0,5)</tr><tr><td> lockIconBackground</td><td> lockIconBackground</td><td> Zeichenfolge</td><td> hex (# 44739e), rgb (20, 50, 200), rgba (20, 50, 200, 0,5)</tr><tr><td> lockBackgroundSizeFactor</td><td> lockBackgroundSizeFactor</td><td> Nummer</td><td></tr><tr><td> lockFilterGrayscale</td><td> Graufilter, wenn gesperrt</td><td> Nummer</td><td></tr></tbody></table></details>

## Karte
![Logo](../../../en/adapterref/iobroker.vis-materialdesign/doc/en/media/cards.png)

## Liste
![Logo](../../../en/adapterref/iobroker.vis-materialdesign/doc/en/media/list.gif)

## IconList
![Logo](../../../en/adapterref/iobroker.vis-materialdesign/doc/en/media/iconList.gif)

### Editoreinstellungen
Einstellungen, die in der folgenden Tabelle nicht aufgeführt sind, sind selbsterklärend.

<table><thead><tr><th>Bildschirmfoto</th><th> Rahmen</th><th> Beschreibung </th></tr></thead><tbody><tr><td rowspan=6><img src="doc/en/media/iconlist_settings_data.png"></td><td> Eingabemethode für die Listendaten</td><td> Die Daten für die IconList können über den Editor eingegeben oder eine JSON-Zeichenfolge verwendet werden</td></tr><tr><td> Editor: Anzahl der Listenelemente</td><td> Anzahl der Listenelemente mit dem vis-Editor für die Listendaten</td></tr><tr><td> JSON-String: Objekt-ID</td><td> Objekt-ID des Datenpunkts, der die JSON-Zeichenfolge enthält. Zulässige Eigenschaften werden unten beschrieben</td></tr></tbody></table>

### JSON-Eigenschaften
Die JSON-Zeichenfolge muss ein Array von Objekten mit den folgenden Eigenschaften sein:

<table><thead><tr><th>Eigentum</th><th> Beschreibung</th><th> Art</th><th> Werte</th></tr></thead><tbody><tr><td> listType</td><td> Art der Liste</td><td> Zeichenfolge</td><td> Text | buttonState | buttonToggle | buttonToggleValueTrue | buttonToggleValueFalse | buttonNav | buttonLink</td></tr><tr><td> Objekt Identifikation</td><td> Objekt-ID für Schaltfläche</td><td> Zeichenfolge</td><td/></tr><tr><td> buttonStateValue</td><td> Wert für den Schaltflächenstatus</td><td> Zeichenfolge</td><td/></tr><tr><td> buttonNavView</td><td> Ansicht zum Navigieren</td><td> Zeichenfolge</td><td/></tr><tr><td> buttonLink</td><td> URL zum Navigieren</td><td> Zeichenfolge</td><td/></tr><tr><td> buttonToggleValueTrue</td><td> wahrer Wert für das Umschalten der Taste</td><td> Zeichenfolge</td><td/></tr><tr><td> buttonToggleValueFalse</td><td> falscher Wert für das Umschalten der Schaltfläche</td><td> Zeichenfolge</td><td/></tr><tr><td> showValueLabel</td><td> Wert als Text anzeigen</td><td> Zeichenfolge</td><td/></tr><tr><td> valueAnhang</td><td> Text an Wert anhängen</td><td> Zeichenfolge</td><td/></tr><tr><td> Hintergrund</td><td> Hintergrundfarbe</td><td> Zeichenfolge</td><td> hex (# 44739e), rgb (20, 50, 200), rgba (20, 50, 200, 0,5)</td></tr><tr><td> Hintergrund</td><td> Text</td><td> Zeichenfolge</td><td/></tr><tr><td> Untertext</td><td> zweiter Text</td><td> Zeichenfolge</td><td/></tr><tr><td> Bild</td><td> Bildpfad oder Name der Material Design Icons</td><td> Zeichenfolge</td><td/></tr><tr><td> imageColor</td><td> Farbe der Material Design Icons</td><td> Zeichenfolge</td><td> hex (# 44739e), rgb (20, 50, 200), rgba (20, 50, 200, 0,5)</td></tr><tr><td> imageActive</td><td> Bildpfad oder Name der Material Design Icons für die aktive Schaltfläche</td><td> Zeichenfolge</td><td> hex (# 44739e), rgb (20, 50, 200), rgba (20, 50, 200, 0,5)</td></tr><tr><td> buttonBackgroundColor</td><td> Hintergrundfarbe der Schaltfläche</td><td> Zeichenfolge</td><td> hex (# 44739e), rgb (20, 50, 200), rgba (20, 50, 200, 0,5)</td></tr><tr><td> buttonBackgroundActiveColor</td><td> Hintergrundfarbe der Schaltfläche für die aktive Schaltfläche</td><td> Zeichenfolge</td><td> hex (# 44739e), rgb (20, 50, 200), rgba (20, 50, 200, 0,5)</td></tr><tr><td> statusBarColor</td><td> Farbe der Statusleiste</td><td> Zeichenfolge</td><td> hex (# 44739e), rgb (20, 50, 200), rgba (20, 50, 200, 0,5)</td></tr><tr><td> statusBarText</td><td> Text der Statusleiste</td><td> Zeichenfolge</td><td/></tr><tr><td> lockEnabled</td><td> Sperren aktivieren</td><td> Boolescher Wert</td><td> false | wahr</tr></tbody></table>

<! - in toc weglassen ->

#### Beispiel
<details> <pre><code> [ { "background": "red", "text": "text1", "subText": "number", "image": "harddisk", "imageColor": "#ec0909", "imageActive": "folder", "imageActiveColor": "#5ad902", "buttonBackgroundColor": "", "buttonBackgroundActiveColor": "", "listType": "buttonState", "objectId": "0_userdata.0.iconList.buttonState.number", "buttonStateValue": "60", "buttonNavView": "", "buttonLink": "", "buttonToggleValueTrue": "", "buttonToggleValueFalse": "", "valueAppendix": "", "showValueLabel": "true", "statusBarColor": "green", "lockEnabled": "false" }, { "background": "green", "text": "text0", "subText": "bool", "image": "home", "imageColor": "#44739e", "imageActive": "home", "imageActiveColor": "#44739e", "buttonBackgroundColor": "", "buttonBackgroundActiveColor": "#a0f628", "listType": "buttonToggle", "objectId": "0_userdata.0.iconList.buttonToggle.bool0", "buttonStateValue": "60", "buttonNavView": "", "buttonLink": "", "buttonToggleValueTrue": "", "buttonToggleValueFalse": "", "valueAppendix": "", "showValueLabel": "false", "statusBarColor": "", "lockEnabled": "false" } ] </code></pre> </details>

## Fortschritt
![Logo](../../../en/adapterref/iobroker.vis-materialdesign/doc/en/media/progress.gif)

<table><thead><tr><th>Bildschirmfoto</th><th> Rahmen</th><th> Beschreibung</th></tr></thead><tbody><tr><td rowspan=6><img src="doc/en/media/progress_settings.png"></td><td> benutzerdefiniertes Etikett</td><td> Für benutzerdefinierte Beschriftungen können Sie die Eigenschaft <code>[#value]</code> , um den tatsächlichen Wert des Datenpunkts <code>[#value]</code> . Um den aktuellen <code>[#percent]</code> können Sie <code>[#percent]</code></td></tr></tbody></table>

##### Fortschrittseigenschaften
Die folgenden Eigenschaften können als [Steuerelement in einer Tabelle] (# Steuerelemente) oder als [HTML-Element](#html-elements) verwendet werden

<details><table><thead><tr><th>Eigentum</th><th> Beschreibung</th><th> Art</th><th> Werte</th></tr></thead><tbody><tr><td> Art</td><td> Widget-Typ</td><td> Zeichenfolge</td><td> linear</td></tr><tr><td> debuggen</td><td> Debug-Modus</td><td> Boolescher Wert</td><td> false | wahr</td></tr><tr><td colspan="4" style="background: #44739e; color: white; border-color: #44739e;"> <i><b>Verbreitet</b></i></td></tr><tr><td> progressIndeterminate</td><td> unbestimmt - kontinuierlich animiert</td><td> Boolescher Wert</td><td> false | wahr</tr><tr><td> oid</td><td> Objekt Identifikation</td><td> Zeichenfolge</td><td></tr><tr><td> Mindest</td><td> Mindest</td><td> Zeichenfolge</td><td></tr><tr><td> max</td><td> max</td><td> Zeichenfolge</td><td></tr><tr><td> umkehren</td><td> Kehrt den Wert um</td><td> Boolescher Wert</td><td> false | wahr</tr><tr><td> generateHtmlControl</td><td> HTML-Element generieren</td><td> Zeichenfolge</td><td></tr><tr><td colspan="4" style="background: #44739e; color: white; border-color: #44739e;"><i><b>Layout</b></i></td></tr><tr><td> progressRounded</td><td> abgerundete Ecken</td><td> Boolescher Wert</td><td> false | wahr</tr><tr><td> progressStriped</td><td> gestreift</td><td> Boolescher Wert</td><td> false | wahr</tr><tr><td> progressStripedColor</td><td> progressStripedColor</td><td> Zeichenfolge</td><td> hex (# 44739e), rgb (20, 50, 200), rgba (20, 50, 200, 0,5)</tr><tr><td colspan="4" style="background: #44739e; color: white; border-color: #44739e;"> <i><b>Farben</b></i></td></tr><tr><td> colorProgressBackground</td><td> Hintergrundfarbe</td><td> Zeichenfolge</td><td> hex (# 44739e), rgb (20, 50, 200), rgba (20, 50, 200, 0,5)</tr><tr><td> colorProgress</td><td> Farbfortschritt</td><td> Zeichenfolge</td><td> hex (# 44739e), rgb (20, 50, 200), rgba (20, 50, 200, 0,5)</tr><tr><td> colorOneCondition</td><td> Bedingung für Farbe 1 Fortschritt [&gt;]</td><td> Nummer</td><td></tr><tr><td> colorOne</td><td> Farbe 1 Fortschritt</td><td> Zeichenfolge</td><td> hex (# 44739e), rgb (20, 50, 200), rgba (20, 50, 200, 0,5)</tr><tr><td> colorTwoCondition</td><td> Bedingung für den Fortschritt von Farbe 2 [&gt;]</td><td> Nummer</td><td></tr><tr><td> colorTwo</td><td> Farbe 2 Fortschritt</td><td> Zeichenfolge</td><td> hex (# 44739e), rgb (20, 50, 200), rgba (20, 50, 200, 0,5)</tr><tr><td colspan="4" style="background: #44739e; color: white; border-color: #44739e;"> <i><b>Beschriftung</b></i></td></tr><tr><td> showValueLabel</td><td> Wert anzeigen</td><td> Boolescher Wert</td><td> false | wahr</tr><tr><td> valueLabelStyle</td><td> Wertbeschriftungsstil</td><td> Zeichenfolge</td><td> progressPercent | progressValue | progressCustom</tr><tr><td> valueLabelUnit</td><td> Einheit</td><td> Zeichenfolge</td><td></tr><tr><td> valueMaxDecimals</td><td> Dezimalpunkte</td><td> Nummer</td><td></tr><tr><td> valueLabelCustom</td><td> benutzerdefiniertes Etikett</td><td> Zeichenfolge</td><td></tr><tr><td> Textfarbe</td><td> Minuten Textfarbe</td><td> Zeichenfolge</td><td> hex (# 44739e), rgb (20, 50, 200), rgba (20, 50, 200, 0,5)</tr><tr><td> textFontSize</td><td> Textgröße</td><td> Nummer</td><td></tr><tr><td> textFontFamily</td><td> Schriftart</td><td> Zeichenfolge</td><td></tr><tr><td> Textausrichtung</td><td> Textausrichtung</td><td> Zeichenfolge</td><td> start | Mitte | Ende</tr></tbody></table></details>

## Fortschrittsrundschreiben
![Logo](../../../en/adapterref/iobroker.vis-materialdesign/doc/en/media/progress.gif)

<table><thead><tr><th>Bildschirmfoto</th><th> Rahmen</th><th> Beschreibung</th></tr></thead><tbody><tr><td rowspan=6><img src="doc/en/media/progress_settings.png"></td><td> benutzerdefiniertes Etikett</td><td> Für benutzerdefinierte Beschriftungen können Sie die Eigenschaft <code>[#value]</code> , um den tatsächlichen Wert des Datenpunkts <code>[#value]</code> . Um den aktuellen <code>[#percent]</code> können Sie <code>[#percent]</code></td></tr></tbody></table>

##### Eigenschaften des Fortschrittskreises
Die folgenden Eigenschaften können als [Steuerelement in einer Tabelle] (# Steuerelemente) oder als [HTML-Element](#html-elements) verwendet werden

<details><table><thead><tr><th>Eigentum</th><th> Beschreibung</th><th> Art</th><th> Werte</th></tr></thead><tbody><tr><td> Art</td><td> Widget-Typ</td><td> Zeichenfolge</td><td> kreisförmig</td></tr><tr><td> debuggen</td><td> Debug-Modus</td><td> Boolescher Wert</td><td> false | wahr</td></tr><tr><td colspan="4" style="background: #44739e; color: white; border-color: #44739e;"> <i><b>Verbreitet</b></i></td></tr><tr><td> oid</td><td> Objekt Identifikation</td><td> Zeichenfolge</td><td></tr><tr><td> Mindest</td><td> Mindest</td><td> Zeichenfolge</td><td></tr><tr><td> max</td><td> max</td><td> Zeichenfolge</td><td></tr><tr><td> generateHtmlControl</td><td> HTML-Element generieren</td><td> Zeichenfolge</td><td></tr><tr><td colspan="4" style="background: #44739e; color: white; border-color: #44739e;"><i><b>Layout</b></i></td></tr><tr><td> progressCircularSize</td><td> Größe</td><td> Nummer</td><td></tr><tr><td> progressCircularWidth</td><td> Dicke</td><td> Nummer</td><td></tr><tr><td> progressCircularRotate</td><td> Startpunkt drehen</td><td> Nummer</td><td></tr><tr><td colspan="4" style="background: #44739e; color: white; border-color: #44739e;"><i><b>Farben</b></i></td></tr><tr><td> colorProgressBackground</td><td> Hintergrundfarbe</td><td> Zeichenfolge</td><td> hex (# 44739e), rgb (20, 50, 200), rgba (20, 50, 200, 0,5)</tr><tr><td> colorProgress</td><td> Farbfortschritt</td><td> Zeichenfolge</td><td> hex (# 44739e), rgb (20, 50, 200), rgba (20, 50, 200, 0,5)</tr><tr><td> innerColor</td><td> Kreis Hintergrundfarbe</td><td> Zeichenfolge</td><td> hex (# 44739e), rgb (20, 50, 200), rgba (20, 50, 200, 0,5)</tr><tr><td> colorOneCondition</td><td> Bedingung für Farbe 1 Fortschritt [&gt;]</td><td> Nummer</td><td></tr><tr><td> colorOne</td><td> Farbe 1 Fortschritt</td><td> Zeichenfolge</td><td> hex (# 44739e), rgb (20, 50, 200), rgba (20, 50, 200, 0,5)</tr><tr><td> colorTwoCondition</td><td> Bedingung für den Fortschritt von Farbe 2 [&gt;]</td><td> Nummer</td><td></tr><tr><td> colorTwo</td><td> Farbe 2 Fortschritt</td><td> Zeichenfolge</td><td> hex (# 44739e), rgb (20, 50, 200), rgba (20, 50, 200, 0,5)</tr><tr><td colspan="4" style="background: #44739e; color: white; border-color: #44739e;"> <i><b>Beschriftung</b></i></td></tr><tr><td> showValueLabel</td><td> Wert anzeigen</td><td> Boolescher Wert</td><td> false | wahr</tr><tr><td> valueLabelStyle</td><td> Wertbeschriftungsstil</td><td> Zeichenfolge</td><td> progressPercent | progressValue | progressCustom</tr><tr><td> valueLabelUnit</td><td> Einheit</td><td> Zeichenfolge</td><td></tr><tr><td> valueMaxDecimals</td><td> Dezimalpunkte</td><td> Nummer</td><td></tr><tr><td> valueLabelCustom</td><td> benutzerdefiniertes Etikett</td><td> Zeichenfolge</td><td></tr><tr><td> Textfarbe</td><td> Minuten Textfarbe</td><td> Zeichenfolge</td><td> hex (# 44739e), rgb (20, 50, 200), rgba (20, 50, 200, 0,5)</tr><tr><td> textFontSize</td><td> Textgröße</td><td> Nummer</td><td></tr><tr><td> textFontFamily</td><td> Schriftart</td><td> Zeichenfolge</td><td></tr></tbody></table></details>

## Schieberegler
![Logo](../../../en/adapterref/iobroker.vis-materialdesign/doc/en/media/slider.gif)

Einstellungen, die in der folgenden Tabelle nicht aufgeführt sind, sind selbsterklärend.

<table><thead><tr><th>Bildschirmfoto</th><th> Rahmen</th><th> Beschreibung</th></tr></thead><tbody><tr><td rowspan=6><img src="doc/en/media/slider.png"></td><td> initDelay</td><td> Wenn der Schieberegler nach dem Laden der Laufzeit nicht sichtbar oder bedienbar ist, muss dieser Wert erhöht werden. Die Eingabe erfolgt in Millisekunden.<br> Erhöhen Sie beispielsweise um 250 Schritte, bis der Schieberegler funktioniert.</td></tr></tbody></table>

##### Slider-Eigenschaften
Die folgenden Eigenschaften können als [Steuerelement in einer Tabelle] (# Steuerelemente) oder als [HTML-Element](#html-elements) verwendet werden

<details><table><thead><tr><th>Eigentum</th><th> Beschreibung</th><th> Art</th><th> Werte</th></tr></thead><tbody><tr><td> debuggen</td><td> Debug-Modus</td><td> Boolescher Wert</td><td> false | wahr</td></tr><tr><td colspan="4" style="background: #44739e; color: white; border-color: #44739e;"> <i><b>Verbreitet</b></i></td></tr><tr><td> oid</td><td> Objekt Identifikation</td><td> Zeichenfolge</td><td></tr><tr><td> oid-arbeiten</td><td> Arbeitsobjekt-ID</td><td> Zeichenfolge</td><td></tr><tr><td> Orientierung</td><td> Orientierung</td><td> Zeichenfolge</td><td> horizontal | vertikal</tr><tr><td> reverseSlider</td><td> Schieberegler umkehren</td><td> Boolescher Wert</td><td> false | wahr</tr><tr><td> knopfgröße</td><td> Knopfgröße</td><td> Zeichenfolge</td><td> knobSmall | knobMedium | knaufBig</tr><tr><td> schreibgeschützt</td><td> schreibgeschützt</td><td> Boolescher Wert</td><td> false | wahr</tr><tr><td> Mindest</td><td> Mindest</td><td> Zeichenfolge</td><td></tr><tr><td> max</td><td> max</td><td> Zeichenfolge</td><td></tr><tr><td> Schritt</td><td> Schritte</td><td> Zeichenfolge</td><td></tr><tr><td> vibrateOnMobilDevices</td><td> vibrieren auf mobilen Geräten [s]</td><td> Nummer</td><td></tr><tr><td> generateHtmlControl</td><td> HTML-Element generieren</td><td> Zeichenfolge</td><td></tr><tr><td colspan="4" style="background: #44739e; color: white; border-color: #44739e;"><i><b>Schritte Layout</b></i></td></tr><tr><td> showTicks</td><td> Schritte zeigen</td><td> Zeichenfolge</td><td> nein | ja | immer</tr><tr><td> tickSize</td><td> Anzeigegröße der Schritte</td><td> Nummer</td><td></tr><tr><td> tickLabels</td><td> Text der Schritte (durch Kommas getrennt)</td><td> Zeichenfolge</td><td></tr><tr><td> tickTextColor</td><td> Textfarbe der Schritte</td><td> Zeichenfolge</td><td> hex (# 44739e), rgb (20, 50, 200), rgba (20, 50, 200, 0,5)</tr><tr><td> tickFontFamily</td><td> Schriftart der Schritte</td><td> Zeichenfolge</td><td></tr><tr><td> tickFontSize</td><td> Schriftgröße</td><td> Nummer</td><td></tr><tr><td> tickColorBefore</td><td> Farbe vor dem Regler</td><td> Zeichenfolge</td><td> hex (# 44739e), rgb (20, 50, 200), rgba (20, 50, 200, 0,5)</tr><tr><td> tickColorAfter</td><td> Farbe nach dem Regler</td><td> Zeichenfolge</td><td> hex (# 44739e), rgb (20, 50, 200), rgba (20, 50, 200, 0,5)</tr><tr><td colspan="4" style="background: #44739e; color: white; border-color: #44739e;"> <i><b>Farben</b></i></td></tr><tr><td> colorBeforeThumb</td><td> Farbe vor dem Regler</td><td> Zeichenfolge</td><td> hex (# 44739e), rgb (20, 50, 200), rgba (20, 50, 200, 0,5)</tr><tr><td> colorThumb</td><td> Farbe des Reglers</td><td> Zeichenfolge</td><td> hex (# 44739e), rgb (20, 50, 200), rgba (20, 50, 200, 0,5)</tr><tr><td> colorAfterThumb</td><td> Farbe nach dem Regler</td><td> Zeichenfolge</td><td> hex (# 44739e), rgb (20, 50, 200), rgba (20, 50, 200, 0,5)</tr><tr><td colspan="4" style="background: #44739e; color: white; border-color: #44739e;"> <i><b>Beschriftung</b></i></td></tr><tr><td> prepandText</td><td> Text vorangestellt</td><td> Zeichenfolge</td><td></tr><tr><td> prepandTextWidth</td><td> prepandTextWidth</td><td> Nummer</td><td></tr><tr><td> prepandTextColor</td><td> Farbe des vorgefertigten Textes</td><td> Zeichenfolge</td><td> hex (# 44739e), rgb (20, 50, 200), rgba (20, 50, 200, 0,5)</tr><tr><td> prepandTextFontSize</td><td> Textgröße vorab erweitert</td><td> Nummer</td><td></tr><tr><td> prepandTextFontFamily</td><td> Schriftart des Textes vorangestellt</td><td> Zeichenfolge</td><td></tr><tr><td> showValueLabel</td><td> Wert anzeigen</td><td> Boolescher Wert</td><td> false | wahr</tr><tr><td> valueLabelStyle</td><td> Wertbeschriftungsstil</td><td> Zeichenfolge</td><td> sliderPercent | sliderValue</tr><tr><td> valueLabelUnit</td><td> Einheit</td><td> Zeichenfolge</td><td></tr><tr><td> valueFontFamily</td><td> valueFontFamily</td><td> Zeichenfolge</td><td></tr><tr><td> valueFontSize</td><td> Wert Schriftgröße</td><td> Nummer</td><td></tr><tr><td> valueLabelColor</td><td> Textfarbe des Wertes</td><td> Zeichenfolge</td><td> hex (# 44739e), rgb (20, 50, 200), rgba (20, 50, 200, 0,5)</tr><tr><td> valueLabelMin</td><td> Text für Wert kleiner als min</td><td> Zeichenfolge</td><td></tr><tr><td> valueLabelMax</td><td> Text für Wert größer als min</td><td> Zeichenfolge</td><td></tr><tr><td> valueLessThan</td><td> &#39;kleiner als&#39; Bedingung für den Text des Wertes</td><td> Nummer</td><td></tr><tr><td> textForValueLessThan</td><td> Text für &#39;kleiner als&#39;</td><td> Zeichenfolge</td><td></tr><tr><td> valueGreaterThan</td><td> Bedingung &#39;größer als&#39; für den Text des Werts</td><td> Nummer</td><td></tr><tr><td> textForValueGreaterThan</td><td> Text für &#39;größer als&#39;</td><td> Zeichenfolge</td><td></tr><tr><td> valueLabelWidth</td><td> Abstandsetikett</td><td> Nummer</td><td></tr><tr><td colspan="4" style="background: #44739e; color: white; border-color: #44739e;"><i><b>Layout des Controller-Labels</b></i></td></tr><tr><td> showThumbLabel</td><td> Etikett anzeigen</td><td> Zeichenfolge</td><td> nein | ja | immer</tr><tr><td> thumbSize</td><td> Etikettengröße</td><td> Nummer</td><td></tr><tr><td> thumbBackgroundColor</td><td> Hintergrundfarbe</td><td> Zeichenfolge</td><td> hex (# 44739e), rgb (20, 50, 200), rgba (20, 50, 200, 0,5)</tr><tr><td> thumbFontColor</td><td> Schriftfarbe</td><td> Zeichenfolge</td><td> hex (# 44739e), rgb (20, 50, 200), rgba (20, 50, 200, 0,5)</tr><tr><td> thumbFontSize</td><td> Schriftgröße</td><td> Nummer</td><td></tr><tr><td> thumbFontFamily</td><td> Schriftart</td><td> Zeichenfolge</td><td></tr><tr><td> useLabelRules</td><td> Verwenden Sie die Regeln des Textes</td><td> Boolescher Wert</td><td> false | wahr</tr></tbody></table></details>

## Slider Round
![Logo](../../../en/adapterref/iobroker.vis-materialdesign/doc/en/media/round_slider.gif)

##### Eigenschaften der Schiebereglerrunde
Die folgenden Eigenschaften können als [Steuerelement in einer Tabelle] (# Steuerelemente) oder als [HTML-Element](#html-elements) verwendet werden

<details><table><thead><tr><th>Eigentum</th><th> Beschreibung</th><th> Art</th><th> Werte</th></tr></thead><tbody><tr><td> debuggen</td><td> Debug-Modus</td><td> Boolescher Wert</td><td> false | wahr</td></tr><tr><td colspan="4" style="background: #44739e; color: white; border-color: #44739e;"> <i><b>Verbreitet</b></i></td></tr><tr><td> oid</td><td> Objekt Identifikation</td><td> Zeichenfolge</td><td></tr><tr><td> oid-arbeiten</td><td> Arbeitsobjekt-ID</td><td> Zeichenfolge</td><td></tr><tr><td> Mindest</td><td> Mindest</td><td> Zeichenfolge</td><td></tr><tr><td> max</td><td> max</td><td> Zeichenfolge</td><td></tr><tr><td> Schritt</td><td> Schritte</td><td> Zeichenfolge</td><td></tr><tr><td> schreibgeschützt</td><td> schreibgeschützt</td><td> Boolescher Wert</td><td> false | wahr</tr><tr><td> startAngle</td><td> Startwinkel</td><td> Nummer</td><td></tr><tr><td> Bogenlänge</td><td> Bogenlänge</td><td> Nummer</td><td></tr><tr><td> sliderWidth</td><td> Slider Thikness</td><td> Nummer</td><td></tr><tr><td> handleSize</td><td> Knopfgröße</td><td> Nummer</td><td></tr><tr><td> handleZoom</td><td> Knopfzoom bei Steuerung</td><td> Nummer</td><td></tr><tr><td> rtl</td><td> Schiebereglerbewegung von rechts nach links</td><td> Boolescher Wert</td><td> false | wahr</tr><tr><td> vibrateOnMobilDevices</td><td> vibrieren auf mobilen Geräten [s]</td><td> Nummer</td><td></tr><tr><td> generateHtmlControl</td><td> HTML-Element generieren</td><td> Zeichenfolge</td><td></tr><tr><td colspan="4" style="background: #44739e; color: white; border-color: #44739e;"><i><b>Farben</b></i></td></tr><tr><td> colorSliderBg</td><td> Hintergrund</td><td> Zeichenfolge</td><td> hex (# 44739e), rgb (20, 50, 200), rgba (20, 50, 200, 0,5)</tr><tr><td> colorBeforeThumb</td><td> Farbe vor dem Regler</td><td> Zeichenfolge</td><td> hex (# 44739e), rgb (20, 50, 200), rgba (20, 50, 200, 0,5)</tr><tr><td> colorThumb</td><td> Farbe des Reglers</td><td> Zeichenfolge</td><td> hex (# 44739e), rgb (20, 50, 200), rgba (20, 50, 200, 0,5)</tr><tr><td> colorAfterThumb</td><td> Farbe nach dem Regler</td><td> Zeichenfolge</td><td> hex (# 44739e), rgb (20, 50, 200), rgba (20, 50, 200, 0,5)</tr><tr><td> valueLabelColor</td><td> Textfarbe des Wertes</td><td> Zeichenfolge</td><td> hex (# 44739e), rgb (20, 50, 200), rgba (20, 50, 200, 0,5)</tr><tr><td colspan="4" style="background: #44739e; color: white; border-color: #44739e;"> <i><b>Beschriftung</b></i></td></tr><tr><td> showValueLabel</td><td> Wert anzeigen</td><td> Boolescher Wert</td><td> false | wahr</tr><tr><td> valueLabelVerticalPosition</td><td> vertikale Textposition des Wertes</td><td> Nummer</td><td></tr><tr><td> valueLabelStyle</td><td> Wertbeschriftungsstil</td><td> Zeichenfolge</td><td> sliderPercent | sliderValue</tr><tr><td> valueLabelUnit</td><td> Einheit</td><td> Zeichenfolge</td><td></tr><tr><td> valueFontFamily</td><td> valueFontFamily</td><td> Zeichenfolge</td><td></tr><tr><td> valueFontSize</td><td> Wert Schriftgröße</td><td> Nummer</td><td></tr><tr><td> valueLabelMin</td><td> Text für Wert kleiner als min</td><td> Zeichenfolge</td><td></tr><tr><td> valueLabelMax</td><td> Text für Wert größer als min</td><td> Zeichenfolge</td><td></tr><tr><td> valueLessThan</td><td> &#39;kleiner als&#39; Bedingung für den Text des Wertes</td><td> Nummer</td><td></tr><tr><td> textForValueLessThan</td><td> Text für &#39;kleiner als&#39;</td><td> Zeichenfolge</td><td></tr><tr><td> valueGreaterThan</td><td> Bedingung &#39;größer als&#39; für den Text des Werts</td><td> Nummer</td><td></tr><tr><td> textForValueGreaterThan</td><td> Text für &#39;größer als&#39;</td><td> Zeichenfolge</td><td></tr></tbody></table></details>

## Kontrollkästchen
![Logo](../../../en/adapterref/iobroker.vis-materialdesign/doc/en/media/checkbox.gif)

##### Checkbox-Eigenschaften
Die folgenden Eigenschaften können als [Steuerelement in einer Tabelle] (# Steuerelemente) oder als [HTML-Element](#html-elements) verwendet werden

<details><table><thead><tr><th>Eigentum</th><th> Beschreibung</th><th> Art</th><th> Werte</th></tr></thead><tbody><tr><td> debuggen</td><td> Debug-Modus</td><td> Boolescher Wert</td><td> false | wahr</td></tr><tr><td colspan="4" style="background: #44739e; color: white; border-color: #44739e;"> <i><b>Verbreitet</b></i></td></tr><tr><td> oid</td><td> Objekt Identifikation</td><td> Zeichenfolge</td><td></tr><tr><td> schreibgeschützt</td><td> schreibgeschützt</td><td> Boolescher Wert</td><td> false | wahr</tr><tr><td> toggleType</td><td> Art des Umschalters</td><td> Zeichenfolge</td><td> boolean | Wert</tr><tr><td> valueOff</td><td> Wert für aus</td><td> Zeichenfolge</td><td></tr><tr><td> valueOn</td><td> Wert für auf</td><td> Zeichenfolge</td><td></tr><tr><td> stateIfNotTrueValue</td><td> Geben Sie an, ob der Wert nicht der Bedingung &quot;Ein&quot; entspricht</td><td> Zeichenfolge</td><td> am | aus</tr><tr><td> vibrateOnMobilDevices</td><td> vibrieren auf mobilen Geräten [s]</td><td> Nummer</td><td></tr><tr><td> generateHtmlControl</td><td> HTML-Element generieren</td><td> Zeichenfolge</td><td></tr><tr><td colspan="4" style="background: #44739e; color: white; border-color: #44739e;"><i><b>Beschriftung</b></i></td></tr><tr><td> labelFalse</td><td> Beschriften Sie false</td><td> Zeichenfolge</td><td></tr><tr><td> labelTrue</td><td> Beschriften Sie true</td><td> Zeichenfolge</td><td></tr><tr><td> labelPosition</td><td> labelPosition</td><td> Zeichenfolge</td><td> links | rechts | aus</tr><tr><td> labelClickActive</td><td> Labelklick aktivieren</td><td> Boolescher Wert</td><td> false | wahr</tr><tr><td> valueFontFamily</td><td> valueFontFamily</td><td> Zeichenfolge</td><td></tr><tr><td> valueFontSize</td><td> Wert Schriftgröße</td><td> Nummer</td><td></tr><tr><td colspan="4" style="background: #44739e; color: white; border-color: #44739e;"><i><b>Farben</b></i></td></tr><tr><td> colorCheckBox</td><td> Kontrollkästchenfarbe</td><td> Zeichenfolge</td><td> hex (# 44739e), rgb (20, 50, 200), rgba (20, 50, 200, 0,5)</tr><tr><td> colorCheckBoxBorder</td><td> Randfarbe</td><td> Zeichenfolge</td><td> hex (# 44739e), rgb (20, 50, 200), rgba (20, 50, 200, 0,5)</tr><tr><td> colorCheckBoxHover</td><td> Schwebefarbe des Kontrollkästchens</td><td> Zeichenfolge</td><td> hex (# 44739e), rgb (20, 50, 200), rgba (20, 50, 200, 0,5)</tr><tr><td> labelColorFalse</td><td> Etikettenfarbe</td><td> Zeichenfolge</td><td> hex (# 44739e), rgb (20, 50, 200), rgba (20, 50, 200, 0,5)</tr><tr><td> labelColorTrue</td><td> aktive Etikettenfarbe</td><td> Zeichenfolge</td><td> hex (# 44739e), rgb (20, 50, 200), rgba (20, 50, 200, 0,5)</tr><tr><td colspan="4" style="background: #44739e; color: white; border-color: #44739e;"> <i><b>Verriegeln</b></i></td></tr><tr><td> lockEnabled</td><td> Sperren aktivieren</td><td> Boolescher Wert</td><td> false | wahr</tr><tr><td> autoLockAfter</td><td> automatische Sperre nach [s]</td><td> Nummer</td><td></tr><tr><td> lockIcon</td><td> Symbol</td><td> Zeichenfolge</td><td></tr><tr><td> lockIconTop</td><td> Symbolabstand von oben [%]</td><td> Nummer</td><td></tr><tr><td> lockIconLeft</td><td> Symbolabstand von links [%]</td><td> Nummer</td><td></tr><tr><td> lockIconSize</td><td> Symbolgröße</td><td> Nummer</td><td></tr><tr><td> lockIconColor</td><td> Symbolfarbe</td><td> Zeichenfolge</td><td> hex (# 44739e), rgb (20, 50, 200), rgba (20, 50, 200, 0,5)</tr><tr><td> lockFilterGrayscale</td><td> Graufilter, wenn gesperrt</td><td> Nummer</td><td></tr></tbody></table></details>

## Schalter
![Logo](../../../en/adapterref/iobroker.vis-materialdesign/doc/en/media/switch.gif)

##### Eigenschaften wechseln
Die folgenden Eigenschaften können als [Steuerelement in einer Tabelle] (# Steuerelemente) oder als [HTML-Element](#html-elements) verwendet werden

<details><table><thead><tr><th>Eigentum</th><th> Beschreibung</th><th> Art</th><th> Werte</th></tr></thead><tbody><tr><td> debuggen</td><td> Debug-Modus</td><td> Boolescher Wert</td><td> false | wahr</td></tr><tr><td colspan="4" style="background: #44739e; color: white; border-color: #44739e;"> <i><b>Verbreitet</b></i></td></tr><tr><td> oid</td><td> Objekt Identifikation</td><td> Zeichenfolge</td><td></tr><tr><td> schreibgeschützt</td><td> schreibgeschützt</td><td> Boolescher Wert</td><td> false | wahr</tr><tr><td> toggleType</td><td> Art des Umschalters</td><td> Zeichenfolge</td><td> boolean | Wert</tr><tr><td> valueOff</td><td> Wert für aus</td><td> Zeichenfolge</td><td></tr><tr><td> valueOn</td><td> Wert für auf</td><td> Zeichenfolge</td><td></tr><tr><td> stateIfNotTrueValue</td><td> Geben Sie an, ob der Wert nicht der Bedingung &quot;Ein&quot; entspricht</td><td> Zeichenfolge</td><td> am | aus</tr><tr><td> vibrateOnMobilDevices</td><td> vibrieren auf mobilen Geräten [s]</td><td> Nummer</td><td></tr><tr><td> generateHtmlControl</td><td> HTML-Element generieren</td><td> Zeichenfolge</td><td></tr><tr><td colspan="4" style="background: #44739e; color: white; border-color: #44739e;"><i><b>Beschriftung</b></i></td></tr><tr><td> labelFalse</td><td> Beschriften Sie false</td><td> Zeichenfolge</td><td></tr><tr><td> labelTrue</td><td> Beschriften Sie true</td><td> Zeichenfolge</td><td></tr><tr><td> labelPosition</td><td> labelPosition</td><td> Zeichenfolge</td><td> links | rechts | aus</tr><tr><td> labelClickActive</td><td> Labelklick aktivieren</td><td> Boolescher Wert</td><td> false | wahr</tr><tr><td> valueFontFamily</td><td> valueFontFamily</td><td> Zeichenfolge</td><td></tr><tr><td> valueFontSize</td><td> Wert Schriftgröße</td><td> Nummer</td><td></tr><tr><td colspan="4" style="background: #44739e; color: white; border-color: #44739e;"><i><b>Farben</b></i></td></tr><tr><td> colorSwitchThumb</td><td> Daumenfarbe des Schalters</td><td> Zeichenfolge</td><td> hex (# 44739e), rgb (20, 50, 200), rgba (20, 50, 200, 0,5)</tr><tr><td> colorSwitchTrack</td><td> Spurfarbe des Schalters</td><td> Zeichenfolge</td><td> hex (# 44739e), rgb (20, 50, 200), rgba (20, 50, 200, 0,5)</tr><tr><td> colorSwitchTrue</td><td> aktive Schalterfarbe</td><td> Zeichenfolge</td><td> hex (# 44739e), rgb (20, 50, 200), rgba (20, 50, 200, 0,5)</tr><tr><td> colorSwitchHover</td><td> Schwebefarbe des Schalters</td><td> Zeichenfolge</td><td> hex (# 44739e), rgb (20, 50, 200), rgba (20, 50, 200, 0,5)</tr><tr><td> colorSwitchHoverTrue</td><td> aktive Schalterfarbe ausgewählt / Hover</td><td> Zeichenfolge</td><td> hex (# 44739e), rgb (20, 50, 200), rgba (20, 50, 200, 0,5)</tr><tr><td> labelColorFalse</td><td> Etikettenfarbe</td><td> Zeichenfolge</td><td> hex (# 44739e), rgb (20, 50, 200), rgba (20, 50, 200, 0,5)</tr><tr><td> labelColorTrue</td><td> aktive Etikettenfarbe</td><td> Zeichenfolge</td><td> hex (# 44739e), rgb (20, 50, 200), rgba (20, 50, 200, 0,5)</tr><tr><td colspan="4" style="background: #44739e; color: white; border-color: #44739e;"> <i><b>Verriegeln</b></i></td></tr><tr><td> lockEnabled</td><td> Sperren aktivieren</td><td> Boolescher Wert</td><td> false | wahr</tr><tr><td> autoLockAfter</td><td> automatische Sperre nach [s]</td><td> Nummer</td><td></tr><tr><td> lockIcon</td><td> Symbol</td><td> Zeichenfolge</td><td></tr><tr><td> lockIconTop</td><td> Symbolabstand von oben [%]</td><td> Nummer</td><td></tr><tr><td> lockIconLeft</td><td> Symbolabstand von links [%]</td><td> Nummer</td><td></tr><tr><td> lockIconSize</td><td> Symbolgröße</td><td> Nummer</td><td></tr><tr><td> lockIconColor</td><td> Symbolfarbe</td><td> Zeichenfolge</td><td> hex (# 44739e), rgb (20, 50, 200), rgba (20, 50, 200, 0,5)</tr><tr><td> lockFilterGrayscale</td><td> Graufilter, wenn gesperrt</td><td> Nummer</td><td></tr></tbody></table></details>

## Eingabe
### Text Eingabe
![Logo](../../../en/adapterref/iobroker.vis-materialdesign/doc/en/media/input.gif)

MACHEN

### Wählen
![Logo](../../../en/adapterref/iobroker.vis-materialdesign/doc/en/media/select.gif)

Einstellungen, die in der folgenden Tabelle nicht aufgeführt sind, sind selbsterklärend.

<table><thead><tr><th>Bildschirmfoto</th><th> Rahmen</th><th> Beschreibung</th></tr></thead><tbody><tr><td rowspan=6><img src="doc/en/media/select_autocomplete_settings.png"></td><td> Methode der Daten des Menüs</td><td> Es gibt drei Methoden, um die Daten des Menüs zu definieren. Zunächst muss es über den Editor definiert werden. Zweitens müssen Sie es über eine JSON-Zeichenfolge definieren. Die dritte Methode besteht darin, sie durch drei Listen für Werte, Beschriftungen und Symbole zu definieren</td></tr><tr><td> Editor: Anzahl der Menüpunkte</td><td> Datenmethode des Menüs: über den Editor<br> Definieren Sie die Anzahl der Menüeinträge. Die einzelnen Menüeinträge können unter Menüpunkt [x] definiert werden.</td></tr><tr><td> JSON-Zeichenfolge</td><td> Datenmethode des Menüs: JSON-Zeichenfolge<br> Hier können Sie eine JSON-Zeichenfolge hinzufügen, um die Menüeinträge zu definieren, oder Bindungen an einen Datenpunkt verwenden, der eine JSON-Zeichenfolge enthält.<br><br> JSON-Zeichenfolge muss das folgende Format haben:<br><pre><code> [ { &quot;text&quot;: &quot;text 0&quot;, &quot;subText&quot;: &quot;sub 0&quot;, &quot;value&quot;: &quot;val0&quot;, &quot;icon&quot;: &quot;account-cancel&quot; }, { &quot;text&quot;: &quot;text 1&quot;, &quot;subText&quot;: &quot;sub 1&quot;, &quot;value&quot;: &quot;val1&quot;, &quot;icon&quot;: &quot;/vis/icon/info.png&quot;, &quot;iconColor&quot;: &quot;red&quot;, &quot;iconColorSelectedTextField&quot;: &quot;red&quot; }, { &quot;text&quot;: &quot;text 2&quot;, &quot;subText&quot;: &quot;sub 2&quot;, &quot;value&quot;: &quot;val2&quot;, &quot;icon&quot;: &quot;facebook-workplace&quot;, &quot;iconColor&quot;: &quot;green&quot; } ]</code></pre></td></tr><tr><td> Werteliste</td><td> Datenmethode des Menüs: Werteliste<br> Definieren Sie die Anzahl der Menüeinträge, indem Sie Werte hinzufügen, die auf den Datenpunkt gesetzt werden. Einträge müssen durch Semikolon getrennt werden</td></tr><tr><td> Werteliste: Labels</td><td> Datenmethode des Menüs: Werteliste<br> Definieren Sie die zugehörigen Beschriftungen der Werte. Einträge müssen durch Semikolon getrennt werden</td></tr><tr><td> Werteliste: Labels</td><td> Datenmethode des Menüs: Werteliste<br> Definieren Sie die zugehörigen Symbole der Werte. Einträge müssen durch Semikolon getrennt werden. Sie können den Bildpfad oder den Namen des Material Design Icons verwenden</td></tr></tbody></table>

### Autocomplete
![Logo](../../../en/adapterref/iobroker.vis-materialdesign/doc/en/media/autocomplete.gif)

Einstellungen, die in der folgenden Tabelle nicht aufgeführt sind, sind selbsterklärend.

<table><thead><tr><th>Bildschirmfoto</th><th> Rahmen</th><th> Beschreibung</th></tr></thead><tbody><tr><td rowspan=6><img src="doc/en/media/select_autocomplete_settings.png"></td><td> Methode der Daten des Menüs</td><td> Es gibt drei Methoden, um die Daten des Menüs zu definieren. Zunächst muss es über den Editor definiert werden. Zweitens müssen Sie es über eine JSON-Zeichenfolge definieren. Die dritte Methode besteht darin, sie durch drei Listen für Werte, Beschriftungen und Symbole zu definieren</td></tr><tr><td> Editor: Anzahl der Menüpunkte</td><td> Datenmethode des Menüs: über den Editor<br> Definieren Sie die Anzahl der Menüeinträge. Die einzelnen Menüeinträge können unter Menüpunkt [x] definiert werden.</td></tr><tr><td> JSON-Zeichenfolge</td><td> Datenmethode des Menüs: JSON-Zeichenfolge<br> Hier können Sie eine JSON-Zeichenfolge hinzufügen, um die Menüeinträge zu definieren, oder Bindungen an einen Datenpunkt verwenden, der eine JSON-Zeichenfolge enthält.<br><br> JSON-Zeichenfolge muss das folgende Format haben:<br><pre><code> [ { &quot;text&quot;: &quot;text 0&quot;, &quot;subText&quot;: &quot;sub 0&quot;, &quot;value&quot;: &quot;val0&quot;, &quot;icon&quot;: &quot;account-cancel&quot; }, { &quot;text&quot;: &quot;text 1&quot;, &quot;subText&quot;: &quot;sub 1&quot;, &quot;value&quot;: &quot;val1&quot;, &quot;icon&quot;: &quot;/vis/icon/info.png&quot;, &quot;iconColor&quot;: &quot;red&quot; }, { &quot;text&quot;: &quot;text 2&quot;, &quot;subText&quot;: &quot;sub 2&quot;, &quot;value&quot;: &quot;val2&quot;, &quot;icon&quot;: &quot;facebook-workplace&quot;, &quot;iconColor&quot;: &quot;green&quot; } ]</code></pre></td></tr><tr><td> Werteliste</td><td> Datenmethode des Menüs: Werteliste<br> Definieren Sie die Anzahl der Menüeinträge, indem Sie Werte hinzufügen, die auf den Datenpunkt gesetzt werden. Einträge müssen durch Semikolon getrennt werden</td></tr><tr><td> Werteliste: Labels</td><td> Datenmethode des Menüs: Werteliste<br> Definieren Sie die zugehörigen Beschriftungen der Werte. Einträge müssen durch Semikolon getrennt werden</td></tr><tr><td> Werteliste: Labels</td><td> Datenmethode des Menüs: Werteliste<br> Definieren Sie die zugehörigen Symbole der Werte. Einträge müssen durch Semikolon getrennt werden. Sie können den Bildpfad oder den Namen des Material Design Icons verwenden</td></tr></tbody></table>

## Top App Bar
Die obere App-Leiste mit Navigationsleiste kann mit der <a href="https://www.iobroker.net/#en/documentation/viz/basic.md">Ansicht in Widget 8</a> kombiniert werden.

<b>Schauen Sie sich die [Beispielprojekt für Material Design Widgets](https://github.com/Scrounger/ioBroker.vis-materialdesign#online-example-project)</b> an, um zu verstehen, wie es funktioniert.

##### Layout modal:
![Logo](../../../en/adapterref/iobroker.vis-materialdesign/doc/en/media/topappbar_modal.gif)

##### Layout permanent:
![Logo](../../../en/adapterref/iobroker.vis-materialdesign/doc/en/media/topappbar_permanent.gif)

<table><thead><tr><th>Bildschirmfoto</th><th> Rahmen</th><th> Beschreibung</th></tr></thead><tbody><tr><td rowspan=3><img src="doc/en/media/topappbar_settings.png"></td><td> Objekt Identifikation</td><td> muss von der Typennummer auf einen Datenpunkt gesetzt werden. Beispielsweise kann dieser Datenpunkt von der <a href="https://www.iobroker.net/#en/documentation/viz/basic.md">Ansicht in Widget 8 verwendet werden</a></td></tr><tr><td> Index der Navigationselemente anzeigen</td><td> Zeigt den Navigationsindex vor der Artikelbezeichnung an. Diese Nummer kann in der <a href="https://www.iobroker.net/#en/documentation/viz/basic.md">Ansicht in Widget 8 verwendet werden</a> , um die Ansicht zu definieren, die angezeigt werden soll, wenn das Element ausgewählt ist</td></tr><tr><td> Anzahl der Navigationselemente</td><td> Definieren Sie die Anzahl der Navigationselemente</td></tr></tbody></table>

### Untermenü
![Logo](../../../en/adapterref/iobroker.vis-materialdesign/doc/en/media/drawer_subMenu.png)

Untermenüs müssen durch eine JSON-Zeichenfolge definiert werden:

#### JSON-Eigenschaften
<table><thead><tr><th>Eigentum</th><th> Beschreibung</th><th> Art</th><th> Werte</th></tr></thead><tbody><tr><td> Text</td><td> Text des Eintrags</td><td> Zeichenfolge</td><td></td></tr><tr><td> Symbol</td><td> Symbol oder Bildpfad des Eintritts</td><td> Zeichenfolge</td><td></td></tr><tr><td> iconColor</td><td> Symbolfarbe (funktioniert nicht, wenn Bild verwendet wird)</td><td> Farbe</td><td> hex (# 44739e), rgb (20, 50, 200), rgba (20, 50, 200, 0,5)</td></tr><tr><td> Teiler</td><td> zeige einen Teiler</td><td> Boolescher Wert</td><td> Falsch Richtig</td></tr><tr><td> Benutzergruppen</td><td> Benutzergruppen, die diesen Eintrag anzeigen und steuern dürfen.</td><td> Array [Zeichenfolge]</td><td> ID der Benutzergruppen</td></tr><tr><td> behaviourNotInUserGroup</td><td> Eintrag ausblenden oder deaktivieren, wenn der Benutzer nicht Teil der Benutzergruppe ist</td><td> Zeichenfolge</td><td> verstecken, deaktiviert</td></tr></tbody></table>

<! - in toc weglassen ->

#### Beispiel
<details> <pre><code> [ { "text": "subitem0", "icon": "account", "iconColor": "red" }, { "text": "subitem1", "icon": "home", "iconColor": "green", "divider": "true" }, { "text": "subitem1", "divider": "true", "icon": "/vis.0/myImages/devices/lxc_iobroker.png", "userGroups": ["administrator", "user"], "behaviorNotInUserGroup": "disabled" } ] </code></pre> </details>

## Diagramme
### Balkendiagramm
![Logo](../../../en/adapterref/iobroker.vis-materialdesign/doc/en/media/barChart.png)

#### Editoreinstellungen
Einstellungen, die in der folgenden Tabelle nicht aufgeführt sind, sind selbsterklärend.

<table><thead><tr><th>Bildschirmfoto</th><th> Rahmen</th><th> Beschreibung </th></tr></thead><tbody><tr><td rowspan=3><img src="doc/en/media/barchart_settings_common.png"></td><td>Datensätze setzen mit</td><td> Die Daten für das BarChart können über den Editor eingegeben oder eine JSON-Zeichenfolge verwendet werden</td></tr><tr><td> Anzahl der Teile</td><td> Anzahl der Balken mit dem vis-Editor für die Daten der Liste</td></tr><tr><td> Objekt Identifikation</td><td> Objekt-ID des Datenpunkts, der die JSON-Zeichenfolge enthält. Zulässige Eigenschaften werden unten beschrieben</td></tr><tr><td rowspan=><img src="doc/en/media/barchart_settings_dataset.png"></td><td> Objekt-ID [x]</td><td> Objekt-ID für die einzelnen Balken mit dem vis-Editor</td></tr></tbody></table>

#### JSON-Eigenschaften
Die JSON-Zeichenfolge muss ein Array von Objekten mit den folgenden Eigenschaften sein:

<table><thead><tr><th>Eigentum</th><th> Beschreibung</th><th> Art</th><th> Werte</th></tr></thead><tbody><tr><td> Etikette</td><td> Achsenbeschriftung des Balkens</td><td> Zeichenfolge</td><td/></tr><tr><td> Wert</td><td> Balkenwert</td><td> Nummer</td><td/></tr><tr><td> dataColor</td><td> Balkenfarbe</td><td> Zeichenfolge</td><td/></tr><tr><td> valueText</td><td> Text der Leiste überschreiben</td><td> Zeichenfolge</td><td/></tr><tr><td> valueColor</td><td> Farbe des Wertetextes</td><td> hex (# 44739e), rgb (20, 50, 200), rgba (20, 50, 200, 0,5)</td><td/></tr><tr><td> valueAnhang</td><td> Anhang des Wertetextes</td><td> Zeichenfolge</td><td/></tr><tr><td> tooltipTitle</td><td> Tooltip-Titel</td><td> Zeichenfolge</td><td/></tr><tr><td> tooltipText</td><td> Tooltip-Text</td><td> Zeichenfolge</td><td/></tr></tbody></table>

<! - in toc weglassen ->

#### Beispiel
<details> <pre><code> [ { "label": "val0", "value": "30", "valueColor": "#ffffff" }, { "label": "val1", "value": "12.54645646", "tooltipTitle": "myTitle" }, { "label": "val2", "value": "48", "dataColor": "#c2c2c2", "valueAppendix": "\n extra" }, { "label": "val3", "value": "97", "valueColor": "#ffffff" }, { "label": "val4", "value": "32", "valueText": "text" } ] </pre></code> </details>

### Kuchendiagramm
![Logo](../../../en/adapterref/iobroker.vis-materialdesign/doc/en/media/pieChart.png)

#### Editoreinstellungen
Einstellungen, die in der folgenden Tabelle nicht aufgeführt sind, sind selbsterklärend.

<table><thead><tr><th>Bildschirmfoto</th><th> Rahmen</th><th> Beschreibung </th></tr></thead><tbody><tr><td rowspan=3><img src="doc/en/media/piechart_settings_common.png"></td><td>Datensätze setzen mit</td><td> Die Daten für das PieChart können über den Editor eingegeben oder eine JSON-Zeichenfolge verwendet werden</td></tr><tr><td> Anzahl der Teile</td><td> Anzahl der Tortenstücke mit vis editor für die Daten der Liste</td></tr><tr><td> Objekt Identifikation</td><td> Objekt-ID des Datenpunkts, der die JSON-Zeichenfolge enthält. Zulässige Eigenschaften werden unten beschrieben</td></tr><tr><td rowspan=><img src="doc/en/media/barchart_settings_dataset.png"></td><td> Objekt-ID [x]</td><td> Objekt-ID für die Einzelkuchenstücke mit dem vis-Editor</td></tr></tbody></table>

#### JSON-Eigenschaften
Die JSON-Zeichenfolge muss ein Array von Objekten mit den folgenden Eigenschaften sein:

### Linienverlaufsdiagramm:
> Erforderlicher Adapter: [SQL] (https://github.com/ioBroker/ioBroker.sql), [Verlauf] (https://github.com/ioBroker/ioBroker.history) oder [InfluxDb](https://github.com/ioBroker/ioBroker.influxdb)!

![Logo](../../../en/adapterref/iobroker.vis-materialdesign/doc/en/media/line_history_chart.gif)

#### Editoreinstellungen
Einstellungen, die in der folgenden Tabelle nicht aufgeführt sind, sind selbsterklärend.

<table><thead><tr><th>Bildschirmfoto</th><th> Rahmen</th><th> Beschreibung </th></tr></thead><tbody><tr><td rowspan=5><img src="doc/en/media/line_hostory_chart_general.png"></td><td> Adapterinstanz</td><td> Instanz für den SQL- oder Verlaufsadapter</td></tr><tr><td> Zeitintervall mit Objekt steuern</td><td> ID eines Datenpunkts zum Ändern des Zeitintervalls des Diagramms.<br><br> Wenn der Datenpunkt vom Typ &#39;Zeichenfolge&#39; ist, muss er <a href="https://github.com/Scrounger/ioBroker.vis-materialdesign/blob/235530e4e54346b5527333ca06ce596519954c67/widgets/materialdesign/js/materialdesign.chart.js#L802">einen der verknüpften Werte enthalten</a><br> Wenn der Datenpunkt vom Typ &#39;Nummer&#39; ist, muss er den Startzeitstempel des Diagramms enthalten.<br><br> Beispielsweise können Sie hier eine Schaltfläche verwenden, um die Anzeige des Diagramms zur Laufzeit zu ändern</td></tr><tr><td> Boolesches Objekt zum Aktualisieren</td><td> ID von adatapoint, um eine manuelle Aktualisierung des Diagramms auszulösen.<br> Beispielsweise können Sie hier eine Schaltfläche verwenden, um das Diagramm zur Laufzeit zu aktualisieren</td></tr><tr><td> Diagramm-Timeout</td><td> Zeitüberschreitung beim Laden der Diagrammdaten. Wenn Sie eine Timeout-Fehlermeldung erhalten, erhöhen Sie diesen Wert</td></tr><tr><td> Debug-Modus</td><td> Wenn Sie Probleme oder Fehler haben, aktivieren Sie den Debug-Modus und hängen Sie die Daten des Konsolenprotokolls (F12) an das Problem an</td></tr><tr><td rowspan=5><img src="doc/en/media/line_hostory_chart_dataset.png"></td><td> Objekt-ID [x]</td><td> ID des Datenpunkts mit aktivierter Verlaufsinstanz</td></tr><tr><td> Anzeigemethode [x]</td><td> <a href="https://www.iobroker.net/docu/index-195.htm?page_id=198&lang=en#Aggregation">Aggregationsmethode</a></td></tr><tr><td> max. Anzahl der anzuzeigenden Datenpunkte [x]</td><td> Anzahl der maximal anzuzeigenden Datenpunkte</td></tr><tr><td> Zeitintervall zwischen den Datenpunkten in [s] [x]</td><td> Die optionale Einstellung überschreibt die Einstellung &#39;Anzahl&#39;.<br> Abstand zwischen den einzelnen Datenpunkten in Sekunden.<br> Wenn Sie beispielsweise jede Minute Datenpunkte anzeigen möchten, müssen Sie hier 60 eingeben</td></tr><tr><td> Daten multiplizieren mit [x]</td><td> Optionale Einstellung: Multiplizieren Sie jeden Datenpunkt mit dem angegebenen Wert</td></tr><tr><td><img src="doc/en/media/line_hostory_chart_xAxis_layout.png"></td><td> Zeitformate der x-Achse</td><td> Ändern Sie das Zeitformat der X-Achse. Zeitformate müssen für alle Zeiteinheiten eingegeben werden, <a href="https://github.com/Scrounger/ioBroker.vis-materialdesign/blob/c677220868961b3cf0b153fb8bf04e13b4475c09/widgets/materialdesign/js/materialdesign.chart.js#L805">die folgenden Zeiteinheiten sind zulässig.</a><br> Genehmigte Zeitformate müssen gemäß der Bibliothek moment.js eingegeben werden, <a href="https://momentjs.com/docs/#/displaying/">siehe Link</a></td></tr><tr><td><img src="doc/en/media/line_hostory_chart_tooltip_layout.png"></td><td> Tooltip-Zeitformate</td><td> Ändern Sie das Zeitformat des Tooltips. Zeitformate müssen für alle Zeiteinheiten eingegeben werden, <a href="https://github.com/Scrounger/ioBroker.vis-materialdesign/blob/c677220868961b3cf0b153fb8bf04e13b4475c09/widgets/materialdesign/js/materialdesign.chart.js#L805">die folgenden Zeiteinheiten sind zulässig.</a><br> Genehmigte Zeitformate müssen gemäß der Bibliothek moment.js eingegeben werden, <a href="https://momentjs.com/docs/#/displaying/">siehe Link</a></td></tr></tbody></table>

### JSON-Diagramm
Mit dem JSON-Diagramm haben Sie die maximale Freiheit, ein gemischtes Diagramm (Linie, Balken und gestapelte Balken) per Skript zu erstellen.

![Logo] (doc / de / media / jsonChart.png)! [Logo](../../../en/adapterref/iobroker.vis-materialdesign/doc/en/media/jsonChart2.png)

#### JSON-Eigenschaften
<! - in toc weglassen ->

##### Allgemeines
<table><thead><tr><th>Eigentum</th><th> Beschreibung</th><th> Art</th><th> Werte</th></tr></thead><tbody><tr><td> axisLabels</td><td> Achsenbeschriftung des Graphen</td><td> Array</td><td> Zahlen oder Zeichenfolge</td></tr><tr><td> Grafiken</td><td> Daten von Graphen</td><td> Array &lt; <a href="#graph">Graph</a> &gt;</td><td> siehe Grafik</td></tr></tbody></table>

<! - in toc weglassen ->

##### Grafik
<details><table><thead><tr><th>Eigentum</th><th> Beschreibung</th><th> Art</th><th> Werte</th></tr></thead><tbody><tr><td> Daten</td><td> Daten des Graphen oder Daten mit Zeitstempel</td><td> Array [Zahlen] | Array [ <a href="#data-with-time-axis">Werte mit Zeitstempel</a> ]</td><td> Nummer</td></tr><tr><td> Art</td><td> Art des Diagramms</td><td> Zeichenfolge</td><td> &#39;line&#39;, &#39;bar&#39;</td></tr><tr><td> legendText</td><td> Text der Legende</td><td> Zeichenfolge</td><td></td></tr><tr><td> Bestellung anzeigen</td><td> Überlagerungsreihenfolge des Diagramms</td><td> Nummer</td><td> 1, 2, ...</td></tr><tr><td> Farbe</td><td> Farbe des Graphen</td><td> Farbe</td><td> hex (# 44739e), rgb (20, 50, 200), rgba (20, 50, 200, 0,5)</td></tr><tr><td> use_gradient_color</td><td> Verwenden Sie eine Verlaufsfarbe</td><td> Boolescher Wert</td><td> Falsch Richtig</td></tr><tr><td> Farbverlauf</td><td> Farbverlaufsarray</td><td> Array [ <a href="#gradientcolor">gradientColor</a> ]</td><td> [{Wert: -20, Farbe: &#39;# 7d3c98&#39;}, {Wert: 0, Farbe: &#39;# 2874a6&#39;}]</td></tr><tr><td> tooltip_title</td><td> Titel des Tooltips</td><td> Zeichenfolge</td><td></td></tr><tr><td> tooltip_text</td><td> Übergreifender Text des Tooltips</td><td> Zeichenfolge</td><td></td></tr><tr><td> tooltip_MinDigits</td><td> Maximale Dezimalstellen des Tooltip-Werts</td><td> Nummer</td><td> 0, 1, 2, ...</td></tr><tr><td> tooltip_MaxDigits</td><td> Maximale Dezimalstellen des Tooltip-Werts</td><td> Nummer</td><td> 0, 1, 2, ...</td></tr><tr><td> tooltip_AppendText</td><td> Fügen Sie Text an den Tooltip-Wert an</td><td> Zeichenfolge</td><td></td></tr><tr><td> datalabel_show</td><td> Datenbeschriftungen für Grafik anzeigen</td><td> Zeichenfolge | Boolescher Wert</td><td> false, true, auto</td></tr><tr><td> datalabel_anchor</td><td> Anker von Datenetiketten</td><td> Zeichenfolge</td><td> zentrieren, beginnen, enden</td></tr><tr><td> datalabel_align</td><td> Position des Datenetiketts relativ zum Ankerpunkt</td><td> Zeichenfolge</td><td> links, Start, Mitte, Ende, rechts, oben, unten</td></tr><tr><td> datalabel_offset</td><td> Abstand (in Pixel), um das Datenetikett vom Ankerpunkt wegzuziehen</td><td> Nummer</td><td> 0, 1, 2, ...</td></tr><tr><td> datalabel_text_align</td><td> Textausrichtung des Datenetiketts</td><td> Zeichenfolge</td><td> links, Start, Mitte, Ende, rechts</td></tr><tr><td> datalabel_rotation</td><td> Drehwinkel des Datenetiketts im Uhrzeigersinn (in Grad)</td><td> Nummer</td><td> 0, 1, 2, ...</td></tr><tr><td> datalabel_steps</td><td> Datenbeschriftung bei jedem x-Schritt anzeigen</td><td> Nummer</td><td> 0, 1, 2, ...</td></tr><tr><td> datalabel_minDigits</td><td> minimale Dezimalstellen von Datenetiketten</td><td> Nummer</td><td> 0, 1, 2, ...</td></tr><tr><td> datalabel_maxDigits</td><td> maximale Dezimalstellen von Datenbeschriftungen</td><td> Nummer</td><td> 0, 1, 2, ...</td></tr><tr><td> datalabel_append</td><td> Text an Datenetikett anhängen</td><td> Zeichenfolge</td><td></td></tr><tr><td> datalabel_color</td><td> Datenetikettenfarbe</td><td> Farbe | Array [Farben]</td><td> hex (# 44739e), rgb (20, 50, 200), rgba (20, 50, 200, 0,5)</td></tr><tr><td> datalabel_fontFamily</td><td> Datenetiketten-Schriftfamilie</td><td> Zeichenfolge</td><td></td></tr><tr><td> datalabel_fontSize</td><td> Schriftgröße der Datenbeschriftung</td><td> Nummer</td><td> 1, 2, 5, ...</td></tr><tr><td> datalabel_backgroundColor</td><td> Hintergrundfarbe des Datenetiketts</td><td> Farbe | Array [Farben]</td><td> hex (# 44739e), rgb (20, 50, 200), rgba (20, 50, 200, 0,5)</td></tr><tr><td> datalabel_borderColor</td><td> Randfarbe der Datenbeschriftung</td><td> Farbe | Array [Farben]</td><td> hex (# 44739e), rgb (20, 50, 200), rgba (20, 50, 200, 0,5)</td></tr><tr><td> datalabel_borderWidth</td><td> Breite des Datenetikettenrahmens</td><td> Nummer</td><td> 1, 2, 5, ...</td></tr><tr><td> datalabel_borderRadius</td><td> Randradius der Datenbeschriftung</td><td> Nummer</td><td> 1, 2, 5, ...</td></tr></tbody></table></details>

<! - in toc weglassen ->

##### Grafik Liniendiagramm spfeicifc
<details><table><thead><tr><th>Eigentum</th><th> Beschreibung</th><th> Art</th><th> Werte</th></tr></thead><tbody><tr><td> line_pointStyle</td><td> Punktstil der Linie</td><td> Zeichenfolge</td><td> Kreis, Kreuz, CrossRot, Strich, Linie, Rect, RectRounded, RectRot, Stern, Dreieck</td></tr><tr><td> line_pointSize</td><td> Punktgröße der Linie</td><td> Nummer</td><td> 1, 2, 3, ...</td></tr><tr><td> line_pointSizeHover</td><td> Punktgröße der Linie</td><td> Nummer</td><td> 1, 2, 3, ...</td></tr><tr><td> line_PointColor</td><td> Farbe des Linienpunktes</td><td> Farbe | Array [Farben]</td><td> hex (# 44739e), rgb (20, 50, 200), rgba (20, 50, 200, 0,5)</td></tr><tr><td> line_PointColorBorder</td><td> Randfarbe des Linienpunktes</td><td> Farbe | Array [Farben]</td><td> hex (# 44739e), rgb (20, 50, 200), rgba (20, 50, 200, 0,5)</td></tr><tr><td> line_PointColorHover</td><td> Schwebefarbe des Linienpunktes</td><td> Farbe | Array [Farben]</td><td> hex (# 44739e), rgb (20, 50, 200), rgba (20, 50, 200, 0,5)</td></tr><tr><td> line_PointColorBorderHover</td><td> Rand Schwebefarbe des Linienpunktes</td><td> Farbe | Array [Farben]</td><td> hex (# 44739e), rgb (20, 50, 200), rgba (20, 50, 200, 0,5)</td></tr><tr><td> line_spanGaps</td><td> Zeichnen Sie Linien, wenn die Daten Lücken aufweisen</td><td> Boolescher Wert</td><td> Falsch Richtig</td></tr><tr><td> line_steppedLine</td><td> gestufte Linie aktivieren</td><td> Boolescher Wert</td><td> Falsch Richtig</td></tr><tr><td> line_Tension</td><td> Glätte der Linie</td><td> Nummer</td><td> 0 - 1</td></tr><tr><td> dicke der Linie</td><td> Dicke der Linie</td><td> Nummer</td><td> 1, 2, 5, ...</td></tr><tr><td> line_UseFillColor</td><td> Verwenden Sie die Füllfarbe unter der Linie</td><td> Boolescher Wert</td><td> Falsch Richtig</td></tr><tr><td> line_FillColor</td><td> Füllfarbe unter Linie</td><td> Farbe</td><td> hex (# 44739e), rgb (20, 50, 200), rgba (20, 50, 200, 0,5)</td></tr><tr><td> use_line_gradient_fill_color</td><td> Verwenden Sie die Verlaufsfüllfarbe</td><td> Boolescher Wert</td><td> Falsch Richtig</td></tr><tr><td> line_gradient_fill_color</td><td> Farbverlaufsarray</td><td> Array [ <a href="#gradientcolor">gradientColor</a> ]</td><td> [{Wert: -20, Farbe: &#39;# 7d3c98&#39;}, {Wert: 0, Farbe: &#39;# 2874a6&#39;}]</td></tr><tr><td> line_FillBetweenLines</td><td> Füllfarbe bis zur nächsten / vorherigen Zeile</td><td> Zeichenfolge</td><td> &#39;+1&#39;, &#39;-1&#39;, &#39;+2&#39;, ...</td></tr></tbody></table></details>

<! - in toc weglassen ->

##### Diagramm Balkendiagramm spfeicifc
<details><table><thead><tr><th>Eigentum</th><th> Beschreibung</th><th> Art</th><th> Werte</th></tr></thead><tbody><tr><td> barIsStacked</td><td> gestapelte Stange. Wenn Sie ein kombiniertes Diagramm (Linie + gestapelter Balken) haben, müssen Sie diesen Wert auch für den Liniendatensatz festlegen!</td><td> Boolescher Wert</td><td> Falsch Richtig</td></tr><tr><td> barStackId</td><td> ID des Stapels. Balken, die zu einem Stapel kombiniert werden sollen, müssen dieselbe ID haben</td><td> Nummer</td><td> 1, 2, 5, ...</td></tr><tr><td> barColorHover</td><td> Schwebefarbe des Balkens</td><td> Farbe | Array [Farben]</td><td> hex (# 44739e), rgb (20, 50, 200), rgba (20, 50, 200, 0,5)</td></tr><tr><td> barBorderColor</td><td> Randfarbe des Balkens</td><td> Farbe | Array [Farben]</td><td> hex (# 44739e), rgb (20, 50, 200), rgba (20, 50, 200, 0,5)</td></tr><tr><td> barBorderWidth</td><td> Dicke der Balkengrenze</td><td> Nummer</td><td> 1, 2, 5, ...</td></tr><tr><td> barBorderColorHover</td><td> Rand Schwebefarbe der Leiste</td><td> Farbe | Array [Farben]</td><td> hex (# 44739e), rgb (20, 50, 200), rgba (20, 50, 200, 0,5)</td></tr><tr><td> barBorderWidthHover</td><td> Schweben Sie die Dicke der Balkengrenze</td><td> Nummer</td><td> 1, 2, 5, ...</td></tr></tbody></table></details>

<! - in toc weglassen ->

##### Graph y-Achse
<details><table><thead><tr><th>Eigentum</th><th> Beschreibung</th><th> Art</th><th> Werte</th></tr></thead><tbody><tr><td> yAxis_id</td><td> ID der y-Achse. Wenn Sie eine gemeinsame y-Achse für mehrere Diagrammdaten verwenden möchten, verwenden Sie dieselbe ID.</td><td> Nummer</td><td> 1, 2, 5, ...</td></tr><tr><td> yAxis_position</td><td> Position der y-Achse</td><td> Zeichenfolge</td><td> links rechts</td></tr><tr><td> yAxis_show</td><td> y-Achse zeigen</td><td> Boolescher Wert</td><td> Falsch Richtig</td></tr><tr><td> yAxis_title_text</td><td> Titel der y-Achse</td><td> Zeichenfolge</td><td></td></tr><tr><td> yAxis_title_color</td><td> Überschreiben Sie die Titelfarbe der y-Achse</td><td> Farbe</td><td> hex (# 44739e), rgb (20, 50, 200), rgba (20, 50, 200, 0,5)</td></tr><tr><td> yAxis_title_fontFamily</td><td> Überschreiben Sie die Schriftfamilie der Titel auf der y-Achse</td><td> Zeichenfolge</td><td></td></tr><tr><td> yAxis_title_fontSize</td><td> Überschreiben Sie die Schriftgröße des Titels der y-Achse</td><td> Nummer</td><td> 1, 2, 5, ...</td></tr><tr><td> yAxis_min</td><td> Minimalwert der y-Achse</td><td> Nummer</td><td> 1, 2, 5, ...</td></tr><tr><td> yAxis_max</td><td> Maximalwert der y-Achse</td><td> Nummer</td><td> 1, 2, 5, ...</td></tr><tr><td> yAxis_step</td><td> Schritte der y-Achse</td><td> Nummer</td><td> 1, 2, 5, ...</td></tr><tr><td> yAxis_minimumDigits</td><td> Mindestanzahl von Dezimalstellen auf der y-Achse</td><td> Nummer</td><td> 1, 2, 5, ...</td></tr><tr><td> yAxis_maximumDigits</td><td> y-Achse maximale Anzahl von Dezimalstellen</td><td> Nummer</td><td> 1, 2, 5, ...</td></tr><tr><td> yAxis_maxSteps</td><td> maximale Schritte der y-Achse</td><td> Nummer</td><td> 1, 2, 5, ...</td></tr><tr><td> yAxis_distance</td><td> y-Achsenwert Abstand zur Achse überschreiben</td><td> Nummer</td><td> 1, 2, 5, ...</td></tr><tr><td> yAxis_appendix</td><td> Fügen Sie Text an den Wert der y-Achse an</td><td> Zeichenfolge</td><td></td></tr><tr><td> yAxis_color</td><td> Überschreiben Sie die Farbe des y-Achsenwerts</td><td> Farbe</td><td> hex (# 44739e), rgb (20, 50, 200), rgba (20, 50, 200, 0,5)</td></tr><tr><td> yAxis_fontFamily</td><td> Überschreiben Sie die Schriftfamilie der y-Achsenwerte</td><td> Zeichenfolge</td><td></td></tr><tr><td> yAxis_fontSize</td><td> Überschreiben Sie die Schriftgröße des y-Achsenwerts</td><td> Nummer</td><td> 1, 2, 5, ...</td></tr><tr><td> yAxis_zeroLineWidth</td><td> Breite der Nulllinie der y-Achse</td><td> Nummer</td><td> 0,3, 1,5, 4, ...</td></tr><tr><td> yAxis_zeroLineColor</td><td> Nulllinienfarbe der y-Achse</td><td> Farbe</td><td> hex (# 44739e), rgb (20, 50, 200), rgba (20, 50, 200, 0,5)</td></tr><tr><td> yAxis_gridLines_show</td><td> Y-Achsen-Gitterlinien anzeigen</td><td> Boolescher Wert</td><td> Falsch Richtig</td></tr><tr><td> yAxis_gridLines_color</td><td> Farbe der Gitterlinien der y-Achse</td><td> Farbe</td><td> hex (# 44739e), rgb (20, 50, 200), rgba (20, 50, 200, 0,5)</td></tr><tr><td> yAxis_gridLines_lineWidth</td><td> Breite der Gitterlinien</td><td> Nummer</td><td> 0 - 1</td></tr><tr><td> yAxis_gridLines_border_show</td><td> Rand der Gitterlinien der y-Achse anzeigen</td><td> Boolescher Wert</td><td> Falsch Richtig</td></tr><tr><td> yAxis_gridLines_ticks_show</td><td> Zeige Tick-Intervall-Ticks auf der y-Achse</td><td> Boolescher Wert</td><td> Falsch Richtig</td></tr><tr><td> yAxis_gridLines_ticks_length</td><td> Länge der Y-Achsen-Gitter-Ticks</td><td> Nummer</td><td> 1, 2, 5, ...</td></tr></tbody></table></details>

<! - in toc weglassen ->

##### Farbverlauf
<details><table><thead><tr><th>Eigentum</th><th> Beschreibung</th><th> Art</th><th> Werte</th></tr></thead><tbody><tr><td> Wert</td><td> Wert, bei dem Farbe angewendet werden soll</td><td> Nummer</td><td> 1, 2, 5, ...</td></tr><tr><td> Farbe</td><td> Farbe für Wert</td><td> Farbe</td><td> hex (# 44739e), rgb (20, 50, 200), rgba (20, 50, 200, 0,5)</td></tr></tbody></table></details>

<! - in toc weglassen ->

##### Diagramm mit Zeitachse JSON-Diagramm unterstützt Daten mit einem Zeitstempel. Um dies zu verwenden, muss das Datenarray Werte für Zeitstempel (x-Achsenwert) und Wert (y-Achsenwert) haben.
###### Werte mit Zeitstempel
<details><table><thead><tr><th>Eigentum</th><th> Beschreibung</th><th> Art</th><th> Werte</th></tr></thead><tbody><tr><td> t</td><td> Zeitstempel - xAxis-Wert</td><td> Nummer</td><td> 1, 2, 5, ...</td></tr><tr><td> y</td><td> Wert für Zeitstempel - yAxis-Wert</td><td> Nummer</td><td> 1, 2, 5, ...</td></tr></tbody></table></details>

###### X-Achseneinstellungen für Daten mit Zeitstempel
<details><table><thead><tr><th>Eigentum</th><th> Beschreibung</th><th> Art</th><th> Werte</th></tr></thead><tbody><tr><td> xAxis_bounds</td><td> Skalengrenzstrategie<br><br> &#39;Daten&#39;: Stellt sicher, dass die Daten vollständig sichtbar sind und Beschriftungen außerhalb entfernt werden<br> &#39;Ticks&#39;: Stellt sicher, dass die Ticks vollständig sichtbar sind und die Daten außerhalb abgeschnitten werden</td><td> String</td><td> Daten, Zecken</td></tr><tr><td> xAxis_timeFormats</td><td> Zeitformate für die x-Achse</td><td> Objekt</td><td> Zeitformate müssen für alle Zeiteinheiten eingegeben werden, <a href="https://github.com/Scrounger/ioBroker.vis-materialdesign/blob/c677220868961b3cf0b153fb8bf04e13b4475c09/widgets/materialdesign/js/materialdesign.chart.js#L805">die folgenden Zeiteinheiten sind zulässig.</a><br> Genehmigte Zeitformate müssen gemäß der Bibliothek moment.js eingegeben werden, <a href="https://momentjs.com/docs/#/displaying/">siehe Link</a></td></tr><tr><td> xAxis_tooltip_timeFormats</td><td> Zeitformate für die x-Achse</td><td> String</td><td> Genehmigte Zeitformate müssen gemäß der Bibliothek moment.js eingegeben werden, <a href="https://momentjs.com/docs/#/displaying/">siehe Link</a></td></tr><tr><td> xAxis_time_unit</td><td> Erzwinge das Zeitformat für die x-Achse</td><td> String</td><td> Folgende Einheiten sind erlaubt, <a href="https://www.chartjs.org/docs/latest/axes/cartesian/time.html#time-units">siehe Link</a></td></tr></tbody></table></details>

<! - in toc weglassen ->

#### Beispiel
<details> <pre><code> { "axisLabels": ["1h", "2h", "3h", "4h", "5h", "6h", "7h", "8h", "9h", "10h", "11h", "12h", "13h", "14h", "17h", "18h", "19h", "20h", "21h", "22h", "23h", "24h"], "graphs": [ { "data": [19, 19, 18, 19, 19, 20, 20, 21, 22, 24, 24, 24, 23, 22, 23, 23, 24, 23, 23, 22, 22, 21, 20, 20], "type": "line", "color": "gray", "legendText": "Temperatur", "line_pointSizeHover": 5, "line_pointSize": 0, "line_Tension": 0.3, "yAxis_show": false, "yAxis_gridLines_show": false, "yAxis_gridLines_ticks_length": 5, "yAxis_min": 0, "yAxis_max": 30, "yAxis_step": 5, "yAxis_position": "left", "yAxis_appendix": " °C", "yAxis_zeroLineWidth": 0.1, "yAxis_zeroLineColor": "black", "displayOrder": 0, "tooltip_AppendText": " °C", "datalabel_backgroundColor": ["#2b9a44", "#2b9a44", "#3aa35b", "#2b9a44", "#2b9a44", "#1d922e", "#1d922e", "#0e8917", "#008000", "#668f00", "#668f00", "#668f00", "#338700", "#008000", "#338700", "#338700", "#668f00", "#338700", "#338700", "#008000", "#008000", "#0e8917", "#1d922e", "#1d922e"], "datalabel_color": "white", "datalabel_offset": -10, "datalabel_fontFamily": "RobotoCondensed-Light", "datalabel_fontSize": 12, "datalabel_borderRadius": 6, "datalabel_show": "auto", "line_PointColor": ["#2b9a44", "#2b9a44", "#3aa35b", "#2b9a44", "#2b9a44", "#1d922e", "#1d922e", "#0e8917", "#008000", "#668f00", "#668f00", "#668f00", "#338700", "#008000", "#338700", "#338700", "#668f00", "#338700", "#338700", "#008000", "#008000", "#0e8917", "#1d922e", "#1d922e"], "line_PointColorBorder": ["#2b9a44", "#2b9a44", "#3aa35b", "#2b9a44", "#2b9a44", "#1d922e", "#1d922e", "#0e8917", "#008000", "#668f00", "#668f00", "#668f00", "#338700", "#008000", "#338700", "#338700", "#668f00", "#338700", "#338700", "#008000", "#008000", "#0e8917", "#1d922e", "#1d922e"], "line_PointColorHover": ["#2b9a44", "#2b9a44", "#3aa35b", "#2b9a44", "#2b9a44", "#1d922e", "#1d922e", "#0e8917", "#008000", "#668f00", "#668f00", "#668f00", "#338700", "#008000", "#338700", "#338700", "#668f00", "#338700", "#338700", "#008000", "#008000", "#0e8917", "#1d922e", "#1d922e"], "line_PointColorBorderHover": ["#2b9a44", "#2b9a44", "#3aa35b", "#2b9a44", "#2b9a44", "#1d922e", "#1d922e", "#0e8917", "#008000", "#668f00", "#668f00", "#668f00", "#338700", "#008000", "#338700", "#338700", "#668f00", "#338700", "#338700", "#008000", "#008000", "#0e8917", "#1d922e", "#1d922e"], "use_gradient_color": true, "gradient_color": [{ "value": -20, "color": "#5b2c6f66" }, { "value": 0, "color": "#2874a666" }, { "value": 14, "color": "#73c6b666" }, { "value": 22, "color": "#00800066" }, { "value": 27, "color": "#ffa50066" }, { "value": 35, "color": "#ff000066" } ], "use_line_gradient_fill_color": true, "line_gradient_fill_color": [{ "value": -20, "color": "#5b2c6f66" }, { "value": 0, "color": "#2874a666" }, { "value": 14, "color": "#73c6b666" }, { "value": 22, "color": "#00800066" }, { "value": 27, "color": "#ffa50066" }, { "value": 35, "color": "#ff000066" } ] }, { "data": [50, 50, 50, 50, 50, 50, 50, 50, 50, 50, 50, 50, 50, 19, 33, 36, 23, 14, 16, 34, 46, 40, 24, 22], "type": "line", "color": "#0d47a1", "legendText": "Regenwahrscheinlichkeit", "line_UseFillColor": true, "line_pointSize": 0, "line_pointSizeHover": 5, "yAxis_min": 0, "yAxis_max": 100, "yAxis_maxSteps": 10, "yAxis_position": "left", "yAxis_gridLines_show": false, "yAxis_gridLines_border_show": false, "yAxis_zeroLineWidth": 0.1, "yAxis_zeroLineColor": "black", "yAxis_appendix": " %", "displayOrder": 1, "tooltip_AppendText": " %", "datalabel_show": false }, { "data": ["0", "0", "0", "0", "0", "0", "0", "0", "0", "0", "0", "1.3", "2.5", 0, 1.9, 1.17, 0, 0, 0, 0.18, 0.7, 0.2, 0, 0], "type": "bar", "color": "#6dd600", "legendText": "Niederschlag", "yAxis_min": 0, "yAxis_max": 5, "yAxis_maxSteps": 10, "yAxis_position": "right", "yAxis_gridLines_show": false, "yAxis_appendix": " mm", "yAxis_gridLines_border_show": false, "yAxis_zeroLineWidth": 0.1, "yAxis_zeroLineColor": "black", "displayOrder": 1, "tooltip_AppendText": " mm", "datalabel_show": false } ] }

</ pre> </ code> </ details>

## Tabelle
![Logo](../../../en/adapterref/iobroker.vis-materialdesign/doc/en/media/table.gif)

### Eingabedaten
Eingabedaten müssen ein JSON-Array von Objekten sein, Beispiel:

```
[
	{
		"img": "/vis.0/myImages/erlebnis_50.png",
		"name": "Empire",
		"betriebszeit": "4h 06m",
		"funk": "5G",
		"ip": "10.0.0.1"
	},
	{
		"img": "/vis.0/myImages/erlebnis_100.png",
		"name": "Handy",
		"betriebszeit": "13m",
		"funk": "5G",
		"ip": "10.0.0.2"
	},
	{
		"img": "/vis.0/myImages/erlebnis_100.png",
		"name": "Harmony Hub - Wohnzimmer",
		"betriebszeit": "18T 07h 21m",
		"funk": "2G",
		"ip": "10.0.0.3"
	}
]
```

#### Steuerelemente
Um ein Steuerelement (Schaltfläche, Kontrollkästchen usw.) in der Zelle der Tabelle zu generieren, müssen Sie ein Objekt anstelle einer Zeichenfolge erstellen.

![Logo](../../../en/adapterref/iobroker.vis-materialdesign/doc/en/media/table_control_example.gif)

```
[
	{
		"control": {
			"type": "buttonToggle",
			"oid": "0_userdata.0.MDW.Buttons.bool",
			"buttonText": "&nbsp;off",
			"buttonTextTrue": "&nbsp;on",
			"image": "home",
			"imagePosition": "left",
			"colorBgTrue": "green",
			"lockEnabled": "true"
		},
		"img": "/vis.0/myImages/erlebnis_50.png",
		"name": "Empire",
		"betriebszeit": "4h 06m",
		"funk": "5G"
	}, {
		"img": "/vis.0/myImages/erlebnis_100.png",
		"control": {
			"type": "buttonToggle",
			"oid": "0_userdata.0.MDW.Buttons.bool",
			"buttonText": "off",
			"buttonTextTrue": "on",
			"image": "home",
			"colorBgTrue": "green"
		},
		"name": "Handy",
		"betriebszeit": "13m",
		"funk": "5G",
		"ip": "10.0.0.2"
	}, {
		"img": "/vis.0/myImages/erlebnis_100.png",
		"name": "Harmony Hub - Wohnzimmer",
		"betriebszeit": "18T 07h 21m",
		"funk": "2G",
		"ip": "10.0.0.3"
	}
]
```

##### Vom Editor generieren
Mit dem Editor können Sie ganz einfach Steuerelemente generieren. Erstellen Sie einfach ein unterstütztes Widget, konfigurieren Sie es über den Editor und exportieren Sie die Einstellungen durch Kopieren und Einfügen in die Tabelle wigdet.
Schauen Sie sich den animierten Screenshot unten an:

![Logo](../../../en/adapterref/iobroker.vis-materialdesign/doc/en/media/table_controls.gif)

##### Allgemeines
<table><thead><tr><th>Eigentum</th><th> Beschreibung</th><th> Art</th><th> Eigenschaften</th></tr></thead><tbody><tr><td> Art</td><td> Art des Steuerelements</td><td> Zeichenfolge</td><td> <b>Tasten</b><ul><li> <a href="#button-link-properties">Button Link</a></li><li> <a href="#button-state-properties">Button State</a></li><li> <a href="#button-toggle-properties">Taste umschalten</a></li></ul> <b>Schaltflächen vertikal</b><ul><li> <a href="#button-vertical-link-properties">Button Icon Link</a></li><li> <a href="#button-vertical-state-properties">Button Icon State</a></li><li> <a href="#button-vertical-toggle-properties">Schaltflächensymbol Umschalten</a></li></ul> <b>Schaltflächen Symbole</b><ul><li> <a href="#button-icon-link-properties">Button Icon Link</a></li><li> <a href="#button-icon-state-properties">Button Icon State</a></li><li> <a href="#button-icon-toggle-properties">Schaltflächensymbol Umschalten</a></li></ul><ul><li> <a href="#progress-1">Fortschritt</a></li><li> <a href="#progress-circular">progress_circular</a></li><li> <a href="#slider-1">Schieberegler</a></li><li> <a href="#slider-round">slider_round</a></li><li> <a href="#switch-1">Schalter</a></li><li> <a href="#checkbox-1">Kontrollkästchen</a></li><li> <a href="#textfield">Textfeld</a></li><li> <a href="#select-1">wählen</a></li><li> <a href="#autocomplete-1">Autocomplete</a></li><li> <a href="#material-design-icons">Material Design Icons</a></li><li> <a href="#html">Html</a></li></ul></td></tr><tr><td> Breite</td><td> Breite in% oder px des Steuerelements</td><td> Zeichenfolge</td><td> 100% | 100px</td></tr><tr><td> Höhe</td><td> Höhe in% oder px des Steuerelements</td><td> Zeichenfolge</td><td> 100% | 100px</td></tr><tr><td> Rowspan</td><td> Zelle, die x Zeilen umfasst</td><td> Nummer</td><td> 1, 2, 3, ...</td></tr><tr><td> Colspan</td><td> Zelle, die x Spalten umfasst</td><td> Nummer</td><td> 1, 2, 3, ...</td></tr><tr><td> vertikaleAlign</td><td> Vertikale Ausrichtung</td><td> Zeichenfolge</td><td> Nach oben | Mitte | Unterseite</td></tr><tr><td> cellStyleAttrs</td><td> CSS-Stilattribute für Zelle</td><td> Zeichenfolge</td><td> ...</td></tr></tbody></table>

##### Textfeld
<details><table><thead><tr><th>Eigentum</th><th> Beschreibung</th><th> Art</th><th> Werte</th></tr></thead><tbody><tr><td> oid</td><td> Objekt Identifikation</td><td> Zeichenfolge</td><td/></tr><tr><td> Eingabetyp</td><td> Eingabetyp</td><td> Zeichenfolge</td><td> Text | Nummer | Datum | Zeit | Maske</td></tr><tr><td> inputAlignment</td><td> Textausrichtung</td><td> Zeichenfolge</td><td> links | Mitte | Recht</td></tr><tr><td> Eingabemaske</td><td> Eingabemaske</td><td> Zeichenfolge</td><td/></tr><tr><td> inputMaxLength</td><td> inputMaxLength</td><td> Nummer</td><td/></tr><tr><td> inputLayout</td><td> Layout</td><td> Zeichenfolge</td><td> regelmäßig | solo | solo gerundet | solo geformt | gefüllt | gefüllt-gerundet | gefüllt-förmig | umrissen | umrissen gerundet | umrissen</td></tr><tr><td> inputLayoutBackgroundColor</td><td> Hintergrundfarbe</td><td> Zeichenfolge</td><td> hex (# 44739e), rgb (20, 50, 200), rgba (20, 50, 200, 0,5)</td></tr><tr><td> inputLayoutBackgroundColorHover</td><td> Hintergrundfarbe schweben</td><td> Zeichenfolge</td><td> hex (# 44739e), rgb (20, 50, 200), rgba (20, 50, 200, 0,5)</td></tr><tr><td> inputLayoutBackgroundColorSelected</td><td> Hintergrundfarbe ausgewählt</td><td> Zeichenfolge</td><td> hex (# 44739e), rgb (20, 50, 200), rgba (20, 50, 200, 0,5)</td></tr><tr><td> inputLayoutBorderColor</td><td> Randfarbe</td><td> Zeichenfolge</td><td> hex (# 44739e), rgb (20, 50, 200), rgba (20, 50, 200, 0,5)</td></tr><tr><td> inputLayoutBorderColorHover</td><td> Randfarbe schweben</td><td> Zeichenfolge</td><td> hex (# 44739e), rgb (20, 50, 200), rgba (20, 50, 200, 0,5)</td></tr><tr><td> inputLayoutBorderColorSelected</td><td> Rahmenfarbe ausgewählt</td><td> Zeichenfolge</td><td> hex (# 44739e), rgb (20, 50, 200), rgba (20, 50, 200, 0,5)</td></tr><tr><td> inputTextFontFamily</td><td> Schriftart</td><td> Zeichenfolge</td><td/></tr><tr><td> inputTextFontSize</td><td> Schriftgröße</td><td> Nummer</td><td/></tr><tr><td> inputTextColor</td><td> Textfarbe</td><td> Zeichenfolge</td><td> hex (# 44739e), rgb (20, 50, 200), rgba (20, 50, 200, 0,5)</td></tr><tr><td> inputLabelText</td><td> Text</td><td> Zeichenfolge</td><td/></tr><tr><td> inputLabelColor</td><td> Textfarbe</td><td> Zeichenfolge</td><td> hex (# 44739e), rgb (20, 50, 200), rgba (20, 50, 200, 0,5)</td></tr><tr><td> inputLabelColorSelected</td><td> Textfarbe ausgewählt</td><td> Zeichenfolge</td><td> hex (# 44739e), rgb (20, 50, 200), rgba (20, 50, 200, 0,5)</td></tr><tr><td> inputLabelFontFamily</td><td> Schriftart</td><td> Zeichenfolge</td><td/></tr><tr><td> inputLabelFontSize</td><td> Schriftgröße</td><td> Nummer</td><td/></tr><tr><td> inputTranslateX</td><td> Versatz x</td><td> Nummer</td><td/></tr><tr><td> inputTranslateY</td><td> Versatz y</td><td> Nummer</td><td/></tr><tr><td> inputPrefix</td><td> vorangestellter Text</td><td> Zeichenfolge</td><td/></tr><tr><td> inputSuffix</td><td> angehängter Text</td><td> Zeichenfolge</td><td/></tr><tr><td> inputAppendixColor</td><td> Textfarbe</td><td> Zeichenfolge</td><td> hex (# 44739e), rgb (20, 50, 200), rgba (20, 50, 200, 0,5)</td></tr><tr><td> inputAppendixFontSize</td><td> Schriftgröße</td><td> Nummer</td><td/></tr><tr><td> inputAppendixFontFamily</td><td> Schriftart</td><td> Zeichenfolge</td><td/></tr><tr><td> showInputMessageAlways</td><td> immer anzeigen</td><td> Boolescher Wert</td><td> false | wahr</td></tr><tr><td> inputMessage</td><td> Text</td><td> Zeichenfolge</td><td/></tr><tr><td> inputMessageFontFamily</td><td> Schriftart</td><td> Zeichenfolge</td><td/></tr><tr><td> inputMessageFontSize</td><td> Schriftgröße</td><td> Nummer</td><td/></tr><tr><td> inputMessageColor</td><td> Textfarbe</td><td> Zeichenfolge</td><td> hex (# 44739e), rgb (20, 50, 200), rgba (20, 50, 200, 0,5)</td></tr><tr><td> showInputCounter</td><td> Zähler anzeigen</td><td> Boolescher Wert</td><td> false | wahr</td></tr><tr><td> inputCounterColor</td><td> Schriftfarbe</td><td> Zeichenfolge</td><td> hex (# 44739e), rgb (20, 50, 200), rgba (20, 50, 200, 0,5)</td></tr><tr><td> inputCounterFontSize</td><td> Schriftgröße</td><td> Nummer</td><td/></tr><tr><td> inputCounterFontFamily</td><td> Schriftart</td><td> Zeichenfolge</td><td/></tr><tr><td> clearIconShow</td><td> Symbol zum Löschen von Text anzeigen</td><td> Boolescher Wert</td><td> false | wahr</td></tr><tr><td> clearIcon</td><td> Symbol zum Löschen von Text</td><td> Benutzerdefiniert</td><td/></tr><tr><td> clearIconSize</td><td> Größe des Textlöschsymbols</td><td> Nummer</td><td/></tr><tr><td> clearIconColor</td><td> Farbe des Textes Löschsymbol</td><td> Zeichenfolge</td><td> hex (# 44739e), rgb (20, 50, 200), rgba (20, 50, 200, 0,5)</td></tr><tr><td> prepandIcon</td><td> vorangestelltes Symbol</td><td> Benutzerdefiniert</td><td/></tr><tr><td> prepandIconSize</td><td> Größe des vorangestellten Symbols</td><td> Nummer</td><td/></tr><tr><td> prepandIconColor</td><td> Farbe des vorangestellten Symbols</td><td> Zeichenfolge</td><td> hex (# 44739e), rgb (20, 50, 200), rgba (20, 50, 200, 0,5)</td></tr><tr><td> prepandInnerIcon</td><td> inneres vorangestelltes Symbol</td><td> Benutzerdefiniert</td><td/></tr><tr><td> prepandInnerIconSize</td><td> Größe des inneren vorangestellten Symbols</td><td> Nummer</td><td/></tr><tr><td> prepandInnerIconColor</td><td> Farbe des inneren vorangestellten Symbols</td><td> Zeichenfolge</td><td> hex (# 44739e), rgb (20, 50, 200), rgba (20, 50, 200, 0,5)</td></tr><tr><td> appendIcon</td><td> angehängtes Symbol</td><td> Benutzerdefiniert</td><td/></tr><tr><td> appendIconSize</td><td> Größe des angehängten Symbols</td><td> Nummer</td><td/></tr><tr><td> appendIconColor</td><td> Farbe des angehängten Symbols</td><td> Zeichenfolge</td><td> hex (# 44739e), rgb (20, 50, 200), rgba (20, 50, 200, 0,5)</td></tr><tr><td> appendOuterIcon</td><td> äußeres angehängtes Symbol</td><td> Benutzerdefiniert</td><td/></tr><tr><td> appendOuterIconSize</td><td> Größe des äußeren angehängten Symbols</td><td> Nummer</td><td/></tr><tr><td> appendOuterIconColor</td><td> Farbe des äußeren angehängten Symbols</td><td> Zeichenfolge</td><td> hex (# 44739e), rgb (20, 50, 200), rgba (20, 50, 200, 0,5)</td></tr></tbody></table></details>

##### Wählen
<details><table><thead><tr><th>Eigentum</th><th> Beschreibung</th><th> Art</th><th> Werte</th></tr></thead><tbody><tr><td> oid</td><td> Objekt Identifikation</td><td> Zeichenfolge</td><td/></tr><tr><td> Eingabetyp</td><td> Eingabetyp</td><td> Zeichenfolge</td><td> Text | Datum | Zeit</td></tr><tr><td> inputAlignment</td><td> Textausrichtung</td><td> Zeichenfolge</td><td> links | Mitte | Recht</td></tr><tr><td> vibrateOnMobilDevices</td><td> vibrieren auf mobilen Geräten [s]</td><td> Nummer</td><td/></tr><tr><td> inputLayout</td><td> Layout</td><td> Zeichenfolge</td><td> regelmäßig | solo | solo gerundet | solo geformt | gefüllt | gefüllt-gerundet | gefüllt-förmig | umrissen | umrissen gerundet | umrissen</td></tr><tr><td> inputLayoutBackgroundColor</td><td> Hintergrundfarbe</td><td> Zeichenfolge</td><td> hex (# 44739e), rgb (20, 50, 200), rgba (20, 50, 200, 0,5)</td></tr><tr><td> inputLayoutBackgroundColorHover</td><td> Hintergrundfarbe schweben</td><td> Zeichenfolge</td><td> hex (# 44739e), rgb (20, 50, 200), rgba (20, 50, 200, 0,5)</td></tr><tr><td> inputLayoutBackgroundColorSelected</td><td> Hintergrundfarbe ausgewählt</td><td> Zeichenfolge</td><td> hex (# 44739e), rgb (20, 50, 200), rgba (20, 50, 200, 0,5)</td></tr><tr><td> inputLayoutBorderColor</td><td> Randfarbe</td><td> Zeichenfolge</td><td> hex (# 44739e), rgb (20, 50, 200), rgba (20, 50, 200, 0,5)</td></tr><tr><td> inputLayoutBorderColorHover</td><td> Randfarbe schweben</td><td> Zeichenfolge</td><td> hex (# 44739e), rgb (20, 50, 200), rgba (20, 50, 200, 0,5)</td></tr><tr><td> inputLayoutBorderColorSelected</td><td> Rahmenfarbe ausgewählt</td><td> Zeichenfolge</td><td> hex (# 44739e), rgb (20, 50, 200), rgba (20, 50, 200, 0,5)</td></tr><tr><td> inputTextFontFamily</td><td> Schriftart</td><td> Zeichenfolge</td><td/></tr><tr><td> inputTextFontSize</td><td> Schriftgröße</td><td> Nummer</td><td/></tr><tr><td> inputTextColor</td><td> Textfarbe</td><td> Zeichenfolge</td><td> hex (# 44739e), rgb (20, 50, 200), rgba (20, 50, 200, 0,5)</td></tr><tr><td> inputLabelText</td><td> Text</td><td> Zeichenfolge</td><td/></tr><tr><td> inputLabelColor</td><td> Textfarbe</td><td> Zeichenfolge</td><td> hex (# 44739e), rgb (20, 50, 200), rgba (20, 50, 200, 0,5)</td></tr><tr><td> inputLabelColorSelected</td><td> Textfarbe ausgewählt</td><td> Zeichenfolge</td><td> hex (# 44739e), rgb (20, 50, 200), rgba (20, 50, 200, 0,5)</td></tr><tr><td> inputLabelFontFamily</td><td> Schriftart</td><td> Zeichenfolge</td><td/></tr><tr><td> inputLabelFontSize</td><td> Schriftgröße</td><td> Nummer</td><td/></tr><tr><td> inputTranslateX</td><td> Versatz x</td><td> Nummer</td><td/></tr><tr><td> inputTranslateY</td><td> Versatz y</td><td> Nummer</td><td/></tr><tr><td> inputPrefix</td><td> vorangestellter Text</td><td> Zeichenfolge</td><td/></tr><tr><td> inputSuffix</td><td> angehängter Text</td><td> Zeichenfolge</td><td/></tr><tr><td> inputAppendixColor</td><td> Textfarbe</td><td> Zeichenfolge</td><td> hex (# 44739e), rgb (20, 50, 200), rgba (20, 50, 200, 0,5)</td></tr><tr><td> inputAppendixFontSize</td><td> Schriftgröße</td><td> Nummer</td><td/></tr><tr><td> inputAppendixFontFamily</td><td> Schriftart</td><td> Zeichenfolge</td><td/></tr><tr><td> showInputMessageAlways</td><td> immer anzeigen</td><td> Boolescher Wert</td><td> false | wahr</td></tr><tr><td> inputMessage</td><td> Text</td><td> Zeichenfolge</td><td/></tr><tr><td> inputMessageFontFamily</td><td> Schriftart</td><td> Zeichenfolge</td><td/></tr><tr><td> inputMessageFontSize</td><td> Schriftgröße</td><td> Nummer</td><td/></tr><tr><td> inputMessageColor</td><td> Textfarbe</td><td> Zeichenfolge</td><td> hex (# 44739e), rgb (20, 50, 200), rgba (20, 50, 200, 0,5)</td></tr><tr><td> showInputCounter</td><td> Zähler anzeigen</td><td> Boolescher Wert</td><td> false | wahr</td></tr><tr><td> inputCounterColor</td><td> Schriftfarbe</td><td> Zeichenfolge</td><td> hex (# 44739e), rgb (20, 50, 200), rgba (20, 50, 200, 0,5)</td></tr><tr><td> inputCounterFontSize</td><td> Schriftgröße</td><td> Nummer</td><td/></tr><tr><td> inputCounterFontFamily</td><td> Schriftart</td><td> Zeichenfolge</td><td/></tr><tr><td> clearIconShow</td><td> Symbol zum Löschen von Text anzeigen</td><td> Boolescher Wert</td><td> false | wahr</td></tr><tr><td> clearIcon</td><td> Symbol zum Löschen von Text</td><td> Benutzerdefiniert</td><td/></tr><tr><td> clearIconSize</td><td> Größe des Textlöschsymbols</td><td> Nummer</td><td/></tr><tr><td> clearIconColor</td><td> Farbe des Textes Löschsymbol</td><td> Zeichenfolge</td><td> hex (# 44739e), rgb (20, 50, 200), rgba (20, 50, 200, 0,5)</td></tr><tr><td> ZusammenbruchIcon</td><td> Menü öffnen Symbol</td><td> Benutzerdefiniert</td><td/></tr><tr><td> kollabierenIconSize</td><td> Größe des Symbols zum Öffnen des Menüs</td><td> Nummer</td><td/></tr><tr><td> kollabierenIconColor</td><td> Farbe des offenen Menüsymbols</td><td> Zeichenfolge</td><td> hex (# 44739e), rgb (20, 50, 200), rgba (20, 50, 200, 0,5)</td></tr><tr><td> prepandIcon</td><td> vorangestelltes Symbol</td><td> Benutzerdefiniert</td><td/></tr><tr><td> prepandIconSize</td><td> Größe des vorangestellten Symbols</td><td> Nummer</td><td/></tr><tr><td> prepandIconColor</td><td> Farbe des vorangestellten Symbols</td><td> Zeichenfolge</td><td> hex (# 44739e), rgb (20, 50, 200), rgba (20, 50, 200, 0,5)</td></tr><tr><td> prepandInnerIcon</td><td> inneres vorangestelltes Symbol</td><td> Benutzerdefiniert</td><td/></tr><tr><td> prepandInnerIconSize</td><td> Größe des inneren vorangestellten Symbols</td><td> Nummer</td><td/></tr><tr><td> prepandInnerIconColor</td><td> Farbe des inneren vorangestellten Symbols</td><td> Zeichenfolge</td><td> hex (# 44739e), rgb (20, 50, 200), rgba (20, 50, 200, 0,5)</td></tr><tr><td> appendOuterIcon</td><td> äußeres angehängtes Symbol</td><td> Benutzerdefiniert</td><td/></tr><tr><td> appendOuterIconSize</td><td> Größe des äußeren angehängten Symbols</td><td> Nummer</td><td/></tr><tr><td> appendOuterIconColor</td><td> Farbe des äußeren angehängten Symbols</td><td> Zeichenfolge</td><td> hex (# 44739e), rgb (20, 50, 200), rgba (20, 50, 200, 0,5)</td></tr><tr><td> listDataMethod</td><td> Eingabemethode für die Menüdaten</td><td> Zeichenfolge</td><td> inputPerEditor | jsonStringObject | multistatesObject | valueList</td></tr><tr><td> countSelectItems</td><td> Editor: Anzahl der Menüpunkte</td><td> Nummer</td><td/></tr><tr><td> jsonStringObject</td><td> JSON-Zeichenfolge</td><td> Zeichenfolge</td><td> Bindungen funktionieren nicht!</td></tr><tr><td> valueList</td><td> Werteliste</td><td> Zeichenfolge</td><td/></tr><tr><td> valueListLabels</td><td> Werteliste: Labels</td><td> Zeichenfolge</td><td/></tr><tr><td> valueListIcons</td><td> Werteliste: Bilder</td><td> Zeichenfolge</td><td/></tr><tr><td> listPosition</td><td> Position</td><td> Zeichenfolge</td><td> auto | Nach oben | Unterseite</td></tr><tr><td> listPositionOffset</td><td> Positionsversatz verwenden</td><td> Boolescher Wert</td><td> false | wahr</td></tr><tr><td> listItemHeight</td><td> Höhe des Menüpunktes</td><td> Nummer</td><td/></tr><tr><td> listItemBackgroundColor</td><td> Hintergrundfarbe</td><td> Zeichenfolge</td><td> hex (# 44739e), rgb (20, 50, 200), rgba (20, 50, 200, 0,5)</td></tr><tr><td> listItemBackgroundHoverColor</td><td> Schwebefarbe</td><td> Zeichenfolge</td><td> hex (# 44739e), rgb (20, 50, 200), rgba (20, 50, 200, 0,5)</td></tr><tr><td> listItemBackgroundSelectedColor</td><td> Farbe des ausgewählten Elements</td><td> Zeichenfolge</td><td> hex (# 44739e), rgb (20, 50, 200), rgba (20, 50, 200, 0,5)</td></tr><tr><td> listItemRippleEffectColor</td><td> Effektfarbe</td><td> Zeichenfolge</td><td> hex (# 44739e), rgb (20, 50, 200), rgba (20, 50, 200, 0,5)</td></tr><tr><td> showSelectedIcon</td><td> Symbol des ausgewählten Elements anzeigen</td><td> Zeichenfolge</td><td> nein | voranstellen | prepend-inner | Append-Outer</td></tr><tr><td> listIconSize</td><td> Symbolgröße</td><td> Nummer</td><td/></tr><tr><td> listIconColor</td><td> Symbolfarbe</td><td> Zeichenfolge</td><td> hex (# 44739e), rgb (20, 50, 200), rgba (20, 50, 200, 0,5)</td></tr><tr><td> listIconHoverColor</td><td> Symbol Schwebefarbe</td><td> Zeichenfolge</td><td> hex (# 44739e), rgb (20, 50, 200), rgba (20, 50, 200, 0,5)</td></tr><tr><td> listIconSelectedColor</td><td> Symbolfarbe des ausgewählten Elements</td><td> Zeichenfolge</td><td> hex (# 44739e), rgb (20, 50, 200), rgba (20, 50, 200, 0,5)</td></tr><tr><td> listItemFontSize</td><td> Schriftgröße</td><td> Nummer</td><td/></tr><tr><td> listItemFont</td><td> Schriftart</td><td> Zeichenfolge</td><td/></tr><tr><td> listItemFontColor</td><td> Schriftfarbe</td><td> Zeichenfolge</td><td> hex (# 44739e), rgb (20, 50, 200), rgba (20, 50, 200, 0,5)</td></tr><tr><td> listItemFontHoverColor</td><td> Schrift schweben Farbe</td><td> Zeichenfolge</td><td> hex (# 44739e), rgb (20, 50, 200), rgba (20, 50, 200, 0,5)</td></tr><tr><td> listItemFontSelectedColor</td><td> Schriftfarbe des ausgewählten Elements</td><td> Zeichenfolge</td><td> hex (# 44739e), rgb (20, 50, 200), rgba (20, 50, 200, 0,5)</td></tr><tr><td> listItemSubFontSize</td><td> zweite Textschriftgröße</td><td> Nummer</td><td/></tr><tr><td> listItemSubFont</td><td> zweite Textschrift</td><td> Zeichenfolge</td><td/></tr><tr><td> listItemSubFontColor</td><td> zweite Textschriftfarbe</td><td> Zeichenfolge</td><td> hex (# 44739e), rgb (20, 50, 200), rgba (20, 50, 200, 0,5)</td></tr><tr><td> listItemSubFontHoverColor</td><td> Schwebefarbe des zweiten Textes</td><td> Zeichenfolge</td><td> hex (# 44739e), rgb (20, 50, 200), rgba (20, 50, 200, 0,5)</td></tr><tr><td> listItemSubFontSelectedColor</td><td> Farbe des zweiten ausgewählten Textes</td><td> Zeichenfolge</td><td> hex (# 44739e), rgb (20, 50, 200), rgba (20, 50, 200, 0,5)</td></tr><tr><td> showValue</td><td> Wert anzeigen</td><td> Boolescher Wert</td><td> false | wahr</td></tr><tr><td> listItemValueFontSize</td><td> Schriftgröße des Wertes</td><td> Nummer</td><td/></tr><tr><td> listItemValueFont</td><td> Schriftart des Wertes</td><td> Zeichenfolge</td><td/></tr><tr><td> listItemValueFontColor</td><td> Schriftfarbe des Wertes</td><td> Zeichenfolge</td><td> hex (# 44739e), rgb (20, 50, 200), rgba (20, 50, 200, 0,5)</td></tr><tr><td> listItemValueFontHoverColor</td><td> Hover-Schriftfarbe des Werts</td><td> Zeichenfolge</td><td> hex (# 44739e), rgb (20, 50, 200), rgba (20, 50, 200, 0,5)</td></tr><tr><td> listItemValueFontSelectedColor</td><td> Schriftfarbe des ausgewählten Werts</td><td> Zeichenfolge</td><td> hex (# 44739e), rgb (20, 50, 200), rgba (20, 50, 200, 0,5)</td></tr><tr><td> Wert <b><i>X.</i></b></td><td> Wert des Menüpunktes X.</td><td> Zeichenfolge</td><td/></tr><tr><td> Etikett <b><i>X.</i></b></td><td> Beschriftung des Menüpunktes X.</td><td> Zeichenfolge</td><td/></tr><tr><td> subLabel <b><i>X.</i></b></td><td> Unteretikett des Menüpunktes X.</td><td> Zeichenfolge</td><td/></tr><tr><td> listIcon <b><i>X.</i></b></td><td> listIcon von Menüpunkt X.</td><td> Benutzerdefiniert</td><td/></tr><tr><td> listIconColor <b><i>X.</i></b></td><td> listIconColor von Menüpunkt X.</td><td> Zeichenfolge</td><td> hex (# 44739e), rgb (20, 50, 200), rgba (20, 50, 200, 0,5)</td></tr></table></details>

##### Autocomplete
<details><table><thead><tr><th>Eigentum</th><th> Beschreibung</th><th> Art</th><th> Werte</th></tr></thead><tbody><tr><td> oid</td><td> Objekt Identifikation</td><td> Zeichenfolge</td><td/></tr><tr><td> Eingabemodus</td><td> Eingabemodus</td><td> Zeichenfolge</td><td> schreiben | wählen</td></tr><tr><td> Eingabetyp</td><td> Eingabetyp</td><td> Zeichenfolge</td><td> Text | Datum | Zeit</td></tr><tr><td> inputAlignment</td><td> Textausrichtung</td><td> Zeichenfolge</td><td> links | Mitte | Recht</td></tr><tr><td> vibrateOnMobilDevices</td><td> vibrieren auf mobilen Geräten [s]</td><td> Nummer</td><td/></tr><tr><td> inputLayout</td><td> Layout</td><td> Zeichenfolge</td><td> regelmäßig | solo | solo gerundet | solo geformt | gefüllt | gefüllt-gerundet | gefüllt-förmig | umrissen | umrissen gerundet | umrissen</td></tr><tr><td> inputLayoutBackgroundColor</td><td> Hintergrundfarbe</td><td> Zeichenfolge</td><td> hex (# 44739e), rgb (20, 50, 200), rgba (20, 50, 200, 0,5)</td></tr><tr><td> inputLayoutBackgroundColorHover</td><td> Hintergrundfarbe schweben</td><td> Zeichenfolge</td><td> hex (# 44739e), rgb (20, 50, 200), rgba (20, 50, 200, 0,5)</td></tr><tr><td> inputLayoutBackgroundColorSelected</td><td> Hintergrundfarbe ausgewählt</td><td> Zeichenfolge</td><td> hex (# 44739e), rgb (20, 50, 200), rgba (20, 50, 200, 0,5)</td></tr><tr><td> inputLayoutBorderColor</td><td> Randfarbe</td><td> Zeichenfolge</td><td> hex (# 44739e), rgb (20, 50, 200), rgba (20, 50, 200, 0,5)</td></tr><tr><td> inputLayoutBorderColorHover</td><td> Randfarbe schweben</td><td> Zeichenfolge</td><td> hex (# 44739e), rgb (20, 50, 200), rgba (20, 50, 200, 0,5)</td></tr><tr><td> inputLayoutBorderColorSelected</td><td> Rahmenfarbe ausgewählt</td><td> Zeichenfolge</td><td> hex (# 44739e), rgb (20, 50, 200), rgba (20, 50, 200, 0,5)</td></tr><tr><td> inputTextFontFamily</td><td> Schriftart</td><td> Zeichenfolge</td><td/></tr><tr><td> inputTextFontSize</td><td> Schriftgröße</td><td> Nummer</td><td/></tr><tr><td> inputTextColor</td><td> Textfarbe</td><td> Zeichenfolge</td><td> hex (# 44739e), rgb (20, 50, 200), rgba (20, 50, 200, 0,5)</td></tr><tr><td> inputLabelText</td><td> Text</td><td> Zeichenfolge</td><td/></tr><tr><td> inputLabelColor</td><td> Textfarbe</td><td> Zeichenfolge</td><td> hex (# 44739e), rgb (20, 50, 200), rgba (20, 50, 200, 0,5)</td></tr><tr><td> inputLabelColorSelected</td><td> Textfarbe ausgewählt</td><td> Zeichenfolge</td><td> hex (# 44739e), rgb (20, 50, 200), rgba (20, 50, 200, 0,5)</td></tr><tr><td> inputLabelFontFamily</td><td> Schriftart</td><td> Zeichenfolge</td><td/></tr><tr><td> inputLabelFontSize</td><td> Schriftgröße</td><td> Nummer</td><td/></tr><tr><td> inputTranslateX</td><td> Versatz x</td><td> Nummer</td><td/></tr><tr><td> inputTranslateY</td><td> Versatz y</td><td> Nummer</td><td/></tr><tr><td> inputPrefix</td><td> vorangestellter Text</td><td> Zeichenfolge</td><td/></tr><tr><td> inputSuffix</td><td> angehängter Text</td><td> Zeichenfolge</td><td/></tr><tr><td> inputAppendixColor</td><td> Textfarbe</td><td> Zeichenfolge</td><td> hex (# 44739e), rgb (20, 50, 200), rgba (20, 50, 200, 0,5)</td></tr><tr><td> inputAppendixFontSize</td><td> Schriftgröße</td><td> Nummer</td><td/></tr><tr><td> inputAppendixFontFamily</td><td> Schriftart</td><td> Zeichenfolge</td><td/></tr><tr><td> showInputMessageAlways</td><td> immer anzeigen</td><td> Boolescher Wert</td><td> false | wahr</td></tr><tr><td> inputMessage</td><td> Text</td><td> Zeichenfolge</td><td/></tr><tr><td> inputMessageFontFamily</td><td> Schriftart</td><td> Zeichenfolge</td><td/></tr><tr><td> inputMessageFontSize</td><td> Schriftgröße</td><td> Nummer</td><td/></tr><tr><td> inputMessageColor</td><td> Textfarbe</td><td> Zeichenfolge</td><td> hex (# 44739e), rgb (20, 50, 200), rgba (20, 50, 200, 0,5)</td></tr><tr><td> showInputCounter</td><td> Zähler anzeigen</td><td> Boolescher Wert</td><td> false | wahr</td></tr><tr><td> inputCounterColor</td><td> Schriftfarbe</td><td> Zeichenfolge</td><td> hex (# 44739e), rgb (20, 50, 200), rgba (20, 50, 200, 0,5)</td></tr><tr><td> inputCounterFontSize</td><td> Schriftgröße</td><td> Nummer</td><td/></tr><tr><td> inputCounterFontFamily</td><td> Schriftart</td><td> Zeichenfolge</td><td/></tr><tr><td> clearIconShow</td><td> Symbol zum Löschen von Text anzeigen</td><td> Boolescher Wert</td><td> false | wahr</td></tr><tr><td> clearIcon</td><td> Symbol zum Löschen von Text</td><td> Benutzerdefiniert</td><td/></tr><tr><td> clearIconSize</td><td> Größe des Textlöschsymbols</td><td> Nummer</td><td/></tr><tr><td> clearIconColor</td><td> Farbe des Textes Löschsymbol</td><td> Zeichenfolge</td><td> hex (# 44739e), rgb (20, 50, 200), rgba (20, 50, 200, 0,5)</td></tr><tr><td> ZusammenbruchIcon</td><td> Menü öffnen Symbol</td><td> Benutzerdefiniert</td><td/></tr><tr><td> kollabierenIconSize</td><td> Größe des Symbols zum Öffnen des Menüs</td><td> Nummer</td><td/></tr><tr><td> kollabierenIconColor</td><td> Farbe des offenen Menüsymbols</td><td> Zeichenfolge</td><td> hex (# 44739e), rgb (20, 50, 200), rgba (20, 50, 200, 0,5)</td></tr><tr><td> prepandIcon</td><td> vorangestelltes Symbol</td><td> Benutzerdefiniert</td><td/></tr><tr><td> prepandIconSize</td><td> Größe des vorangestellten Symbols</td><td> Nummer</td><td/></tr><tr><td> prepandIconColor</td><td> Farbe des vorangestellten Symbols</td><td> Zeichenfolge</td><td> hex (# 44739e), rgb (20, 50, 200), rgba (20, 50, 200, 0,5)</td></tr><tr><td> prepandInnerIcon</td><td> inneres vorangestelltes Symbol</td><td> Benutzerdefiniert</td><td/></tr><tr><td> prepandInnerIconSize</td><td> Größe des inneren vorangestellten Symbols</td><td> Nummer</td><td/></tr><tr><td> prepandInnerIconColor</td><td> Farbe des inneren vorangestellten Symbols</td><td> Zeichenfolge</td><td> hex (# 44739e), rgb (20, 50, 200), rgba (20, 50, 200, 0,5)</td></tr><tr><td> appendOuterIcon</td><td> äußeres angehängtes Symbol</td><td> Benutzerdefiniert</td><td/></tr><tr><td> appendOuterIconSize</td><td> Größe des äußeren angehängten Symbols</td><td> Nummer</td><td/></tr><tr><td> appendOuterIconColor</td><td> Farbe des äußeren angehängten Symbols</td><td> Zeichenfolge</td><td> hex (# 44739e), rgb (20, 50, 200), rgba (20, 50, 200, 0,5)</td></tr><tr><td> listDataMethod</td><td> Eingabemethode für die Menüdaten</td><td> Zeichenfolge</td><td> inputPerEditor | jsonStringObject | multistatesObject | valueList</td></tr><tr><td> countSelectItems</td><td> Editor: Anzahl der Menüpunkte</td><td> Nummer</td><td/></tr><tr><td> jsonStringObject</td><td> JSON-Zeichenfolge</td><td> Zeichenfolge</td><td> Bindungen funktionieren nicht!</td></tr><tr><td> valueList</td><td> Werteliste</td><td> Zeichenfolge</td><td/></tr><tr><td> valueListLabels</td><td> Werteliste: Labels</td><td> Zeichenfolge</td><td/></tr><tr><td> valueListIcons</td><td> Werteliste: Bilder</td><td> Zeichenfolge</td><td/></tr><tr><td> listPosition</td><td> Position</td><td> Zeichenfolge</td><td> auto | Nach oben | Unterseite</td></tr><tr><td> listPositionOffset</td><td> Positionsversatz verwenden</td><td> Boolescher Wert</td><td> false | wahr</td></tr><tr><td> listItemHeight</td><td> Höhe des Menüpunktes</td><td> Nummer</td><td/></tr><tr><td> listItemBackgroundColor</td><td> Hintergrundfarbe</td><td> Zeichenfolge</td><td> hex (# 44739e), rgb (20, 50, 200), rgba (20, 50, 200, 0,5)</td></tr><tr><td> listItemBackgroundHoverColor</td><td> Schwebefarbe</td><td> Zeichenfolge</td><td> hex (# 44739e), rgb (20, 50, 200), rgba (20, 50, 200, 0,5)</td></tr><tr><td> listItemBackgroundSelectedColor</td><td> Farbe des ausgewählten Elements</td><td> Zeichenfolge</td><td> hex (# 44739e), rgb (20, 50, 200), rgba (20, 50, 200, 0,5)</td></tr><tr><td> listItemRippleEffectColor</td><td> Effektfarbe</td><td> Zeichenfolge</td><td> hex (# 44739e), rgb (20, 50, 200), rgba (20, 50, 200, 0,5)</td></tr><tr><td> showSelectedIcon</td><td> Symbol des ausgewählten Elements anzeigen</td><td> Zeichenfolge</td><td> nein | voranstellen | prepend-inner | Append-Outer</td></tr><tr><td> listIconSize</td><td> Symbolgröße</td><td> Nummer</td><td/></tr><tr><td> listIconColor</td><td> Symbolfarbe</td><td> Zeichenfolge</td><td> hex (# 44739e), rgb (20, 50, 200), rgba (20, 50, 200, 0,5)</td></tr><tr><td> listIconHoverColor</td><td> Symbol Schwebefarbe</td><td> Zeichenfolge</td><td> hex (# 44739e), rgb (20, 50, 200), rgba (20, 50, 200, 0,5)</td></tr><tr><td> listIconSelectedColor</td><td> Symbolfarbe des ausgewählten Elements</td><td> Zeichenfolge</td><td> hex (# 44739e), rgb (20, 50, 200), rgba (20, 50, 200, 0,5)</td></tr><tr><td> listItemFontSize</td><td> Schriftgröße</td><td> Nummer</td><td/></tr><tr><td> listItemFont</td><td> Schriftart</td><td> Zeichenfolge</td><td/></tr><tr><td> listItemFontColor</td><td> Schriftfarbe</td><td> Zeichenfolge</td><td> hex (# 44739e), rgb (20, 50, 200), rgba (20, 50, 200, 0,5)</td></tr><tr><td> listItemFontHoverColor</td><td> Schrift schweben Farbe</td><td> Zeichenfolge</td><td> hex (# 44739e), rgb (20, 50, 200), rgba (20, 50, 200, 0,5)</td></tr><tr><td> listItemFontSelectedColor</td><td> Schriftfarbe des ausgewählten Elements</td><td> Zeichenfolge</td><td> hex (# 44739e), rgb (20, 50, 200), rgba (20, 50, 200, 0,5)</td></tr><tr><td> listItemSubFontSize</td><td> zweite Textschriftgröße</td><td> Nummer</td><td/></tr><tr><td> listItemSubFont</td><td> zweite Textschrift</td><td> Zeichenfolge</td><td/></tr><tr><td> listItemSubFontColor</td><td> zweite Textschriftfarbe</td><td> Zeichenfolge</td><td> hex (# 44739e), rgb (20, 50, 200), rgba (20, 50, 200, 0,5)</td></tr><tr><td> listItemSubFontHoverColor</td><td> Schwebefarbe des zweiten Textes</td><td> Zeichenfolge</td><td> hex (# 44739e), rgb (20, 50, 200), rgba (20, 50, 200, 0,5)</td></tr><tr><td> listItemSubFontSelectedColor</td><td> Farbe des zweiten ausgewählten Textes</td><td> Zeichenfolge</td><td> hex (# 44739e), rgb (20, 50, 200), rgba (20, 50, 200, 0,5)</td></tr><tr><td> showValue</td><td> Wert anzeigen</td><td> Boolescher Wert</td><td> false | wahr</td></tr><tr><td> listItemValueFontSize</td><td> Schriftgröße des Wertes</td><td> Nummer</td><td/></tr><tr><td> listItemValueFont</td><td> Schriftart des Wertes</td><td> Zeichenfolge</td><td/></tr><tr><td> listItemValueFontColor</td><td> Schriftfarbe des Wertes</td><td> Zeichenfolge</td><td> hex (# 44739e), rgb (20, 50, 200), rgba (20, 50, 200, 0,5)</td></tr><tr><td> listItemValueFontHoverColor</td><td> Hover-Schriftfarbe des Werts</td><td> Zeichenfolge</td><td> hex (# 44739e), rgb (20, 50, 200), rgba (20, 50, 200, 0,5)</td></tr><tr><td> listItemValueFontSelectedColor</td><td> Schriftfarbe des ausgewählten Werts</td><td> Zeichenfolge</td><td> hex (# 44739e), rgb (20, 50, 200), rgba (20, 50, 200, 0,5)</td></tr><tr><td> value0</td><td> value0</td><td> Zeichenfolge</td><td/></tr><tr><td> label0</td><td> label0</td><td> Zeichenfolge</td><td/></tr><tr><td> subLabel0</td><td> subLabel0</td><td> Zeichenfolge</td><td/></tr><tr><td> listIcon0</td><td> listIcon0</td><td> Benutzerdefiniert</td><td/></tr><tr><td> listIconColor0</td><td> listIconColor0</td><td> Zeichenfolge</td><td> hex (# 44739e), rgb (20, 50, 200), rgba (20, 50, 200, 0,5)</td></tr><tr><td> value1</td><td> value1</td><td> Zeichenfolge</td><td/></tr><tr><td> label1</td><td> label1</td><td> Zeichenfolge</td><td/></tr><tr><td> subLabel1</td><td> subLabel1</td><td> Zeichenfolge</td><td/></tr><tr><td> listIcon1</td><td> listIcon1</td><td> Benutzerdefiniert</td><td/></tr><tr><td> listIconColor1</td><td> listIconColor1</td><td> Zeichenfolge</td><td> hex (# 44739e), rgb (20, 50, 200), rgba (20, 50, 200, 0,5)</td></tr></tbody></table></details>

##### Material Design Icons
<details><table><thead><tr><th>Eigentum</th><th> Beschreibung</th><th> Art</th><th> Werte</th></tr></thead><tbody><tr><td> mdwIcon</td><td> <a href="https://materialdesignicons.com/">materialdesignicon name</a></td><td> Zeichenfolge</td><td> Zuhause, ...</td></tr><tr><td> mdwIconSize</td><td> Größe des Symbols</td><td> Nummer</td><td> 0, 1, 2, ...</td></tr><tr><td> mdwIconColor</td><td> Farbe des Symbols</td><td> Zeichenfolge</td><td> hex (# 44739e), rgb (20, 50, 200), rgba (20, 50, 200, 0,5)</td></tr></tbody></table></details>

##### Html
<details><table><thead><tr><th>Eigentum</th><th> Beschreibung</th><th> Art</th><th> Werte</th></tr></thead><tbody><tr><td> html</td><td> ein beliebiges HTML-Element</td><td> Zeichenfolge</td><td></td></tr><tr><td> oid</td><td> Objekt-ID, die in HTML verwendet werden soll. Verwenden Sie in HTML &#39;[#value]&#39; als Wert</td><td> Zeichenfolge</td><td></td></tr></tbody></table></details>

<br>

### Editoreinstellungen
<table><thead><tr><th>Bildschirmfoto</th><th> Rahmen</th><th> Beschreibung</th></tr></thead><tbody><tr><td rowspan=2><img src="doc/en/media/table_general.png"></td><td> Schalter</td><td> Datenpunkt aus Typzeichenfolge mit Eingabedaten wie oben gezeigt</td></tr><tr><td> Daten als JSON</td><td> Optional können Sie Daten wie oben gezeigt eingeben, wenn kein OID-Datenpunkt festgelegt ist</td></tr><tr><td rowspan=4><img src="doc/en/media/table_column.png"></td><td> colType [x]</td><td> Wenn Bild ausgewählt ist, muss die Objekteigenschaft den Pfad zum Bild haben ( <a href="https://github.com/Scrounger/ioBroker.vis-materialdesign#input-data">siehe oben</a> ).</td></tr><tr><td> Präfix [x]</td><td> Das Präfix für Objekteigenschaft, interne Objektbindung ( <a href="https://github.com/Scrounger/ioBroker.vis-materialdesign#internal-object-binding">siehe unten</a> ) und HTML kann verwendet werden</td></tr><tr><td> Suffix [x]</td><td> Es können Suffixe für Objekteigenschaften, interne Objektbindung ( <a href="https://github.com/Scrounger/ioBroker.vis-materialdesign#internal-object-binding">siehe unten</a> ) und HTML verwendet werden</td></tr><tr><td> Objektname zum Sortieren [x]</td><td> Hier können Sie eine andere Objekteigenschaft definieren, die zum Sortieren verwendet werden soll.</td></tr></tbody></table>

##### Interne Objektbindung
Präfix & Suffix unterstützt die tabelleninterne Objektbindung -> Sie können mit auf andere Objekteigenschaften zugreifen

```
#[obj.'propertyName']
```

Beispiel <a href="https://github.com/Scrounger/ioBroker.vis-materialdesign#input-data">siehe oben</a> .

Ein Beispiel für ein funktionierendes Widget finden Sie hier

* [hier] (https://forum.iobroker.net/topic/26199/test-adapter-material-design-widgets-v0-1-x/113)
* [ical Adapter] (https://forum.iobroker.net/topic/29658/material-design-widgets-table-widget/2)

## Responsive Layout
Es gibt zwei Widgets - Masonry Views und Grid Views - mit denen ein reaktionsfähiges Layout erstellt werden kann (ein Layout für Desktop, Tablet und Mobile). In beiden Widgets sind mehrere `view in widget` integriert.

### Mauerwerksansichten
In Masonry Views sind mehrere `view in widget` integriert, die je nach Breite des Widgets automatisch sortiert werden. Mit diesem Widget ist es möglich, ein ansprechendes Layout zu erstellen (ein Layout für Desktop, Tablet und Handy).
Mauerwerksansichten sind besonders nützlich, wenn die enthaltenen Ansichten unterschiedliche Höhen haben.

<b>Schauen Sie sich die [Beispielprojekt für Material Design Widgets](https://github.com/Scrounger/ioBroker.vis-materialdesign#online-example-project)</b> an, um zu verstehen, wie es funktioniert.

![Logo](../../../en/adapterref/iobroker.vis-materialdesign/doc/en/media/masnory.gif)

<table><thead><tr><th>Bildschirmfoto</th><th> Rahmen</th><th> Beschreibung </th></tr></thead><tbody><tr><td rowspan=1><img src="doc/en/media/masonry_resolution_settings.png"></td><td colspan=2>Abhängig von der Breite des Widgets können die Anzahl der Spalten und der Abstand zwischen den Ansichten festgelegt werden. Die Einstellungen können unabhängig voneinander für das Hoch- und Querformat vorgenommen werden. Aktivieren Sie den Auflösungsassistenten unter den allgemeinen Einstellungen, um die Breite der Auflösung für die verschiedenen Geräte zu ermitteln.</td></tr><tr><td rowspan=2><img src="doc/en/media/masnory_settings_views.png"></td><td> Sichtweite [x]</td><td> Definieren Sie die Breite der Ansicht. Zulässige Werte sind number, px,% oder calc. Beispiele: <code>100</code> , <code>100px</code> , <code>55%</code> , <code>calc(60% - 12px)</code></td></tr><tr><td> Sichthöhe [x]</td><td> Hier können Sie die Höhe der verwendeten Ansicht festlegen.<br><br> Wenn Sie möchten, dass die Höhe variabel an die Ansicht angepasst wird, muss diese Eingabe leer sein, und für das Widget mit der höchsten Höhe in der Ansicht muss die Position auf relativ gesetzt werden (siehe Screenshot).<br><br><img src="doc/en/media/masonry_grid_position_settings.png"></td></tr></tbody></table>

### Rasteransichten
In Grid Views sind mehrere `view in widget` integriert, die je nach Breite des Widgets automatisch sortiert werden. Mit diesem Widget ist es möglich, ein ansprechendes Layout zu erstellen (ein Layout für Desktop, Tablet und Handy).
Rasteransichten sind besonders nützlich, wenn die enthaltenen Ansichten dieselbe Höhe haben.

<b>Das Widget &quot;Rasteransicht&quot; enthält insgesamt 12 Spalten. Wenn eine Ansicht eine Breite von 4 Spalten haben soll, müssen Sie in der entsprechenden Ansicht [x] die Spaltenspanne auf 4 setzen.</b>

<b>Schauen Sie sich die [Beispielprojekt für Material Design Widgets](https://github.com/Scrounger/ioBroker.vis-materialdesign#online-example-project)</b> an, um zu verstehen, wie es funktioniert.

![Logo](../../../en/adapterref/iobroker.vis-materialdesign/doc/en/media/grid.gif)

<table><thead><tr><th>Bildschirmfoto</th><th> Rahmen</th><th> Beschreibung </th></tr></thead><tbody><tr><td rowspan=1><img src="doc/en/media/grid_settings_resolution.png"></td><td colspan=2> Abhängig von der Breite des Widgets wird festgelegt, ab welcher Breite des Widgets die Regeln für die Spaltenspanne der einzelnen Ansichten [x] und der Abstand zwischen den Ansichten angewendet werden können. Die Einstellungen können unabhängig voneinander für das Hoch- und Querformat vorgenommen werden. Aktivieren Sie den Auflösungsassistenten unter den allgemeinen Einstellungen, um die Breite der Auflösung für die verschiedenen Geräte zu ermitteln.</td></tr><tr><td rowspan=2><img src="doc/en/media/grid_settings_view.png"></td><td colspan=2> Definieren Sie die Spaltenspanne der Ansicht in Abhängigkeit von der aktuellen Auflösungsregel für die Breite.<br> Hier können Sie auch festlegen, ob eine Ansicht nur mit einer Auflösung angezeigt werden soll, die höher oder niedriger als ein definierter Wert ist, oder ob sie über eine Objekt-ID sichtbar sein soll.</td></tr><tr><td> Sichthöhe [x]</td><td> Hier können Sie die Höhe der verwendeten Ansicht festlegen.<br><br> Wenn Sie möchten, dass die Höhe variabel an die Ansicht angepasst wird, muss diese Eingabe leer sein, und für das Widget mit der höchsten Höhe in der Ansicht muss die Position auf relativ gesetzt werden (siehe Screenshot).<br><br><img src="doc/en/media/masonry_grid_position_settings.png"></td></tbody></table>

## Warnungen
Das Warnungs-Widget kann z.B. Anzeigen von Nachrichten im VIS, wie es mit dem Pushover-Adapter funktioniert, jedoch direkt im VIS.

![Logo](../../../en/adapterref/iobroker.vis-materialdesign/doc/en/media/alerts.gif)

Das Alerts-Widget erfordert eine JSON-Zeichenfolge als Objekt, die wie folgt strukturiert sein muss:

```
[
       {
		"text": "we have a new message",
		"backgroundColor": "",
		"borderColor": "darkred",
		"icon": "message-alert-outline",
		"iconColor": "darkred",
		"fontColor": "blue"
	}, {
		"text": "we have a new message",
		"backgroundColor": "#e6b0aa",
		"borderColor": "green",
		"icon": "/vis/img/bulb_on.png",
		"iconColor": "green",
		"fontColor": "gold"
	}, {
		"text": "we have a new message",
		"backgroundColor": "",
		"borderColor": "gold",
		"icon": "alert-outline",
		"iconColor": "gold",
		"fontColor": ""
	}
]
```

<table><thead><tr><th>Bildschirmfoto</th><th> Rahmen</th><th> Beschreibung</th></tr></thead><tbody><tr><td rowspan=3><img src="doc/en/media/alerts_settings.png"></td><td> Anzahl der Spalten</td><td> Anzahl der Spalten definieren</td></tr><tr><td> Objekt Identifikation</td><td> Das Objekt muss eine JSON-Zeichenfolge sein, die wie oben beschrieben strukturiert sein muss</td></tr><tr><td> max. Warnungen</td><td> Maximale Anzahl von Warnungen, die angezeigt werden sollen.</td></tr></tbody></table>

Mit dem folgenden Skript können Sie einfache Nachrichten an den Datenpunkt senden, der vom Warnungs-Widget verwendet wird.
Das Skript muss in globale Skripte eingefügt werden. Dann ist es möglich, eine Nachricht mit dem folgenden Befehl zu senden

`materialDesignWidgets.sendTo('datapoint_id', 'message', 'color');`

```


var materialDesignWidgets = {};
materialDesignWidgets.sendTo = function (id, text, backgroundColor = '', borderColor = '', icon = '', iconColor = '', fontColor = '') {
    let json = getState(id).val;

    if (json) {
        try {

            json = JSON.parse(json);

        } catch (e) {
            json = [];
            console.warn('Wert ist kein JSON string! Wert wird ersetzt!');
        }
    } else {
        json = [];
    }

    json.push(
        {
            text: text,
            backgroundColor: backgroundColor,
            borderColor: borderColor,
            icon: icon,
            iconColor: iconColor,
            fontColor: fontColor
        }
    )
    setState(id, JSON.stringify(json), true);
}
```

## Kalender
![Logo](../../../en/adapterref/iobroker.vis-materialdesign/doc/en/media/calendar.gif)

Das Kalender-Widget erfordert eine JSON-Zeichenfolge als Objekt, die wie folgt strukturiert sein muss:

```
[
	{
		"name": "Event",
		"color": "#e74c3c",
		"colorText": "#FFFFFF",
		"start": "2020-01-24",
		"end": "2020-01-26"
	},
	{
		"name": "Meeting",
		"color": "#717d7e",
		"colorText": "#FFFFFF",
		"start": "2020-03-23 16:00",
		"end": "2020-03-24 17:15"
	}
]
```

Nur Hex und RGBA können als Farben verwendet werden!

Einstellungen, die in der folgenden Tabelle nicht aufgeführt sind, sind selbsterklärend.

<table><thead><tr><th>Bildschirmfoto</th><th> Rahmen</th><th> Beschreibung</th></tr></thead><tbody><tr><td rowspan=2><img src="doc/en/media/calendar_layout.png"></td><td> Wochentage angezeigt werden</td><td> Gibt an, welche Wochentage angezeigt werden sollen. Um nur Montag bis Freitag anzuzeigen, kann ein Wert von <code>1, 2, 3, 4, 5</code> verwendet werden. Um eine Woche ab Montag anzuzeigen, kann ein Wert von <code>1, 2, 3, 4, 5, 6, 0</code> verwendet werden.</td></tr><tr><td> Objekt Identifikation</td><td> Das Objekt muss eine JSON-Zeichenfolge sein, die wie oben beschrieben strukturiert sein muss</td></tr><tr><td rowspan=2><img src="doc/en/media/calendar_timeaxis.png"></td><td> Startstunde</td><td> Die Stunde, ab der Termine in der Wochen- und Tagesansicht angezeigt werden sollen.</td></tr><tr><td> Endstunde</td><td> Die Stunde, bis zu der Termine in der Wochen- und Tagesansicht angezeigt werden sollen</td></tr></tbody></table>

Wenn Sie das Widget mit [Adapter](https://github.com/iobroker-community-adapters/ioBroker.ical) verwenden möchten, können Sie das ical-Objekt mit dem folgenden Skript für die Arbeit mit dem Widget konvertieren.

```
// momentjs is required as dependecies in javascript adapter
const moment = require("moment");

var instances = $(`[id=ical.*.data.table]`);
instances.on(ical2CalendarWidget);

// remove this, if you know to use your own datapoint
let datapointId = 'materialdesignwidgets.calendar.ical2calendar'
createState(datapointId, "[]", {
  read: true,
  write: false,
  desc: "JSON String for Calendar Widget",
  type: "string",
  def: "[]"
});

function ical2CalendarWidget() {
    try {
        let calList = [];

        for (var inst = 0; inst <= instances.length - 1; inst++) {
            let icalObj = getState(instances[inst]).val;

            if (icalObj) {
                for (var i = 0; i <= icalObj.length - 1; i++) {
                    let item = icalObj[i];

                    // extract calendar color
                    let calendarName = item._class.split(' ')[0].replace('ical_', '');

                    let startTime = moment(item._date);
                    let endTime = moment(item._end);

                    let start = startTime.format("YYYY-MM-DD HH:mm");
                    let end = endTime.format("YYYY-MM-DD HH:mm");

                    if (startTime.format('HH:mm') === '00:00' && endTime.format('HH:mm') === '00:00') {
                        // is full-day event
                        if (endTime.diff(startTime, 'hours') === 24) {
                            // full-day event, one day
                            start = startTime.format("YYYY-MM-DD");
                            end = startTime.format("YYYY-MM-DD");
                        } else {
                            // full-day event, multiple days
                            start = startTime.format("YYYY-MM-DD");
                            end = endTime.format("YYYY-MM-DD");
                        }
                    }

                    // create object for calendar widget
                    calList.push({
                        name: item.event,
                        color: getMyCalendarColor(calendarName),
                        colorText: getMyCalendarTextColor(calendarName),
                        start: start,
                        end: end
                    })
                }

                function getMyCalendarColor(calendarName) {
                    // assign colors via the calendar names, use calendar name as set in ical
                    if (calendarName === 'calendar1') {
                        return '#FF0000';
                    } else if (calendarName === 'calendar2') {
                        return '#44739e'
                    } else if (calendarName === 'calendar3') {
                        return '#32a852'
                    }
                }

                function getMyCalendarTextColor(calendarName) {
                    // assign colors via the calendar names, use calendar name as set in ical
                    if (calendarName === 'calendar1') {
                        return '#FFFFFF';
                    } else if (calendarName === 'calendar2') {
                        return '#FFFFFF'
                    } else if (calendarName === 'calendar3') {
                        return '#FFFFFF'
                    }
                }
            }

            // Enter the destination data point that is to be used as object ID in the widget
            setState(datapointId, JSON.stringify(calList), true);
        }
    } catch (e) {
        console.error(`ical2MaterialDesignCalendarWidget: message: ${e.message}, stack: ${e.stack}`);
    }
}

ical2CalendarWidget();
```

## HTML-Elemente
Erstellen Sie ein HTML-Element aus den unterstützten Material Design-Widgets, um es in jedem anderen Widget zu verwenden, das HTML unterstützt.
Gestalten Sie einfach Ihr Material Design-Widget, drücken Sie die `generate Html Element`, kopieren Sie die Daten und fügen Sie sie in ein Widget ein, das HTML-Tags unterstützt.
Oder verwenden Sie es in Skripten, um dynamisch Widgets zu generieren.

![Logo](../../../en/adapterref/iobroker.vis-materialdesign/doc/en/media/html-elements.gif)

Weitere Informationen zu den unterstützten Eigenschaften finden Sie in den einzelnen Widgets:

* [Tasten] (# Tasten)
* [Schaltflächen vertikal] (# Schaltflächen vertikal)
* [Buttons Icon] (# Buttons-Icon)

*

* [Schieberegler] (# Schieberegler)

*

* [Fortschritt] (# Fortschritt)
* [Fortschrittsrundschreiben] (# Fortschrittsrundschreiben)

*

* [Checkbox] (# Checkbox)
* [Schalter] (# Schalter)

# Gebrauchte Bibliotheken
Der Adapter verwendet die folgenden Bibliotheken:

* [Google Materialkomponenten für das Web] (https://github.com/material-components/material-components-web)
* [Vuetify] (https://github.com/vuetifyjs/vuetify)
* [chartjs] (https://www.chartjs.org/)
* [runder Schieberegler von Thomasloven] (https://github.com/thomasloven/round-slider)
* [Material Design Icons] (https://materialdesignicons.com/)

## Changelog

<!--
    Placeholder for the next version (at the beginning of the line):    
	### __WORK IN PROGRESS__
-->

<!-- omit in toc -->
### __WORK IN PROGRESS__
* (Scrounger) icon list: option for status bar text added
* (Scrounger) icon list: status bar position bug fix
* (Scrounger) progress circular: auto size option added
* (Scrounger) VIS editor: html previews bug fixes

<!-- omit in toc -->
### 0.4.2 (2020-12-29)
* (Scrounger) vis-google-fonts dependency removed

<!-- omit in toc -->
### 0.4.1 (2020-12-27)
* (Scrounger): Adapter settings: theme editor implementation completed
* (Scrounger): Progress Widget: condition binding bug fix
* (Scrounger): minimal VIS adapter dependency set to v1.3.6
* (Scrounger): VIS editor: image dialog bug fix
* (Scrounger): Color themes for buttons and dialogs widgets implemented
* (Scrounger): Calendar Widget: week number bug fix
* (Scrougner): icon list: scrollbar bug fix
* (Scrounger): bug fixes

<!-- omit in toc -->
### 0.4.0-beta (2020-12-09)
* (Scrounger): Line History Chart Widget: Breaking Changes !!! aggregate (display) method for every dataset configurable, [see documentation for detailed infos](#line-history-chart)!
* (Scrounger): TopAppBar Widget: Breaking Changes !!! Submenus must now be created using JSON string, [see documentation for detailed infos](#since-version-040)!
* (Scrounger): Adapter settings wiht theme editor added
* (Scrounger): bug fix for compatibility issues with other widget adapters
* (Scrounger): Chechbox Widget: option for border and hover color added
* (Scrounger): Chechbox Widget: ripple effect bug fix
* (Scrounger): Buttons Vertical: text alignment option added
* (Scrounger): added URL support as source for symbols / images
* (Scrounger): HTML Card Widget: option to hide title, subtitle and text added
* (Scrounger): HTML Card Widget: background image refresh options by datapoint added
* (Scrounger): Fixed some errors reported via Sentry
* (Scrounger): Select & Autocomplete Widget: overriding icon color bug fix
* (Scrounger): Select & Autocomplete Widget: overriding icon bug fix
* (Scrounger): Select & Autocomplete Widget: colors bug fixes
* (Scrounger): Select & Autocomplete Widget: option to override the icon color of textfield for selected menu icon
* (Scrounger): Select & Autocomplete Widget: text alignment option added
* (Scrounger): Input Widget: text alignment option added
* (Scrounger): JSON Chart Widget: option to force x-axis time unit added
* (Scrounger): JSON Chart Widget: gradient colors for multipe dataset bug fixes
* (Scrounger): JSON Chart: default tooltip title added
* (Scrounger): JSON Chart: option to use Today / Yesterday for x-axis labeling added
* (Scrounger): JSON Chart: option to use Today / Yesterday for tooltip added
* (Scrounger): JSON Chart: option to change x-axis label distance added
* (Scrounger): Line History Chart: option for point color added
* (Scrounger): Line History Chart: option to use Today / Yesterday for x-axis labeling added
* (Scrounger): Line History Chart: option to use Today / Yesterday for tooltip added
* (Scrounger): Line History Chart: tooption change x-axis label distance added
* (Scrounger): Charts Widget: x-Axis time axis bug fixes
* (Scrounger): Calendar Widget: option to show calendar week numbers in month view added
* (Scrounger): Calendar Widget: option for custom date format added
* (Scrounger): IconList Widget: bug fix for performance issue
* (Scrounger): TopAppBar Widget: options for user groups added
* (Scrounger): Table Widget: html element added
* (Scrounger): Masonry & Grid View Widget: default width for handy portrait and landscape view changed
* (Scrounger): Progress Widget: option for indeterminate style added
* (Scrounger): dependencies updated
* (Scrounger): bug fixes

<!-- omit in toc -->
### 0.3.19 (2020-07-18)
* (Scrounger): Icon Button Widget: background color option for lock icon added
* (Scrounger): possibility to deactivate sentry implemented -> see documentation
* (Scrounger): Fixed some bugs reported via Sentry
* (Scrounger): prevent set value in vis editor
* (Scrounger): Grid & Mansonry Widget: visibilty by resoltuin bug fix
* (Scrounger): IconList Widget: Card Background for whole icon list added
* (Scrounger): Table Wigdet: button link widget added
* (Scrounger): Table Wigdet: material design icon widget added
* (Scrounger): Table Wigdet: alignment option for controls added
* (Scrounger): materialdesignicons library updated to v5.3.45
* (Scrounger): Round Slider lib updated to v0.5.0
* (Scrounger): Round Slider Widget: readonly option added
* (Scrounger): Table Widget: background color hover option added
* (Scrounger): bug fixes

## License

MIT License

Copyright (c) 2021 Scrounger <scrounger@gmx.net>

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