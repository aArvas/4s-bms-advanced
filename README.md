# 🔋 4S Advanced Battery Management System

This is a fully custom-designed Battery Management System (BMS) for 4-cell Li-ion configurations.  
The system includes core protection circuits, passive balancing, and CAN communication — all implemented on a professional PCB layout and documented with Altium and Draftsman files.

---

## 🧠 Features

- 🔌 Overvoltage and undervoltage protection  
- ⚡ Overcurrent protection  
- 🔄 Passive cell balancing  
- 📡 CAN communication for integration with MCUs or PLCs  
- 📐 Designed using Altium Designer with full documentation

---

## 📁 Project Structure

Hardware/
├── BMSV2.PcbDoc → PCB layout
├── BMSV2.PrjPcb → Altium project file
├── *.SchDoc → Schematic modules (MCU, balancing, power, measurement etc.)
├── BMS_Schematic.pdf → Full schematic (combined view)
├── Draftsman.pdf → Manufacturing drawing (from Altium Draftsman)
├── SourceFiles/ → Additional resources, libraries or helper files

---

## 🧾 Documentation

- 📘 **Schematic PDF:** [`Hardware/BMS_Schematic.pdf`](./Hardware/BMS_Schematic.pdf)  
- 📐 **Manufacturing Drawing:** [`Hardware/Draftsman.pdf`](./Hardware/Draftsman.pdf)

---

## 📄 License

This project is licensed under the [MIT License](LICENSE).  
You are free to use, modify, and distribute it — including commercial use — as long as attribution is given.

---

## 📌 Notes

- Gerber files are not provided. You can generate them from the Altium source files.
- Firmware is not included yet. This repo currently contains hardware-only resources.
- Tested on bench setups. Designed for educational, prototyping, and embedded applications.

---

## 👤 Author

**Abdurahman Arvas**  
[LinkedIn](https://www.linkedin.com/in/abdurahman-arvas1665/)  
📩 [aarvas.07@gmail.com](mailto:aarvas.07@gmail.com)
