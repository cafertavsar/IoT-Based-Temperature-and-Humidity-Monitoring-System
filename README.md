IOT-BASED TEMPERATURE AND HUMIDITY MONITORING SYSTEM

PROJECT DESCRIPTION

This project is an IoT-based solution designed to measure and monitor environmental temperature and humidity in real time. It utilizes a DHT11 sensor to collect data, and an ESP32 development board to send the collected values to the ThingSpeak cloud platform over Wi-Fi. The data can be visualized through charts remotely, providing a low-cost and scalable environmental monitoring system.


KEY FEATURES


-Real-time temperature and humidity data collection

-Wireless data transmission using ESP32

-Cloud integration with ThingSpeak

-Remote visualization on web dashboards

-Easy to modify and expand


HARDWARE USED


-ESP32 Wi-Fi module

-DHT11 temperature and humidity sensor

-Breadboard and jumper wires
(Optional: OLED display, buzzer, power source)


SOFTWARE TOOLS


-Arduino IDE

-DHT sensor library

-ThingSpeak library

-ThingSpeak cloud platform

HOW IT WORKS

The DHT11 sensor measures the temperature and humidity every few seconds. The ESP32 board reads these values and uploads them to a specific ThingSpeak channel using your Wi-Fi connection. You can view the uploaded data remotely on a browser in the form of live graphs.


SETUP INSTRUCTIONS


-Connect the DHT11 sensor to the ESP32 (VCC to 3.3V, GND to GND, Data to GPIO4).

-Open Arduino IDE, install the required libraries (DHT and ThingSpeak).

-Enter your Wi-Fi credentials and ThingSpeak API information into the code.

-Upload the code to the ESP32.

-Log in to your ThingSpeak channel to monitor the data.


POTENTIAL ENHANCEMENTS


-Send alerts when thresholds are exceeded (email, SMS, buzzer)

-Use an OLED screen to display values locally

-Add a mobile app interface with Firebase

-Extend battery life for portable monitoring
