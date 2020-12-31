# Vector Hysteresis Distortion

These are the KiCAD schematics and board layout filed for my Vector Hysteresis Distortion pedal.  
If you just want the Gerber files or a PDF of the schematic check out the releases tab for downloads.

This PCB should be easily manufacturable with most online PCB houses by just uploading the gerber files.

This board is designed to be used with my Switchboard Pedal IO PCB which you can find [here](https://github.com/NuclearLighthouseStudios/Switchboard).

## BOM

| Reference      | Quantity | Value  | Description                                          |
| :------------- | -------: | -----: | :--------------------------------------------------- |
| C1 C3 C5 C6 C7 | 5        | 100n   | WIMA MKS2 63V                                        |
| C2 C8          | 2        | 1µ     | WIMA MKS2 50V                                        |
| C4             | 1        | 470n   | WIMA MKS2 50V                                        |
| D1 D2          | 2        | 1N4148 | DO-35 Diode                                          |
| J1             | 1        |        | Pin Header, 6 pins, 2.54mm spacing                   |
| J2             | 1        |        | DC Barrel Jack with internal switch                  |
| Q1 Q2 Q3 Q4    | 4        | BC547B | 0.1A Ic, 45V Vce, Small Signal NPN Transistor, TO-92 |
| R1 R2 R5 R13   | 4        | 1M     | Metal film resistor 1%, DIN 0207                     |
| R10            | 1        | 470k   | Metal film resistor 1%, DIN 0207                     |
| R11            | 1        | 22k    | Metal film resistor 1%, DIN 0207                     |
| R12            | 1        | 100k   | Metal film resistor 1%, DIN 0207                     |
| R15            | 1        | 39k    | Metal film resistor 1%, DIN 0207                     |
| R3 R14         | 2        | 10k    | Metal film resistor 1%, DIN 0207                     |
| R4 R7 R8 R9    | 4        | 100k   | Metal film resistor 1%, DIN 0207                     |
| R6             | 1        | 470k   | Metal film resistor 1%, DIN 0207                     |
| RV1 RV2        | 2        | 100k   | Alps RK09K1130C94 Potentiometer                      |
