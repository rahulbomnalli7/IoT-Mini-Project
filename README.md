# Water Level Monitoring System with Blynk and Arduino

## Overview

This project is an IoT-based water level monitoring system using an Arduino, ultrasonic sensor, LCD display, and the Blynk cloud platform. It allows you to monitor water levels in a tank in real-time, making it suitable for applications like home water tanks, agricultural irrigation, and industrial water storage.

The system uses an ESP8266 microcontroller, which is connected to the internet via Wi-Fi. It continuously measures the water level in the tank using an ultrasonic sensor and provides real-time updates to your smartphone or computer via the Blynk app. Additionally, it displays the water level on a 16x2 LCD screen for local monitoring.

## Components and Libraries

- Arduino IDE
- ESP8266WiFi library
- BlynkSimpleEsp8266 library
- Wire library
- LiquidCrystal_I2C library

## Hardware Components

- ESP8266 microcontroller
- Ultrasonic sensor (HC-SR04)
- 16x2 LCD display with I2C interface
- LEDs (5 pieces)
- Resistors, wires, and a power source

## Setup Instructions

1. Install Arduino IDE on your computer if not already installed.
2. Install the necessary libraries mentioned in the code.
3. Configure the ESP8266 with your Wi-Fi credentials and Blynk authentication token.
4. Wire up the components according to the provided pin definitions.
5. Upload the Arduino sketch to the ESP8266.
6. Open the Blynk app on your smartphone and create a new project, obtaining the Blynk authentication token.
7. Add a Gauge widget to your Blynk project to visualize the water level.
8. Power up your system, and you can now monitor the water level through the app and the LCD screen.

## Usage

- The system continuously measures the water level and sends it to the Blynk app.
- The LCD screen displays the current water level.
- LEDs indicate the water level categories: Very Low, Low, Medium, High, and Full.
- You can set up alerts or triggers on the Blynk app for automated actions based on water level.

## Acknowledgments

- This project was inspired by the need for a simple and efficient water level monitoring system.
- Special thanks to the open-source Arduino and Blynk communities for their support and libraries.

