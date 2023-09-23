# CMOS_NOR_GATE_cadence_virtuoso
The CMOS Nand Gate Schematic creation , Simulation and Layout Creation using Cadence Virtuoso.
2-input NOR gate using 2x1 mux: Figure 1 below shows the truth table of a 2-input NOR gate. If we observe carefully, OUT equal B' when A is '0'. Similarly, OUT equals '0' when A is '1'. So, we can make a 2-input mux act like a 2-input NOR gate, if we connect SEL of mux to A, D0 to B' and D1 to '0'.
# Tools Used
+ Schematic : Cadence Virtuoso - Schematic XL
+ Simulation :Cadence Virtuoso - ADE L
+ Layout : Cadence Virtuoso - Layout XL
+ Technology : gpdk90
  
Verification tool :Assura All DRC's were cleared and the design met LVS.
# NOR Schematic 
![image](https://github.com/VishwajithVPai/CMOS_NOR_GATE_cadence_virtuoso/assets/130815256/cecb3104-d12d-4ac0-93a4-9812599b339d)
# NOR Simulation
![image](https://github.com/VishwajithVPai/CMOS_NOR_GATE_cadence_virtuoso/assets/130815256/fe8fe5e9-8e0e-4507-a638-4ee85da81795)
# Transient Analysis
![image](https://github.com/VishwajithVPai/CMOS_NOR_GATE_cadence_virtuoso/assets/130815256/6c706ee5-b8f8-4ecf-bf9b-1fca5f5750f3)
# NOR Layout
![image](https://github.com/VishwajithVPai/CMOS_NOR_GATE_cadence_virtuoso/assets/130815256/fe4fc175-fd05-471c-bd47-d1cde968553a)
# Result
![image](https://github.com/VishwajithVPai/CMOS_NOR_GATE_cadence_virtuoso/assets/130815256/0722a847-eef1-4e92-8920-32ab0d2235d1)
![image](https://github.com/VishwajithVPai/CMOS_NOR_GATE_cadence_virtuoso/assets/130815256/0fec8767-6400-45b2-9fe8-5c7332a26c79)
![image](https://github.com/VishwajithVPai/CMOS_NOR_GATE_cadence_virtuoso/assets/130815256/0d85732a-ffe5-47f7-ba0d-acb714f2d829)
# Parasitic Extraction
![image](https://github.com/VishwajithVPai/CMOS_NOR_GATE_cadence_virtuoso/assets/130815256/5ee2e714-c101-4c27-8b1f-79eef5785208)









