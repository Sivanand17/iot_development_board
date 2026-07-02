# ESP32-C3 IoT Development Board

A 4-layer ESP32-C3 development board designed in KiCad 9 for IoT and embedded systems applications. This project integrates wireless connectivity, onboard peripherals, external storage, and power management into a compact and manufacturable PCB.

---

## Overview

This project is based on the ESP32-C3 microcontroller and is designed as a general-purpose IoT development board. It includes commonly used interfaces and components required for rapid prototyping of embedded applications while following professional PCB design practices.

The project was developed using KiCad 9 and covers the complete hardware design workflow, from schematic capture and PCB layout to design verification and manufacturing preparation.

---

## Features

- ESP32-C3 microcontroller
- 4-layer PCB
- USB Type-C interface
- Li-Po battery charging circuit
- Battery power management
- External SPI Flash memory
- MicroSD card interface
- Onboard sensors
- Status LEDs
- Reset and Boot buttons
- Power regulation circuitry

---

## Hardware Specifications

| Component | Description |
|-----------|-------------|
| MCU | ESP32-C3 |
| Wireless | Wi-Fi & Bluetooth Low Energy |
| USB | USB Type-C |
| Storage | External SPI Flash & MicroSD |
| Power | USB and Li-Po Battery |
| PCB | 4 Layers |
| Design Software | KiCad 9 |

---

## Repository Structure

```text
iot_development_board/
│
├── hardware/
│   ├── iot_board.kicad_pro
│   ├── iot_board.kicad_sch
│   ├── iot_board.kicad_pcb
│   ├── Footprints/
│   └── Symbols/
│
├── docs/
│   ├── journal.md
│   └── images/
│
├── manufacturing/
│   ├── gerbers/
│   ├── drill/
│   └── bom/
│
├── README.md
├── LICENSE
└── .gitignore
```

---

## Design Goals

The primary objectives of this project are:

- Design a complete ESP32-C3 development board
- Learn professional PCB design workflows
- Understand multi-layer PCB routing
- Implement reliable power management
- Generate manufacturing-ready design files

---

## Tools Used

- KiCad 9
- Git & GitHub
- ESP32-C3 Datasheet
- Component Datasheets

---

## Project Status

- [x] Schematic Design
- [x] PCB Layout
- [ ] Design Review
- [ ] Manufacturing Files
- [ ] PCB Fabrication
- [ ] Hardware Testing

---

## Acknowledgements

This project was created as a learning exercise based on a public KiCad 9 PCB design tutorial. The tutorial provided guidance on the overall design process and helped me understand professional PCB development workflows. All project documentation reflects my own understanding and learning throughout the design process.

---

## License

This project is licensed under the MIT License.

---

## Author

**Sivanand**

GitHub: https://github.com/Sivanand17
