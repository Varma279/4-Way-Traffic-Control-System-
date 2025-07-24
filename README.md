# 🚦 Automatic 4-Way Traffic Control System

This project simulates a real-time **automatic traffic signal controller** using the **8051 microcontroller**, written in **Assembly Language** and tested using **Keil** and **Proteus 8**.

---

## 📁 Project Structure

- `traffic_control.asm` – Main assembly code for the traffic control logic.
- `layout_diagram.png` – Proteus design file for the circuit layout.
- `video_output.mp4` – Video demonstration showing the real-time operation of the project.
- `README.md` – Project description and documentation.

---

## 🔧 Tools Used

- **Microcontroller:** 8051 (AT89C51)
- **Programming Language:** Assembly (ASM)
- **IDE:** Keil µVision
- **Simulation Tool:** Proteus 8

---

## 🛠️ Features

- Automatically switches traffic signals in **10-second intervals**.
- Supports **4-directional traffic flow** with LED indicators (Red, Yellow, Green).
- Microcontroller-driven decision logic for real-time control.
- Efficient use of 8051 timers and I/O ports to interface with signal LEDs

---

## 🔍 How It Works

1. The ASM code initializes timers and output ports.
2. The logic sequence turns ON/OFF each direction's RED, GREEN, and YELLOW LEDs at 10-second intervals.
3. The cycle repeats indefinitely to manage traffic automatically.

---

## 🧠 Learning Outcomes

- Gained hands-on experience with **8051 programming** in assembly.
- Learned real-time simulation and debugging using **Proteus**.
- Understood how embedded systems can control urban infrastructure.

---

## 🎥 Project Output

- A video demo (`video_output.mp4`) shows the full simulation of traffic signal cycles.

---

## 📚 Future Improvements

- We can add vehicle density sensors for adaptive timing.
- Integrate pedestrian crossing signals.
- Interface with IoT for remote monitoring and control.

---

## 👤 Author

**M V V Satya Varma**  
[LinkedIn](https://www.linkedin.com/in/satya-varma-4bb310362/) 

---
