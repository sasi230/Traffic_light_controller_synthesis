#   EXP NO:6   Traffic_light_controller_Synthesis

## Aim:

Synthesize Traffic Light Controller design using Constraints and analyse area and Power reports.

## Tool Required:

Functional Simulation: Incisive Simulator (ncvlog, ncelab, ncsim)

Synthesis: Genus

### Step 1: Getting Started

Synthesis requires three files as follows,

◦ Liberty Files (.lib)

◦ Verilog/VHDL Files (.v or .vhdl or .vhd)

### Step 2 : Creating an SDC File

•	In your terminal type “gedit input_constraints.sdc” to create an SDC File if you do not have one.

### Step 3 : Performing Synthesis

The Liberty files are present in the library path,

• The Available technology nodes are 180nm ,90nm and 45nm.

• In the terminal, initialise the tools with the following commands if a new terminal is being used.

◦ csh

◦ source /cadence/install/cshrc

• The tool used for Synthesis is “Genus”. Hence, type “genus -gui” to open the tool.

• Genus Script file with .tcl file Extension commands are executed one by one to synthesize the netlist.

## Synthesis RTL Schematic :
![Screenshot 2024-11-18 104525](https://github.com/user-attachments/assets/8a1acaa1-3ecc-4da4-8bce-7e62cb3deaf6)
## Area report:
![image](https://github.com/user-attachments/assets/4ab1dad8-916f-4b3d-9184-ae765fe5f0f8)
## Power Report:
![image](https://github.com/user-attachments/assets/a0fc6ff3-5e84-4016-bf62-7bf7652b8b05)
## Result:
The generic netlist of Traffic Light Controller has been created, and area, power reports have been tabulated and generated using Genus.
