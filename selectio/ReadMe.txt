Docs for reference
https://docs.amd.com/r/en-US/ug571-ultrascale-selectio/Supported-I/O-Standards-and-Terminations

I/O Tile Overview
• The HP I/O banks are designed to meet the performance requirements of high-speed memory and other chip-to-chip interfaces with voltages up to 1.8V.
• The HR I/O banks are designed to support a wider range of I/O standards with voltages up to 3.3V.
• The HD I/O banks are designed to support low-speed interfaces. 

SelectIO Interface Resources 
describes the electrical behavior of the output drivers and input receivers, and gives detailed examples of many standard interfaces available in these devices. 

1. SelectIO Interface General Guidelines
  -> I/O Bank Rules
    -> Supply Voltages for the SelectIO Pins
      -> Vcco, Vref, Vccaux, Vccaux_io, Vccint_io
    
2. DCI (Digitally Controlled Impedance)

3. SelectIO Interface Primitives
  -> IBUF, OBUF
  
4. SelectIO Interface Attributes and Constraints
  -> DCI_CASCADE Constraint

5. Supported I/O Standards and Terminations
  -> LVTTL, LVCMOS, LVDCI, HSLVDCI, HSTL ...
  -> WX: Selecting the IO Standards restrict the supportable Interface Primitives, Interface Attributes and Constraints
  -> WX: 

SelectIO Logic Resources 
describes the I/O logic resources available in these devices.

1. Component Primitives
-> Simple Registered Inputs and Outputs (FDCE, FDPE, FDRE, FDSE), IDDRE1, ODDRE1, ISERDES3, OSERDES3, IDELAYCTRL

2. Native Primitives
Are the fundamental structures from which Component primitives are created.
