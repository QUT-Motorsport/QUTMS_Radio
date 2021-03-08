# QUTMS_Radio

## Purpose

The intent of this project is to create a robust communications link between the pits base station and one/many roving cars. Additionally the system is to provide extremely accurate RTK data.

## Project Structure

 - QUTMS-RADIO-MASTER-V00 | Overarching container for all of the projects. Open this and all other projects will open in Altium, also contains the larger mechanical assembly
 - QUTMS-RADIO-COMPUTE-V00 | The baseboard that will serve as the interface between any developed RF module and the car / base station systems
 - QUTMS-RADIO-GPS-V00 | GNSS Module
 - QUTMS-RADIO-M2M-V00 | Machine to Machine Radio module
 - QUTMS-RADIO-USB-V00 | Simple USB board to handle the issue of mounting a USB-C connector to a case
 - QUTMS-RADIO-COMPILE-V00 | Simple project to compile together all of the PCB''s into one panel
 - QUTMS-RADIO-CELL-V00 | An eventual board that will have cellular capabilities

## System configuration