# 🚦 Smart Traffic Management System using IoT

**By Mohammed Zyaan C**  
📧 cmdzyaan27@gmail.com  
📍 Vellore, Tamil Nadu  
📱 +91 8072372498  

---

## 📋 Project Overview

This IoT-based Smart Traffic Management System is designed to detect heavy traffic congestion at intersections using **ultrasonic sensors**, and automatically send alerts via **GSM (SIM800L)** to authorities. The system helps in controlling traffic lights dynamically and notifying the control center in real-time for emergency action.

---

## 🎯 Objectives

- Detect traffic density using ultrasonic sensors
- Control traffic signals automatically based on traffic presence
- Send SMS alerts to traffic control authorities
- Provide audio warnings via buzzer
- Maintain a safe zebra crossing for pedestrians

---

## ⚙️ Technologies & Components Used

- 🔌 **Arduino UNO**
- 🌐 **GSM Module (SIM800L)**
- 🔊 **Buzzer**
- 🟢🔴🟡 **LED Traffic Lights**
- 📡 **Ultrasonic Sensors** (3 sensors for 3 lanes)
- 🔌 **Power Supply**
- 💻 **Arduino IDE**
- 🔧 **TimerOne Library** for scheduling

---

## 📄 Code Summary (Arduino)

- Monitors distance via ultrasonic sensors
- Sends SMS to predefined numbers when traffic exceeds a threshold
- Controls LED-based traffic signals dynamically
- Sounds buzzer alerts in high-traffic scenarios

### 🔐 Predefined Alert Numbers
```cpp
const String PHONE_1 = "+918072372498";
const String PHONE_2 = ""; // optional
const String PHONE_3 = ""; // optional
