
# Overview

This is a list I made for myself of the electrolytics capacitors from Super Nintendo / Famicom motherboards.
It includes all the specs from the original boards, in order to find exact modern replacements.

This only contains lists for the boards I repaired myself.


Pitch means lead spacing for radial leaded caps (through-hole).


The capacitor_bom.xls contains a list of modern replacements for some of the boards.
It can be imported on major resellers websites like Farnell, Digikey, Mouser...

At the moment, it only contains a BOM for the SHVC-CPU-01 boards.


# Super Famicom (NTSC)

## SHVC-CPU-01

| Marking | Capacitance | Voltage | Type   | Diameter | Pitch | Note      |
|---------|-------------|---------|--------|----------|-------|-----------|
| C50     | 47µF        | 10V     | Radial | 6.3mm    | 5mm   | See below |
| C51     | 47µF        | 10V     | Radial | 6.3mm    | 5mm   | See below |
| C57     | 100µF       | 6V      | SMT    | 6.3mm    |       |           |
| C58     | 100µF       | 6V      | SMT    | 6.3mm    |       |           |
| C59     | 100µF       | 6V      | SMT    | 6.3mm    |       |           |
| C60     | 100µF       | 6V      | SMT    | 6.3mm    |       |           |
| C61     | 10µF        | 16V     | SMT    | 4.0mm    |       |           |
| C62     | 2.2µF       | 50V     | SMT    | 4.0mm    |       |           |
| C63     | 33µF        | 25V     | SMT    | 6.3mm    |       |           |
| C64     | 33µF        | 25V     | SMT    | 6.3mm    |       |           |
| C65     | 10µF        | 16V     | SMT    | 4.0mm    |       |           |
| C66     | 10µF        | 16V     | SMT    | 4.0mm    |       |           |
| C67     | 1000µF      | 25V     | Radial | 13mm     | 5mm   | 25mm tall |

Notes for C50 and C51:
 - These caps are in the sound module (SHVC-SOUND)
 - Maximum height from board to shield is 8mm
 - Original caps were ~5mm tall
 - Board pitch is 5mm, but original caps had 2mm pitch with bent legs


## SNS-CPU-GPM-02

| Marking | Capacitance | Voltage | Type   | Diameter | Pitch | Note      |
|---------|-------------|---------|--------|----------|-------|-----------|
| C57     | 220µF       | 6.3V    | Radial | 6.604mm  | 2.5mm |           |
| C59     | 220µF       | 6.3V    | Radial | 6.604mm  | 2.5mm |           |
| C61     | 10µF        | 16V     | SMT    | 4.0mm    |       |           |
| C62     | 2.2µF       | 50V     | SMT    | 4.0mm    |       |           |
| C63     | 33µF        | 25V     | SMT    | 6.3mm    |       |           |
| C64     | 33µF        | 25V     | SMT    | 6.3mm    |       |           |
| C65     | 10µF        | 16V     | SMT    | 4.0mm    |       |           |
| C66     | 10µF        | 16V     | SMT    | 4.0mm    |       |           |
| C67     | 1000µF      | 25V     | Radial | 13mm     | 5mm   | 25mm tall |
| C73     | 47µF        | 16V     | SMT    | 6.3mm    |       |           |


# Super Nintendo (PAL)

## SNSP-CPU-01

| Marking | Capacitance | Voltage | Type   | Diameter | Pitch | Note                         |
|---------|-------------|---------|--------|----------|-------|------------------------------|
| C59     | 10µF        | 25V     | SMT    | 6.3mm    |       | Should be updated to bipolar |
| C60     | 10µF        | 50V     | SMT    | 6.3mm    |       |                              |
| C61     | 10µF        | 50V     | SMT    | 6.3mm    |       |                              |
| C62     | 2.2µF       | 50V     | SMT    | 4.0mm    |       |                              |
| C63     | 33µF        | 25V     | SMT    | 6.3mm    |       |                              |
| C64     | 33µF        | 25V     | SMT    | 6.3mm    |       |                              |
| C65     | 10µF        | 50V     | SMT    | 6.3mm    |       |                              |
| C66     | 10µF        | 50V     | SMT    | 6.3mm    |       |                              |
| C67     | 2200µF      | 25V     | Radial | 16mm     | 7.5mm | 25mm tall                    |
| C73     | 47µF        | 16V     | SMT    | 6.3mm    |       |                              |

**Note:**
The C59 issue was known to Nintendo and was adressed in the SNSP-CPU-02 revision.
Some consoles have been fixed by Nintendo and had their C59 replaced with a bipolar one.
These fixed consoles usually have a small circular "C59" sticker on their underside.


## SNSP-CPU-02

| Marking | Capacitance | Voltage | Type   | Diameter | Pitch        | Note                         |
|---------|-------------|---------|--------|----------|--------------|------------------------------|
| C59     | 10µF        | 25V     | SMT    | 6.3mm    |              | Bipolar                      |
| C60     | 10µF        | 50V     | SMT    | 6.3mm    |              |                              |
| C61     | 10µF        | 50V     | SMT    | 6.3mm    |              |                              |
| C62     | 2.2µF       | 50V     | SMT    | 4.0mm    |              |                              |
| C63     | 33µF        | 25V     | SMT    | 6.3mm    |              |                              |
| C64     | 33µF        | 25V     | SMT    | 6.3mm    |              |                              |
| C65     | 10µF        | 50V     | SMT    | 6.3mm    |              |                              |
| C66     | 10µF        | 50V     | SMT    | 6.3mm    |              |                              |
| C67     | 2200µF      | 25V     | Radial | 13mm     | 5mm or 7.5mm | 25mm tall                    |
| C73     | 47µF        | 16V     | SMT    | 6.3mm    |              |                              |

**Note:** multiple holes are present on the PCB for C67



# Useful links

Some useful links if you plan on restoring your SNES/SFC:
- https://www.retrorgb.com/restoring-a-super-nintendo.html



# TODO

- Extend BOM for other boards
