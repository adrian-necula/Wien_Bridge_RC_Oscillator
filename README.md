# Wien Bridge RC Oscillator

This repository contains the complete hardware design, TINA-TI simulation, and PCB layout for a tunable Wien Bridge RC Oscillator. The project was developed for the **Fundamental Electronic Circuits 2 (CEF2)** course at ETTI, UNSTPB.

## ⚙️ Technical Specifications
The circuit generates a stable sine wave and features automatic amplitude control using a diode dipole. 
* **Tunable Frequency Range:** 9.5 kHz to 57 kHz.
* **Output Amplitude:** 0.70 V.
* **Output Load:** 19 kΩ.
* **Operating Temperature:** -40°C to 120°C.
* **Amplitude Control:** Automatic, implemented via a diode dipole network.
* **Visual Indicator:** LED power presence indicator.

## 🛠️ Tools & Technologies
* **Simulation:** TINA-TI (Transient and AC Analysis).
* **Schematic Capture:** OrCAD Capture CIS.
* **PCB Design:** OrCAD PCB Editor (Surface-Mount Technology - SMT).

## 📂 Repository Structure
The repository is organized to follow the standard hardware design flow:

* 📁 **`Schematics/`**: Contains the OrCAD source schematic (`.dsn`), the TINA-TI simulation file, and high-resolution images of the final schematic.
* 📁 **`Layout/`**: Contains the OrCAD PCB layout file (`.brd`), the generated manufacturing files (Gerbers/NC Drill), and an image of the routed PCB.
* 📁 **`Simulations/`**: Contains oscilloscope screenshots from TINA-TI verifying the sine wave generation and frequency response.
* 📁 **`Data_Sheets/`**: Official manufacturer datasheets for the critical components used in the design (e.g., op-amps, diodes).
* 🖼️ **`schema_bloc.png`**: The system-level block diagram illustrating the oscillator's functional stages.
* 📄 **`BOM_Oscilator.docx`**: The Bill of Materials detailing the selected components.
* 📄 **`Documentatie.pdf`**: The comprehensive project report, including design equations, thermal considerations, and full layout prints.
