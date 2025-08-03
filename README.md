# Smart Helmet: Drunk Driving Prevention and Accident Alert System

This project aims to enhance motorcycle rider safety through a smart helmet that integrates alcohol detection, accident notification, and emergency response features using IoT technologies.

## 🚀 Features

- **Alcohol Detection**  
  Uses MQ-3 sensor to detect alcohol in the rider’s breath. If the level is too high, the bike’s ignition is blocked via a relay module.

- **Accident Detection**  
  MPU6050 (accelerometer and gyroscope) detects sudden impacts or falls. Upon detection, the system identifies it as a crash event.

- **Emergency Alert System**  
  In case of an accident, the helmet sends an SOS message with the rider’s GPS coordinates to predefined emergency contacts using Twilio.

- **Wireless Communication**  
  ESP8266 modules enable Wi-Fi communication between the helmet (transmitter) and the bike (receiver).

## 🧠 Technologies Used

- **Microcontroller**: ESP8266 / ESP32  
- **Sensors**: MQ-3 (Alcohol), MPU6050 (Motion)  
- **GPS Module**: NEO-6M  
- **Communication**: Wi-Fi (ESP8266), Twilio (SMS)  
- **Software**: Arduino IDE, Proteus/LTSpice for simulation  
- **Programming Language**: Embedded C++  

## 📁 Contents

- `smart_helmet final.pptx` – Final project presentation
- `Code/` – (You can include Arduino sketches here)
- `Docs/` – Project reports, circuit diagrams, references

## 📅 Timeline

Includes setup, development, testing, and deployment stages. (See presentation for details.)

## 📚 References

- Ramesh K., IJERT (2021) – Smart Helmet for Alcohol Detection  
- Kumar A., IJARECE (2020) – Zigbee-based Alcohol Detection  
- Gupta S., IEEE Xplore (2022) – IoT-based Smart Helmet  
- Sharma R.K., IEEE B-HTC (2020) – Smart Helmet Prototype

---

**Note**: This project was developed as part of an academic submission. Always wear helmets and never ride under the influence.
