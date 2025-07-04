# ⚡ IoT-Based Power Theft Detector

A real-time embedded IoT system to detect and report unauthorized electricity usage using Arduino and ESP8266.

## 📌 Project Overview

This mini project detects illegal power consumption using ZMCT103C current sensors and an Arduino Uno. It displays real-time current data on an I2C LCD and triggers an alert when an illegal load exceeds a threshold. An ESP8266 (NodeMCU) module sends theft alerts via email using Gmail SMTP. The system runs off-grid using Li-ion and lead-acid batteries with an inverter.

---

## 🧰 Components Used

- Arduino Uno  
- ZMCT103C Current Sensors ×2  
- ESP8266 NodeMCU  
- 16x2 LCD with I2C Module  
- Logic Level Converter  
- 10W LED Bulbs (legal & illegal loads)  
- Lead-Acid Battery (12V)  
- 12V–220V Inverter  
- 18650 Li-ion Batteries ×2

---

## ⚙️ Features

- Real-time current monitoring of both legal and illegal loads  
- Detects theft when illegal load exceeds 0.1A  
- LCD displays “THEFT DETECTED!” upon detection  
- Sends theft alert emails via Gmail SMTP using ESP8266  
- Fully portable/off-grid with battery power  
- Detection & alert within 5 seconds

---

## 📬 Output Example

### Normal Load (Legal):
A0: 0.045A
A1: 0.000A


### Theft Detected:
THEFT DETECTED!


**Email Sent:**
- Subject: *Power Theft Alert*
- Body: *Theft in process detected!*

---

## 🖼️ Images


## 🚀 Future Scope

- Mobile app integration for real-time alerts  
- Solar-powered version for sustainable deployment  
- Multi-load monitoring for grid-level application  
- AI-based anomaly detection

---

## 📄 Report

Read the full project report here: [`report.pdf`](./report.pdf)

---

🔧 Developed as part of the B.Tech Mini Project in Electronics & Communication Engineering (IoT Minor) at SCT College of Engineering, Kerala.
