---
title: Panel
parent: Generation 2
nav_order: 2
---

# Panel 8x8 32mm

The display devices in [Generation 2 (G2)](({{site.baseurl}}/Generation%202/Arenas/docs/g2_system.html)) and [Generation 3 (G3)]({{site.baseurl}}/Generation%203) of the Modular LED Display consists of a standard 8×8 LED matrix component mounted to a custom PCB. This custom PCB, in the original [paper](https://doi.org/10.1016/j.jneumeth.2007.07.019) and our [documentation]({{site.baseurl}}) referred to as the __panel__, is responsible for the communication with the controller.

The LED matrix component [BM-10288MD]({{site.baseurl}}/Generation%203/Hardware/docs/assets/green-panels_BM-10288MD.pdf) that was used in the Generation 2 displays measures 32×32mm² and consists of 8×8 = 64 LEDs. The panel board has the same dimension and is attached to the back of the matrix component. It contains an ATmega168-A and a ULN2804A to drive the LED matrix.

__Note__: To clarify the terminology: in [Generation 4]({{site.baseurl}}/docs/G4-index.html) of the Modular LED Display, we built our own LED PCBs then referred to as [_driver_]({{site.baseurl}}/Generation%204/Panel/docs/driver.html), and the PCBs providing part of the panel board functionally being called [_comm board_]({{site.baseurl}}/Generation%204/Hardware/docs/comm.html).

## Production

The KiCAD design files are in the `panel_8x8_32mm` directory. Gerber files and a Bill of Materials (BOM) are in a subdirectory `production_v1`. The most recently produced version is version 1.3 generated in 2012. Internally these files are still labeled as __flypanel__ and the production files are in `panel_8x8_32mm/production_v1/panel_8x8_32mm_v1p3.zip`.

 The most recent production of these drivers we are aware of was in 2020, when the Frye lab ordered fly panels at [Bittele Electronics Inc](https://7pcb.com) in Canada. If you want to replicate the exact same order, feel free to include the order reference number Q12295E in your conversation with Bittele.
