# 🤖 Arduino Dual-Mode Obstacle-Avoiding & Bluetooth Car

An advanced robotic car that switches between **manual smartphone Bluetooth control** and **autonomous obstacle avoidance** using an ultrasonic sensor and a servo motor.

---

## 🛠️ Hardware Requirements
* Arduino Uno
* L293D Motor Driver
* HC-05 or HC-06 Bluetooth Module
* HC-SR04 Ultrasonic Sensor
* SG90 Micro Servo Motor
* 2WD/4WD Chassis & Battery Pack

---

## 📌 Pinout Connections
| Arduino Pin | Connected Component |
| :--- | :--- |
| **Pin 3, 4, 5, 7** | Motor Driver IN1, IN2, IN3, IN4 |
| **Pin 9** | Servo Motor Signal (Sweeps HC-SR04) |
| **Pin 10 & 11** | Bluetooth TX & RX (SoftwareSerial) |
| **Pin A1 & A2** | Ultrasonic Sensor Trig & Echo |
