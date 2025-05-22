# 🔌 Power Supply Module (LM7805)

This is a small 5V regulated power supply board based on the LM7805 linear regulator. It converts a 7–12V DC input to a stable 5V DC output.

---

## 🧰 Features

- 5V output using LM7805 regulator
- Power LED indicator
- Optional output capacitor for stability
- Screw terminal connectors for easy wiring
- Designed for perfboard or custom enclosures

---

## 🖼 Board Preview

![Top View](board-top.png)
![Bottom View](board-bottom.png)

---

## 📐 Schematic

File: `schematic.json`  
(Designed in EasyEDA — open using [EasyEDA Editor](https://easyeda.com/editor))

---

## 📝 Bill of Materials (BOM)

| Component    | Value      | Package | Notes                 |
|--------------|------------|---------|------------------------|
| U1           | LM7805     | TO-220  | Linear voltage regulator |
| C1           | 100nF      | Ceramic | Input bypass capacitor |
| C2           | 100µF      | Electrolytic | Output filtering |
| R1           | 330Ω       | Through-hole | For power LED |
| D1           | 1N4007     | DO-41   | Reverse polarity protection |
| LED1         | Red LED    | 5mm     | Power indicator        |
| J1, J2       | Screw Terminal | 2-pin | Input/Output connections |

---

## 🛠 How to Use

1. Connect a 7–12V DC source to the input terminals.
2. Output terminals provide regulated 5V.
3. Power LED lights up when voltage is applied.

---

## 🔧 Manufacturing

You can export Gerber files from EasyEDA and send to [JLCPCB](https://jlcpcb.com) or another manufacturer.

---

## 📎 Notes

- Ensure adequate heat sinking if drawing >250mA.
- Reverse polarity protection prevents damage from incorrect input wiring.

---

