# Multi-stage Cascode Amplifier Design

This repository contains the design, simulation, and analysis of a multi-stage cascode amplifier, cascode current mirror, and beta multiplier in both 180 nm and 22 nm technology nodes. The designs were implemented and tested using LTSpice and Magic EDA tools, focusing on the comparison between 180 nm and 22 nm technology nodes in terms of performance and simulation results.

## Project Overview

This project aims to design a multi-stage cascode amplifier along with its biasing network, including the beta multiplier and cascode current mirror. The following tools were used for schematic design and layout:
- **LTSpice** for circuit simulation.
- **Magic** for circuit layout and verification.

### Key Components:
1. **Beta Multiplier**: Provides a stable biasing current.
2. **Cascode Current Mirror**: Improves current transfer accuracy by utilizing cascoding.
3. **Cascode Amplifier**: Achieves high gain, high output impedance, and improved bandwidth.

### Technology Nodes:
- **180 nm**: Schematic and layout were designed, simulated, and verified.
- **22 nm**: Only the schematic was created to compare the effect of reducing the technology node.

### Target Specifications (180 nm Technology):
- Supply Voltage (**VDD**) = 1.8V
- Gain (**AV**) = 20 V/V
- Power Dissipation (**PD**) < 5 mW
- Load Capacitance (**CL**) = 1 pF
- Unity Gain Bandwidth (**UGB**) > 500 KHz


## How to Run

### LTSpice Simulations:
1. Open the `.asc` file in LTSpice.
2. Ensure the corresponding technology node files (`TSMC180nm.txt` or `22nm.txt`) are properly included for accurate simulation.
3. Run the simulation to analyze various parameters like gain, power dissipation, and bandwidth.

### Magic Layout:
1. Open the `.mag` file in Magic EDA tool.
2. Use the provided `.tech27.txt` technology file to visualize and verify the layout.
3. Export Spice netlists and perform layout vs. schematic (LVS) verification.

## Conclusion

The simulations and practical calculations show a strong agreement between estimated, computed, and LTSpice values. Both the 180 nm and 22 nm designs demonstrated expected performance, validating the impact of technology scaling on amplifier characteristics.

## Tools Used

- **LTSpice** for simulation of both 180 nm and 22 nm designs.
- **Magic** for layout design and verification in 180 nm technology.
- **PTM Models** for accurate transistor modeling in different technology nodes.

## Author

[Yash Agarwal](https://github.com/Yash070707)



