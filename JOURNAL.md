Day 1

Title:

Started the power section and project structure

Content:

Today I started the schematic for my ESP32-C3 IoT development board in KiCad. I decided to begin with the power section because every other part of the board depends on having a stable power supply.

I completed the USB Type-C input, Li-Po battery charging circuit, 3.3V LDO regulator, battery connector, and a power indicator LED. While working on the charging circuit, I spent some time reading the MCP73871 datasheet because I wanted to understand what each pin was doing instead of just copying the circuit.

One thing that slowed me down was setting up some of the required symbols and footprints. I also had to double-check a few connections after comparing them with the datasheet to make sure I hadn't missed anything.

By the end of the session, the power section was complete and I was ready to start building the rest of the board.

Hours: About 2.5 hours

Day 2

Title:

Added the ESP32 core and remaining peripheral circuits

Content:

Today I focused on building the main functional blocks of the board. I completed the ESP32-C3 circuit, USB-to-UART interface using the CP2102, SPI flash memory, MicroSD card interface, sensor circuits, microphone amplifier, reset and boot buttons, OLED connector, GPIO breakout header, and test points.

To keep the project organized, I separated different parts of the design into hierarchical sheets. At first I had trouble getting the sheet connections to appear correctly on the root schematic, and I also ran into duplicate reference errors while annotating the design. After checking the sheet connections and re-annotating the project, the errors were resolved.

I also started assigning footprints to the components. This took longer than expected because I wanted to make sure the footprints matched the actual components I plan to use instead of selecting them randomly.

The schematic is now much closer to completion, and my next goal is to finish the remaining ERC issues, verify every connection, and start the PCB layout.

Hours: About 6.5 hours

