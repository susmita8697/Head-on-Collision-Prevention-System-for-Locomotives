# Head-on-Collision-Prevention-System-for-Locomotives

> Thesis Score: 10/10 | Grade: 1.5 | Techno Main Salt Lake, India | 2023–2024

# What It Does
A hardware-based real-time safety system that automatically detects collision risk between two locomotives on the same track and triggers emergency braking — without driver intervention.

# How It Works
- **Sharp IR sensor** detects obstacles within 80 cm → triggers braking via L298N motor driver
- **Two ultrasonic sensors** (0.6 m apart) measure train speed and presence in under 100 ms
- **MPU6050 gyroscope** detects crash or derailment → sends alert via HC-05 Bluetooth to control room

# Hardware Used
Arduino Uno · Sharp IR Sensor · HC-SR04 Ultrasonic (×2) · MPU6050 IMU · HC-05 Bluetooth · L298N Motor Driver · DC Gear Motor · Li-ion Battery · LED · Buzzer

# Built With
Embedded C (Arduino IDE) · MATLAB · UART Serial Communication

# Background
Inspired by vocational training at **Indian Railways, Kharagpur** where I studied relay protection and signalling systems for electric locomotives.

---
**Susmita Samanta** 
[LinkedIn](https://www.linkedin.com/in/susmita-samanta-a2aba5208)
