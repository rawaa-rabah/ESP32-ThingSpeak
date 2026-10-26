# ESP32 ThingSpeak Project

Name: Rawaa Shahade
University ID: 12325320

## Project description
In this project I connected an ESP32 with a DHT22 sensor to measure temperature and humidity.
The ESP32 connects to the Wi-Fi, reads the data from the sensor, and sends it to ThingSpeak every 20 seconds.
On ThingSpeak I made a public channel with 2 fields: Field 1 for temperature and Field 2 for humidity.
The data is shown in two live charts that anyone can open using the public link.
I used Wokwi to simulate the ESP32 and the sensor, because I don't have the real hardware.
Also, the code prints my university ID in the Serial Monitor with every reading.

## Links
ThingSpeak public channel: https://thingspeak.mathworks.com/channels/3551588

Wokwi project: https://wokwi.com/projects/478954487865016321

## Wiring
- DHT22 VCC -> ESP32 3V3
- DHT22 SDA (data) -> ESP32 GPIO 15
- DHT22 GND -> ESP32 GND


## ThingSpeak channel
Channel name: Rawaa_Shahade_12325320
- Field 1: Temperature (C)
- Field 2: Humidity (%)




