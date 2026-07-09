<div align="center">
  <h1>🚀 Smart Public Distribution System (PDS) 🌾</h1>
</div>

### 🛒 Revolutionizing Government Ration Distribution! 
Traditional Public Distribution Systems (PDS) suffer from manual errors, long queues, and rampant fraud. We are fixing that with IoT! 🌐
This project is a highly secure, **IoT-based automated vending machine system** designed to ensure the fair distribution of essential commodities (rice, wheat, sugar) to eligible beneficiaries. 🍚🌾

### 🔐 How It Works
We completely removed the human element from dispensing rations! 
* 🆔 **Ironclad Security:** Beneficiaries authenticate using strict **Biometric** and **RFID** verification. 
* ⚖️ **Precision Dispensing:** Embedded systems (Arduino/ESP32) precisely measure and dispense the exact grain quantity owed.
* ☁️ **Cloud Tracking:** Every transaction is beamed to the cloud for real-time inventory monitoring and automated stock alerts!

### ✨ Key Features
* 🛑 **Fraud Prevention:** Stops corruption and fake transactions in their tracks.
* 📶 **IoT Driven:** Smart inventory tracking so stock never runs out unexpectedly.
* ⚙️ **Automated Vending:** Fast, seamless, and completely contactless dispensing!

---

### 📖 Deep Dive Details

In this repository, we will be exploring the complete architecture and intricate workings of our Smart PDS! 🚀 

---

## 🍚 Smart Public Distribution System (PDS) – IoT Based Ration Monitoring

## 🔍 Overview

The **Smart Public Distribution System (PDS)** is an IoT-based solution designed to improve transparency, prevent ration fraud, and automate distribution in government ration shops.
The system monitors **grain quantity, user authentication, and transaction records** in real time, reducing manual errors and corruption.

This project focuses on ensuring **fair distribution of essential commodities** such as rice, wheat, and sugar to eligible beneficiaries.

---

## Problem Statement

Traditional PDS systems suffer from:

* Ration theft and black marketing
* Manual record manipulation
* Incorrect quantity distribution
* Lack of transparency
* No real-time monitoring

This system solves these issues comprehensively using **advanced automation, highly secure biometrics, and robust IoT tracking**.

---

## ✨ Features

* Automated ration distribution
* Real-time weight monitoring using load sensor
* User authentication (RFID / biometric / OTP depending on your build)
* Live transaction logging
* Cloud / server data monitoring
* Prevents over-dispensing and fraud
* LCD/OLED display for user feedback
* Admin monitoring capability

---

## 🏗️ System Architecture

```
User Authentication → Microcontroller → Load Sensor → Controlled Dispensing
                            ↓
                      Cloud / Database
                            ↓
                      Admin Monitoring
```
<img width="817" height="518" alt="image" src="https://github.com/user-attachments/assets/299d0c5f-8a48-45e1-a5ed-993166cf5c8b" />


---

## 🛠️ Technologies Used

### ⚙️ Hardware

* ESP32 / Arduino (based on your build)
* Load Cell + HX711 amplifier
* RFID / Keypad / Biometric (whichever you used)
* Servo / Motor for grain dispensing
* LCD / OLED display
* Power supply

### 💻 Software

* Embedded C / Arduino IDE
* IoT Platform (Blynk / Firebase / ThingSpeak / Web Server — use your actual one)
* Python / Web Dashboard (if used)
* Serial Communication

---

## 🚀 Working Principle

1. User authenticates using RFID / entered ID.
2. System verifies eligibility from stored database.
3. Load cell measures container weight.
4. Required ration quantity is dispensed automatically.
5. Real-time weight ensures accurate distribution.
6. Transaction data is recorded and sent to cloud/server.
7. Admin can monitor distribution remotely.

---

## 📥 Installation

### 1️⃣ Clone Repository

```bash
git clone https://github.com/Ashwin_Suresh/smart-pds.git
cd smart-pds
```

### 2️⃣ Upload Firmware

* Open code in **Arduino IDE**
* Select board (ESP32 / Arduino)
* Install required libraries:

  * HX711
  * WiFi (for ESP32)
  * IoT platform library (Blynk / Firebase etc.)
* Upload code to microcontroller

---

## ⚙️ Configuration

Update these in the code:

```cpp
WIFI_SSID = "your_wifi"
WIFI_PASS = "your_password"

USER_ID = "registered_user"
RATION_LIMIT = 5   // kg example
```

---

## 📂 Project Structure

```
├── firmware/
├── circuit_diagram/
├── images/
├── dashboard/
├── README.md
```

---

## 🎯 Use Cases

* Government ration shops
* Smart inventory distribution
* Anti-fraud public systems
* Rural automation
* Transparent subsidy distribution

---

## 🏆 Advantages

* Eliminates manual corruption
* Accurate quantity control
* Real-time monitoring
* Digital record keeping
* Scalable across multiple ration shops

---

## 🔮 Future Improvements

* Aadhaar / biometric authentication
* SMS alert to user after transaction
* Mobile app for monitoring
* AI-based fraud detection
* Stock prediction system
* Solar-powered unit for rural areas

---

## ✍️ Authors

**Ashwin Suresh** & **Neha**

Electronics and Communication Engineering

---

## 📜 License

For academic and research use.

---

---

<div align="center">
  <h2><strong>👨‍💻 Connect with Me</strong></h2>
  <a href="https://github.com/Ashwin-Sahyadri-ECE022"><img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white" /></a>
  <a href="https://www.linkedin.com/in/ashwin-suresh-aa2573268"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" /></a>
  <a href="mailto:ashwinsuresh1122@gmail.com"><img src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white" /></a>
</div>
