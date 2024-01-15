# Open Source CDIs
These CDIs have been pulled from online and transferred to modern circuit editing software.

## Table of Contents
- [Jaguar](#jaguar)
- [Baker](#baker)
- [Rohmell](#rohmell)
- [Design Principles](#designprinciples)

## Jaguar CDI
This is one of Jaguar's older designs, photos are openly found online. Credit to him on facebook here: https://www.facebook.com/michael.forrest.7798. Design is from [here](https://www.dragonfly75.com/motorbike/CDI/CDI-layout.jpg)
![Jaguar CDI Image](https://github.com/MBI-Ignitions/MBI_Ignition_Systems/blob/main/Open%20Source%20CDIs/Jaguar/Schematic.PNG)

## Baker 
Jim Baker's design. This is his ultimate version with jumpers instead of a selector switch, and smaller 1N4007 diodes. Credit to him on facebook here: https://www.facebook.com/jim.baker.7927, he no longer builds them currently. 
One of his designs can be found online [here](https://www.blasterforum.com/media/zappy-cdi-coil-fired-adjustable-ignition.9499/full?d=1545531996)
![Baker CDI Image](https://github.com/MBI-Ignitions/MBI_Ignition_Systems/blob/main/Open%20Source%20CDIs/Baker/Schematic.PNG)

## Rohmell
Pulled from the motorized bike forum. Design can be found [here](https://www.google.com/url?sa=i&url=https%3A%2F%2Fmotoredbikes.com%2Fthreads%2Fcdi-upgrade.45720%2F&psig=AOvVaw3EV8G8pml-__hgrAlN-TIA&ust=1705089441070000&source=images&cd=vfe&opi=89978449&ved=0CBMQjRxqFwoTCIim86mP1oMDFQAAAAAdAAAAABAD)
![Rohmell CDI Image](https://github.com/MBI-Ignitions/MBI_Ignition_Systems/blob/main/Open%20Source%20CDIs/Rohmell/Schematic.PNG)

## DevPot (V1)
Our first open source development board designed in house. Uses potentiometers to control the resistance in critical areas, which allows for more adjustablility than other CDIs. Capacitance is changed by loading different capacitors into the push lock connectors.
![DevPot CDI Image](https://github.com/MBI-Ignitions/MBI_Ignition_Systems/blob/main/Open%20Source%20CDIs/DevPot/Schematic.PNG)

## DevPot V2
Identical to DevPot but with jumpers and a capacitor array to change the capacitance values.
![DevPot CDI Image](https://github.com/MBI-Ignitions/MBI_Ignition_Systems/blob/main/Open%20Source%20CDIs/DevPot_v2/Schematic.PNG)

## DevSnapLock
Our second open source development board with snap connectors for every value. This allows for the use of resistor packs instead of potentiometers, which are expensive. The capacitor bank is the same as DevPot with one connectors to load different capacitors.
![DevPot CDI Image](https://github.com/MBI-Ignitions/MBI_Ignition_Systems/blob/main/Open%20Source%20CDIs/DevSnapLock/Schematic.PNG)

## Design Principles
All of these designs follow the same principles:
- SCR to control the spark
- RC bank to control timing
- Diodes for rectification
- Resistor divider for further timing

Some designs also have themistors or thermal resistors. These are to change the timing depending the ambient temperature.
