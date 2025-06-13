# IoT Biometric Fingerprint Attendance System

This project implements a smart attendance system using a fingerprint sensor and ESP8266 (NodeMCU). It enables contactless, accurate, and automated check-in/check-out logging for students, with real-time feedback and data storage in a Google Sheet.

## 🔧 Components Used
- ESP8266 NodeMCU
- R305 Fingerprint Sensor
- 0.96″ OLED Display (I2C)
- Breadboard & Jumper Wires
- Internet Connectivity (Wi-Fi)

## 📋 Features
- Fingerprint-based student authentication
- Logs both check-in and check-out times
- Real-time feedback on OLED display (e.g., "Welcome" / "Goodbye")
- Attendance data automatically saved in Google Sheet
- Easy fingerprint enrollment and deletion
- Useful for classrooms and small institutes

## 🛠️ Technologies
- Arduino IDE
- Google Apps Script (for Sheet integration)
- Blynk (optional for mobile alerting)
- I2C communication for OLED

## 📂 How It Works
1. Enroll each student's fingerprint.
2. When a fingerprint is scanned:
   - If it's the first scan of the day → logs check-in.
   - If it's the second scan → logs check-out.
3. Sends attendance data (Name, Date, Time) to a Google Sheet over Wi-Fi.
4. Displays real-time messages on OLED.

## 🚀 Getting Started
1. Clone the repository
2. Open the `.ino` file in Arduino IDE
3. I
