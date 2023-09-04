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
* activated charcoal, suitable for air purification, a safe bet is the nevermore material (https://www.kris3d.de/products/nevermore-xl-bag?_pos=2&_sid=f7ffb3feb&_ss=r), alternatively source equivalent material from a respectable source.

Optional:
* 2x WAGO 221-2401 (https://www.digikey.at/de/products/detail/wago-corporation/221-2401/16284533)


# Assembly

Prepare MOLEX Micro-fit 3.0 connectors by removing the snap connection points as shown in the below before and after image:

https://github.com/thejiral/Separator-filtration_system/blob/main/images/microfit-modification.png





