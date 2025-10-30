# CS11 Computer Architecture Development Tool Evaluation

## Development Tools
* [MPLab X](https://www.microchip.com/en-us/tools-resources/develop/mplab-x-ide) - NetBeans-based IDE from Microchip from C/Assembly development to simulation and debug
* [SimulIDE](https://simulide.com/p/) - Full featured IDE and circuit simulation environment
* [VS Code MPLab Extensions](https://marketplace.visualstudio.com/items?itemName=Microchip.mplab-extension-pack) - VS Code Extensions from Microchip for full development including simulation and debugging
* [AVR C RPi Build](https://github.com/lkoepsel/AVR_C/blob/main/docs/RPi_build.md) - Detailed instructions as to how to build an AVR-GCC tools environment on a Raspberry Pi

## Objectives

For the above development tools, evaluate their suitability for:
1. Student use
2. Cross-platform capability
3. Code development including debug and simulation

## Microcontroller Targets

The desired targets are the [*ATtiny13A*](https://github.com/lkoepsel/ATtiny) and the [*ATmega328P*](https://github.com/lkoepsel/AVR_C).

## Tools Background

The tools must be capable of the following actions:
1. Compile C99 code
2. Assemble AVR code
3. Link both into a embedded-compatible format
4. Load executable into chip
5. Debug either on chip or via simulation
6. Provide circuit simulation capabilities (*OPTIONAL*)

## Docs

* [AVR Passing Arguments into Functions](./Docs/AVR_AppendixI.pdf) 
* [AVR Instructions Explained](./Docs/AVR2_AppendixB.pdf)
* [AVR Simulation Using SimulIDE](./Docs/AvrSimulationUsingSimulIDE.pdf)
* [AVR Assembly Programming in MPLAB X](./Docs/MPLab_asm.pdf)