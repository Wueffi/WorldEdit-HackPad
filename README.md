# WorldEdit Hackpad

The WorldEdit Hackpad is a 15 key macropad designed to run [WorldEdit](https://modrinth.com/plugin/worldedit) Macros inside of Minecraft. It also includes 15 WS2812B LEDs to give each Key and Keygroup a different Backlight.

## Features:
- Sleek 3D-Printed Case
- 15 Cherry MX Keys, ordered in one 3x3 and two 1x3 Keygroups
- 15 WS2812B RGB LEDs to give the keys a Backlight.
- Seeed Studio XIAO RP2040 Microcontroller

## CAD Model:
Everything holds together using 4 M3 Bolts and heatset inserts in each 4 corners of the case.

Disassembled
<img width="1920" height="1080" alt="HackPad_Disassembled" src="https://github.com/user-attachments/assets/c9add087-0641-49e8-934b-eb94f7b0348e" />

Assembled
<img width="1920" height="1080" alt="9f875656-4e49-4065-aad0-a275639147f7" src="https://github.com/user-attachments/assets/74d2f98d-b0fd-46ef-9c4c-54c0a9a48d7d" />


## PCB
Schematic
<img width="1409" height="1138" alt="image" src="https://github.com/user-attachments/assets/0024d1cc-66b7-4d56-8300-523a1ab9981a" />

PCB
<img width="1078" height="1081" alt="image" src="https://github.com/user-attachments/assets/ed81a19c-ce5f-4a9f-aa68-9ec77f9927b2" />

I have decided to not use diodes, since I want to only press one button at a time and thus not have to care about ghosting. It also is easier to wire, fit and looks more aesthetic.

## Firmware
This hackpad uses [QMK](https://qmk.fm/) firmware. The Switches are encoded in a 4x3 Matrix


## BOM:
This is everything you need to make this HackPad!

- 1x XIAO RP2040
- 15x Cherry MX Switches
- 15x Keycaps
- 15x WS2812B LEDs
- 4x M3x5x4 Heatset inserts
- 4x M3x16mm SHCS Bolts
- 1x Case (Top and Bottom parts printed)
