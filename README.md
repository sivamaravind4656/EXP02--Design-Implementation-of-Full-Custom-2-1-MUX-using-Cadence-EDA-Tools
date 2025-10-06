# Ex No: 02 - Design & Implementation of Full Custom 2:1 MUX using Cadence EDA Tools
# Aim
The aim is to design and simulate a full custom 2:1 multiplexer (MUX) using Cadence EDA tools, ensuring accurate logic operation through waveform analysis and verification.

# Tools Required
## Cadence EDA Suite
Virtuoso Schematic Editor (for circuit design)
Spectre Simulator (for circuit simulation)
## Process Design Kit (PDK)
CMOS technology library (e.g., 180nm, 45nm node)
## Computer System
Minimum 4GB RAM and a multi-core processor
# Procedure
## 1. Launch Cadence Virtuoso Environment
Open the Cadence Virtuoso tool and set up the working library.
Create a new schematic cell view for the 2:1 MUX design.
## 2. Schematic Design
Select NMOS and PMOS transistors from the library.
Implement the following logic equation for the 2:1 MUX output:
Y = (A · S′) + (B · S)
Connect the respective transistors to form the desired logic.
Assign input voltage sources for control signal (S) and data inputs (A and B).
## 3. Simulation
Verify the schematic design for connection errors.
Launch the Analog Design Environment (ADE).
Configure transient analysis to observe switching behavior.
Set simulation parameters such as voltage levels, sweep range, and step size.
Use Spectre simulator to perform the analysis.
## 4. Waveform Analysis
Observe the output waveform to ensure correct MUX functionality.
Confirm that the output reflects the selected input (A or B) based on the control signal (S).
# Circuit Diagram
## 1. 2:1 MUX USING CMOS
![image.](https://github.com/user-attachments/assets/2c7a00e1-1ecf-40e2-aa2a-49e2a3d0c264)


## 2. Schematic of Full Custom 2:1 MUX
<img width="1586" height="836" alt="Screenshot 2025-09-25 121258" src="https://github.com/user-attachments/assets/ddbbce95-4e1f-4520-9dba-2ca42e064d9e" />


## 3. Transient Response Setup
![image.](https://github.com/user-attachments/assets/c397e86e-785f-4db4-8340-669c504e6922)


![image.](https://github.com/user-attachments/assets/4abd8114-397c-4f1d-8c39-7961386f41cc)


# Output
## 1. Transient Analysis Output
<img width="1580" height="841" alt="Screenshot 2025-09-25 121535" src="https://github.com/user-attachments/assets/0a642317-ed37-47cd-b5fa-6e533e3a279e" />


# Results
Successfully designed the full custom 2:1 MUX schematic using Cadence EDA tools.
The simulation results verified the correct MUX functionality, where the output accurately followed the selected input based on the control signal.
The waveform analysis demonstrated proper switching behavior for different control signal states.

