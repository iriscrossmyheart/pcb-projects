# 🔊 Audio Amplifier Board (LM386)

This is a compact audio amplifier PCB based on the LM386 chip. It’s designed for driving small 8Ω speakers with minimal external components.

---

## 🧰 Features

- Amplification using LM386 IC
- Gain configurable via capacitor (default: 20x)
- Compact design for breadboards or enclosures
- Volume control (optional)
- Capacitor decoupling for noise reduction

---

## 🖼 Board Preview

![Top View](board-top.png)  
![Bottom View](board-bottom.png)

---

## 📐 Schematic

File: `schematic.json`  
(Open in [EasyEDA](https://easyeda.com/editor) for editing)

---

## 📝 Bill of Materials (BOM)

| Component    | Value       | Package     | Notes                       |
|--------------|-------------|-------------|------------------------------|
| U1           | LM386       | DIP-8       | Audio amplifier IC           |
| C1           | 10µF        | Electrolytic| Gain capacitor (optional)    |
| C2           | 100µF       | Electrolytic| Output capacitor             |
| C3           | 100nF       | Ceramic     | Input decoupling             |
| R1           | 10kΩ        | Through-hole| Input resistor (optional)    |
| SPK1         | Speaker     | Header      | Output to 8Ω speaker         |
| J1           | Audio Jack  | 3.5mm Stereo| Input source                 |

---

## 🛠 How to Use

1. Connect audio input to the 3.5mm jack or pin headers.
2. Connect speaker to output terminals.
3. Power the board with 5V–12V DC.
4. Adjust gain by changing C1 if needed.

---

## 🔧 Notes

- Default gain: 20x (no cap). Add 10µF between pins 1 and 8 for ~200x gain.
- Use a heatsink if drawing significant current at high volume.
- Ensure speaker impedance is ≥8Ω for stable operation.

---

## 🔗 Resources

- [LM386 Datasheet (TI)](https://www.ti.com/lit/ds/symlink/lm386.pdf)
- PCB design available in EasyEDA

