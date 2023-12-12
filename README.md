# MatLab_Demo_Files

This repository contains MATLAB scripts for controlling and monitoring Arroyo Instruments' Laser and TEC devices. This is here to help you get started with your Arroyo Instruments device in MATLAB. Feel free to use and modify these scripts as you see fit. There are two versions of each script: a broader compatibility version and a live version. The broader compatibility version should work with any modern version of MATLAB. The live version is a MATLAB Live Script, which is only viewable and editable in MATLAb. The live version is more user-friendly and has section breaks for incrementally running the script.

## Directory Structure

- `MatLab Files/`: Contains all of the MATLAB scripts
    - `Laser Utility/`: Contains the Laser Utility scripts
    - `Tec Utility/`: Contains the TEC Utility scripts

## Laser Utility

The Laser Utility scripts are located in the `MatLab Files/Laser Utility/` directory. 

- `Arroyo_Instruments_Laser_Utility.m`: Broader compatibility version
- `Arroyo_Instruments_Laser_Utility_Live.mlx`: Live version of the Laser Utility

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


## Usage

To use these scripts, you need to ...


## Requirements

- These scripts should work with any modern version of MATLAB.
These scripts require that your PC has USB access to one of Arroyo Instruments' Laser or TEC devices.

## Troubleshooting

- If you are having trouble connecting to your device, make sure that you have the correct COM port selected in the script.

- If you are having trouble connecting and you are using a USB hub, try connecting directly to your PC.

- If you are having trouble connecting and you are using a USB 3.0 port, try connecting to a USB 2.0 port.