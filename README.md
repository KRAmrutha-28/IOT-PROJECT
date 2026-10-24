# Smart Rain Alert and Grain Protection System

## Description
An IoT-based smart agriculture system using ESP32, Rain Sensor, Soil Moisture Sensor, DHT11, OLED Display, Blynk Dashboard, Buzzer, and Servo Motors.

## Features
- Rain Detection
- Soil Moisture Monitoring
- Temperature & Humidity Monitoring
- OLED Display
- Blynk Dashboard Monitoring
- Roof Control Using Servo Motors

## Hardware Used
- ESP32
- DHT11
- Rain Sensor
- Soil Moisture Sensor
- OLED Display
- SG90 Servo Motors
- Buzzer

## Setup
1. Install the Arduino libraries used by the sketch: Blynk, DHT sensor library, ESP32Servo, Adafruit GFX, and Adafruit SSD1306.
2. Copy `secrets.h.example` to `secrets.h`.
3. Set `WIFI_SSID`, `WIFI_PASSWORD`, and `BLYNK_AUTH_TOKEN` in `secrets.h`. Do not commit or share this file.
4. Open `Smart_Agriculture_Project.ino` in the Arduino IDE, select your ESP32 board and port, then upload.

## Developed By
PANDIRI SIVARAMAKRISHNA
SHIRISHA KS
AMRUTHA KR
KALYANI AN
