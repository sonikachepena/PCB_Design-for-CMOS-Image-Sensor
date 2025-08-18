# PCB_Design-for-CMOS-Image-Sensor
The image sensor used in this project does not provide traditional physical pins for connecting to external controllers or FPGAs. Instead, it has bonding pads on the bottom surface. To overcome this, I designed a custom PCB to:
Mount the sensor securely.
Provide external control and communication interfaces. 
Ensure proper power delivery, clocking, and signal routing.
Key Features of the PCB 
High-Speed Differential Signals (LVDS): For reliable high-bandwidth data transfer. 
I²C Interface: For low-speed configuration and register programming. 
Power Regulation: Stable voltage supply using MIC37303 LDO regulator.
Clocking: 5 MHz crystal oscillator for precise timing. 
Signal Conditioning: Schmitt-trigger inverter and LVDS receivers for clean data handling. 
4-Layer PCB: Dedicated power and ground planes for signal integrity and reduced noise. 
🔧 Implementation Steps :
Designed schematic with power, clock, LVDS, and I²C circuitry. 
Created a 4-layer PCB layout with controlled impedance routing. 
Fabricated and assembled the PCB. 
Verified power rails, performed continuity checks, and tested differential/I²C signals. 
Successfully integrated the sensor with external controllers for data acquisition. 
📂 Repository Contents 
Schematics 
PCB Layout 
Supporting documentation and references.
