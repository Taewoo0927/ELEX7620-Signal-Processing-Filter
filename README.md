# ELEX7620-Signal-Processing-Filter

# Lab01 - Sallen-Key Active Filter
## Purpose
Design and implement a second-order low-pass Sallen-Key active filter to attenuate high-frequency noise.

## Steps
1. **Simulation**:  
   - Use LTSpice to verify calculations and circuit functionality.

2. **Experimental Validation**:  
   - Build the circuit and measure performance using an oscilloscope.

3. **Data Analysis**:  
   - Analyze measured vs. ideal values in MATLAB Live Script.

## Design Notes
- **Cutoff Frequency**:  
  Set to 4000 Hz based on Nyquist theorem and MSP432 ADC (12 kHz) sampling rate.
---
| Circuit Schematic | Circuit Simulation |
|-------------------|--------------------|
| <img src="/Lab%2001%20-%20Sallen%20Key%20Active%20Filter/LTSpice/Schematic%20&%20Plot/Circuit-Schematic.png" alt="Circuit Schematic" width="700" height="400"> | <img src="/Lab%2001%20-%20Sallen%20Key%20Active%20Filter/LTSpice/Schematic%20&%20Plot/Circuit-Simulation.png" alt="Circuit simulation" width="700" height="400"> |
---
| Measured Magnitude |   Measured Phase   |
|--------------------|--------------------|
| <img src="/Lab 01 - Sallen Key Active Filter/Matlab-live-script/Magnitude-Plot.PNG" alt="Measured Magnitude" width="700" height="400"> | <img src="/Lab 01 - Sallen Key Active Filter/Matlab-live-script/Phase-Plot.PNG" alt="Measured Phase" width="700" height="400"> |