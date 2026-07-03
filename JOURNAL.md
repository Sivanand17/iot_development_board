# Day 1 - Started Schematic Design

**Date:** 2 July 2026

Today I started working on the schematic of my ESP32-C3 IoT development board in KiCad 9.

Completed:
- USB Type-C connector 
- Li-Po battery charging circuit
- 3.3V LDO regulator
- Battery connector
- Power LED
- Created the ESP32-C3 hierarchical sheet

I spent some time understanding how the battery charging IC works and how the power section is connected. I also learned more about USB-C power input and voltage regulation.

**Next:** Complete the ESP32-C3 circuit and connect the remaining peripherals.
To see the developments in day 1, check out the images folder.

# Day 2 - Completed Major Functional Blocks

**Date:** 4 July 2026

Today I made good progress on the schematic by completing most of the remaining functional blocks of the ESP32-C3 IoT development board.

### Completed
- ESP32-C3 main circuit
- USB to UART interface using CP2102
- External SPI flash memory
- MicroSD card interface
- BME280 sensor circuit
- Photo sensor circuit
- Microphone amplifier circuit
- Reset and Boot button circuit
- OLED (I2C) connector
- GPIO breakout header
- Test points for debugging

I also organized the design into hierarchical sheets to keep the schematic cleaner and easier to navigate.

### Challenges

I spent some time fixing hierarchical sheet connections, assigning footprints, and resolving ERC issues caused by duplicate component references.
To see the developments in day 2, check out the images folder.


### Next

- Finish ERC with no errors
- Assign footprints to all components
- Review the complete schematic
- Start PCB layout
