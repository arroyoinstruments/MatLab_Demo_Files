# MatLab_Demo_Files

This repository contains MATLAB scripts for controlling and monitoring Arroyo Instruments' Laser and TEC devices.

## Directory Structure


## Laser Utility

The Laser Utility scripts are located in the `MatLab Files/Laser Utility/` directory. 

- `Arroyo_Instruments_Laser_Utility.m`: Broader compatibility version
- `Arroyo_Instruments_Tec_Utility_Live.mlx`: Live version of the TEC Utility

### Laser Utility Features

1. Simple changing of set point and turning on (current mode)
    - Change the current set point

    - Turn output on

2. Logging of data
    - Log and graph data over a user-defined amount of time

    - User-defined log interval (1 Hz by default)

    - Log all dynamic values

3. LVI curve (current ramp)
    - User selected start, stop, and step sizes

    - User selected dwell time at each point

    - Log all dynamic values

## TEC Utility

The TEC Utility scripts are located in the `MatLab Files/Tec Utility/` directory.

- `Arroyo_Instruments_Tec_Utility.m`: Broader compatibility version
- `Arroyo_Instruments_Tec_Utility_Live.mlx`: Live version of the TEC Utility

### TEC Utility Features

1. List of COM Ports

2. Simple changing of set point and turning on
    - Change the temperature
    - Turn output on

3. Logging of data
    - Log and graph data over a user-defined amount of time
    - User-defined log interval (1 Hz by default)
    - Log all dynamic values

4. Changing of set point and logging of data until stable
    - User selected tol time and tol temp

    - User-defined log interval (1 Hz by default)

    - Change set point and turn output on

    - Log all dynamic values

    - Log data until stable.

5. Temperature ramp (# points, record current and voltage once stable)
    - User selected start, stop, and step sizes

    - User selected tol time and tol temp

    - User-defined log interval (1 Hz by default)

    - Log all dynamic values

    - Log data until stable.

    - Calculate Rtec? TEC power?

## Usage

To use these scripts, you need to ...

## Requirements

- These scripts should work with any modern version of MATLAB.
These scripts require that your PC has USB access to one of Arroyo Instruments' Laser or TEC devices.
