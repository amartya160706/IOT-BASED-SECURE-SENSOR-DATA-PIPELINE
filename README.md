# 🔐 IoT-Based Secure Sensor Data Pipeline

## 📌 Overview

This project implements a secure IoT-based data pipeline using Raspberry Pi and sensors to collect, process, transmit, and store real-time environmental data. The system integrates IoT communication protocols, cloud services, database storage, and encryption techniques to ensure efficient and secure data handling.

---

## 🚀 Features

* Real-time data collection using sensors (DHT11, Light, Proximity, Temperature)
* Lightweight communication using MQTT protocol
* Cloud integration with ThingSpeak and The Things Network (TTN)
* RESTful API-based data storage and retrieval
* Local database storage using MySQL (LAMP stack)
* Secure data transmission using Fernet encryption
* Sensor-based automation and monitoring systems

---

## 🏗️ System Architecture

```
Sensors → Raspberry Pi → MQTT → Cloud (ThingSpeak / TTN)
                     ↓
                  REST API → MySQL Database
                     ↓
                 Encryption (Fernet)
```

---

## 🛠️ Technologies Used

* Raspberry Pi
* Arduino (Tinkercad simulation)
* Python
* MQTT Protocol
* REST APIs
* MySQL (LAMP Stack)
* JSON
* Fernet Encryption

---

## 🔍 Components & Modules

### 1. Sensor Data Acquisition

* DHT11 sensor for temperature and humidity
* Light and proximity sensors for environmental monitoring
* Real-time data collection from hardware and emulator

---

### 2. IoT Communication

* MQTT protocol used for efficient, low-bandwidth data transmission
* Data sent to cloud platforms like ThingSpeak and TTN

---

### 3. Data Storage

* REST APIs used for data transfer between system components
* MySQL database used for persistent storage

---

### 4. Security

* Sensor data converted to JSON format
* Data encrypted using Fernet encryption to ensure confidentiality

---

### 5. Embedded Systems Integration

* LED dimming using potentiometer (PWM control)
* Automatic water level control system
* Servo motor control using analog input
* Temperature monitoring system with alert mechanism

---

## 📊 Example Data Format

```json
{
  "temperature": 30,
  "humidity": 65
}
```


## 📈 Applications

* Smart home automation
* Environmental monitoring
* Industrial IoT systems
* Real-time alert systems

---

## 📌 Key Learnings

* IoT system design and architecture
* Real-time data processing and communication
* Secure data handling using encryption
* Integration of hardware, software, and cloud services

---

## ⚠️ Note

This project includes both hardware-based implementations and simulation-based experiments (Tinkercad) to demonstrate IoT concepts and system behavior.

https://www.tinkercad.com/dashboard/designs/all

---
