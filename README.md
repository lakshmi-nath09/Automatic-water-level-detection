# 💧 Automatic Water Level Detection System (Simulation)

## 📌 Project Overview

This project demonstrates an **Automatic Water Level Detection System** using Arduino.
It reads analog values from a sensor (or simulated input) and indicates the water level using LEDs.

This project is implemented and tested in a **simulation environment** (no physical hardware used).

---

## 🎯 Objective

* To detect water levels in a tank automatically
* To indicate levels using LEDs
* To understand analog input and embedded systems

---

## ⚙️ Working Principle

* Sensor connected to **Analog Pin A0**
* Arduino reads values using `analogRead()`
* Based on value range, LEDs turn ON

### 📊 Water Level Conditions:

* **100 – 600** → Low Level → LED (Pin 2) ON
* **601 – 625** → Medium Level → LED (Pin 3) ON
* **626 – 700** → High Level → LEDs (Pin 4 & 5) ON
* **Else** → All LEDs OFF

---

## 🖼️ Project Output

![Output](<img width="369" height="676" alt="demopic" src="https://github.com/user-attachments/assets/d864730d-dc3f-4d16-8eab-7b2407066cd1" />)

---

## 🎥 Project Demo

[Click here to watch the demo video](https://docs.google.com/videos/d/1C3dW3uIq1UYu51VXg2gUJLqADjaHxUqRGvpYfTXghUU/edit?scene=id.p#scene=id.p)


---

## 🔌 Components (For Real Implementation)

* Arduino Uno
* Water Level Sensor / Probes
* LEDs (4)
* Resistors (220Ω)
* Breadboard and wires

---

## 💻 Code Explanation

* `analogRead(A0)` reads sensor values (0–1023)
* `if-else` conditions check water levels
* `digitalWrite()` controls LEDs
* Serial Monitor prints values for debugging

---

## 🧠 Concepts Used

* Analog Input
* Digital Output
* Conditional Statements
* Embedded Systems

---

## 🖥️ Simulation Note

This project is developed and tested in simulation.
The same logic can be directly implemented in real hardware.

---

## 🚀 Applications

* Water tank level monitoring
* Smart irrigation systems
* Industrial liquid monitoring
* Home automation

---

## 🔮 Future Enhancements

* Automatic motor ON/OFF using relay
* Buzzer alert system
* IoT-based monitoring (mobile app)

---

## 📁 Project Files

* `sensor_project.ino` → Arduino code
* `README.md` → Documentation
* `demopic.png` → Output image
* `waterleveldetection.mp4` → Project demo video

---

## 👩‍💻 Author

Lakshmi Devi
