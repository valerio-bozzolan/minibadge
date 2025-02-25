# End Summer Camp - Mini Badge

![3D Model](docs/3d.webp "3D Model")

This is the first official ESC badge with a microcontroller!

## Hardware Features

- RP2040 microcontroller
- 9 RGB(W) LEDs
- IR transmitter and receiver
- 1 button
- USB-C connector
- JTAG and expansion pads

## Software Features
- Fully featured and composable animation engine for light effects and patterns
- A lot of built-in animations, more can be added easily
- IR remote control support (NEC and Samsung NEC), commands can be added easily
- IR transmitter (NEC), badge-to-badge communication
- USB CDC for debug and control
- USB MIDI for control (you can send standard MIDI messages to control the lights)
- Automatic overheating protection
- Torchlight mode (power up with the button held down)
- to be continued...


## Project Structure
- `antani_hw/`: Contains the hardware design files, KiCad project.
- `antani_sw/`: Contains the firmware for the badge.
- `minibadge-cli/`: Contains the CLI tool to interact with the badge from a computer.
- `docs/`: Contains all the documentation for the project.