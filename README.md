# Uroki_Esp32
заметки по esp32 и попыткам научиться с ней работать.
## Вводная часть
В наличии ESP-WROOM-32 38 PIN и esp32cam с Alieexpress. В плане среды разработки - Arduino Ide.
### Полезные видео
При обучении отталкивался от этих двух каналов.

https://www.youtube.com/watch?v=iLTHgnZ4li4

https://www.youtube.com/watch?v=g1pJ3RYAPwE


###Установка драйверов и.т.д.
Часть информации брал отсюда: https://voltiq.ru/instruction-installing-esp32-board-in-arduino-ide-for-windows/

а) Запустить среду Arduino Ide>>>меню "файл">>>настройки>>>"дополнительные ссылки для менеджера плат">>>вставить ссылку https://raw.githubusercontent.com/espressif/arduino-esp32/gh-pages/package_esp32_index.json

б) Далее зайти в "Инструменты" >>>"Платы">>> Менеджер плат. Найти Esp32. В "Платах" появится вкладка "Esp Arduino".

в) На самой плате стоит микросхема usb uart cp2102. Драйвера для windows брал отсюда: https://www.silabs.com/developers/usb-to-uart-bridge-vcp-drivers?tab=downloads

г) Среди плат выбрал "esp32 dev module". В штатном скетче с блинком указавал порт принудительно.
