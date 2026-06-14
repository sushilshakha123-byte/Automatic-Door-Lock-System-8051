# 🔐 Automatic Door Lock System (8051 Based)

This project is an **Automatic Door Lock System** developed using the **AT89C51 microcontroller**. It includes both **simulation (Proteus)** and **hardware implementation**.

The system is based on a password-controlled security mechanism using a keypad, with output displayed on LCD and controlled through relay and buzzer.

---

## 🧠 Project Overview

The system allows secure access using a password entered via a 4x4 keypad. The microcontroller verifies the password and controls the locking mechanism accordingly.

---

## 💻 Simulation Setup (Proteus)

In simulation, the system is designed and tested using Proteus software.

### Components used in simulation:
- AT89C51 Microcontroller
- 4x4 Matrix Keypad
- 16x2 LCD Display
- Relay
- Buzzer
- Potentiometer
- Resistors
- LED
- Lamp (used as door lock indicator/output load)
- EEPROM (for memory storage/handling data)
- Power Supply
- COMPIM (used as an alternative to SIM800L module)

👉 COMPIM is used in simulation in place of SIM800L due to hardware limitations in Proteus.

---

## 🔧 Hardware Implementation

In real hardware, the system is implemented using:

- AT89C51 Microcontroller
- SIM800L GSM Module
- EEPROM
- 4x4 Matrix Keypad
- 16x2 LCD Display
- Relay
- Buzzer
- Potentiometer
- Resistors
- LED (used as door lock indicator)
- Power Supply

---

## 🔄 Difference Between Simulation & Hardware

| Feature        | Simulation | Hardware         |
|----------------|------------|------------------|
| GSM Module     | COMPIM     | SIM800L          |
| Memory         | EEPROM     | EEPROM           |
| Lock Indicator | Lamp / LED | LED              |
| Environment    | Proteus    | Physical Circuit |

---

## ⚙️ Working Principle

1. User enters password using the keypad  
2. Microcontroller verifies the input  
3. If password is correct:
   - Relay activates
   - Lock opens (Lamp in simulation / LED in hardware)
4. If password is incorrect:
   - Buzzer triggers alarm
   - Access denied message appears on LCD

---

## 📌 Features

- Password-based security system  
- LCD display for system status  
- EEPROM-based data handling  
- GSM alert system (hardware)  
- Buzzer alarm for incorrect password  
- Relay-controlled locking mechanism  

---

## 🔥 Project Demonstration

The project has been developed in multiple stages. Below are the release versions:

### 🚀 Latest Release (v1.1)
Final implementation with simulation and hardware demonstration.

👉 [View Release v1.1](https://github.com/sushilshakha123-byte/Automatic-Door-Lock-System-8051/releases/tag/v1.1)

---

### 🛠 Initial Release (v1.0)
Early prototype with basic simulation.

👉 [View Release v1.0](https://github.com/sushilshakha123-byte/Automatic-Door-Lock-System-8051/releases/tag/v1.0)

## 👨‍💻 Author

Sushil Sakhakarmi  

---

## 📌 Note

- COMPIM is used only in simulation instead of SIM800L  
- EEPROM is used in both simulation and hardware  
- Lamp is used as output load in simulation  
- LED is used as lock indicator in hardware  
- This project demonstrates both simulation and real-world embedded system design
