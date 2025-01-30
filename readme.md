# ioSender for 2-Axis Plasma Cutting (Custom Fork)

## Overview
This is a custom fork of ioSender, modified to better support a CNC plasma cutting system designed as part of a capstone project for the ME 481/482 course at the University of Waterloo. These modifications tailor ioSender for 2-axis plasma cutting by adapting terminology, improving safety features, and removing unnecessary functions.

## Key Modifications
- **Terminology Changes**: Replaced references to "Spindle" with "Torch" to reflect plasma cutting terminology.
- **Safety Enhancements**: Added modifications to improve safety, including removing the "Feed Hold" button (which stops the motors but not the torch) and disabling the torch "On" radio button.
- **User Interface Simplifications**: Removed unnecessary buttons and features, such as Z-axis jogging (since our plasma cutter operates without active Z-axis movement) and probing.

## Installation
1. Clone this repository
2. Build the application following the original ioSender build instructions.

## Date
January 30, 2025
