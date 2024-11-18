# Exp-6: Traffic_light_controller_Synthesis

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

Synthesis RTL Schematic :

![WhatsApp Image 2024-11-18 at 22 41 57_7770499c](https://github.com/user-attachments/assets/9cdff5d3-7f17-4842-a227-343729d93a1a)


Area report:

![WhatsApp Image 2024-11-18 at 22 41 56_b9a989fa](https://github.com/user-attachments/assets/f2938da2-a5d6-4840-af2c-9b64d322cdc7)


Power Report:

![WhatsApp Image 2024-11-18 at 22 41 57_b24dabd7](https://github.com/user-attachments/assets/a6106d62-d701-4475-bf05-fd9a8f1aa64b)


Result:

The generic netlist of Traffic Light Controller has been created, and area, power reports have been tabulated and generated using Genus.
