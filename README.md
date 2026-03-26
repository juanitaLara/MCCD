# MCCD fluctuation control code

This repository contains MATLAB code used to operate the Millifluidic Continuous Culture Device (MCCD) under fluctuating nutrient conditions.

The code generates controlled temporal variation in nutrient supply by sending commands from MATLAB to an Arduino microcontroller that actuates valves and/or pumps.

## Requirements
- MATLAB R2022b
- MATLAB Support Package for Arduino Hardware
- Arduino microcontroller
- External hardware: valves, pumps, relay modules (as used in the MCCD setup)

## How to run
1. Connect the Arduino to the computer via USB.
2. Open MATLAB.
3. Ensure the Arduino support package is installed.
4. Run:
   ```matlab
   MCCD_fluctuating.mlapp
