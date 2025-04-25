# Final-Project

# **Micromouse Power Subsystem - EEE3088F 2025**

This repository contains all design files, reports, and documentation related to the **Micromouse Power Subsystem** for the **EEE3088F 2025** course project at the University of Cape Town.

## **Project Overview**
The **micromouse** is a **maze-solving robot**, and this project focuses on designing and manufacturing its **power subsystem**. The motherboard, processor, and sensor modules have been predefined, but the **power module** requires a custom solution. The power subsystem must meet strict requirements for **voltage regulation, motor control, power management, and efficiency** while adhering to budget constraints.

## **Repository Structure**

## **Power Subsystem Requirements**
- **Voltage Regulation:** Provide **3.3V (±5%) at 300mA max** and **5V (±5%) at 1.5A max**.
- **Motor Operation:** Support **two brushed DC motors (200mA each) and two auxiliary motors (500mA each)**.
- **Battery Management:** Include **INA219 sensor for monitoring**, ensuring **correct configuration** on the **I2C Bus**.
- **Power Control:** Implement **an ON/OFF switch** to fully disconnect battery draw (<30µA when off).
- **Battery Charging:** Support **dual charging modes** (200mA & ~600mA).
- **USB Power Input:** Extract **9V from USB-C host** for external power compatibility.
- **External Load Switching:** Provide **two high-side switched outputs (1A each)**.
- **Pin Header Connectivity:** Ensure proper interfacing with the **motherboard's 2x16 pin header**.

## **Installation & Usage**
### **KiCad PCB Design**
To view or modify the PCB layout:
1. Install [KiCad](https://kicad.org/)
2. Open `KiCad_Files/*.kicad_pcb` for PCB design.
3. Open `KiCad_Files/*.kicad_sch` for schematic review.

### **LaTeX Reports**
Reports follow **IEEE formatting** and are compiled using a LaTeX editor.
To compile:
