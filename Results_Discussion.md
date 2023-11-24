# Results and Discussion

The D-flip flop module generated was converted into partially adiabatic circuits by simply
converting the fundamental block i.e the ‘nand2’ into an adiabatic logic design.

In the analysis and simulation of partially adiabatic D-flip flop circuit using HSPICE simulations,
it is observed several key findings that shed light on its performance and energy efficiency. SPICE
library used in this study : TSMC 180um (tsmc018.lib)

The waveform of the d-flip flop created is given as under. This signal is observed and analysed in
the simulation tool named as `Avan-waves` :

![]()

 *The yellow signal depicts a data (Din) signal. The red signal is the clock signal with a period of 100ns and the peach waveform depicts the output (Qout) of the d-flip flop that is positive edge triggered.*
 
 
### POWER CONSUMPTION:
The partially adiabatic design demonstrated a notable reduction in average power consumption
compared to a conventional, non-adiabatic circuit. Specifically, power consumption was reduced by
approximately 40% during typical operation, validating the potential benefits of the adiabatic
approach in low-power applications.

### SPEED AND DELAY:
While the partially adiabatic circuit showed lower power consumption, it exhibited a slightly
increased propagation delay when compared to the conventional circuit. The additional delay was
primarily attributed to the energy recovery and recycling mechanisms inherent in adiabatic designs.
It is essential to consider this trade-off between power efficiency and delay when selecting the
appropriate circuit design for a specific application.

The table under incapsulates the essence of the study and showcases the power consumption by the
listed design methodologies.



In summary, the simulation results emphasize the trade-off between power consumption and
performance in flip-flop designs. While CMOS flip-flops offer high performance, they consume
more power. The ECRL and 2N-2N2P flip-flops achieve notable power savings, with the 2N-2N2P
design being the most power-efficient. The PFAL flip-flop, while efficient in some contexts,
demonstrates a higher power consumption in this particular evaluation. The choice of flip-flop design
should be guided by the specific requirements of the digital system, balancing power efficiency with
performance considerations
