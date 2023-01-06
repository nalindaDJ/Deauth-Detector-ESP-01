# WiFi Deauth Detector

This project uses an ESP01S with an ESP8266 chipset to detect WiFi deauth packets and uses an LED to indicate when a deauth packet is detected.

## Hardware

- ESP01S with ESP8266 chipset
- LED
- Resistor (optional)

## Software

- Arduino IDE
- ESP8266WiFi library

## Setup

1. Connect the LED to the appropriate pin on the ESP01S. If using a resistor, connect it in series with the LED.
2. Open the sketch in the Arduino IDE and upload the sketch to the ESP01S.
4. When the ESP01S powers up, The LED will turn on whenever a deauth packet is detected.

## What's Next
- Add OLED Display to show deauth packets and status
