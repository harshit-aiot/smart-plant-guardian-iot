# 🌱 Smart Plant Guardian (IoT Based)

## 📌 Overview
Smart Plant Guardian is an intelligent IoT-based system designed to monitor plant health using real-time sensor data and automate irrigation. The system ensures optimal plant growth by analyzing environmental conditions and controlling water supply automatically.

---

## 🚀 Features
- 🌡️ Real-time temperature & humidity monitoring  
- 💧 Soil moisture detection  
- 🤖 Automatic irrigation system  
- 📡 IoT-based remote monitoring  
- ⚡ Efficient water usage  
- 🔔 Alerts for critical conditions (optional)

---

## 🛠️ Tech Stack
- **Microcontroller:** ESP8266 / ESP32  
- **Sensors:** Soil Moisture Sensor, DHT11  
- **Programming:** Arduino IDE (C++)  
- **IoT Platform:** Blynk / ThingSpeak  
- **Communication:** WiFi  

---

## ⚙️ Components Used
- ESP8266 / ESP32  
- Soil Moisture Sensor  
- DHT11 Temperature Sensor  
- Relay Module  
- Water Pump  
- Jumper Wires  
- Power Supply  

---

## 🔄 Working Principle
1. Soil moisture and temperature data are continuously collected using sensors.  
2. Data is sent to the microcontroller (ESP8266/ESP32).  
3. If soil moisture drops below a threshold:
   - Relay activates the water pump automatically.  
4. Sensor data is sent to an IoT dashboard for real-time monitoring.  
5. System maintains optimal plant conditions without manual intervention.  

---

## 📊 System Architecture
Sensors → ESP32/ESP8266 → WiFi → IoT Dashboard → User
↓
Relay → Water Pump

---

## 📸 Project Images
(Add your images here)

![Project Image](images/project1.jpg)  
![Circuit Diagram](images/circuit.png)  

---

## 📁 Folder Structure
smart-plant-guardian-iot/
│── code/
│ └── smart_plant.ino
│── images/
│ ├── project1.jpg
│ └── circuit.png
│── README.md

---

## 🔮 Future Enhancements
- 📱 Mobile App Integration  
- 🤖 AI-based plant health prediction  
- 🌍 Cloud data analytics  
- 🔔 SMS/Email alerts  

---

## 👨‍💻 Author
**Harshit Bhargava**  
IoT & Data Analytics Engineer  

---

## ⭐ Support
If you like this project, give it a ⭐ on GitHub!
