# High-Gain Boost Converter: SiC vs. Si MOSFET Analysis
A comparative power electronics study on the design, simulation, and hardware validation of a high-efficiency DC–DC boost converter operating at high duty ratios.
## Project Overview
This project explores the performance gap between traditional Silicon (Si) and wide-bandgap Silicon Carbide (SiC) MOSFETs in high-gain applications. The system steps up a 20V DC input to an 800V DC output, targeting high-voltage DC buses for renewable energy and microgrid systems.
## Objectives
Design & Calculate: Determine optimal values for the inductor, capacitor, and duty cycle for extreme voltage gain.
Comparative Simulation: Analyze switching/conduction losses and efficiency using real-world device models in LTspice.
Hardware Validation: Build and test a physical prototype to verify simulation accuracy and device feasibility.
## Tools & Technologies
Simulation: LTspice (Detailed device modeling)
Control: Microchip PIC16F877A Microcontroller
Hardware: Si & SiC MOSFETs, Power Electronics lab testing equipment
Metrics: Output/Inductor ripple, Device Stress, and System Efficiency
## Methodology
Mathematical Design: Comprehensive calculations for duty cycle and passive components.
LTspice Modeling: Simulated the circuit using authentic Si and SiC MOSFET parameters to predict thermal and electrical behavior.
Efficiency Analysis: Evaluated switching and conduction losses specifically under high duty-cycle stress.
Prototyping: Implemented a hardware version controlled by a PIC16F877A to validate the theoretical model.
## Key Results & Comparison
The analysis revealed a significant performance leap when utilizing Silicon Carbide technology:
SiC MOSFET Efficiency: ~91%
Silicon (Si) MOSFET Efficiency: ~75%
Reduced Losses: SiC devices showed drastically lower switching losses and better thermal stability during high-frequency operation.
Voltage Gain: Successfully achieved the 20V to 800V step-up, confirming the viability of SiC for high-voltage DC buses.
## Conclusion
The project confirms that SiC MOSFETs are superior for high-frequency, high-voltage applications. While traditional Silicon components struggle with losses at high duty cycles, SiC provides the thermal and electrical efficiency required for modern renewable energy infrastructure.
