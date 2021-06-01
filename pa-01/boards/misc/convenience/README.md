# Conveience Board (FALK PA-01)

![Conveience Board outline](img/pcb-outline.png)

To power on/off low-power devices (line sources) or to control equipment via a switching power filter (like a Rotel RLC900), the Conveience Board provides a way to provide a switched mains voltage based on the power state of the preamplifier. Simply connect the incoming mains power (120V, 220V) to the IN terminals and connect the OUT terminals to a power socket on the rear of the device. Plug any devices you wish to be switched to the output connector.

**BE AWARE** This board uses singal relays that are rated at 2A. Attempting to draw more than 2A will damage the signal relays. **Do not** use this board to switch power amplifiers, etc. that consume large currents.

## Building the board
You can find the full Bill Of Materials below, this board is very simple, just solder each component in place and plug into the main board chain using a chained IDC cable.

### Schematic
![Conveience Board Schematic](img/schematic.png)

## PCB Layout
![Conveience Board Layout](img/pcb.svg)

## Bill Of Materials
| Part | Quantity | Symbol | Manufacturer | Distributor |
|-|-|-|-|-|
| G6A-274P-ST-US-DC5 | 1 | RLY_1 | OMRON | DigiKey, Mouser |
| 1N4148 | 1 | D1 | ON Semiconductor | DigiKey, Mouser |
| 75869-131LF | 2 | CHAIN | Amphenol FCI | DigiKey, Mouser |
| 6PCV-02-006 | 2 | IN, OUT | TE Connectivity | DigiKey, Mouser |