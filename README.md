# Smart Energy Meter (GSM 4G Based)

⚡ A low-cost smart energy meter that measures household electricity consumption and transmits data via **GSM 4G module** for real-time remote monitoring.

---

##  Overview
This project implements a **smart energy meter** using:
- Current/voltage sensors (for power & kWh calculation)
- A microcontroller (Arduino/ESP32)
- A **GSM 4G module** for reliable communication in Pakistan

The system records power usage and sends data either through **SMS alerts** or **HTTP requests** to a remote server. It solves the limitations of conventional energy meters by enabling **real-time monitoring**.

---

##  Important Note (Pakistan Users)
📡 Traditional GSM modules (SIM800L / SIM900) rely on **2G/3G networks**, which are **no longer supported in Pakistan**.  
> That’s why this project uses **4G LTE modules** (e.g., SIM7600, A7670, EC200U), ensuring stable connectivity.

---

##  Hardware Components
- Microcontroller: Arduino Uno / ESP32  
- Current Sensor: SCT-013 / ACS712  
- GSM Module: **SIM7600 / A7670 / EC200U (4G LTE)**  
- RTC (optional): DS3231  
- SD card module (optional, for local data logging)  
- Regulated power supply (5V / 3.3V depending on components)

---

##  Software
- Developed in Arduino IDE or PlatformIO  
- Uses essential libraries: SoftwareSerial, HTTPClient, etc.  
- Maintained via GitHub for version control and transparency

---

##  Features
- Real-time power consumption monitoring (kWh)  
- SMS alerts on pre-defined thresholds  
- HTTP POST for IoT server integration  
- Calibration using standard electrical loads  
- Includes full thesis and documentation

---

##  Project Structure
---

##  Thesis & Materials
All project materials—including your thesis, code, diagrams, testing logs, and more—are available in one place. Download them from the following link:

[Download Full Project Materials](https://drive.google.com/file/d/1Wwutq1DLHnxlb_M8NCObm5ZfGK2llNwJ/view?usp=drivesdk)

---

##  Future Enhancements
- Dashboard integration using cloud services like ThingSpeak or Firebase  
- Prepaid energy meter feature  
- Companion mobile app for real-time monitoring

---

##  Safety Warning
Handling **AC mains voltage is dangerous**.  
Always use proper isolation, protective equipment, and follow safety guidelines. If uncertain, work with low-voltage test setups or seek professional help.

---

##  License
This project is distributed under the **MIT License**—feel free to use, modify, and share.
