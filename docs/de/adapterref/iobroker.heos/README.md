---
translatedFrom: en
translatedWarning: Wenn Sie dieses Dokument bearbeiten möchten, löschen Sie bitte das Feld "translationsFrom". Andernfalls wird dieses Dokument automatisch erneut übersetzt
editLink: https://github.com/ioBroker/ioBroker.docs/edit/master/docs/de/adapterref/iobroker.heos/README.md
title: ioBroker.heos
hash: DCjvEfljhMQR9HEQnV7G6zbATno+KP5R6w8X5bmIxLk=
---
![Logo](../../../en/adapterref/iobroker.heos/admin/heos.png)

![NPM-Version](http://img.shields.io/npm/v/iobroker.heos.svg)
![Downloads](https://img.shields.io/npm/dm/iobroker.heos.svg)
![Anzahl der Installationen (aktuell)](http://iobroker.live/badges/heos-installed.svg)
![Anzahl der Installationen (stabil)](http://iobroker.live/badges/heos-stable.svg)
![Abhängigkeitsstatus](https://img.shields.io/david/withstu/iobroker.heos.svg)
![Bekannte Sicherheitslücken](https://snyk.io/test/github/withstu/ioBroker.heos/badge.svg)
![NPM](https://nodei.co/npm/iobroker.heos.png?downloads=true)

# IoBroker.heos
## Heos Adapter für ioBroker
Mit dem Adapter können Sie HEOS von ioBroker aus steuern

## Aufbau
* "AutoPlay": Spielt automatisch Musik ab, nachdem der Player angeschlossen oder die Stummschaltung aufgehoben wurde. Kann global in der Konfiguration konfiguriert werden. Wenn es global aktiviert ist, können Sie es für einen bestimmten Spieler mit dem Status auto_play deaktivieren
* "ignore_broadcast_cmd": Dieser Player-Status wird konfiguriert, wenn der Player Befehle an alle Player ignorieren soll, z. player / set_mute & state = on oder Drücken der Wiedergabetaste für Voreinstellungen / Wiedergabelisten

## Befehl
HEOS CLI-Spezifikation: http://rn.dmglobal.com/euheos/HEOS_CLI_ProtocolSpecification.pdf

### HEOS-Befehlsstatus
* "system / connect": Versuchen Sie, eine Verbindung zu HEOS herzustellen
* "System / Trennen": Trennen Sie die Verbindung zum HEOS
* "System / Wiederverbindung": Trennen und Verbinden
* "system / load_sources": Quellen neu laden
* "group / set_group? pid = <pid1>, <pid2>, ...": Gruppe mit der Liste der Spieler-IDs festlegen, z. "group / set_group? pid = 12345678,12345679".
* "group / set_group? pid = <pid1>": Löschen Sie eine vorhandene Gruppe, z. "group / set_group? pid = 12345678"
* "group / ungroup_all": Alle Gruppen löschen
* "group / group_all": Gruppiert alle Spieler in einer Gruppe
* "player / [cmd]": Sende den Befehl an alle Spieler. z.B. player / set_mute & state = on
* "Anführer / [cmd]": Senden Sie den Befehl an alle führenden Spieler. z.B. Leader / set_mute & state = on
* "scope / [cmd]": Senden Sie den Befehl an den konfigurierten Bereich aller Spieler, führenden Spieler oder durch Kommas getrennten Spieler-Pids in scope_pids
* "...": Alle anderen Befehle werden versucht, an HEOS zu senden

### Player-Befehlsstatus
Hinweis: Mehrere Befehle sind möglich, wenn sie mit der Pipe getrennt sind, z. set_volume & level = 20 | play_preset & preset = 1

* "set_volume & level = 0 | 1 | .. | 100": Stellen Sie die Player-Lautstärke ein
* "set_play_state & state = play | pause | stop": Legt den Player-Status fest
* "set_play_mode & repeat = on_all | on_one | off & shuffle = on | off": Set Repeat and Shuffle-Modus
* "set_mute & state = on | off": Spieler stumm schalten
* "volume_down & step = 1..10": Niedrigere Lautstärke
* "volume_up & step = 1..10": Erhöhen Sie die Lautstärke
* "play_next": Weiter spielen
* "play_previous": Vorherige spielen
* "play_preset & preset = 1 | 2 | .. | n": Preset n abspielen
* "play_stream & url = url_path": URL-Stream abspielen
* "add_to_queue & sid = 1025 & aid = 4 & cid = [CID]": Wiedergabeliste mit [CID] auf dem Player abspielen (Hilfe: 1 - jetzt spielen; 2 - als nächstes spielen; 3 - zum Ende hinzufügen; 4 - ersetzen und spielen)

## Regex stumm schalten
In der Konfiguration können Sie eine Funktion aktivieren, um den Player basierend auf einer Regex-Übereinstimmung mit den Songinformationen stummzuschalten. Damit können Anzeigen automatisch stummgeschaltet werden. Für Spotify können Sie beispielsweise den folgenden regulären Ausdruck verwenden: ```spotify:ad:|Advertisement```.

## Quellen durchsuchen
Um den Statusbetrag in ioBroker zu reduzieren, werden automatisch nur Wiedergabelisten und Voreinstellungen in den Status gespeichert. Zuerst müssen Sie jedoch auf die Schaltfläche Durchsuchen im Ordner Wiedergabelisten oder Voreinstellungen klicken. Sie finden und steuern sie im Ordner "Quellen". Wenn Sie die Musik einer Quelle durchsuchen möchten, klicken Sie einfach auf die Schaltfläche Durchsuchen. Sie finden das Suchergebnis im Status "sources.browse_result". Es gibt auch Befehle, um tiefer zu navigieren oder eine Ressource abzuspielen. Fügen Sie einfach die Befehle in das globale HEOS-Befehlsfeld ein. Wenn es sich um einen Durchsuchungsbefehl handelt, finden Sie das Ergebnis im Status browse_result. In der Konfiguration finden Sie eine Option zur Steuerung des Umfangs der Wiedergabebefehle. Damit können Sie steuern, ob die Spielbefehle an alle Spieler, an alle Anführer und Nicht-Gruppenspieler oder an eine Liste von Spieler-IDs gehen, die im Status command_scope_pid definiert sind.

Für die VIS-Integration können Sie das browse_result und das folgende Skript verwenden, um eine HTML-Tabelle zu generieren (diese ist nicht im Adapter integriert, sodass Sie die Möglichkeit haben, sie zu formatieren). Alternativ verwenden Sie das Skript von Uhula https://forum.iobroker.net/post/498779:

```javascript
on({id: 'heos.0.sources.browse_result', change: 'any'}, function (obj) {
  let data = JSON.parse(obj.state.val);
  let html = `<style>
  .heos-browse {
      background-color: #333333;
      color: #eaeaea;
      height: 100%;
      width: 100%;
      position: absolute;
      overflow: auto;
  }
  .heos-browse table {
      width: 100%;
      border-collapse: collapse;
  }
  .heos-browse table,
  .heos-browse th,
  .heos-browse td {
      border: 1px solid #929292;
      border-width:1px 0;
  }
  .heos-browse th {
      font-size: 2em;
      border: 1px solid #c50000;
      border-width: 0 0 1px 0;
      text-align: center;
  }
  .heos-browse th {
      padding: 15px;
      height: 60px;
  }
  .heos-browse td {
      padding: 5px;
      height: 60px;
  }
  .heos-browse-btn {
      color: #fff;
      background-color: Transparent;
      background-repeat:no-repeat;
      border: none;
      cursor:pointer;
      overflow: hidden;
      outline:none;
      margin: 0 !important;
      padding: 0 !important;
      font-size: 30px !important;
      line-height: 30px;
      width: 60px;
      height: 60px;
  }
  .heos-browse-btn-multi {
      border-right: 1px solid #929292;
  }
  .heos-browse-row-media {
      cursor: pointer;
  }
  .heos-browse-row-control {
      color: #d60000;
      cursor: pointer;
  }
  .heos-browse-image {
      white-space: nowrap;
      padding: 0 !important;
      text-align: right;
      font-size: 0;
  }
  .heos-browse-image img {
      height: 60px;
  }
  .heos-browse-name {
      width: 100%;
      text-align: left;
  }
  .heos-browse-control {
      padding: 0 !important;
      margin: 0 !important;
      white-space: nowrap;
      font-size: 0;
      text-align: right;
  }
  </style>`;
  if(data){
      html += "<div class=\"heos-browse\">"
      html += "<table>"
      html += "<tr><th>";
      if(data.image_url.length){
          html += "<img src=\"" + data.image_url + "\" height=\"30px\">";
      }
      html += "</th><th>" + (data.name == "sources" ? "Overview" : data.name) + "</th><th></th></tr>";
      for (let i = 0; i < data.payload.length; i++) {
          let payload = data.payload[i];
          html += "<tr class=\"";
          if(payload.type == "control"){
            html += "heos-browse-row-control";
          } else {
              html += "heos-browse-row-media"
          }
          html += "\">";
          html += "<td class=\"heos-browse-image\"";
          if("browse" in payload.commands){
              html += " onClick=\"servConn.setState('heos.0.command','" + payload.commands["browse"].replace(/'/g, "\\'") +"')\"";
          } else if(Object.keys(payload.commands).length == 1){
              html += " onClick=\"servConn.setState('heos.0.command','" + payload.commands[Object.keys(payload.commands)[0]].replace(/'/g, "\\'") +"')\"";
          }
          html += ">"
          if(payload.image_url.length){
            html += "<img src=\"" + payload.image_url + "\">";
          }
          html += "</td>";
          html += "<td class=\"heos-browse-name\"";
          if("browse" in payload.commands){
              html += " onClick=\"servConn.setState('heos.0.command','" + payload.commands["browse"].replace(/'/g, "\\'") + "')\"";
          } else if(Object.keys(payload.commands).length == 1){
              html += " onClick=\"servConn.setState('heos.0.command','" + payload.commands[Object.keys(payload.commands)[0]].replace(/'/g, "\\'") +"')\"";
          }
          html += ">"
          if(payload.type == "control"){
            switch(payload.name){
              case "load_next":
                html += "Next page";
                break;
              case "load_prev":
                html += "Previous page";
                break;
              case "play_all":
                html += "Play all";
                break;
              case "back":
                html += "Back";
                break;
              case "sources":
                html += "Overview";
                break;
            }
          } else {
            html += payload.name;
          }
          html +="</td>";
          html += "<td class=\"heos-browse-control\">";
          for (let key in payload.commands) {
            let command = payload.commands[key];
            html += "<button class=\"heos-browse-btn"
            if(Object.keys(payload.commands).length > 1){
                html += " heos-browse-btn-multi"
            }
            html += "\" onClick=\"servConn.setState('heos.0.command','" + command.replace(/'/g, "\\'") +"')\">"
            switch(key){
                case "play":
                html += "►";
                break;
                case "browse":
                html += ">";
                break;
            }
            html += "</button>";
          }
          html += "</td>";
          html += "</tr>";
      }
      html += "</table></div>";
  }
  setState("0_userdata.0.heos.browse_result_html", html);
});
```

## Changelog

### 1.6.1 (2020-11-25)
* (withstu) clear timeout and interval on unload; fix roles; remove sleep in tts module

### 1.6.0 (2020-11-22)
* (withstu) add regex mute

### 1.5.6 (2020-11-22)
* (withstu) add source images & optimize auto play

### 1.5.5 (2020-11-01)
* (withstu) update some packages and add sources event

### 1.5.4 (2020-10-24)
* (withstu) ignore invalid now playing responses

### 1.5.3 (2020-10-18)
* (withstu) minor improvements related to auto play feature

### 1.5.2 (2020-10-11)
* (withstu) improve tts stop method

### 1.5.1 (2020-10-11)
* (withstu) improve tts and don't update queue during tts

### 1.5.0 (2020-10-10)
* (withstu) add tts support and maximum volume

### 1.4.0 (2020-10-10)
* (withstu) add more play and queue settings
* (withstu) bugfixing for invalid heos responses (empty player name)

### 1.3.4 (2020-10-04)
* (withstu) remove sorting and available filter and fix browse play

### 1.3.3 (2020-10-04)
* (withstu) fix previous page button in browse feature

### 1.3.2 (2020-10-04)
* (withstu) fix preset sorting

### 1.3.1 (2020-10-03)
* (withstu) add back button to browse feature

### 1.3.0 (2020-10-03)
* (withstu) add queue and some browse improvements

### 1.2.4 (2020-09-29)
* (withstu) minor bugfix

### 1.2.3 (2020-09-29)
* (withstu) improve browse feature (add pictures and sources view)

### 1.2.2 (2020-09-28)
* (withstu) rename browse command

### 1.2.1 (2020-09-28)
* (withstu) introduce browse_result state

### 1.2.0 (2020-09-27)
* (withstu) Breaking change: restructure playlists/presets (you should delete the devices playlists, presets and sources before installation)

### 1.1.2 (2020-09-26)
* (withstu) log browse parameters

### 1.1.1 (2020-09-26)
* (withstu) add source browse feature (Click the button in the sources. You can find the possible next commands in the log.)

### 1.1.0 (2020-09-26)
* (withstu) encrypt password

### 1.0.1 (2020-09-21)
* (withstu) remove connected state, because it is included in the info channel

### 1.0.0 (2020-09-21)
* (withstu) initial release

## License
MIT License

Copyright (c) 2020 withstu <withstu@gmx.de>

derived from https://forum.iobroker.net/topic/10420/vorlage-denon-heos-script by Uwe Uhula
TTS derived from https://github.com/ioBroker/ioBroker.sonos

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