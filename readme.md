# Friendly USB hub
Note: work in progress.

I've always wanted a little desk-top gadget to display graphics, but my PC doesn't have that many USB ports, and having too many cables routed through my desk makes a mess. So, I wanted to make a USB hub that can also display graphics (programmable by usb or wifi) and be a useful second HUD or mini-display.

## Hardware
The project uses a Pi Pico W/2W, [8-pin display](https://www.aliexpress.com/item/4000219159401.html) and CoreChips SL2.1s USB controller. It has 5 USB ports, 1xUSB-C input, 2xUSB-A output, 1xUSB-C output and 1x internal USB-A, used to connect to the Pi Pico. It will support USB 2.0 transfer speeds (up to 480MB/s), and the Pico will use WiFi for data and management, and WiFi Direct for initial WiFi setup. This will all be integrated into a 3D-printed case.