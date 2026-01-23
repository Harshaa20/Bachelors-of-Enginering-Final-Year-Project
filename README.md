Design and Analysis of Boost Converter Using SiC MOSFET at High Duty Ratio

This project focuses on the design, simulation, and hardware validation of a high-gain DC–DC boost converter operating at a very high duty ratio, with a comparative performance analysis between Silicon (Si) MOSFET and Silicon Carbide (SiC) MOSFET devices.

The converter is designed to step up a low DC input (~20 V) to a high DC output (~800 V), targeting applications such as renewable energy systems, DC microgrids, and high-voltage DC buses. Detailed design calculations for duty cycle, inductor, capacitor, and load are carried out, followed by LTspice simulations using real device models.

Key performance metrics including output voltage ripple, inductor current ripple, switching and conduction losses, device stress, and efficiency are evaluated for both Si and SiC implementations. Results clearly demonstrate that SiC MOSFETs significantly reduce losses and improve efficiency (≈91%) compared to conventional Si MOSFETs (≈75%), especially under high duty-cycle operation.

A hardware prototype controlled using a PIC16F877A microcontroller is implemented to validate simulation results, confirming the feasibility of SiC-based converters for high-voltage, high-frequency power conversion.

Tools & Technologies:

LTspice (simulation)

Si & SiC MOSFET device modeling

PIC16F877A microcontroller

Power electronics hardware testing

📄 Full technical details, calculations, waveforms, and comparison results are documented in the project report.
