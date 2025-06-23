# Arduino Nano Design using Altium

This repository contains the schematic and PCB design files for the Arduino Nano, created using Altium Designer. The project includes both the hardware design and the necessary components for building the Arduino Nano from scratch.

### 📽️ Project Demo 
click here 👇

[![Watch on YouTube](https://img.youtube.com/vi/eV60IgspMpo/hqdefault.jpg)](https://www.youtube.com/watch?v=eV60IgspMpo)

## Project Overview

The goal of this project is to design a custom Arduino Nano board using Altium Designer. It covers the following aspects:

- **Schematic Design:** The complete schematic of the Arduino Nano, including the microcontroller, power supply, and all necessary components.
- **PCB Layout:** A well-optimized PCB layout for the Arduino Nano that follows good design practices.
- **Bill of Materials (BOM):** A list of all components used in the design, with part numbers, values, and supplier information.

## Features

- **Microcontroller:** ATmega328P, same as the original Arduino Nano.
- **USB Communication:** CH340G for USB-to-Serial conversion.
- **Power Supply:** Supports both USB power and external power supply.
- **I/O Pins:** All Arduino Nano pins are available, including analog inputs, digital I/O, and PWM pins.

## Folder Structure

The repository is structured as follows:

```plaintext
├── Schematic/
│   ├── arduino_nano.schdoc  # Schematic document
│   ├── components.lib       # Custom components library
│   └── ...                  # Other schematic-related files
├── PCB/
│   ├── arduino_nano.pcbdoc  # PCB layout document
│   ├── gerber_files/        # Generated Gerber files for manufacturing
│   └── ...                  # Other PCB-related files
├── BOM/
│   ├── bill_of_materials.xlsx  # Complete BOM for the project
└── README.md                # Project documentation
