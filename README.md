# ZTAT Bandgap Reference (UMC 180nm)

## 📌 Project Overview
**Analog Circuit Design Project**
This project focuses on the design and simulation of a CMOS ZTAT (Zero Temperature Coefficient) Bandgap Reference circuit. The goal was to generate a temperature-independent reference current suitable for biasing analog blocks in mixed-signal systems.

* **Technology:** UMC 180nm CMOS
* **Tool:** Cadence Virtuoso
* **Target Output:** 5 µA Constant Current

## 📊 Performance Metrics
| Parameter | Value | Unit |
| :--- | :--- | :--- |
| **Reference Current** | 5.0 | µA |
| **Temperature Coefficient** | 36 | ppm/°C |
| **Temp Range** | -40 to 120 | °C |
| **Supply Voltage** | 1.8 | V |

## 📷 Simulation Results

### 1. Temperature Sweep (I_ref vs Temp)
The plot below demonstrates the stability of the reference current across the industrial temperature range (-40°C to 120°C).
![Temp Sweep Plot](curr_result.bmp)

### 2. Circuit Schematic
Top-level schematic of the Bandgap core and startup circuit.
![Schematic](BGR.jpg)

---
*Note: This repository serves as a design portfolio. Foundry proprietary models are not included.*
