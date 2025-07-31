# 🔥 Flame Sensor Alert System using Arduino

This Arduino project simulates a basic fire detection system using a flame sensor. If a flame is detected, the system triggers a **buzzer** and **LED alert**, making it useful for early fire warning applications.

---

## 🧠 Features

- Detects flame using a digital flame sensor
- Activates **buzzer** and **LED** if flame is detected
- Outputs real-time sensor status via Serial Monitor
- Simple and efficient fire alert simulation

---

## 🧰 Hardware Components (Simulated)

- Arduino UNO
- Flame sensor module (digital output)
- Buzzer
- LED
- Jumper wires

---

## 🔌 Circuit Connections

| Component      | Arduino Pin |
|----------------|-------------|
| Flame Sensor   | D2 (digital input) |
| Buzzer         | D9 (digital output) |
| LED            | D13 (built-in LED or external) |

---

## 📟 Output

- **"🔥 Flame Detected! ALERT!"** → Buzzer ON, LED ON
- **"No flame detected. All safe."** → Buzzer OFF, LED OFF

---

## 📁 File Structure


---

## ✅ How to Use

1. Upload the `.ino` file to your Arduino board.
2. Open Serial Monitor at 9600 baud rate.
3. Simulate flame detection by manually triggering the sensor or modifying input logic.
4. Observe real-time status messages and alerts.

---

## 📜 License

This project is open-source and free to use for educational and non-commercial purposes.
