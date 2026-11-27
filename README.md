# Ex No: 01 - Design a CMOS Inverter and Analyze Transient Response using Synopsis EDA Tools

## Aim
To design and simulate a CMOS inverter circuit using Synopsys EDA tools, analyze its electrical characteristics, and study its transient response

## Tools Required

### Synopsys EDA Suite
- Synopsys Custom Compiler – For CMOS inverter schematic design.
- Synopsys PrimeWave Design Environment – For simulation setup and waveform analysis.
- Synopsys PrimeSim HSPICE / PrimeSim – For circuit simulation and analysis.

### Process Design Kit (PDK)
- CMOS technology library (e.g., 180nm, 45nm node)  

### Computer System
- Minimum **4GB RAM** and a **multi-core processor**
- Linux-based operating system compatible with the installed Synopsys tools.

## Procedure:
### 1. Launch Synopsys Custom Compiler Environment :
     Open Synopsys Custom Compiler and set up the working library.
     Create a new design library and associate it with the appropriate CMOS technology PDK.
     Create a new schematic cell view for the CMOS inverter design.
### 2. Schematic Design:
    Select the NMOS and PMOS transistors from the technology library.
    Connect the source terminal of the NMOS transistor to GND and its drain terminal to the output node.
    Connect the source terminal of the PMOS transistor to VDD and its drain terminal to the same output node as the NMOS transistor.
    Connect the gate terminals of both transistors together to form the input node (VIN).
    Connect the NMOS bulk terminal to GND and the PMOS bulk terminal to VDD.
    Connect a DC voltage source (VDC) to provide the supply voltage (VDD).
    Connect a pulse voltage source (VPULSE) to provide the input signal.
### 3. Simulation:
    Check the schematic for errors and verify the electrical connections.
    Create a testbench for the CMOS inverter.
    Launch Synopsys PrimeWave Design Environment.
    Select the appropriate simulator, such as PrimeSim HSPICE.
    Configure transient analysis to study the time-domain response.
    Set the simulation parameters, including supply voltage, input pulse period, rise time, fall time, and simulation stop time.
    Run the simulation and verify the simulation results.
### 4. Waveform Analysis:
    Observe the input and output voltage waveforms using the PrimeWave waveform viewer.
    Verify the inverter operation by comparing the input and output voltage levels.

## Circuit Diagram:
#### 1. CMOS Inverter:

![image](https://github.com/user-attachments/assets/e3e06487-52b2-4b56-9dcd-03c5c9394a4c)

#### 2. Schematic of CMOS Inverter:

<img width="1920" height="1080" alt="Screenshot 2026-11-26 135024" src="https://github.com/user-attachments/assets/abfeee34-b6e0-469b-bae8-3171d53360d3" />



#### 3. Transient Response Setup:


<img width="1920" height="1080" alt="Screenshot 2026-11-27 123459" src="https://github.com/user-attachments/assets/046d037e-b9a9-4ad7-a3b0-39cae5ea5cc4" />


## Output
#### 1.Transient Analysis  Output

<img width="1920" height="1080" alt="Screenshot 2026-11-27 123948" src="https://github.com/user-attachments/assets/3c5c00f2-976f-418a-9a51-6abd78a5e5a9" />


## Results:

1.	Successfully designed the CMOS inverter schematic using Cadence EDA tools.
2.	The simulation results demonstrated the correct logic operation of the inverter, where the output voltage switches between high (Vdd) and low (0V) levels, corresponding to the input voltage transitions.










