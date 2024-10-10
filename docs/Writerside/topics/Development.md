# Development

The following is the plan for development, with discovery and multiple iterations of custom boards.

## Discovery

* Documentation of Memory Cards
* Design Diagrams
* Plan of hardware
* Logic Analyzing Hardware

## Dev Hardware V1
First iteration of hardware, utilizing development boards cobbled together.

Goals:

* Prove out timing of original hardware
* 

Hardware:

* ESP32 Dev Board w/Touch : [LilyGo T-Display S3 AMOLED](https://www.lilygo.cc/products/t-display-s3-amoled?variant=43228221636789)
* MachX02 7000HE Breakout : [Lattice Evaluation Kit](https://www.latticesemi.com/products/developmentboardsandkits/machxo2breakoutboardf)
* Transfer Pack breakout to Custom Board [Transfer Pack](Transfer-Pack-Breakout.md)

## Dev Hardware V2
Second iteration, Custom board with FPGA / supporting hardware, connected to the esp32 dev board (able to run without connected to esp32)

Hardware:
* ESP32 Dev Board w/Touch : [LilyGo T-Display S3 AMOLED](https://www.lilygo.cc/products/t-display-s3-amoled?variant=43228221636789)

## Dev Hardware v3
Third iteration, Custom board w FPGA, ESP32, and connector for Screen / buttons. This will be the fully custom hardware,  

All hardware listed here is "initial concept", further cost optimization, hardware decisions will be 

Hardware:
* FPGA: Lattice MachX02 [Mouser](https://www.mouser.com/ProductDetail/Lattice/LCMXO2-1200HC-4TG100C?qs=O0MBHUYBjj1HTrW%252BXg%252BVUQ%3D%3D)
* Storage: SPI vs parallel flash / frame TBD
* Microcontroller: ESP32-S3-WROOM-1-N8 [Mouser](https://www.mouser.com/ProductDetail/Espressif-Systems/ESP32-S3-WROOM-1-N8?qs=sGAEpiMZZMu3sxpa5v1qrpuLb1YRQvRH486xd1meH8w%3D)
* Input: PCB Mount Switches [Mouser](https://www.mouser.com/ProductDetail/CK/TLS-A-040J-LFS?qs=GedFDFLaBXFBOP%252BaqwFsiQ%3D%3D)
* Screen: Newhaven display [Mouser](https://www.mouser.com/ProductDetail/Newhaven-Display/NHD-1.8-160128B?qs=2wMNvWM5ZX6vJtW6l4VG4g%3D%3D)
* 3d Printed Shell