# Калькулятор расхода воздуха

Полевой калькулятор для наладки вентиляции. Работает офлайн, данные хранятся только на устройстве.

Адрес: https://dooffall78-lgtm.github.io/HVAC-AirFlow-Calculator/

## Установка на Android
1. Откройте адрес выше в Chrome при включённом интернете и дождитесь загрузки страницы.
2. Перейдите на вкладку «Журнал» и нажмите «Установить как приложение».
   Если кнопки нет: меню ⋮ в Chrome → «Установить приложение».
3. Запускайте калькулятор с нового значка. Проверить офлайн-режим можно в режиме полёта.

## Установка на iPhone
Откройте адрес в Safari → «Поделиться» → «На экран “Домой”».

## Замеры
- Журнал замеров хранится в браузере этого устройства. Очистка данных браузера удалит его.
- Периодически делайте копию: «Журнал» → «Копия JSON». Вернуть данные можно кнопкой «Импорт JSON».
- Экспорт для Excel: «Журнал» → «Экспорт CSV».

## Обновление
При изменении кода в файле `sw.js` меняйте номер в строке `V="airflow-v5"`, иначе на устройствах останется старая версия.

## Файлы
index.html, manifest.webmanifest, sw.js, icon-192.png, icon-512.png, apple-touch-icon.png

# HVAC Airflow Calculator

A field calculator for ventilation commissioning. Works offline; all data stays on your device.

URL: https://dooffall78-lgtm.github.io/HVAC-AirFlow-Calculator/

## Install on Android
1. Open the URL above in Chrome while online and wait for the page to load.
2. Go to the "Журнал" (Log) tab and tap "Установить как приложение" (Install as app).
   If the button is missing: Chrome menu ⋮ → "Install app".
3. Launch the calculator from the new icon. To check offline mode, enable airplane mode and open it again.

## Install on iPhone
Open the URL in Safari → Share → "Add to Home Screen".

## Measurements
- The measurement log is stored in this device's browser. Clearing browser data will erase it.
- Back up regularly: Log → "Копия JSON" (JSON backup). Restore with "Импорт JSON" (Import JSON).
- Excel export: Log → "Экспорт CSV" (Export CSV).

## Updating
When you change the code, bump the version in the `V="airflow-v5"` line of `sw.js`, otherwise devices will keep serving the old version.

## Files
index.html, manifest.webmanifest, sw.js, icon-192.png, icon-512.png, apple-touch-icon.png
