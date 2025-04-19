# Neptune 4 series X rail

Shield: [![CC BY-NC-SA 4.0][cc-by-nc-sa-shield]][cc-by-nc-sa]

This work is licensed under a
[Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License][cc-by-nc-sa].

[![CC BY-NC-SA 4.0][cc-by-nc-sa-image]][cc-by-nc-sa]

[cc-by-nc-sa]: http://creativecommons.org/licenses/by-nc-sa/4.0/
[cc-by-nc-sa-image]: https://licensebuttons.net/l/by-nc-sa/4.0/88x31.png
[cc-by-nc-sa-shield]: https://img.shields.io/badge/License-CC%20BY--NC--SA%204.0-lightgrey.svg

![Thumbnail](Images/Thumbnail.png)

## Introduction

The design allows you to put a front mounted MGN12H linear rail on the neptune 4 series.

Many testing data yielded from 20% to 75% increase in recommended accel via input shaping(IS), with a reduction in vibrations and corner smoothing measured via a nozzle adxl.

### Features
- Improved COM placement.
- Increased rigidity.
- Proper parallel belt path.
- Increase movement accuracy, toolhead rigidity.
- Lowers the gantry compared to toolhead -> z cable bracket no longer hitting tie rods.
- Retains most mod compatibility (cable chains, fan mods, etc).
### Cons:
- 8mm loss in Y axis compared to stock.
- Renders the aux fan null.
- Requires skill, hardware, and machine tuning.

🤩 Do you like the design? You can help fund innovations like this!

[Consider supporting me!](https://buymeacoffee.com/silencedfrost)

Much appreciation given to my supporters, and you get exclusive access to various CAD files!

Submit feature requests [here!](https://trello.com/b/vacGVoLQ/cad-modelling-requests)

## BOM (Only listing extra parts, no stock)

|Item                         |Amount|Recommended source                                                         |
|-----------------------------|------|---------------------------------------------------------------------------|
|MGN12H linear rail           |1     |[Youmetong Z2](https://www.aliexpress.com/item/1005001463833841.html?)     |
|EU profile aluminum extrusion|1     |[MS N Metal fitting(Affiliated)](https://s.click.aliexpress.com/e/_oCB5XCB)|
|Gates gt2/edpm gt2 6mm belt  |1     |[Mellow Ali(Affiliated)](https://s.click.aliexpress.com/e/_oFvKV4n)        |
|Lithium grease               |      |Mobilux EP2/Mobil XHP222                                                   |
|Filament                     |      |PETG-GF/CF or ABS/ASA and above                                            |
|M3x35mm BHCS                 |2     |                                                                           |
|M3x40mm BHCS                 |2     |                                                                           |
|M3x16mm BHCS                 |4     |                                                                           |
|M3x6mm FHCS                  |4     |                                                                           |
|M3x10mm FHCS                 |1     |                                                                           |
|M3 Hex/Square nut            |4     |                                                                           |
|M4x8 BHCS                    |4     |                                                                           |
|M4 T-nuts                    |4     |                                                                           |
|M3x8mm SHCS                  |plenty|                                                                           |
|M3 T-nuts                    |plenty|                                                                           |
|M3 heat inserts (<4.7mm OD)  |4     |                                                                           |
|10mm metal drillbit          |1     |                                                                           |
|6900-2rs                     |1     |[6900-2rs(Affiliated)](https://s.click.aliexpress.com/e/_okwDcDg)          |

### Rail, extrusion, and belt lengths

|Model   |Rail       |Extrusion       |Belt  |
|--------|-----------|----------------|------|
|Base/pro|295mm-325mm|355mm           |820mm |
|Plus    |400mm-430mm|460mm           |1040mm|
|Max     |480mm-510mm|540mm           |1200mm|

### Note: get highest preload option the brand offers for budget rails

## Print settings

STL wasn't accounted for shrinkage, compensate as needed.

### Minimum:
- 3 walls.
- 1 mm top-bottom.
### Recommended
- 5 walls.
- 1.6mm top-bottom.
- 0.2mm layer height.

# Assembly guide

## Inserting heatsets

![Insert 2 into main piece](Images/Main%20piece%20-%20heatset%20insert.png)

![Insert 2 into adapter piece](Images/Adapter%20piece%20-%20heatset%20insert.png)

## Drilling extrusion x2 (One hole for each end)

### Assembling drill guide tool

![Assembling drill guide](Images/Extrusion%20drill%20jig%20-%20assembly.png)

![Putting drill guide on](Images/Extrusion%20drill%20jig%20-%20assembly2.png)

### Drilling the extrusion

Run at high rpm and feed the drillbit in slowly, or else it'll bite on the aluminum and you'll have a bad time! Hold the extrusion down tight.

There's no need to drill deeper than the first top flange.

![Drilling extrusion](Images/Extrusion%20-%20drill.png)

![Ensure both ends drilled](Images/Extrusion%20-%20ensure.png)

## Mounting the rail

![TNuts and Alignment](Images/Extrusion%20-%20mounting%20rails1.png)

![Screwing down](Images/Extrusion%20-%20mounting%20rails2.png)

## Disassembling stock gantry

### Taking out the gantry

Take off the toolhead + cabling

Remove the top brackets, bar, and z belt + pulleys

Pull the X gantry out the top

### Disassembling stock gantry

Remove 2 endcap covers

Remove the X belt

Undo 4 M4 screws holding the brackets to the beam

Remove the M3 TNut on the new beam (from the drill jig)

Insert 4 M4 TNuts corresponding to where the bracket holes are

## Assembling the new gantry

### Putting on the beam

Loosely screw on the brackets with 4 M4x8 BHCS

Put the assembly back onto the z extrusions

Tram the gantry, adjust eccentric nuts

Tighten 3 out of the 4 accessible M4 screws

Take the gantry out again

Tighten the last M4 screw

Put the assembly back onto the z extrusions

Tram the gantry

Put back the z belts, top beam, top brackets, loosely screw the top brackets in place

Run the gantry to max height with synchonized z

Tighten the top brackets

Why all this you ask? you just perfectly trammed your gantry and made sure the z beams are parallel!

## Final assembly of the adapter

### Preparations

Install the MGN12H cart via 4 M3x6 FHCS

Insert 4 M3 Hex/Square nuts into the recesses of the belt clamp

Screw on the toolhead adapter onto the toolhead with M3x10mm FHCS

### Assembly

Slide the carriage onto the rail

Install the belt with the belt clamps with 4 M3x16mm BHCS

(Optional) Install Lamarc's chain with 2 M3x8mm FHCS

Install the toolhead




