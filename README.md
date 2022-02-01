## An open source S2-WROVER board with minimun components and DFU USB

H stands for Hardware.

![PCB preview](components/imgs/S2-Wrover-dev-pcb.jpg)
Initial dimensions:
99x50mm

This board aims to be the simplest possible configuration to have a breakout PCB to start developing something with Espressif S2.
The minimun requirements are:

- Lipo charger and a 2 leds indicator (charge, full)
- All GPIOs exposed
- No Serial-to-UART. Only dfu USB, please check this [blog post from Espressif](https://blog.espressif.com/dfu-using-the-native-usb-on-esp32-s2-for-flashing-the-firmware-b2c4af3335f1)



Still a work in progress, no Gerbers, no pick-place and no production files at all. It needs testing before everything can be published.
