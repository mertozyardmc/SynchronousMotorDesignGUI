# SynchronousMotorDesignGUI
MATLAB GUI for synchronous motor design calculations in EEE 3002 Electric Machines Design Experiment.
# Synchronous Motor Design GUI

This repository contains a MATLAB graphical user interface developed for the EEE 3002 Electric Machines Design Experiment.

## Project Description

The application calculates and visualizes the main design parameters of a variable-frequency controlled synchronous motor. The user can change the motor input parameters and observe the corresponding results in separate tabs.

## Input Parameters

- Line voltage VL
- Rated power P
- Power factor PF
- Frequency f
- Pole number
- Connection type
- Synchronous reactance Xs
- Minimum and maximum speed
- Leading or lagging power factor selection

## Output Results

- Frequency range
- Phase voltage
- Armature current
- Internal generated voltage EA
- Maximum power at rated speed
- Low-speed voltage, internal voltage, and synchronous reactance
- Maximum power at low speed
- Power capability versus speed

## How to Run

1. Download or clone this repository.
2. Open MATLAB.
3. Open the file `SynchronousMotorDesignGUI.m`.
4. Run the file or type the following command in MATLAB Command Window:

```matlab
SynchronousMotorDesignGUI
