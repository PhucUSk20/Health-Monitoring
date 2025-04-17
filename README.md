
# 🤖 Health Monitoring BLE

This project features a Bluetooth-enabled health monitoring system designed to measure heart rate and blood oxygen levels using the MAX30102 sensor and the ESP32 microcontroller. The firmware was programmed in C to acquire and transmit biometric data via BLE. A mobile application was developed using MIT App Inventor to display real-time heart rate and SpO2 readings through interactive charts. The app also includes data visualization features for trend tracking and real-time monitoring.

---

## 📌 Table of Contents

- [1. Operating Principle](#1-operating-principle)
- [2. Hardware Wiring Diagram](#2-hardware-wiring-diagram)
- [3. System Operation Flow](#3-system-operation-flow)
- [4. Mobile App Development](#4-mobile-app-development)
- [5. Demo](#5-demo)
- [✅ Technologies Used](#-technologies-used)

---

## 1. Operating Principle

### 1.1 Pulse Oximetry and Heart Rate Measurement
![Pulse Oximetry](https://i.imgur.com/vYC4ZbQ.png)

The measurement principle is based on the difference in light absorption between oxygenated and deoxygenated hemoglobin. A pulse oximeter uses two wavelengths of light—red and infrared—to measure the oxygen saturation in the blood. The sensor emits light through body tissue such as a finger, earlobe, or toe, and detects how much light is absorbed to calculate the SpO2 level. Heart rate monitors function similarly and are commonly worn on the chest, wrist, or ear.

### 1.2 MAX30102 Sensor
![MAX30102 Sensor Overview](https://i.imgur.com/PQfHPLz.png)

The MAX30102 measures blood oxygen levels (SpO2) and heart rate (HR) using a combination of infrared and red light. The sensor includes integrated LEDs and photodiodes that detect reflected light from the bloodstream. The signal is amplified and converted to digital form using an ADC.

![MAX30102 Schematic](https://i.imgur.com/QEPcDPW.png)

---

## 2. Hardware Wiring Diagram
![Wiring Diagram](https://i.imgur.com/hHhhpoH.png)

---

## 3. System Operation Flow

### 3.1 System Block Diagram
![System Block Diagram](https://i.imgur.com/He2zY34.png)

### 3.2 Data Flow
![Data Flow Diagram](https://i.imgur.com/T90ruGr.png)

---

## 4. Mobile App Development with MIT App Inventor

### 4.1 UI Design
![App UI](https://i.imgur.com/xOcw54c.png)

### 4.2 Block Programming
![Blocks 1](https://i.imgur.com/y4z7pJZ.png)
![Blocks 2](https://i.imgur.com/DFrBkk5.png)

### 4.3 Final App Interface
![Final App](https://i.imgur.com/LYu6sfl.png)

---

## 5. Demo
### 🔗 BLE Packet advertising process
[![BLE Packet Reception](https://img.youtube.com/vi/YfaoEofEVxw/0.jpg)](https://youtube.com/shorts/YfaoEofEVxw?feature=share)  
This video demonstrates how the ESP32 continuously broadcasts data packets using BLE advertising.

### 📱 BLE Communication Demo – Mobile App Receiving Data Packets  
[![Mobile BLE Reception](https://img.youtube.com/vi/ORNJgFoQhWs/0.jpg)](https://youtube.com/shorts/ORNJgFoQhWs?feature=share)  
This video shows the mobile application connecting to the BLE device and successfully receiving data in real time.


---

## ✅ Technologies Used

- **Microcontroller**: ESP32  
- **Sensor**: MAX30102  
- **Programming Language**: C  
- **Display**: MIT App Inventor Mobile App  
- **Data Transmission**: Bluetooth Low Energy (BLE)

---
