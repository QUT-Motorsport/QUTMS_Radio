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

For a full system there will be a total of 4 modules, 8 PCBs in total. For both the car side and pits side there will need to be a radio communications module, and a gnss module.

Ideally at the pits there will be one or two erectable tripods. One will have to hold the GNSS antenna, and needs to be high enough 

## Ordering Instructions

Only a single PCB has to be ordered for the system. This is the RAD-COMPILE pcb, a large PCB pane, 190x220mm, that contains all the PCBs needed for one side of the system (2x COMPUTE, 1x GNSS, 1x M2M).

On PCBWay's website, these are the setting required to correctly order the PCB. DO NOT DEVIATE OR RF WILL FAIL!

PCB Specification Section

- Board Type: Panel By Customer
- X-out Allowance: (Your choice, Accepting will allow some of the PCBs per panel to fail, so those failed panels will have to be accounted for in the total quantity. Not Accepting this will mean they will make a few extra PCB's (+$30) to ensure that you will have the quantity you specify of fully working panels) No/Yes 
- Different Design in Panel: 3
- Size: (Should auto fill on PCB upload) 220 x 190mm
- Quantity: 5-10 (X-Out = True -> 5, X-Out = False -> 10) (You need 2 panels min for a full system)
- Layers: 4
- Material: FR-4
- FR4-TG: TG150-160
- Thickness: 1.6mm
- Min Track/Spacing: 6/6mil
- Min Hole Size: 0.3mm
- Solder Mask: (Would prefer Green TBH due to solder mask dam thickness, but can be any colour (JUST NOT BLACK!)) Green / Purple / Blue
- Silkscreen: White
- Edge Connector: No
- Surface Finish: (Gold is an absolute must for RF) Immersion Gold (ENIG)
- Via Process: Tenting Vias
- Finished Copper: 1oz Cu
- Inner Copper: 1oz
- Extra PCB product number: (Your Choice)
- Additional Options: N/A

SMD-Stencil

- Stencil Type: Non-Framework
- Multi-level / Step Stencil: No
- Size (mm): 370x470mm (Valid Area 190 x 290mm)
- Stencil Side: Top
- Quantity: 1
- Thickness: 0.12mm
- Existing Fiducials: None (Accounted for in PCB design)
- Electropolishing: No
- Special Request: N/A