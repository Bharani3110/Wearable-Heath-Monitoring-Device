# Wearable Health Monitoring Device 🩺📟

This project presents a prototype of a **Smart Wearable Health Monitoring Device** built using Arduino components. It simulates real-time monitoring of key health parameters like heart rate, temperature, and water intake. Designed with affordability, portability, and user-friendliness in mind, this wearable device offers a foundation for next-generation health tech solutions.

---

## 👨‍💻Project Created by 

- Bharani Velan M  


### 👩‍🏫 Project Guide
- Mrs. Suganya J

---

## 🧠 Project Overview

The objective of the project is to design a wearable device that seamlessly integrates with daily life to monitor:
- 💓 Heart Rate  
- 🌡️ Body Temperature  
- 💧 Water Intake  

With added components like:
- Servo Motor (for medicine dispensing simulation)  
- LCD Display  
- LEDs & Buttons  
- Arduino Uno

This system also demonstrates how data can be simulated, displayed, and used to trigger basic health alerts in real-time.

---

## 🛠️ Technologies & Tools

- **Hardware:** Arduino Uno, LCD Display, Servo Motor, LEDs, Push Button, Breadboard  
- **Software:** Arduino IDE, Wokwi Simulator  
- **Programming Language:** C/C++ for Arduino  

---

## 🧪 Functional Features

- **Heart Rate Simulation**: Random value between 70–90 bpm shown on LCD.  
- **Temperature Simulation**: Random values between 0–15°C displayed.  
- **Water Intake Trigger**: On button press, servo simulates medicine dispense and heart rate increase.  
- **Real-Time Monitoring**: LCD displays live sensor values.  
- **User Interaction**: Push-button input triggers physical response.

---

## 🧰 System Architecture

1. **Hardware Setup**
   - Sensors and actuators wired via breadboard
   - LCD connected using LiquidCrystal library

2. **Program Logic**
   - Random data generation for simulations
   - Button debouncing for accurate readings
   - Servo angle adjustments for water intake

---

## 🧗 Challenges Faced

- Simulated sensors lack real data accuracy
- No threshold-based alerts for abnormal readings
- Local-only data storage
- Limited to temperature and heart rate

---

## 🚀 Future Enhancements

- Integrate real heart rate and temperature sensors  
- Add Bluetooth/Wi-Fi for remote data monitoring  
- Implement real-time alerts for abnormal health conditions  
- Expand to include SpO2, blood pressure, and step tracking  

---

## 📚 References

- [Arduino Official Docs](https://www.arduino.cc)  
- [Wokwi Arduino Simulator](https://www.wokwi.com/simulator)  
- Dr. Rahul K. Kher, “Wearable Health Monitoring Device”  
- Smart wearable devices in cardiovascular care (2021)  
- Wearable Digital Health Technologies (2024)

---



## 📷 Screenshots & Simulations

> Include images or simulator GIFs here (LCD output, circuit design, etc.)

---

## 📝 License

This project is open-source and free to use under the MIT License.
