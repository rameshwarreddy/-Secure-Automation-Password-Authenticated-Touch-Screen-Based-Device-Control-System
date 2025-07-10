# 🔐 Secure Automation: Password Authenticated Touch Screen Based Device Control System

## 📌 Project Overview

This project is a secure embedded automation system built using the **LPC2148 ARM7 microcontroller**, enabling password-authenticated control of multiple devices via a **touch screen and keypad interface**. It integrates **EEPROM for password storage**, **interrupts**, and **SPI communication**, making it a robust embedded solution for home or industrial automation.

---

## 🎯 Objective

To design a secure, password-protected device control system using a touch screen and matrix keypad interface that operates multiple devices through an LPC2148-based embedded platform.

---

## ⚙️ Features

- ✅ **Password Authentication** via 4x4 matrix keypad
- 📱 **Touch Screen Interface** for device selection
- 💡 **Control of Multiple Devices** (Device 1, Device 2)
- 🔒 **Secure Password Storage** using 25LC512 EEPROM (via SPI)
- 🔁 **Login/Logout Functionality**
- 🔔 **Interrupt Handling** for real-time inputs
- 🔌 **Relay/Device Switching Mechanism**
- 🔄 **EEPROM Read/Write Functions**
- 📤 **UART Communication** for debugging/status updates

---

## 🧰 Components Used

| Component            | Description / Function                            |
|---------------------|----------------------------------------------------|
| **LPC2148**          | ARM7 Microcontroller (Core system controller)     |
| **4x4 Matrix Keypad**| Password input interface                          |
| **Touch Screen Module** | Device selection interface                      |
| **16x2 LCD Display** | Status display (e.g., login success/failure)      |
| **25LC512 EEPROM**   | External memory for secure password storage (SPI) |
| **Device 1, 2**      | Output loads (e.g., Light, Fan)                   |
| **LSW (Limit Switch)**| Optional manual override or trigger              |
| **Buzzer/LEDs**      | Alerts & status indicators                        |
| **SPI Protocol**     | Communication with EEPROM                         |
| **UART Interface**   | Serial communication (PC Debugging/Display)       |
| **Interrupts**       | Used for events like keypad press or LSW change   |

---

## 🔄 System Workflow

1. 🔌 **System Power On**
2. ⌨️ **Password Entry** via 4x4 matrix keypad
3. ✅ On correct password → Access granted to control panel via touchscreen
4. ❌ On incorrect password → Access denied, alert triggered
5. 👆 **Touch screen** used to control Device 1, Device 2
6. 🔁 User can logout, reset, or change password (optional feature)

---

## 📁 Project Structure




