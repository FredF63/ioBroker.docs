---
translatedFrom: en
translatedWarning: Если вы хотите отредактировать этот документ, удалите поле «translationFrom», в противном случае этот документ будет снова автоматически переведен
editLink: https://github.com/ioBroker/ioBroker.docs/edit/master/docs/ru/adapterref/iobroker.growatt/README.md
title: ioBroker.growatt
hash: qqvE2OM/6oZMWmhSpifTAMEcDCczFUPaus8TIljn38Y=
---
![Логотип](../../../en/adapterref/iobroker.growatt/admin/glogo.png)

![Версия NPM](http://img.shields.io/npm/v/iobroker.growatt.svg)
![Загрузки](https://img.shields.io/npm/dm/iobroker.growatt.svg)
![Количество установок (последнее)](http://iobroker.live/badges/growatt-installed.svg)
![Количество установок (стабильно)](http://iobroker.live/badges/growatt-stable.svg)
![Статус зависимости](https://img.shields.io/david/PLCHome/ioBroker.growatt.svg)
![НПМ](https://nodei.co/npm/iobroker.growatt.png?downloads=true)

# IoBroker.growatt
## Адаптер Growatt для ioBroker
ioBroker Growatt Адаптер для связи с Growatt Shine Server.
Я не аффилирован.
Обычно данные отправляются из регистратора данных в облако каждые 5 минут.
Вы можете изменить его, см. Ниже.
Программное обеспечение опрашивает сервер каждые 30 секунд, чтобы смещение не было слишком большим.

Реализованы не все типы установок.

В настоящее время можно читать только данные, запись параметров или изменение параметров невозможно.

# Интервал данных ускорения
## Вы можете установить интервал регистрации от 5 минут до 1 минуты.
Снимите резиновую заглушку кнопки KEY с ShineWiFi-S и коротко нажмите кнопку внутри. Загорится синий светодиод. Используйте свой телефон или компьютер для подключения к беспроводной сети, излучаемой модулем ShineWiFi-S. Имя сети / SSID - это серийный номер модуля ShineWiFi-S.

## Страница авторизации
После успешного установления соединения откройте веб-браузер на своем телефоне или компьютере и введите 192.168.10.100 в адресной строке. Имя пользователя - admin, пароль по умолчанию - 12345678.
![Страница авторизации](../../../en/adapterref/iobroker.growatt/docs/login.png)

## Расширенные настройки
Измените время интервала данных на 1 минуту ![Расширенные настройки](../../../en/adapterref/iobroker.growatt/docs/advancedsettings.png)

## Перезагрузка системы
Перезапустите модуль ShineWiFi-S на этой странице, нажмите «Перезагрузить немедленно», чтобы активировать новые настройки, которые вы только что сделали, и выйдите из внутреннего веб-сервера вашего модуля ShineWiFi.
![Перезагрузка системы](../../../en/adapterref/iobroker.growatt/docs/restart.png)

** Нет изменений в диаграммах на стороне роста. Здесь вы можете увидеть только изменение данных из регистратора данных. **

# Немецкий - Интервал данных ускорения
## Du kannst das Protokollierungsintervall von 5 Minuten auf 1 Minute einstellen
Den Gummi vor dem KEY Button des ShineWiFi-S entfernen und den Button kurz drücken.
Der ShineWiFi-S spielt nun kurz Hotspot (SSID = Seriennummer des ShineWiFi-S). Beim Netz mit einem Laptop or dem Handy anmelden.

## Einloggen
также Webadresse http://192.168.10.100 в браузере eingeben.
Имя пользователя является администратором и паролем 12345678 (только для управления системой).
![Страница авторизации](../../../en/adapterref/iobroker.growatt/docs/login.png)

## Расширенные настройки
Auf "Advanced Settings" gehen und das Intervall ändern. (фон 5 ауф 1) ![Расширенные настройки](../../../en/adapterref/iobroker.growatt/docs/advancedsettings.png)

## Перезагрузка системы
Auf System Restart gehen und Button herzhaft, aber vorsichtig Klicken.
![Перезагрузка системы](../../../en/adapterref/iobroker.growatt/docs/restart.png)

** Es gibt keine Änderung an den Diagrammen auf der Growatt-Seite, die bleiben bei 5min. Dort sehen Sie nur eine Änderung der Daten im Datenlogger. **

# Страница администратора адаптера
### Пользователь и пароль
Введите имя и пароль, которые вы также используете в приложении Shine или на веб-портале.

### Войти с общим ключом
На веб-сайте Growatt в разделе «Энергия, управление заводом, инструменты управления» вы можете отправить себе ключ по электронной почте.

### Прочитать данные о заводе
Эта запись данных содержит сохраненные основные данные

### Прочитать последние данные истории
Считывает последнюю запись данных из истории регистратора данных.
Эта функция поддерживает минутные интервалы для регистратора данных.

### Прочитать данные о статусе
Эти данные доступны не для всех заводов (кроме INV / MAX / TLX). Этот набор данных содержит данные в реальном времени.
Эта функция поддерживает минутные интервалы для регистратора данных.

### Прочитать последние данные графика
** Устарело: скоро будет удалено. ** Эти данные доступны только для заводов без считывания данных о состоянии (INV / MAX / TLX). Ищутся последние действительные данные за день.
Минутные интервалы не поддерживаются.

### Прочитать данные диаграммы
** Устарело: скоро будет удалено. ** Эти данные доступны только для заводов без считывания данных о состоянии и требуют считывания последних данных диаграммы (INV / MAX / TLX). Данные записываются и хранятся в виде строки JSON.
Минутные интервалы не поддерживаются.

### Прочитать общие данные
Эта запись данных содержит данные агрегирования.

### Прочитать данные устройства
Эта запись данных содержит некоторые данные с устройства. Некоторые данные также доступны в других категориях.

### Читать погоду
Этот набор данных содержит прогноз погоды.

-*-

## Changelog
### 0.0.17 (21.01.2021)
* (PLCHome) fixes a date issue on inverter history data.

### 0.0.16 (20.01.2021)
* (PLCHome) npm package version update
* (PLCHome) add last history for all plants. Special thanks to magix for the key, so i can test the inverter history function.

### 0.0.15 (04.12.2020)
* (PLCHome) npm package version update

### 0.0.14 (01.12.2020)
* (PLCHome) improvement for objects not returned from Growatt website

### 0.0.12 (27.11.2020)
* (PLCHome) wrong initialization for shared key: string instead of boolean

### 0.0.11 (27.11.2020)
* (PLCHome) Read me

### 0.0.10 (26.11.2020)
* (PLCHome) Shared key login
* (PLCHome) Last value of the graph if there are no live data.
* (PLCHome) Change of the polling interval

### 0.0.9 (05.10.2020)
* (PLCHome) fix no feature 'ADAPTER_AUTO_DECRYPT_NATIVE'

### 0.0.8 (05.10.2020)
* (PLCHome) fix io-package

### 0.0.7 (05.10.2020)
* (PLCHome) with "@iobroker/adapter-core": "^2.4.0", the js-controller dep needs to be >=2.0.0!
* (PLCHome) io-package native defined 5 values, admin sets 7
* (PLCHome) store password encrypted

### 0.0.6 (31.08.2020)
* (PLCHome) translation with ioBroker tool.

### 0.0.5
* (PLCHome) initial release.

### 0.0.1
* (PLCHome) initial release.


-*-

## License
MIT License

Copyright (c) 2021 PLCHome <https://github.com/PLCHome>

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