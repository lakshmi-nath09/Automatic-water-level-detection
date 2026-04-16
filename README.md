# 💧 Automatic Water Level Detection System (Simulation)

## 📌 Project Overview

This project demonstrates an **Automatic Water Level Detection System** using Arduino.
It reads analog values from a sensor (or simulated input) and indicates the water level using LEDs.

This implementation is tested in a **simulation environment**, without physical hardware.

---

## 🎯 Objective

* To detect different water levels in a tank
* To display the level using LEDs
* To understand analog input processing in Arduino

---

## ⚙️ Working Principle

* The sensor (connected to analog pin A0) gives different voltage values based on water level.
* Arduino reads this using `analogRead()`.
* Based on predefined ranges, LEDs are turned ON.

### 📊 Water Level Conditions:

* **100 – 600** → Low Level → LED on Pin 2 ON
* **601 – 625** → Medium Level → LED on Pin 3 ON
* **626 – 700** → High Level → LED on Pins 4 & 5 ON
* **Else** → All LEDs OFF

---

## 🔌 Components (For Real Implementation)

* Arduino Uno
* Water Level Sensor / Probes
* LEDs (4)
* Resistors (220Ω)
* Breadboard and wires

---

## 💻 Code Explanation

* `analogRead(A0)` reads sensor value (0–1023)
* `if-else` conditions decide which LED to turn ON
* `digitalWrite()` controls LED states
* Serial Monitor displays real-time sensor values

---

## 🧠 Concepts Used

* Analog Input
* Digital Output
* Conditional Statements
* Embedded Systems Basics

---

## 🖥️ Simulation Note

This project is implemented and tested in a simulation environment.
It can be easily extended to real hardware with the same logic.

---

## 🚀 Applications

* Water tank level monitoring
* Smart irrigation systems
* Industrial liquid level detection
* Home automation systems

---

## 🔮 Future Enhancements

* Automatic motor ON/OFF using relay
* Buzzer alert for overflow
* IoT integration (monitor via mobile app)

---

## 📁 Project Files

* `sensor_project.ino` → Arduino code
* `README.md` → Project documentation

---

## 👩‍💻 Author

Lakshmi Nath
