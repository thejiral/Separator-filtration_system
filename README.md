# SEPARATOR - Activated charcoal air purification system for Voron 2.4

![Full_installation](https://github.com/thejiral/Separator-filtration_system/assets/62755624/00366042-8d77-4483-a73f-eb24123f4942)


# Introduction

This is my total remix of The_Filter (https://github.com/nateb16/VoronUsers/tree/master/printer_mods/nateb16/THE_FILTER), following the same general principle but designed from scratch with a number of smaller and larger differences to it.

The key features, which sets "The_Filter" apart from the Nevermore are kept in place: reversing the airflow so that air is not blown directly at the weak link of the enclosure (the door) and a design for 4 blowers to improve ventillation below the heatbed, for better and faster heating of the enclosure.

The following aspects however differ from "The_Filter": 

* The blowers are fully embedded in a dampening EPDM layer. Vibration noise is a major component of fan noise, especially for blowers. This substantially reduces the transmission of vibrations into the filter body. 
* Inlet and outlet mesh of the filter module is as slim as possible with the least air resistance in mind, while containing the activated charcoal pellets (diameter: >4 mm) and featuring the needed stability. 
* The filtration cassette is from one piece and (re-)filled vertically. This enables filling with smaller air gap at the top.
* The filtration cassette is gap free, except for the outlet and the interface to the blowers, which is sealed by EPDM, to maintain the positive pressure better within the cassette.
* Like "The_Filter" the "Separator" is designed in a way that blowers are removed with the cassette when refilling AC pellets. "The_Filter" offers the two options of either an Ali-Express magentic connector, which can be harmfull to the board however, or just long cables, possible with a regular connector. This is safer but messier and less comfortable. The "Separator" has an entirely different connector strategy, based on a modified Micro-fit 3.0 connector where the snap-lock has been removed and functionally replaced by magnets, which are only used for keeping the connector in place, not for transmitting electricity. 


# BOM

Needed parts for a full setup with one central "dual"-module and a "single-left" as well as a "single-right" module.

* 4x 5015 high performance blower (24V), for example https://en.kris3d.de/products/gdstime-gdb5015-50x50x15mm-blower-fan?_pos=3&_sid=fd8a2629a&_ss=r
* 3x MOLEX Microfit 3.0 connector part Nr. 0430200201 (https://www.digikey.at/de/products/detail/molex/0430200201/1132437)
* 3x MOLEX Microfit 3.0 connector part Nr. 0430250208 (https://www.digikey.at/de/products/detail/molex/0430250208/4247397)
* 6x MOLEX crimping contacts part Nr. 0430300008 (add some spares, according to your crimping skills) (https://www.digikey.at/de/products/detail/molex/0430300008/1132448)
* 6x MOLEX crimping contacts part Nr. 0430310008 (add some spares, according to your crimping skills) (https://www.digikey.at/de/products/detail/molex/0430310008/1132450)
* 14x magnets (6mm diameter, depth: 3 mm) preferably of the strongest type N52 (https://en.kris3d.de/products/5x-neodym-zylindermagnet-6x3mm-n52?_pos=1&_sid=f31803bf3&_ss=r)
a few meters of >0.25 mm2 cable for cable management, preferably Heluflon or equivalent due to the very high heat resistance
* 13x M3x6mm countersunk head cap screws DIN7991
* 18x M3x6mm button head screws ISO 7380-1
* 6x M2x4mm button head screws ISO7380-1 (compatible hex-key (1.27mm or 0.05"): https://www.digikey.at/de/products/detail/wiha/66945/511457))
* 31x M3 Voron style heat inserts (M3x5x4) (https://www.kris3d.de/products/heatinserts-m3x5x4?_pos=1&_sid=886fd1c22&_ss=r)
* 6x M2 heat inserts (https://cnckitchen.store/products/gewindeeinsatz-threaded-insert-m2-standard-100-stk-pcs)
a few meters of 2mm thick and 10 mm wide EPDM tape or similar (for example: https://www.fugendichtband24.de/EPDM-Zellkautschuk-einseitig-selbstklebend-10m-Rolle-2mm-x-diverse-Breiten.htm)
* 6xM3 t-nut
* activated charcoal, suitable for air purification, a safe bet is the nevermore material (https://www.kris3d.de/products/nevermore-xl-bag?_pos=2&_sid=f7ffb3feb&_ss=r), alternatively source equivalent material from a respectable source.

Optional:
* 2x WAGO 221-2401 (https://www.digikey.at/de/products/detail/wago-corporation/221-2401/16284533)


# Assembly

Prepare MOLEX Micro-fit 3.0 connectors by removing the snap connection points with a cutter, so that the surface is flush afterwards, as shown in the below before and after image:

![microfit-modification](https://github.com/thejiral/Separator-filtration_system/assets/62755624/4b3ffcca-e1b7-49d7-8b20-1bed130a67ff)

Test assemble the Microfit 3.0 connectors as shown in the two following images. Be careful of the precise orientation.

![PartB-microfit_orientation](https://github.com/thejiral/Separator-filtration_system/assets/62755624/c0bba41e-f407-4de7-a276-bb98c74003ae)

![PartA-micorfit_orientation](https://github.com/thejiral/Separator-filtration_system/assets/62755624/8120119f-c552-4c31-a1f6-9076cc177c68)

Test the connection of both parts, they should easily slide into each other. If they don't one of the connectors is either upside down or there is some printing artifact which needs to be cleared by cutter. The connection should look like this: 

![microfit-connection-testfit](https://github.com/thejiral/Separator-filtration_system/assets/62755624/0e051a12-e469-4881-89b1-1167154d1c1c)

Disassemble the connectors and remove the micro-fit 3.0 plugs from the printed parts again. 

Install the bottom mesh in partA by sliding it in while keeping it tilted until the intentation in the filter body, press the mesh then past the holding protrusions. Use some Hexkey if your fingers don't make it as far. Check if the mesh is fully clipped in as seen here:

![Meshinsert](https://github.com/thejiral/Separator-filtration_system/assets/62755624/fd99f50d-7af2-4311-bb3e-fd61a32a6a52)

Add M3 heat inserts to the back of partA. 

![PartA-heatinserts](https://github.com/thejiral/Separator-filtration_system/assets/62755624/68e92178-643f-4388-a1da-3b57399fa0d0)

Screw together PartA and PartC with 4 M3x6 button head screws. 

![PartA+C_assembly](https://github.com/thejiral/Separator-filtration_system/assets/62755624/687874d8-2432-4e53-bc5f-f2e97afba82a)

Apply EPDM tape (thickness: 2mm) as shown. The blower inlet is prepared with EPDM tape on all sides, make sure that on the other side, those strips only reach as far as the opening and not further. 

![PartA+C_EPDM](https://github.com/thejiral/Separator-filtration_system/assets/62755624/4a482e1f-2ce8-4515-a05e-1462455c236b)

Add M3 heat inserts and EPDM tape to partD as shown. Cut the 10 mm tape in half to a width of 5 mm and apply it ring shaped around the opening. Along the vertical wall apply the 10 mm tape centrally.

![partD-heatinserts+EPDM](https://github.com/thejiral/Separator-filtration_system/assets/62755624/ff8793ec-f17c-4f55-847e-3b377118fdab)

Insert the blower in PartD by wiggling it in, make sure not to push the tape down and direct the cable to the opening. 

![PartD+blower+cablemanagement](https://github.com/thejiral/Separator-filtration_system/assets/62755624/212a4d9f-24d6-4585-8319-989fb36548fc)

Combine partA+C and partD. Make sure not to clamp in cable or other parts or cause some EPDM tape overlap. There should be only slight backpressure when screwing it together. Keep both parts together with one hand and fasten 3Mx6mm countersunk head cap screws with the other hand. The cable has to be lead through the opening on the side and has to be routed to the front where the connector will be located. Insert the 6 mm magnets into the holes after making sure that there are no bulges from the heatsets or other artifacts blocking the opening. Test fit the magnet and see if it fully goes in. If it holds by itself, fine, if not use a tiny drop of superglue at the bottom to glue the magnet in place. When inserting magnets make sure that the counterpart is inserted in the right direction, that it attracts the other magnet.

![Full_assembly-magnets+cablemanagement](https://github.com/thejiral/Separator-filtration_system/assets/62755624/8795b6d1-7762-4bdb-904f-95841f553d67)

Shorten the cables as needed, crimp them, assemble the connector and insert it in place. 

Repeat the assembly for all modules and fill the filter with active carbon. The filter cassette is closed by sliding a mesh in place at the end of the module. 

![middle-module-full_assembly](https://github.com/thejiral/Separator-filtration_system/assets/62755624/dad6a8ce-c682-4781-baa3-e8287f24bcd9)




#Installing modules in a Voron 2.4

Add M2 heat inserts to the profile magnet holders. There are two different versions in the STL folder. Use the flush ones. For the dual module in the center one can use the "+1mm" magnet holder on the right side if there is too much play with the dual module between both profiles.

![magnetholder-heatinserts](https://github.com/thejiral/Separator-filtration_system/assets/62755624/d586e65b-87fc-451a-9bf1-51008e5471ad)

Turn around the magnet holder and check if plastic debris is blocking the heat insert. If so clear it with a fine cutter knife.

![magnetholder-heatinserts-front](https://github.com/thejiral/Separator-filtration_system/assets/62755624/24f6f29a-c5fa-4244-a2f8-2aec626ec8d9)

Insert a 6mm magnet in the central hole and make sure it is point the right way so that it attracts the counterpart on the respective module. 

The maget holders are then installed in the profile by first pushing in the side parts and in between the magnet holder as shown in the image below: 

![profile-magnet0](https://github.com/thejiral/Separator-filtration_system/assets/62755624/1ddf7919-5be3-42ab-8c7e-d748f51836f2)

Subsequently move the 3 parts together and to the very front. Add M2 button head screws and fasten the screws just enough to fix the maget holder in place. Don't overtighten. 

![profile-magnet1](https://github.com/thejiral/Separator-filtration_system/assets/62755624/9694269e-e8f2-42db-b396-fbc2d56b2b36)

Assemble partB. Crimp the Microfit connector and insert it in part B. Add the magnet in the central hole. Make sure it is oriented the correct way. 

One magnet holder goes into each side of both bed profiles on the front side, four in total. Test install each module. When a module is pulled in place by the profile magnet it is time to install part B at the profile. Two M3 T-nuts are inserted (with the two wholes close to each other), loosely screw partB to the T-nuts and move it forward to the module until the microfit connnection is closed. Fasten partB in the orientation where the connection is aligned. 

Optional: 2 WAGO clamps can be mounted sideways with the WAGO clamp mount and the 3 positive cables go to one clamp and the 3 negative cables to the other clamp. The other side is connected to a 24V fan control pin or the 24V hotendheater outlet. 


Final assembly with a left and right single module and a dual module:

![Final-assembly](https://github.com/thejiral/Separator-filtration_system/assets/62755624/b78d6265-5532-42d7-8d36-78bdf5108e7d)



