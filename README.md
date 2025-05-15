# Minimal Arduino-Compatible Board
A minimal-component Arduino-compatible development board designed to learn the complete schematic and PCB layout flow for embedded system applications.

---

## 🧠 Objective

To design a compact, breadboard-friendly board using minimal components for an ATmega328P microcontroller — practicing core concepts of schematic design, PCB layout, decoupling, power regulation, and DFM.

---

## 🔧 Core Components

- **MCU:** ATmega328P (with Arduino bootloader)
- **Clock:** 16 MHz crystal oscillator with load capacitors
- **Voltage Regulation:** LM7805 (5V), optional LM1117 (3.3V)
- **Other:** FTDI header, reset button, power LED

---

## ⚡ Power & Programming

- 9V battery input via DC jack
- Onboard 5V regulation
- USB programming via FTDI header
- Standard Arduino pinout

---

## 📐 Design Highlights

- 2-layer PCB
- Breadboard-compatible layout
- Decoupling capacitors for MCU and regulators
- Power supply filtering
- Reset circuit and crystal oscillator layout
- DFM checked with Sierra Circuits tool

---

## 📎 Files

- [`/GerberandODB++`](./Gerber and ODB++): Gerber files for manufacturing
- [`/Documents`](./Documents): Schematic (PDF), board layout image
- [`/BOM`](./BOM): Bill of Materials

> ⚠️ Prototype not yet fabricated. Designed in OrCAD for educational purposes under mentorship from Hasofu Academy.

---

## 👨‍🏫 Acknowledgments

This project was completed as part of guided hardware design coursework from **Hasofu Academy**, mentored by **Kirsch Mackey**.

---

## 🚫 Notes

- No personal libraries or proprietary components included.
- This project is for educational use only.

