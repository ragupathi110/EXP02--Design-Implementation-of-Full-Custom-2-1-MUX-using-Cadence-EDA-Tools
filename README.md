# Ex No: 02 - Design & Implementation of Full Custom 2:1 MUX using Cadence EDA Tools
## REG NO 212222060185
## NAME : RAGUPATHI RAJ M
## Aim

The aim is to design and simulate a full custom 2:1 multiplexer (MUX) using Cadence EDA tools, ensuring accurate logic operation through waveform analysis and verification.

## Tools Required

### Cadence EDA Suite
- **Virtuoso Schematic Editor** (for circuit design)
- **Spectre Simulator** (for circuit simulation)

### Process Design Kit (PDK)
- CMOS technology library (e.g., 180nm, 45nm node)

### Computer System
- Minimum **4GB RAM** and a **multi-core processor**

## Procedure

### 1. Launch Cadence Virtuoso Environment
- Open the Cadence Virtuoso tool and set up the working library.
- Create a new schematic cell view for the 2:1 MUX design.

### 2. Schematic Design
- Select NMOS and PMOS transistors from the library.
- Implement the following logic equation for the 2:1 MUX output:  
  **Y = (A · S′) + (B · S)**
- Connect the respective transistors to form the desired logic.
- Assign input voltage sources for control signal (S) and data inputs (A and B).

### 3. Simulation
- Verify the schematic design for connection errors.
- Launch the Analog Design Environment (ADE).
- Configure transient analysis to observe switching behavior.
- Set simulation parameters such as voltage levels, sweep range, and step size.
- Use Spectre simulator to perform the analysis.

### 4. Waveform Analysis
- Observe the output waveform to ensure correct MUX functionality.
- Confirm that the output reflects the selected input (A or B) based on the control signal (S).

## Circuit Diagram

### 1. 2:1 MUX USING CMOS
![image](https://github.com/user-attachments/assets/6fe3965a-47de-47d4-9dd1-0d52054de81b)


### 2. Schematic of Full Custom 2:1 MUX
![mux 1](https://github.com/user-attachments/assets/1c529df1-0fa8-4e84-919a-79b12d8af026)

### symbol
![mux 2](https://github.com/user-attachments/assets/3751417b-8f5b-4925-9e2f-835c06de7dea)

### Schematic Diagram
![mux 3](https://github.com/user-attachments/assets/20c24cbc-1d52-4281-ab27-2bd5e639f087)


### 3. Transient Response Setup

![mux 4](https://github.com/user-attachments/assets/deecc2fe-a8e1-4df8-8e54-337a0aef0dbb)


![image](https://github.com/user-attachments/assets/92eae130-d124-4f8b-a4b5-0040f418f193)

## Output

### 1. Transient Analysis Output
*![image](https://github.com/user-attachments/assets/557307b6-a35f-4e94-90e4-59bdb361c676)*

## Results
1. Successfully designed the full custom 2:1 MUX schematic using Cadence EDA tools.
2. The simulation results verified the correct MUX functionality, where the output accurately followed the selected input based on the control signal.
3. The waveform analysis demonstrated proper switching behavior for different control signal states.
