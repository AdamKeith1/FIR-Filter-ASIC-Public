# FIR-Filter-ASIC-Public
Just contains description, actual project must be in private repo per ECE 337 NDA agreements.
- ---
### Design Process
- Tasked with creating RTL architecture for subcomponents of a controller to control timing and processes involved with applying and edge detecting filter to an image.
- Created comprehensive FSM diagram for the controller.
- ---
### System Verilog
- Implement all of the components in system verilog
    #### Components
    - controller unit
    - magnitude combinational logic (signed -> unsigned)
    - synchronizers
    - counter to flag every 1k samples
    - datapath (ALU, src regs, dest reg, etc. (given))
- ---
### Testing
- Test with exhaustive test bench
- Simulate mapped version using QuestaSim
