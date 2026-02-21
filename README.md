# ESP32 Project: Combined Version

## Опис ідеї (Vision)
Система моніторингу навколишнього середовища на базі ESP32. 
Цей MVP (Minimum Viable Product) дозволяє зчитувати дані з сенсорів та передавати їх по UART/Wi-Fi.

## Стек технологій
* Microcontroller: ESP32-C6
* Language: C++ (ESP-IDF / Arduino)
* Protocol: MQTT/HTTP

## Інструкція з розгортання та запуску
1. Встановіть середовище розробки (VS Code + PlatformIO).
2. Підключіть ESP32 до USB.
3. Виконайте збірку: `pio run`.
4. Завантажте код: `pio run -t upload`.