![Microchip logo](images/microchip.png)
# Op-amp Mindi simulation for PIC16F17146 product family

**Note : Currently this repository contains mindi model of PIC18-Q41 family's OPAMP module. Mindi model of PIC16F17146 family's OPAMP module will be available soon.**

This guide will get you up and running with simulating the analog OPAMP module in PIC16F17146 family devices using the Mindi simulation tool. For more information about getting started with and using the MPLAB Mindi Analog Simulator please refer to the following resources:

- [Using the MPLAB Mindi Analog Simulator with the 8-Bit Operational Amplifier Module Technical Brief](https://www.microchip.com/DS90003293)
- [Microchip Developer - Introduction to MPLAB Mindi Analog Simulator](https://www.microchipdeveloper.com/mindi:mindi-analog-simulator-introduction)
- [Getting Started with the MPLAB Mindi Analog Simulator Document](https://www.microchip.com/DS50002564)

## Configuration: Connected Directly to Pins
This configuration connects the bare op-amp directly to the pins, allowing any standard op-amp configuration to be achieved by connecting the appropriate external components

![Op-Amp](images/configuration.png)

### Mindi Simulation
![Mindi](images/mplab-mindi-analog-simulator.png)

Download and open the **Mindi schematic [here](https://www.github.com/microchip-pic-avr-examples/pic16f17146-opamp-mindi-direct-connection/releases/latest)**. Press the _play_ button to simulate with an example stimulus source. Note that the un-connected op-amp example is provided without any standard external circuitry.

### Don't have Mindi?
You can download and install [Mindi simulation tool](https://www.microchip.com/mplab/mplab-mindi), or use another SPICE simulator of your own preference. For use with different simulators, a plain spice model can be found in "Opamp_PIC18_Q41.txt" to replace the mindi-optimized "Opamp_PIC18_Q41.lb"
