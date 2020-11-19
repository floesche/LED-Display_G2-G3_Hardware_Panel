---
title: Panel PCBs
parent: Generation 2
nav_order: 2
---

The panel in Generation 2 of the Modular LED Display consists of a standard 8×8 LED matrix component with a custom PCB, the driver. Throughout the documentation the term "panel" either describes the LED matrix itself or the combination with the driver.

The matrix component [BM-10288MD](https://www.americanbrightled.com/products/led-displays/dot-matrix/) measures 32×32mm² and consists of 8×8 = 64 LEDs. 

The driver has similar dimensions and is attached to the back of the matrix component. It contains an ATMEGA168-A and a ULN2804A to drive the LEDs.

The most recent version is Flypanels v1.3, generated in 2012. The KiCAD design files are in the `flypanels` directory. Gerber files and a Bill of Materials (BOM) are in a subdirectory `production_v1`.


## Generation 2 and 3

The driver is used for both, G2 and G3 panels. The most recent production of these drivers we are aware of was in 2020, when the Frye lab ordered fly panels at [Bittele Electronics Inc](https://7pcb.com) in Canada. If you want to replicate the exact same order, feel free to include the order reference number Q12295E in your conversation with Bittele.



## Project content

```
├── datasheets
└── flypanels
    └── production_v1
```

3 directories
