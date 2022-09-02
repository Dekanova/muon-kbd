# A smol and simple osu keypad

This is the Muon PCB (currently in development).

## Details
Firmware for this board can be found here https://github.com/Dekanova/muon-firmware.
ROM flash is pretty big and should be able to fit whatever you want on it.

Feel free to make a PR if you get other firmware working on this board!

- RP2040 (easy firmware changes)
- hybrid MX/low profile choc hotswap socket
- rgb keyglow & underglow
- usb-c


## Usage
TODO: once hybrid keyswitch gen is merged, move from local reference

- Kicad 6.0
- openinput library from kicad content&lib manager

## Images (last updated: v0.4)
![pcb](media/v0-4/pcb.jpg?raw=true "PCB")
![front](media/v0-4/front.jpg?raw=true "Front")
![back](media/v0-4/back.jpg?raw=true "Back")

A huge thanks to openinput for their generic [KiCad lib](https://github.com/openinput-fw/openinput-kicad-library).

Also thanks to [marbastlib](https://github.com/ebastler/marbastlib) for their component lib.

This project is licenced under [CERN Open Hardware Licence v2 - Strongly Reciprocal](LICENCE)
