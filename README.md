
# Overview

This is a list I made myself of the electrolytics capacitors from Super Nintendo / Famicom motherboards.
It includes all the specs from the original boards, in order to find exact modern replacements.

This only contains lists for the boards I had on my desk.


Pitch means lead spacing for radial caps (through-hole).

# Super Famicom (NTSC)

## SHVC-CPU-01

| Marking | Capacitance | Voltage | Type   | Diameter | Pitch | Note             |
|---------|-------------|---------|--------|----------|-------|------------------|
| C50     | 47µF        | 10V     | Radial | 6.3mm    | 5mm   | For sound module |
| C51     | 47µF        | 10V     | Radial | 6.3mm    | 5mm   | For sound module |
| C57     | 100µF       | 6V      | SMT    | 6.3mm    |       |                  |
| C58     | 100µF       | 6V      | SMT    | 6.3mm    |       |                  |
| C59     | 100µF       | 6V      | SMT    | 6.3mm    |       |                  |
| C60     | 100µF       | 6V      | SMT    | 6.3mm    |       |                  |
| C61     | 10µF        | 16V     | SMT    | 4.0mm    |       |                  |
| C62     | 2.2µF       | 50V     | SMT    | 4.0mm    |       |                  |
| C63     | 33µF        | 25V     | SMT    | 6.3mm    |       |                  |
| C64     | 33µF        | 25V     | SMT    | 6.3mm    |       |                  |
| C65     | 10µF        | 16V     | SMT    | 4.0mm    |       |                  |
| C66     | 10µF        | 16V     | SMT    | 4.0mm    |       |                  |
| C67     | 1000µF      | 25V     | Radial | 13mm     | 5mm   | 25mm tall        |


Sample replacement list

| Manufacturer  | Reference        | Quantity | Capacitance | Voltage | Type    | Diameter | Pitch |
|---------------|------------------|----------|-------------|---------|---------|----------|-------|
| Panasonic     | EEEFP1C101AP     | 4        | 100µF       | 6V      | SMT     | 6.3mm    |       |
| Panasonic     | EEEFK1E100R      | 3        | 10µF        | 16V     | SMT     | 4.0mm    |       |
| Panasonic     | EEE1HA2R2SR      | 1        | 2.2µF       | 50V     | SMT     | 4.0mm    |       |
| Panasonic     | EEEFC1E330P      | 2        | 33µF        | 25V     | SMT     | 6.3mm    |       |
| Panasonic     | EEUFC1V470       | 2        | 47µF        | 10V     | Radial  | 6.3mm    | 2.5mm |
| Multicomp pro | MCRH25V108M13X21 | 1        | 1000µF      | 25V     | Radial  | 13mm     | 5mm   |

**Note:** Need to recheck pitch for C50/C51


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

- Recheck pitch for C50/C51 on SHVC-CPU-01 sound modules
- Add parts list for other boards
- Add a way to directly import a list of suitable replacements on Farnell/Digikey/Mouser
