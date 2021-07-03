# _33BLE
A bluetooth drop-in PCB for the [_33 keyboard](https://github.com/tominabox1/_33-Keyboard) by [tominabox1](https://github.com/tominabox1). Documentation is available [here](https://dez.li/_33ble), and the ZMK config repository is available [here](https://github.com/dezlidezlidezli/underscore33-zmk-config). 

The board can be produced at [JLCPCB](jlcpcb.com) for rather cheap, and through their PCBA service they will assemble every component other than the the Holyiot 18010 module. You'll need to purchase this seperately, and solder it. You'll also need to flash the bootloader to the Holyiot module. The bootloader file can be found [here](/underscore33_bootloader.hex), and should be flashed using an ST-Link V2 clone, or a J-Link. Details for how to do this are available on the nice!keyboards wiki, and on the nRFMicro wiki. Please note that the Holyiot module does not need to be unlocked. 

Alternatively, you can choose to export files suited for another manufacturer, such as Elecrow or PCBWay, where they will assemble the entire board. 

Thank you to [Makenova](https://github.com/makenova) and [Matthew Dias](https://github.com/matthewdias) for funding the open-sourcing of this project. 
