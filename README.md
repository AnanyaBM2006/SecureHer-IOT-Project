<h1 align="center">🚨 IoT-Based Women’s Safety Emergency Alert System</h1>
<h3 align="center">ESP32 Wearable SOS Alert Device</h3>

<p align="center">
<img src="https://img.shields.io/badge/Platform-ESP32-blue">
<img src="https://img.shields.io/badge/Language-Arduino%20C-green">
<img src="https://img.shields.io/badge/IoT-Enabled-orange">
<img src="https://img.shields.io/badge/Cloud-Google%20Sheets-yellow">
</p>

<p align="center">
A wearable IoT safety device that allows women to trigger an emergency SOS alert instantly and log location data to the cloud.
</p>

---

# 📌 Project Overview

Women’s safety is a major concern in both urban and rural environments. In dangerous situations, victims may not have time to use a mobile phone.

This project presents a **wearable IoT emergency alert system using ESP32**. A **touch sensor acts as an SOS trigger** embedded in a bracelet or necklace. When pressed, the device:

• Displays an emergency alert on LCD
• Generates location coordinates
• Sends the data to the cloud (Google Sheets)

The prototype demonstrates a **low-cost IoT solution for quick emergency response**.

---

# 🧠 Problem Statement

During emergencies, victims may not be able to unlock a phone or dial numbers quickly. Current solutions often require multiple steps.

A **simple wearable safety device** capable of triggering alerts instantly and sharing location data is needed.

---

# 🎯 Objectives

* Design a wearable women’s safety device
* Use a touch sensor for instant SOS triggering
* Implement the system using ESP32
* Display alerts using a 16×2 LCD
* Generate simulated GPS coordinates
* Log emergency data to Google Sheets
* Demonstrate scalable IoT architecture

---

# 🏗 System Architecture

<p align="center">
</p>

```
Touch Sensor
     ↓
ESP32 Microcontroller
     ↓
Emergency Detection Logic
     ↓
16x2 LCD Display (SOS Alert)
     ↓
GPS Coordinate Generator
     ↓
Cloud Logging (Google Sheets)
```

---

# 🔧 Hardware Components

| Component           | Description           |
| ------------------- | --------------------- |
| ESP32-C6            | Main microcontroller  |
| TTP223 Touch Sensor | Emergency trigger     |
| 16×2 LCD with I2C   | Display alert message |
| Breadboard          | Circuit prototyping   |
| Jumper wires        | Connections           |

<p align="center">
</p>

---

# 💻 Software Technologies

* Arduino IDE
* Embedded C / Arduino Programming
* I2C Communication
* Random GPS Coordinate Generator
* Google Sheets Cloud Logging
* Google Apps Script API

---

# ⚙️ Working Principle

1️⃣ The ESP32 continuously monitors the **touch sensor input**.

2️⃣ When the sensor is pressed:

* SOS alert is triggered
* LCD displays emergency message

3️⃣ The system generates **simulated GPS coordinates**.

4️⃣ Coordinates are displayed in the **serial monitor**.

5️⃣ Data can be logged into **Google Sheets** for tracking.

---

# 📊 Example Output

```
SOS ACTIVATED
Sending Alert...

Latitude  : 12.973400
Longitude : 77.586700
```

---

# ☁️ Cloud Logging Example

<p align="center">

</p>

Example Google Sheets Log

| Timestamp | Device | Latitude | Longitude | Status        |
| --------- | ------ | -------- | --------- | ------------- |
| 10:32 AM  | ESP32  | 12.9734  | 77.5867   | SOS Triggered |

---

# 🚀 Future Improvements

* Real GPS module (NEO-6M)
* GSM SMS alert system
* Mobile app integration
* Live location tracking
* Emergency siren alert

---

# 📷 Prototype Idea

<p align="center">
</p>

Wearable form factor:

* Bracelet
* Necklace
* Smart pendant

---

# 👩‍💻 Author

Developed as an **IoT prototype for women's safety using ESP32**.

---

⭐ If you like this project, consider giving it a star on GitHub!
