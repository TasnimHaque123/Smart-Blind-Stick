# 🦯 Smart Blind Stick using Arduino & Ultrasonic Sensors

An IoT and embedded systems-based assistive technology solution designed to enhance safe navigation and independent mobility for visually impaired individuals.

---

## 📌 Project Overview

Navigating unfamiliar or complex physical environments poses significant daily challenges for visually impaired individuals. Traditional white canes provide limited physical feedback and cannot detect head-level or mid-air obstacles. 

This project presents a **Smart Blind Stick** built using an **Arduino** microcontroller and **ultrasonic distance sensors**. The system continuously scans the user's surroundings in real-time to detect physical obstacles in the path. Upon obstacle detection, it triggers immediate sensory alerts via an integrated audio buzzer and a vibration motor, allowing users to navigate safely and confidently.

---

## ✨ Key Features

* **Real-time Obstacle Detection:** Uses ultrasonic sensors to measure distances and identify nearby obstacles instantly.
* **Dual Feedback System:** Combines acoustic (buzzer) and haptic (vibration motor) feedback to ensure clear alerting even in noisy outdoor environments.
* **Low Power & Cost-Effective:** Engineered with minimal component complexity, making it an affordable assistive technology option.
* **Compact & Lightweight:** Easy to mount on any standard white cane or custom physical frame.

---

## 🛠️ Hardware Components

* **Microcontroller:** Arduino Uno / Nano
* **Sensors:** HC-SR04 Ultrasonic Distance Sensor
* **Alert Mechanisms:** Piezo Buzzer, Coin Vibration Motor
* **Power Source:** 9V Battery / Rechargeable Li-ion Battery
* **Misc:** Transistors, Resistors, Jumper Wires, and Breadboard/PCB

---

## ⚡ Working Principle

1. **Triggering Sensor:** The ultrasonic sensor emits high-frequency sound waves through its transmitter.
2. **Echo Processing:** The sound wave reflects off nearby obstacles and returns to the sensor's receiver.
3. **Distance Calculation:** The Arduino calculates time elapsed to determine exact obstacle proximity:
   $$\text{Distance} = \frac{\text{Speed of Sound} \times \text{Time Elapsed}}{2}$$
4. **Alert Trigger:** If the obstacle falls within the safety threshold (e.g., less than 50 cm), the system activates both the buzzer tone and physical vibration.

---

## 🚀 Getting Started

1. Clone this repository:
   ```bash
   git clone [https://github.com/TasnimHaque123/Smart-Blind-Stick.git](https://github.com/TasnimHaque123/Smart-Blind-Stick.git)
