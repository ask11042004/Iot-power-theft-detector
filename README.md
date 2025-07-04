# ⚡ IoT-Based Power Theft Detector

A real-time embedded IoT system to detect and report unauthorized electricity usage using Arduino and ESP8266.

## 📌 Project Overview

This mini project detects illegal power consumption using ZMCT103C current sensors and an Arduino Uno. It displays real-time current data on an I2C LCD and triggers an alert when an illegal load exceeds a threshold. The system uses an ESP8266 (NodeMCU) to send email notifications via Gmail SMTP, enabling remote theft alerts. It's powered off-grid using 18650 Li-ion batteries and a lead-acid battery + inverter combo.

## 🧰 Components Used

- Arduino Uno  
- ZMCT103C Current Sensors (×2)  
- ESP8266 NodeMCU  
- 16x2 LCD with I2C Module  
- I2C Logic Level Converter  
- 10W LED Bulbs (Legal & Illegal Loads)  
- Lead-Acid Battery (12V)  
- 12V–220V Inverter  
- 18650 Li-ion Batteries (×2) + Holder  

## ⚙️ Features

- Real-time current monitoring
- Theft detection based on illegal current threshold
- Visual alert: **“THEFT DETECTED!”** on LCD
- Email notification via Gmail SMTP using ESP8266
- Off-grid operation via batteries and inverter
- Response time: Theft detected and notified within 5 seconds

## 📬 Output Example

- LCD Displays:
A0: 0.045A
A1: 0.045A

➡ If illegal load exceeds 0.1A:
THEFT DETECTED!


- Email Alert:
- Subject: **Power Theft Alert**
- Body: *Theft in process detected!*

## 🖼️ Images

> Upload these to a folder named `/images` in your repo

- Setup overview  
- LCD showing real-time current  
- LCD showing “THEFT DETECTED!”  
- Block diagram  
- Circuit diagram

## 🚀 Future Scope

- Mobile app integration for theft alerts
- Solar-powered version for sustainable deployment
- Support for multiple monitored loads
- Integration with AI/ML models for anomaly detection

## 📄 Report

The full project report is available in this repository: [`report.pdf`](./report.pdf)

---

🔗 **Developed as part of the mini project for B.Tech in Electronics and Communication Engineering (IoT Minor) at SCT College of Engineering, Kerala.**

