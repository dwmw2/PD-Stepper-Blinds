# Power PCB

The custom power distribution PCB is an optional component that provides two key features:

- **Internal Power Delivery** - Supplies power directly to internal pads on the PD-Stepper board via Harwin S1761-42R spring terminals, bypassing the USB-C connector
- **Reed Switch Connection** - Provides a connector for a reed switch to detect when the blinds are fully closed

### Design Files

KiCad project files are located in the `power-pcb/` directory. Gerber files for fabrication are available in `power-pcb/Gerber/`.

For PCB assembly through JLCPCB, the `jlcbom.csv` file contains the spring terminal part number in the required format.

![Power PCB](../images/PCB.png)

## Assembly

The power PCB is designed to make contact with the back of the PD-Stepper board, using the terminals shown.

![Power PCB Terminals](../images/image.webp)

The JST-PH socket is fitted at right angles to the board with its pins laying flat on the copper, so manufacturers like JLCPCB won't be able to build that. Using the jig as shown to position the socket and PCB, solder them by hand.

![PCB Jig](../images/PXL_20250314_105317922.webp)
