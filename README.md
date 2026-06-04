Amplifier-Design-in-LTspice
Analog common source amplifier design and power optimization using simulation tools such as Ngspice and LTspice.


Current Mirror Biased Common Source Amplifier

Objective:Design and analyze a current mirror biased common source amplifier in 180nm CMOS.

Tools Used:
- LTspice
- ngspice
- Python
- Excel

Key Results:
 
- Designed and verified a current mirror biased common source amplifier using TSMC 180 nm CMOS models.
- Performed power optimization by progressively scaling bias current while maintaining transistor operating constraints and process limitations such as minimum achievable device width.
- Demonstrated that amplifier gain remains nearly constant from ID to ID/64 while reducing power consumption by approximately 64×.
- Investigated the transition from strong inversion to weak inversion using the gm/ID methodology.
- Observed gain increase in weak inversion due to improved transconductance efficiency (gm/ID).
- Verified subthreshold conduction for VGS < VTH and studied exponential current behavior in the weak inversion region.
- Analyzed the effects of channel length modulation, output resistance (ro), and transconductance (gm) on amplifier gain.


Files:

- LTspice schematic
- ngspice netlists
- Experimental data
- Plots
