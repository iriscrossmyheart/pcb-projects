# 🧠 PCB Projects

This repository contains a collection of custom-designed PCBs for various electronics projects. All boards are created using EasyEDA and tested for functionality in real-world applications.

How to Make a Circuit Board: https://www.youtube.com/watch?v=la5BafeXsUI
Order Circuit Boards: https://jlcpcb.com/

---

## 📦 Project List

### 555 Timer Flashing LED circuit **Description:** 
In this video Chris creates a schematic symbol for the 7555 timer. This will allow us to connect other symbols to the pins that represent the physical pins. 

Video: https://www.youtube.com/watch?v=LaUd8WfFooU
Article: https://contextualelectronics.com/topic/creating-schematic-symbols-gtb-5-0/

### 🔌 Power Supply Module
**Description:** A compact LM7805-based 5V regulated power supply board.
- Input: 7–12V DC
- Output: 5V DC regulated
- Includes power LED, screw terminals

📁 Folder: `power-supply/`

---

### 🎙️ Audio Amplifier Board
**Description:** Simple audio amplifier using LM386 for small speaker output.
- Gain configurable with capacitor
- Compact layout
- Breadboard compatible

📁 Folder: `audio-amplifier/`

---

### 🌡️ Sensor Breakout Board
**Description:** Custom breakout for DHT11/DHT22 sensors with pull-up resistors and headers.
- Clean mounting on perfboard or enclosure
- Bypass capacitor included

📁 Folder: `sensor-breakout/`

---

### 📍 GSM Antenna Board (Optional Project)
**Description:** PCB for SIM800L module with external antenna connector, filtering caps, and UART pins.

📁 Folder: `gsm-antenna/`

---

### Temperature + Pressure Sensor
**Description:** PCB Design using a BMP390 module.

## 📂 Folder Structure

Each folder contains:
- `schematic.json` or `.schdoc`: EasyEDA/KiCad schematic in schematics folder
- Rendered board layout (top and bottom) screenshots in layout folder
- Gerber file in manufacturing folder
- `README.md`

---

## 🛠 Tools Used
- [EasyEDA](https://easyeda.com)
- JLCPCB for manufacturing
- Multimeter, logic analyzer, soldering tools

---

## 📫 Contact

- GitHub: [@iriscrossmyheart](https://github.com/iriscrossmyheart)
