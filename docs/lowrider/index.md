# Low Rider CNC 3

The LowRider3 is the V1 Engineering version of a CNC router that can handle up to full sheet material! If the MPCNC is not big 
enough for you this picks up where that left off.

![!LR3 Fancy Picture](../img/lr3/LR3_Fancy (6).jpg){: loading=lazy width="600"}

### Key Points

 * Most parts can be 3D printed. To save from shipping or printing large parts the machine can be partially assembled to cut them itself.

 * Easily Removable from the table for storage or portability.

 * Inexpensive hardware store conduit is the recommended X rail. Rails ranging from 23.4mm to 25.4mm will work. This saves considerable cost over the LR2.

 * Many tool options, in terms of functionality and brands. Blank DIY mount files are available.

 * Full Y and Z axis squaring, leveling, and Z probing are available for excellent precision and accuracy.

 * Works with any 5 driver board. 4 driver boards can be used but some automation, one axis dual endstops, will be lost.

 * Can be used with Marlin, RepRap firmware, GRBL, FluidNC, or others.

 ![!LR3 Fancy Picture](../img/lr3/LR3_Fancy (2).jpg){: loading=lazy width="600"} 
 
### Geometry

* This CNC router can handle any length (within reason), the Y direction is only bound by your table length.

* The single Y rail keeps the machine properly constrained while maintaining ease of use. Two rails are extremely difficult to 
align, and fully constrained rails do not allow for easy removal of the machine.

* Width (X axis or "Beam") should always be the shorter axis.

* The Z direction (height) is best kept to 80mm. This allows for 1.5" of cutting depth, that is a lot. If you need to cut more that 1.5" deep this is not 
the CNC for you. Now if you need to cut a few millimeters off  really thick material (facing a slab), this can be a great machine for that. You want to keep the machine as low as possible and 
make the table surface adjustable, drop table. This keeps the Material Removal Rate very high. The answer is not making a taller machine.

* This router is most rigid when working near the table surface, opposite of most conventional gantry CNC machines. So the lower the axis the more rigid the machine.

![!LR3 Fancy Picture](../img/lr3/LR3_Fancy (3).jpg){: loading=lazy width="600"}
 
### License

This work is licensed under a [Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License](https://creativecommons.org/licenses/by-nc-sa/4.0/).

More details to my loosened restrictions can be found here on [the home page](https://www.v1engineering.com/license/). 

![!LR3 Fancy Picture](../img/lr3/LR3_Fancy (4).jpg){: loading=lazy width="600"}

### Files can be found at the links below

Printables.com
:   [Printables.com Link](https://www.printables.com/model/204709-lowrider-3-cnc)

Thingiverse Printed parts files:
:   [Thingiverse.com Link](https://) Coming soon!

![!LR3 Fancy Picture](../img/lr3/LR3_Fancy (7).jpg){: loading=lazy width="600"}

!!! info Previous build "LR V2"
    Version two instructions are [here](../lowrider/lrv2/indexv2.md)

## Parts Needed

### Printed Parts

Buy a set here, [V1 Shop](https://shop.v1engineering.com/collections/lowrider-parts/products/lowrider-v3-printed-parts).

Or print your own. No supports needed, keep the default orientation. PLA is recommended for ultimate rigidity, other 
filaments should be evaluated for rigidity. 2-3 walls rectilinear infill. Thicker layers since these are large parts, no 
more than 80% nozzle diameter to keep overhangs working.

|QTY |File Name                   |Infill |Comment                              |Link                                     | 
|----|----------------------------|-------|-------------------------------------|-----------------------------------------|
|1   |LR Core                     |35%    |                                     |                                         |
|1   |X Drive Mount               |30%    |                                     |                                         |
|2   |Y Drive                     |30%    |                                     |                                         |
|2   |Z Drive                     |30%    |                                     |                                         |
|4   |Temporary Strut             |30%    |                                     |                                         |
|1   |Front Rail Roller           |30%    |                                     |                                         |
|1   |Rear Rail Roller            |30%    |                                     |                                         |
|1   |Bearing Wheel Bracket Front |30%    |* See note below - Optional Version  |[Link][Wheels]                           |
|1   |Bearing Wheel Bracket Rear  |30%    |* See note below - Optional Version  |[Link][Wheels]                           |
|1   |Z Stop                      |30%    |                                     |                                         |
|1   |Z Stop M                    |30%    |                                     |                                         |
|6-8 |Brace -Choose one size-     |30-50% |* See Brace Note below               |                                         |
|6-8 |Hose Hanger                 |30%    |Same number as braces, Optional part |                                         |
|1   |X Tensioner                 |30%    |                                     |                                         |
|1   |XZ Plate Left               |70%    |* See XZ note below - Can be milled  |[Shop][xz1] - [DXF](/lowrider/#xz-plates)|
|1   |XZ Plate Right              |70%    |* See XZ note below - Can be milled  |[Shop][xz1] - [DXF](/lowrider/#xz-plates)|
|1   |Front Y Belt Holder         |30%    |                                     |                                         |
|1   |Front Y Belt Base           |30%    |                                     |                                         |
|1   |Front Y Belt Holder Right   |30%    |                                     |                                         |
|1   |Front Y Belt Base Right     |30%    |                                     |                                         |
|1   |Y Tension Block Rear        |30%    |                                     |                                         |
|1   |Y Tension Base Rear         |30%    |                                     |                                         |
|1   |Y Tension Block Rear Right  |30%    |                                     |                                         |
|1   |Y Tension Base Rear Right   |30%    |                                     |                                         |
|8-14|Rail Block -Choose one size-|30%    |* See Rail block note below          |                                         |
|    |Optionally Printed          |       |                                     |                                         |
|2   |YZ Plate                    |50%    |Best as a milled part                |[Shop][yz1] - [DXF](/lowrider/#yz-plates)|

[Wheels]: https://www.printables.com/model/211714-lr3-60mm-wheel-brackets
[xz1]: https://shop.v1engineering.com/products/lowrider-3-metal-xz-plates
[yz1]: https://shop.v1engineering.com/collections/lowrider-parts/products/lowrider-cnc-v3-yz-plates

 * Optional Version- You can use 58-62mm X 25mm with the option brackets. The wheels might provide for a smoother rider over 
 a rough table or debris with the downside being a bit of "give" and the possibility of the Wheels steering a non parallel build. 
 The bearings should be more precise and make for a more forgiving build. [Wheels](https://shop.v1engineering.com/collections/lowrider-parts/products/urethane-wheels) 
 [Spacers](https://shop.v1engineering.com/collections/all/products/axle-spacers)

 * Brace note-  Print the end two braces with 50% infill and the rest with 30%. 2' wide builds need 6 total,
 4 foot versions need 8 total. Recommended US 3/4" EMT = 23.4mm = Brace 23p4 That is the suggested size for US based builds.

 * XZ Note- Can be a flat part. Milled or Purchased. If you do use a flat part you will need to print both "XZ Leadscrew Stub Right" and "XZ Leadscrew Stub".

 * Rail Block note- You want these with no larger than an 8" gap between them. Recommended US 1/2" EMT = 18.1mm = Rail Block 18p1.3mf


### Tool Mounts
Recommended [Makita 700 series router](https://amzn.to/3PnQKUf) (available in many countries with slightly different model 
numbers), [tool mount and dust shoe](https://www.printables.com/model/167678-makita-700-series-mount-and-removable-dust-shoe-fo).

[DeWalt 611](https://amzn.to/3leu6zL), [Tool mount and dust shoe](https://www.printables.com/model/166254-dewalt-611-mount-and-removable-dust-shoe-for-the-l).

Build your own, [CAD](https://a360.co/3vbUQFX) and [step files](https://www.printables.com/model/167687-lowrider-3-cnc-blank-tool-mount).

### Board Boxes

[SKR Pro](https://www.printables.com/model/209348-skr-pro-lr3-specific-case)
[Rambo](https://www.printables.com/model/209411-rambo-or-mini-rambo-lr3-specific-case)
[Mini Rambo](https://www.printables.com/model/209411-rambo-or-mini-rambo-lr3-specific-case)

Blank Box, Include CAD *to do

## Flat Parts

#### Strut Plates

The Strut plates were designed to be up to 6.35mm (1/4") thick. Hardboard or any similarly rigid materials work best 
here.

Here are the pre-made most common Strut Plate sizes.

[4' Strut PLate Plate DXF](../img/lr3/Strut Plate 1400mm.dxf)

[4' Strut PLate Plate CAD/Fusion360](https://a360.co/34F4cAL)


[2' Strut plate Plate DXF](../img/lr3/Strut Plate 790mm.dxf)

[2' Strut PLate Plate CAD/Fusion360](https://a360.co/3CrRkKw)

If you choose to adjust these to fit your build the only thing to know is you want no more than 200mm (8") between the braces.
Start with whichever CAD file is closest to your desired size and edit the first sketch.

![Strut Edit Picture](../img/lr3/strut edit.jpg){: loading=lazy width="600"}

#### YZ Plates

The YZ Plates can be nearly any thickness. Again here, rigidity is key. 1/2" (12mm) MDF is a great choice. Much thicker than 
that and you will need to clearance some for the coupler. At 16.5mm and thicker you will need to counter bore for the M5 nuts
 or get longer screws.

[YZ Plate DXF](../img/lr3/YZ plate DXF.dxf)
[Mirrored set YZ Plate DXF](../img/lr3/two YZ plates.dxf), just to make it easy to mill up a set.
[YZ Plate STL](../img/lr3/YZ Plate.stl), If you want to try and print it.

#### XZ Plates

The printed XZ plates (when printed in PLA) prove to be more rigid than 1/2" MDF. The only way to get any more rigidity 
is going to metal. If you choose to make your own here are the guidelines. 

![!LR3 Fancy Picture](../img/lr3/nomorethan9p5.jpg){: loading=lazy width="600"}

The M5 screws provided with the kit can handle up to 9.5mm thick plates and anything less than that. Anything above and 
you will need to counter bore the heads.

![!LR3 Fancy Picture](../img/lr3/nomorethan7.jpg){: loading=lazy width="600"}

The M3 screws provided with the kit need 6.35mm to 7mm plate thickness. If you go thinner you will needs washers, to go 
thicker you will need to counter bore the heads. 

[XZ Plate DXF](../img/lr3/XZ Plate.dxf)


### Specialty Parts

You can buy most of the Specialty Parts and hardware here, [V1 Shop](https://shop.v1engineering.com/collections/lowrider-parts/products/lowrider-v3-hardware-kit)

|QTY  |Description             |Comment                                        |Link                        | 
|-----|------------------------|-----------------------------------------------|----------------------------|
|1    |Control Board           |5 driver minimum                               |[Shop][sh1] – [Amazon][az1]|
|5    |Steppers, Nema17        |20mm+ shaft length                             |[Shop][sh2] – [Amazon][az2]|
|3    |stepper wire extenders  |                                               |[Shop][sh3] – [Amazon][az3]|
|3    |Pulleys 16T 10mm        |10mm GT2 16 Tooth                              |[Shop][sh4] – [Amazon][az4]|
|6    |Idlers Smooth 20T       |20T Smooth 5mm Bore                            |[Shop][sh5] – [Amazon][az5]|
|8M   |Belt GT2 10mm           |See [Calculator](calculator.md), no steel belt |[Shop][sh6] – [Amazon][az6]|
|5    |Endstops                |                                               |[Shop][sh7] – [Amazon][az7]|
|14   |6082rs Bearings         |                                               |[Shop][sh8] – [Amazon][az8]|
|2    |T8 Leadscrew & nut      |110mm or larger                                |[Shop][sh9] – [Amazon][az9]|
|2    |Coupler                 |8mm to 5mm                                     |[Shop][sh10] – [Amazon][az10]|
|4    |Linear rails MGN        |MGN12H 150mm                                   |[Shop][sh11] – [Amazon][az11]|
|1    |Power Supply            |12-36V Board dependant 36W+                    |[Shop][sh12] – [Amazon][az12]|
|*    |Thread locker           |Optional for grubs screws                      |[Shop][sh13] – [Amazon][az13]|
|*    |Lube                    |Optional for idlers and linear rails           |[Shop][sh14] – [Amazon][az14]|
|*    |Vac Hose                |Optional any 1.5" OD Vacuum hose should work   | – [Amazon][az15]|

[sh1]: https://shop.v1engineering.com/collections/3dprinter-parts/products/skr-pro1-2-6x-2209-drivers-tft35-e3-v3
[sh2]: https://shop.v1engineering.com/collections/3dprinter-parts/products/nema-17-76oz-in-steppers
[sh3]: https://shop.v1engineering.com/products/wiring-kit-1
[sh4]: https://shop.v1engineering.com/collections/3dprinter-parts/products/pulley-16-tooth-gt2-10mm
[sh5]: https://shop.v1engineering.com/collections/3dprinter-parts/products/20t-idler-gt2-10mm 
[sh6]: https://shop.v1engineering.com/collections/3dprinter-parts/products/gt2-10mm-belt
[sh7]: https://shop.v1engineering.com/collections/parts/products/limit-switch-endstop
[sh8]: https://shop.v1engineering.com/collections/lowrider-parts/products/bearings-608-2rs 
[sh9]: https://shop.v1engineering.com/collections/lowrider-parts/products/110mm-t8-leadscrew-and-nut 
[sh10]: https://shop.v1engineering.com/collections/lowrider-parts/products/5mm-to-8mm-flex-coupler
[sh11]: https://shop.v1engineering.com/products/150mm-mgn12h-linear-guides
[sh12]: https://shop.v1engineering.com/collections/lowrider-parts/products/12v-6a-power-supply
[sh13]: https://shop.v1engineering.com/collections/3dprinter-parts/products/0-5ml-threadlocker-242
[sh14]: https://shop.v1engineering.com/collections/3dprinter-parts/products/super-lube-silicone-lubricating-grease-with-syncolon-ptfe 

[az1]: https://amzn.to/3mp6nOk
[az2]: https://amzn.to/3FcxGlE
[az3]: https://amzn.to/39DSW9I
[az4]: https://amzn.to/3n9mUGM
[az5]: https://amzn.to/3JXAXJi 
[az6]: https://amzn.to/3u5imW6
[az7]: https://amzn.to/396oRzi
[az8]: https://amzn.to/3FDI8EI 
[az9]: https://amzn.to/3wnjvrI 
[az10]: https://amzn.to/3yoet0D 
[az11]: https://amzn.to/3PyAujr
[az12]: https://amzn.to/3Pe0P6m
[az13]: https://amzn.to/3GhaKmx
[az14]: https://amzn.to/31H7yS6
[az15]: https://amzn.to/38iqA4v

As an Amazon Associate I earn from qualifying purchases.

### Hardware

This is what is needed for a 4' x 8' (1.2M x 2.4M) build. You will need more or less depending on what size you build.

|QTY  |Description             |US Equivalent                                  | 
|-----|------------------------|-----------------------------------------------|
|14   |M8 x 40mm               |5/16" x 1.5"                                   |
|14   |M8 Nylock nuts          |5/16" Nylock                                   |
|100  |M5 x 30mm               |None                                           |
|100  |M5 Nylock               |None                                           |
|40   |M3 x 10mm               |None                                           |
|10   |M2.5 x 12mm             |None                                           |
|24   |3mm x 12mm Wood/metal   |#4 x 1/2" Wood or Sheet metal screws           |
|*22  |M4 x 12mm+ Wood/metal   |#8 x 1/2"+ Screws to mount things to your table|

* Not included in the hardware kit. 

### LR2 to LR3 hardware differences for updating your build
|QTY  |Description             |US Equivalent                                  | 
|-----|------------------------|-----------------------------------------------|
|14   |M8 x 40mm               |5/16" x 1.5"                                   |
|94   |M5 x 30mm               |None                                           |
|94   |M5 Nylock               |None                                           |
|36   |M3 x 10mm               |None                                           |
|10   |M2.5 x 12mm             |None                                           |
|24   |3mm x 12mm Wood/metal   |#4 x 1/2" Wood or Sheet metal screws           |
|22   |M4 x 12mm+ Wood/metal   |#8 x 1/2"+ Screws to mount things to your table|
|4    |150mm MGN12H Rails      |[Shop Link](https://shop.v1engineering.com/collections/lowrider-parts/products/150mm-mgn12h-linear-guides)|

### Table

Any flat surface you can screw into will work great. Basic torsion box tables can 
be a step up in terms of long term stability with not all that much added complexity. 
A Removable spoil board section that can be easily replaced comes in handy as well.

footprint *to do
rail position
Belt block positions

[Calculator for table, rail, and belt lengths.](calculator.md)


## Assembly

#### Core Assembly

![!LR3 Fancy Picture](../img/lr3/LR3 (1).jpg){: loading=lazy width="400"}

 * LR Core, and six M5 nuts.

![!LR3 Fancy Picture](../img/lr3/LR3 (2).jpg){: loading=lazy width="400"}

 * Press these 6 nuts in place.
 * If they are not snug use some loctite or glue to keep them in place, or mount your tool mount now loosely.
 * The 7th hole is a spare for future expansion packs.

![!LR3 Fancy Picture](../img/lr3/LR3 (3).jpg){: loading=lazy width="400"}

 * Bolts, 6082RS bearings and nuts for the next step.

![!LR3 Fancy Picture](../img/lr3/LR3 (4).jpg){: loading=lazy width="400"}

 * Snug up these 6 bolts and make sure everything still moves freely.
 * These last two bolts control how much tension the core has on the Beam.
 * Lightly seat these nuts and wait to set the tension until you have the beam ready.

![!LR3 Fancy Picture](../img/lr3/LR3 (5).jpg){: loading=lazy width="400"}

 * Get your Micro switch ready along with some M2.5 screws.

![!LR3 Fancy Picture](../img/lr3/LR3 (6).jpg){: loading=lazy width="400"}

 * Notice the lever orientation.
 * Lightly set the M2.5 screws. If they strip out, add a drop of glue or thread locker to the threads
  and they should stay seated when it dries.

##### X Drive

![!LR3 Fancy Picture](../img/lr3/LR3 (7).jpg){: loading=lazy width="400"}
 
 * This section uses the X Stepper Mount, M5's, and Idlers.

![!LR3 Fancy Picture](../img/lr3/LR3 (8).jpg){: loading=lazy width="400"}

 * Assemble as show with the nuts down, very lightly seating the nuts.
 * The inside nut fits in a small groove in the printed part. 
 * Make sure the Idlers spin freely.

![!LR3 Fancy Picture](../img/lr3/LR3 (9).jpg){: loading=lazy width="400"}

 * Add the pulley to the stepper 1-2mm up from the base.
 * Tighten the flat grub screw first and then the next.
 * Threadlocker or LocTite is recommended.

![!LR3 Fancy Picture](../img/lr3/LR3 (10).jpg){: loading=lazy width="400"}

 * Assure the pulley in centered with the idlers when assembled.

![!LR3 Fancy Picture](../img/lr3/LR3 (11).jpg){: loading=lazy width="400"}

 * Make sure to orient the wire out, as shown.
 * Snug the stepper in place with M3's

![!LR3 Fancy Picture](../img/lr3/LR3 (12).jpg){: loading=lazy width="400"}

 * Add the stepper assembly to the Core.
 * Make sure the M5's Engage the nuts properly, any sign of binding back out and try again.
 * If for some reason the nuts spin, use a small flat head screw driver to pin it in place as you tighten.

![!LR3 Fancy Picture](../img/lr3/LR3 (13).jpg){: loading=lazy width="400"}

 * Snugged in place.

![!LR3 Fancy Picture](../img/lr3/LR3 (14).jpg){: loading=lazy width="400"}

 * Tuck the wires into the groove and you can secure them at the top with a wire or cable tie.
 * Now is a good time to add your touch plate wires if you are using one.
 * If you are concerned you can add a piece of tape in between the screw holes but any tool mount should also do the trick here.

---
#### Side Plate Assemblies
![!LR3 Fancy Picture](../img/lr3/LR3 (15).jpg){: loading=lazy width="400"}

 * Z drives, steppers, M3 screws.

![!LR3 Fancy Picture](../img/lr3/LR3 (16).jpg){: loading=lazy width="400"}

 * Pay attention to wire routing here. 
 * Snug up the M3 Screws

![!LR3 Fancy Picture](../img/lr3/LR3 (17).jpg){: loading=lazy width="400"}

 * Y drives, Idlers, M5's

![!LR3 Fancy Picture](../img/lr3/LR3 (18).jpg){: loading=lazy width="400"}

 * Seated not snug, screws are axles here.
 * Nuts facing down.
 * Make sure idlers are very free to spin.

![!LR3 Fancy Picture](../img/lr3/LR3 (19).jpg){: loading=lazy width="400"}

 * Add the pulley to the Stepper. 1-2mm gap next picture has a visual check.
 * Tighten the grub screw on the Flat shaft surface first then the other screw.
 * LocTite is recommend on all grub screws.

![!LR3 Fancy Picture](../img/lr3/LR3 (20).jpg){: loading=lazy width="400"}

 * Make sure Pulley teeth are centered with the idlers.
 * Snug The Stepper in place with the M3 Screws.
 * Wires should face one in each direction (mirrored), just like the Y drives.

![!LR3 Fancy Picture](../img/lr3/LR3 (21).jpg){: loading=lazy width="400"}

 * Microswitches, M2.5 screws.

![!LR3 Fancy Picture](../img/lr3/LR3 (22).jpg){: loading=lazy width="400"}

 * Make sure the lever faces out (up in this picture).
 * Switch away from the stepper wires, route wires together (for now).
 * Gentle with the tiny screws threading into the printed part. Seated no more.
 * If you do happen to strip out the screw holes a drop aon nearly any glue or 
 locTite on the threads will fix it.

![!LR3 Fancy Picture](../img/lr3/LR3 (23).jpg){: loading=lazy width="400"}

 * Orientation, mirrored sets.

![!LR3 Fancy Picture](../img/lr3/LR3 (24).jpg){: loading=lazy width="400"}

 * Z Stop & Z Stop M, Wired Endstops, M2.5mm screws.

![!LR3 Fancy Picture](../img/lr3/LR3 (25).jpg){: loading=lazy width="400"}

 * Notice the direction of the Switch levers
 * Tuck the wires nicely into the grove, make sure not to pinch them when installing them later.
 * Gentle with the small M2.5 screws.

![!LR3 Fancy Picture](../img/lr3/LR3 (26).jpg){: loading=lazy width="400"}

 * T8 nut, and 1-2 M3 screws.
 * In the following steps you will either be using the Printed XZ plates, or XZ Lead Screw Stubs.

![!LR3 Fancy Picture](../img/lr3/LR3 (27).jpg){: loading=lazy width="400"}

 * One screw is plenty as it is just there to stop the brass nut from spinning.

![!LR3 Fancy Picture](../img/lr3/LR3 (31).jpg){: loading=lazy width="400"}

 * A completed XZ printed plate.

![!LR3 Fancy Picture](../img/lr3/LR3 (28).jpg){: loading=lazy width="400"}

 * With Milled XZ plates you will need to attach the stubs to the plate with an M5.

![!LR3 Fancy Picture](../img/lr3/LR3 (29).jpg){: loading=lazy width="400"}

 * The nuts gets seated in the printed stub.
 * Align the angled surfaces of both parts.

![!LR3 Fancy Picture](../img/lr3/LR3 (30).jpg){: loading=lazy width="400"}

 * Orientation of the stubs and XZ plates.

![!LR3 Fancy Picture](../img/lr3/LR3 (32).jpg){: loading=lazy width="400"}

 * The MGN12H bearing blocks get attached to the XZ plate.
 * If you are using the printed version, M3x10mm screws will fit.
 * If you are using a milled part follow the guidelines for thickness only use washers if necessary.

![!LR3 Fancy Picture](../img/lr3/LR3 (33).jpg){: loading=lazy width="400"}

 * Now is a good time to assure the linear guides are moving freely. If not loosen the 4 small screws
 On the end of the bearing block a full turn move the bearing block back and forth and tighten the 
 screws back up.
 * You can add a touch of a light oil or dab of the superlube, but it should not be necessary.
 * Keep the stops in the end until they are mounted to the YZ plates to avoid tiny bearings everywhere.

![!LR3 Fancy Picture](../img/lr3/LR3 (34).jpg){: loading=lazy width="400"}

 * With the rails mounted make sure they are parallel by measuring how far apart they are at the top 
 and bottom of travel at the ends.
 * Snug up the M3's, LocTite is not a bad idea here.

![!LR3 Fancy Picture](../img/lr3/LR3 (35).jpg){: loading=lazy width="400"}

 * You will need to add two M5's to the holes shown here. Actually you only need the lower two but just to be safe drop them all in for now.
 * Use the small wood screws to attach the rails to the YZ plate.

![!LR3 Fancy Picture](../img/lr3/LR3 (36).jpg){: loading=lazy width="400"}

 * Start attaching the rails in the middle, one screw each. Loosely.
 * Once you have a screw in each rail you can remove the stops.
 * Keep adding screws and checking for smooth motion as you go.
 * If all is going well snug up the screws into the wood. Gentle here, do not strip out the wood it does not take much.

![!LR3 Fancy Picture](../img/lr3/LR3 (37).jpg){: loading=lazy width="400"}

 * Add the Z drive wires facing the back.
 * Use M5 screws here and snug it up a bit.

##### Z End Stop

![!LR3 Fancy Picture](../img/lr3/LR3 (38).jpg){: loading=lazy width="400"}

 * Z Stop & Z Stop M
 * Test to make sure the micro switch clicks before the XZ plate hits the top.
 * If not the printed parts are slotted and you can bend the triggers to adjust. 
 Bend after the actual tiny trigger.

![!LR3 Fancy Picture](../img/lr3/LR3 (39).jpg){: loading=lazy width="400"}

 * The endstop wires will run through a small slot in the Y drive. Make sure they are free to move and not pinched.

 * Keeping the printed parts aligned with the plates keeps it looking nice.
 * Make sure the screws are snug so the switches do not move.

![!LR3 Fancy Picture](../img/lr3/LR3 (40).jpg){: loading=lazy width="400"}

 * Insert the Y drive. It goes in with a 90 degree twist. Should be plenty of room just.
 * Make sure the endstop wires are free moving.
 * Snug the screws.

 * Wire routing, each side should run towards the back of the plate.
 * Cable tie points on the Y and Z drives.
 * wire sleeve optional but looks nice here.

##### Wheels

![!LR3 Fancy Picture](../img/lr3/LR3 (41).jpg){: loading=lazy width="400"}

 * 608rs and bolts, Bearing Wheel Bracket Front & Rear.

![!LR3 Fancy Picture](../img/lr3/LR3 (42).jpg){: loading=lazy width="400"}

 * Preferred "wheels" 
 * Seat the bolt so the Head and nut are making contact but do not tighten. This is just an axle.
 * pay attention to the bolt orientation the nut goes in the deeper side.

![!LR3 Fancy Picture](../img/lr3/LR3 (43).jpg){: loading=lazy width="400"}

 * Optional Wheel brackets [Link](https://www.printables.com/model/211714-lr3-60mm-wheel-brackets)
 * Use spacers to prevent over tightening 
 * Seat the bolt but no need to snug it.

![!LR3 Fancy Picture](../img/lr3/LR3 (44).jpg){: loading=lazy width="400"}

 * Wheels installed, Heads in Nuts out. Snug these four screws.

![!LR3 Fancy Picture](../img/lr3/LR3 (45).jpg){: loading=lazy width="400"}

##### Rail Rollers

![!LR3 Fancy Picture](../img/lr3/LR3 (46).jpg){: loading=lazy width="400"}

* Front and Rear Rail Roller, Bolts and Bearings.

![!LR3 Fancy Picture](../img/lr3/LR3 (47).jpg){: loading=lazy width="400"}

* Insert the bearings, and seat the bolts.
* No need to snug as these are just axles.
* Bolt orientation is important here. One bolt is facing up and the nuts is tricky to slide into the top.

![!LR3 Fancy Picture](../img/lr3/LR3 (48).jpg){: loading=lazy width="400"}

* Side Plates are done!
* Roll them around on your table making motor noises to make sure they work right.

---

#### Beam Assembly

![!LR3 Fancy Picture](../img/lr3/LR3 (49).jpg){: loading=lazy width="400"}
![!LR3 Fancy Picture](../img/lr3/LR3 (50).jpg){: loading=lazy width="400"}
![!LR3 Fancy Picture](../img/lr3/LR3 (51).jpg){: loading=lazy width="400"}
![!LR3 Fancy Picture](../img/lr3/LR3 (52).jpg){: loading=lazy width="400"}
![!LR3 Fancy Picture](../img/lr3/LR3 (53).jpg){: loading=lazy width="400"}
![!LR3 Fancy Picture](../img/lr3/LR3 (54).jpg){: loading=lazy width="400"}
![!LR3 Fancy Picture](../img/lr3/LR3 (55).jpg){: loading=lazy width="400"}
![!LR3 Fancy Picture](../img/lr3/LR3 (56).jpg){: loading=lazy width="400"}
![!LR3 Fancy Picture](../img/lr3/LR3 (57).jpg){: loading=lazy width="400"}
---

#### X Belt

![!LR3 Fancy Picture](../img/lr3/LR3 (58).jpg){: loading=lazy width="400"}
![!LR3 Fancy Picture](../img/lr3/LR3 (59).jpg){: loading=lazy width="400"}
![!LR3 Fancy Picture](../img/lr3/LR3 (60).jpg){: loading=lazy width="400"}
![!LR3 Fancy Picture](../img/lr3/LR3 (61).jpg){: loading=lazy width="400"}
![!LR3 Fancy Picture](../img/lr3/LR3 (62).jpg){: loading=lazy width="400"}
![!LR3 Fancy Picture](../img/lr3/LR3 (63).jpg){: loading=lazy width="400"}
![!LR3 Fancy Picture](../img/lr3/LR3 (64).jpg){: loading=lazy width="400"}
---

#### Y Rail

![!LR3 Fancy Picture](../img/lr3/LR3 (65).jpg){: loading=lazy width="400"}
![!LR3 Fancy Picture](../img/lr3/LR3 (66).jpg){: loading=lazy width="400"}
![!LR3 Fancy Picture](../img/lr3/LR3 (67).jpg){: loading=lazy width="400"}
![!LR3 Fancy Picture](../img/lr3/LR3 (68).jpg){: loading=lazy width="400"}
![!LR3 Fancy Picture](../img/lr3/LR3 (69).jpg){: loading=lazy width="400"}
---

#### Wire Routing

![!LR3 Fancy Picture](../img/lr3/LR3 (70).jpg){: loading=lazy width="400"}
![!LR3 Fancy Picture](../img/lr3/LR3 (71).jpg){: loading=lazy width="400"}
![!LR3 Fancy Picture](../img/lr3/LR3 (72).jpg){: loading=lazy width="400"}
![!LR3 Fancy Picture](../img/lr3/LR3 (73).jpg){: loading=lazy width="400"}
![!LR3 Fancy Picture](../img/lr3/LR3 (74).jpg){: loading=lazy width="400"}
![!LR3 Fancy Picture](../img/lr3/LR3 (75).jpg){: loading=lazy width="400"}
---

#### Y Belt

![!LR3 Fancy Picture](../img/lr3/LR3 (76).jpg){: loading=lazy width="400"}
![!LR3 Fancy Picture](../img/lr3/LR3 (77).jpg){: loading=lazy width="400"}
![!LR3 Fancy Picture](../img/lr3/LR3 (78).jpg){: loading=lazy width="400"}
![!LR3 Fancy Picture](../img/lr3/LR3 (79).jpg){: loading=lazy width="400"}
![!LR3 Fancy Picture](../img/lr3/LR3 (80).jpg){: loading=lazy width="400"}
---

## Getting Started, cutting your strut plates

test move
Square
Level
cut strut plates

#### Initial Squaring

![!LR3 Fancy Picture](../img/lr3/LR3 (81).jpg){: loading=lazy width="400"}
![!LR3 Fancy Picture](../img/lr3/LR3 (82).jpg){: loading=lazy width="400"}
![!LR3 Fancy Picture](../img/lr3/LR3 (83).jpg){: loading=lazy width="400"}
![!LR3 Fancy Picture](../img/lr3/LR3 (84).jpg){: loading=lazy width="400"}
---

#### Z Leveling

![!LR3 Fancy Picture](../img/lr3/LR3 (85).jpg){: loading=lazy width="400"}
![!LR3 Fancy Picture](../img/lr3/LR3 (86).jpg){: loading=lazy width="400"}
![!LR3 Fancy Picture](../img/lr3/LR3 (87).jpg){: loading=lazy width="400"}
---

#### Making the Strut plates

![!LR3 Fancy Picture](../img/lr3/LR3 (88).jpg){: loading=lazy width="400"}
![!LR3 Fancy Picture](../img/lr3/LR3 (89).jpg){: loading=lazy width="400"}
![!LR3 Fancy Picture](../img/lr3/LR3 (90).jpg){: loading=lazy width="400"}
![!LR3 Fancy Picture](../img/lr3/LR3 (91).jpg){: loading=lazy width="400"}
---

#### Disassembly

![!LR3 Fancy Picture](../img/lr3/LR3 (92).jpg){: loading=lazy width="400"}
![!LR3 Fancy Picture](../img/lr3/LR3 (93).jpg){: loading=lazy width="400"}
![!LR3 Fancy Picture](../img/lr3/LR3 (94).jpg){: loading=lazy width="400"}
![!LR3 Fancy Picture](../img/lr3/LR3 (95).jpg){: loading=lazy width="400"}
![!LR3 Fancy Picture](../img/lr3/LR3 (96).jpg){: loading=lazy width="400"}
![!LR3 Fancy Picture](../img/lr3/LR3 (97).jpg){: loading=lazy width="400"}
---

#### Final Assembly

![!LR3 Fancy Picture](../img/lr3/LR3 (98).jpg){: loading=lazy width="400"}
![!LR3 Fancy Picture](../img/lr3/LR3 (99).jpg){: loading=lazy width="400"}
![!LR3 Fancy Picture](../img/lr3/LR3 (100).jpg){: loading=lazy width="400"}
---

### Vacuum
![!LR3 Fancy Picture](../img/lr3/LR3_Fancy (8).jpg){: loading=lazy width="600"}

Size, options, routing, grounding.  *to do

[Quick release coupler](https://www.printables.com/model/168405-vacuum-hose-coupler) for 1.5" hose.



### Using the machine.


### Firmware

Dual endstop LowRider "DualLR" firmware recommended for ultimate accuracy and precision. This requires 
at least a 5 driver control board. This allows you to align the Y axis and Z axis using dual endstops.

The standard MPCNC firmware will work with any board on the LowRider  if you are not using endstops or 
wired in series (using a 4 driver board). You will just use hardstops like the LR2 did.

[Firmware page.](../electronics/marlin-firmware.md)

## Go get it dirty, be safe, have fun!
