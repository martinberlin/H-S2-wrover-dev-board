## An open source S2-WROVER board with minimun components and DFU USB

H stands for Hardware.

![PCB preview](https://raw.githubusercontent.com/martinberlin/H-S2-wrover-dev-board/v1/components/imgs/S2-Wrover-dev-pcb.jpg)
Initial dimensions:
99x50mm
![PCB preview-back](https://raw.githubusercontent.com/martinberlin/H-S2-wrover-dev-board/v1/components/imgs/S2-Wrover-dev-pcb-back.jpg)
![PCB layers](https://raw.githubusercontent.com/martinberlin/H-S2-wrover-dev-board/v1/components/imgs/PCB-preview.png)
Note: Previews are taken from the [v1 branch](https://github.com/martinberlin/H-S2-wrover-dev-board/tree/v1).

This board aims to be the simplest possible configuration to have a breakout PCB to start developing something with Espressif S2.
The minimun requirements are:

- Lipo charger and a 2 leds indicator (charge, full)
- All GPIOs exposed
- No Serial-to-UART. Only dfu USB, please check this [blog post from Espressif](https://blog.espressif.com/dfu-using-the-native-usb-on-esp32-s2-for-flashing-the-firmware-b2c4af3335f1)
- Only 2 layer (Cheaper to fabricate)
- **Important** For simplicity this test board has no Auto-Reset circuit (Check [epdiy Schematic](https://github.com/martinberlin/H-S2-wrover-dev-board/tree/epd-v1/Schematic))

## EPDiy S2 PCB

In the **epd-v1** branch it's my first attempt to design an EPDiy V6 clone. This is still on fabrication and as the prototype Revision 1.1 still need a lot of tests and adjustments.
This will be probably merged in master once is tested and working as expected. Being my first somehow complex ESP32S2 boards I will for sure 

Both boards Still a work in progress, no Gerbers, no pick-place and no production files at all. It needs testing before everything can be published.
