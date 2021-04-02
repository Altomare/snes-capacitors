
# Overview

This is a list I made myself of the electrolytics capacitors from Super Nintendo / Famicom motherboards.
It includes all the specs from the original boards, in order to find exact modern replacements.

This only contains lists for the boards I had on my desk.


# Super Famicom (NTSC)

## SHVC-CPU-01

| Marking | Capacitance | Voltage | Type         | Diameter | Pitch | Note             |
|---------|-------------|---------|--------------|----------|-------|------------------|
| C50     | 47uf        | 10v     | Through hole | 6.3mm    | 5mm   | For sound module |
| C51     | 47uf        | 10v     | Through hole | 6.3mm    | 5mm   | For sound module |
| C57     | 100uf       | 6v      | SMT          | 6.3mm    |       |                  |
| C58     | 100uf       | 6v      | SMT          | 6.3mm    |       |                  |
| C59     | 100uf       | 6v      | SMT          | 6.3mm    |       |                  |
| C60     | 100uf       | 6v      | SMT          | 6.3mm    |       |                  |
| C61     | 10uf        | 16v     | SMT          | 4.0mm    |       |                  |
| C62     | 2.2uf       | 50v     | SMT          | 4.0mm    |       |                  |
| C63     | 33uf        | 25v     | SMT          | 6.3mm    |       |                  |
| C64     | 33uf        | 25v     | SMT          | 6.3mm    |       |                  |
| C65     | 10uf        | 16v     | SMT          | 4.0mm    |       |                  |
| C66     | 10uf        | 16v     | SMT          | 4.0mm    |       |                  |
| C67     | 1000uf      | 25v     | Through hole | 13mm     | 5mm   | 25mm tall        |


## SNS-CPU-GPM-02

| Marking | Capacitance | Voltage | Type         | Diameter | Pitch | Note      |
|---------|-------------|---------|--------------|----------|-------|-----------|
| C57     | 220uf       | 6.3v    | Through hole | 6.604mm  | 2.5mm |           |
| C59     | 220uf       | 6.3v    | Through hole | 6.604mm  | 2.5mm |           |
| C61     | 10uf        | 16v     | SMT          | 4.0mm    |       |           |
| C62     | 2.2uf       | 50v     | SMT          | 4.0mm    |       |           |
| C63     | 33uf        | 25v     | SMT          | 6.3mm    |       |           |
| C64     | 33uf        | 25v     | SMT          | 6.3mm    |       |           |
| C65     | 10uf        | 16v     | SMT          | 4.0mm    |       |           |
| C66     | 10uf        | 16v     | SMT          | 4.0mm    |       |           |
| C67     | 1000uf      | 25v     | Through hole | 13mm     | 5mm   | 25mm tall |
| C73     | 47uf        | 16v     | SMT          | 6.3mm    |       |           |


# Super Nintendo (PAL)

## SNSP-CPU-01

| Marking | Capacitance | Voltage | Type         | Diameter | Pitch | Note                         |
|---------|-------------|---------|--------------|----------|-------|------------------------------|
| C59     | 10uF        | 25v     | SMT          | 6.3mm    |       | Should be updated to bipolar |
| C60     | 10uF        | 50v     | SMT          | 6.3mm    |       |                              |
| C61     | 10uF        | 50v     | SMT          | 6.3mm    |       |                              |
| C62     | 2.2uF       | 50v     | SMT          | 4.0mm    |       |                              |
| C63     | 33uF        | 25v     | SMT          | 6.3mm    |       |                              |
| C64     | 33uF        | 25v     | SMT          | 6.3mm    |       |                              |
| C65     | 10uF        | 50v     | SMT          | 6.3mm    |       |                              |
| C66     | 10uF        | 50v     | SMT          | 6.3mm    |       |                              |
| C67     | 2200uF      | 25V     | Through hole | 16mm     | 7.5mm | 25mm tall                    |
| C73     | 47uF        | 16v     | SMT          | 6.3mm    |       |                              |

**Note:**
The C59 issue was known to Nintendo and was adressed in the SNSP-CPU-02 revision.
Some consoles have been fixed by Nintendo and had their C59 replaced with a bipolar one.
These fixed consoles usually have a small circular "C59" sticker on their underside.


## SNSP-CPU-02

| Marking | Capacitance | Voltage | Type         | Diameter | Pitch        | Note                         |
|---------|-------------|---------|--------------|----------|--------------|------------------------------|
| C59     | 10uF        | 25V     | SMT          | 6.3mm    |              | Bipolar                      |
| C60     | 10uF        | 50V     | SMT          | 6.3mm    |              |                              |
| C61     | 10uF        | 50V     | SMT          | 6.3mm    |              |                              |
| C62     | 2.2uF       | 50V     | SMT          | 4.0mm    |              |                              |
| C63     | 33uF        | 25V     | SMT          | 6.3mm    |              |                              |
| C64     | 33uF        | 25V     | SMT          | 6.3mm    |              |                              |
| C65     | 10uF        | 50V     | SMT          | 6.3mm    |              |                              |
| C66     | 10uF        | 50V     | SMT          | 6.3mm    |              |                              |
| C67     | 2200uF      | 25V     | Through hole | 13mm     | 5mm or 7.5mm | 25mm tall                    |
| C73     | 47uF        | 16V     | SMT          | 6.3mm    |              |                              |

**Note:** multiple holes are present on the PCB for C67



# Useful links

Some useful links if you plan on restoring your SNES/SFC:
- https://www.retrorgb.com/restoring-a-super-nintendo.html



# TODO

- Add a way to directly import a list of suitable replacements on Farnell/Digikey/Mouser
