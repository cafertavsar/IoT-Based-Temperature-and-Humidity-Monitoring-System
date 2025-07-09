# IoT-Based Temperature and Humidity Monitoring System

## Project Description
This project is an IoT-based solution for real-time monitoring of environmental temperature and humidity. Using a DHT11 sensor, the system collects data and sends it to the ThingSpeak cloud platform via an ESP32 development board over Wi-Fi. The project provides a low-cost, scalable solution with remote visualization through web-based charts, making it ideal for environmental monitoring.

## Key Features
- **Real-Time Monitoring**: Collects temperature and humidity data in real-time.
- **Wireless Data Transmission**: Uses ESP32 for Wi-Fi connectivity.
- **Cloud Integration**: Sends data to the ThingSpeak cloud platform.
- **Remote Visualization**: View live graphs of the data on web dashboards.
- **Modular and Expandable**: Easily customizable for various use cases.

## Hardware Used
- ESP32 Wi-Fi Module
- DHT11 Temperature and Humidity Sensor
- Breadboard and Jumper Wires
- *(Optional)* OLED Display, Buzzer, Power Source

## Software Tools
- **Arduino IDE**
- **DHT Sensor Library**
- **ThingSpeak Library**
- **ThingSpeak Cloud Platform**

## How It Works
1. The DHT11 sensor measures temperature and humidity periodically.
2. The ESP32 reads these values and uploads them to a ThingSpeak channel using a Wi-Fi connection.
3. The uploaded data can be viewed remotely on a browser, visualized as live graphs.

## Setup Instructions
1. **Hardware Connections**:
   - Connect the DHT11 sensor to the ESP32:
     - VCC → 3.3V
     - GND → GND
     - Data → GPIO4
2. **Software Setup**:
   - Open the Arduino IDE and install the required libraries:
     - `DHT Sensor Library`
     - `ThingSpeak Library`
   - Enter your Wi-Fi credentials and ThingSpeak API information in the code.
3. **Upload Code**:
   - Upload the code to the ESP32 using the Arduino IDE.
4. **Monitor Data**:
   - Log in to your ThingSpeak channel to view the data in real-time.

## Potential Enhancements
- **Threshold Alerts**: Send notifications (email, SMS, or buzzer) when thresholds are exceeded.
- **Local Display**: Use an OLED screen to display values locally.
- **Mobile App**: Integrate with Firebase for a mobile app interface.
- **Battery Optimization**: Extend battery life for portable monitoring.

---
This project is a simple yet powerful platform for IoT-based environmental monitoring. Its accessibility and scalability make it suitable for both educational and practical applications.
