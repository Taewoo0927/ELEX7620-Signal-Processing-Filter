# ELEX7620-Signal-Processing-Filter

# Lab01 - Sallen-Key Active Filter
## Purpose
Design and implement a second-order low-pass Sallen-Key active filter to attenuate high-frequency noise.

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

# Lab02 - PWM DAC Filter
## Purpose
The DSP board we are using this term does not have a traditional DAC, so we need to use the PWM output to emulate a DAC. As such, the PWM output must be filtered to recover the desired signal.
For this purpose, we will build a 3rd order Butterworth lowpass filter. Taking the 2nd order filter from Lab 1, we will add a 1st order section to create a third order filter.

## Design Notes
- **Cutoff Frequency**:  
  Set to 4000 Hz based on Nyquist theorem and MSP432 ADC (12 kHz) sampling rate.
---
| Circuit Schematic | Circuit Simulation |
|-------------------|--------------------|
| <img src="/Lab 02 - PWM DAC Filter/LTSpice/Schematic & Plot/Circuit-Schematic.png" alt="Circuit Schematic" width="700" height="400"> | <img src="/Lab 02 - PWM DAC Filter/LTSpice/Schematic & Plot/Circuit-Simulation.png" alt="Circuit simulation" width="700" height="400"> |
---
| Measured Magnitude |   Measured Phase   |
|--------------------|--------------------|
| <img src="/Lab 02 - PWM DAC Filter/Matlab-live-script/Magnitude-Plot.png" alt="Measured Magnitude" width="700" height="400"> | <img src="/Lab 02 - PWM DAC Filter/Matlab-live-script/Phase-Plot.png" alt="Measured Phase" width="700" height="400"> |
