# Ex No: 01 - Design & Implementation of CMOS Inverter Design Using Cadence EDA Tools

## Aim
The aim is to create and simulate a CMOS inverter circuit with Cadence EDA tools, assess its key electrical properties, and explore foundational CMOS principles, including the design workflow and simulation approaches.

## Tools Required

### Cadence EDA Suite
- **Virtuoso Schematic Editor** (for circuit design)  
- **Spectre Simulator** (for circuit simulation)  

### Process Design Kit (PDK)
- CMOS technology library (e.g., 180nm, 45nm node)  

### Computer System
- Minimum **4GB RAM** and a **multi-core processor**

## Procedure:
### 1. Launch Cadence Virtuoso Environment:
     Open the Cadence Virtuoso tool and set up the working library.
     Create a new schematic cell view for the CMOS Inverter design.
### 2. Schematic Design:
    Select the NMOS and PMOS transistors from the library.
    Connect the NMOS transistor with its source terminal to GND and its drain terminal to the output node.
    Connect the PMOS transistor with its source terminal to VDD and its drain terminal to the same output node as NMOS.
    Join the gate terminals of both transistors to form the input node.
    Connect input voltage sources Vdc and Vpulse
### 3. Simulation:
    Check the Design for Errors and proceed for Simulation
    Launch the Analog Design Environment (ADE).
    Configure transient analysis for time-domain response.
    Set the simulation parameters such as voltage sweep range and step size.
    Use Spectre simulator to perform transient and DC analyses.
### 4. Waveform Analysis:
    Observe the output voltage waveform concerning the input voltage.

## Circuit Diagram:
#### 1. CMOS Inverter:

<img width="1920" height="1200" alt="Screenshot 2026-01-29 092504" src="https://github.com/user-attachments/assets/7af1ede3-67dc-4d05-96b9-67b70722436e" />


#### 2. Schematic of CMOS Inverter:

<img width="867" height="634" alt="Screenshot 2026-01-29 092635" src="https://github.com/user-attachments/assets/5f9e2dab-3e08-4990-bb02-1a806a580db8" />

#### 3. Transient Response Setup:
<img width="519" height="929" alt="Screenshot 2026-01-29 092548" src="https://github.com/user-attachments/assets/ad331a3d-5a52-4839-b8fc-2d5e0dcd5d35" />

<img width="519" height="606" alt="Screenshot 2026-01-29 092616" src="https://github.com/user-attachments/assets/95efc7dd-ae7d-490c-b660-5eb8f207759c" />


## Output
#### 1.Transient Analysis Output

<img width="1920" height="1200" alt="Screenshot 2026-01-29 092051" src="https://github.com/user-attachments/assets/d5bb028f-f3bc-4792-b5da-fe0552c5949a" />


## Results:

1.	Successfully designed the CMOS inverter schematic using Cadence EDA tools.
2.	The simulation results demonstrated the correct logic operation of the inverter, where the output voltage switches between high (Vdd) and low (0V) levels, corresponding to the input voltage transitions.
3.	The Voltage Transfer Characteristic (VTC) curve was plotted, showing the relationship between input and output voltages.











