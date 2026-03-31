# 🚗 Accident Alert System using MSP430

An embedded system designed to **detect road accidents automatically** and **send real-time alerts with location details** to emergency contacts using GSM communication.

---

## 📌 Overview

Road accidents often lead to delayed emergency response due to lack of timely reporting. This project solves that problem by building an **automated accident detection and alert system** using the MSP430 microcontroller.

The system detects sudden impacts using a vibration sensor and instantly sends an SMS containing **GPS coordinates** of the accident location.

---

## ⚙️ Features

* 🚨 Automatic accident detection using vibration sensor
* 📍 Real-time location tracking using GPS module
* 📩 Instant SMS alert via GSM module
* 🔋 Low power consumption (MSP430-based system)
* ⚡ Fast emergency response support
* 🧠 Fully automated system (no human intervention required)

---

## 🏗️ System Architecture

```
[Vibration Sensor] → [MSP430 Microcontroller] → [GPS Module]
                                      ↓
                                 [GSM Module]
                                      ↓
                           SMS Alert to Emergency Contact
```

---

## 🧰 Hardware Components

* MSP430G2 LaunchPad Microcontroller
* Vibration Sensor
* GPS Module (NEO-6M)
* GSM Module (SIM900)
* Breadboard & Jumper Wires
* Power Supply

---

## 💻 Software Requirements

* Energia IDE (for MSP430 programming)
* Embedded C / Arduino-style programming

---

## 🔄 Working Principle

1. System continuously monitors vibrations using the sensor
2. If a sudden impact is detected:

   * MSP430 triggers the alert process
3. GPS module fetches **latitude & longitude**
4. GSM module sends SMS with accident details
5. Emergency contacts receive real-time alert

---

## 📊 Results

* Successfully detects accident-like vibrations
* Sends SMS alerts with accurate GPS location
* Demonstrates fast and reliable emergency notification

---

## 🚀 Applications

* 🚗 Vehicle safety systems
* 🏍️ Motorcycle accident detection
* 🚑 Emergency response systems
* 🛣️ Smart transportation & IoT systems

---

## 🔮 Future Scope

* Integration with **IoT & Cloud platforms**
* AI-based accident detection (reduce false positives)
* Real-time tracking dashboard
* Camera integration for accident validation
* Enhanced GPS accuracy using multi-satellite systems

---

## 👨‍💻 Contributors

* **Anurag Sardar**
* Prajwal Malegavi
* Rishab Kar Chaudhuri

---

## 🔗 Reference

This project is inspired by:

<a href="https://circuitdigest.com/microcontroller-projects/msp430-vehicle-tracking-and-accident-detection-using-vibration-sensor" target="_blank">Complete Guide to the Project</a>

---

## 📜 License

Project developed as part of a team during undergraduate studies.
This project is for academic and educational purposes. Feel free to use and modify with proper credit.

---

## ⭐ Support

If you like this project, consider giving it a ⭐ on GitHub!

