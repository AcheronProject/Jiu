# Jiu PCB

![alt text](https://raw.githubusercontent.com/Gondolindrim/acheronLibrary/master/graphics/acheronReadme.png "Acheron Logo")

*Jiu* is a replacement PCB for the Kyuu keyboard by Quantrik. The name is a reference to the original name as *Kyuu* is the word for the algarism nine in japanese and *Jiu* expresses the same algarism in chinese.

Jiu runs with an STM32F072CxT MCU, and is QMK and VIA compatible.

## Technical information

- Layout size: 65% 2ith blocker
- Compatible switches: MX-like only, solderable
- Lighting: none
- Microcontroller: STM32F072CxT6 (x can be either 8 or B)
- Connector: centered USB Type C
- Firmware compatibility: QMK (with VIA support)
- Protection hardware:
  * USB data lines and power rail ESD suppressing
  * USB power overvoltage protection
  * Overcurrent protection
  * LDO crowbar diode
  * EMI suppression (shielding ferrite bead)
- Current release: pre-release Alpha (has not been prototyped yet)
- Designer: Gondolindrim
- License: Creative Commons 4.0 BY-NC-SA

## Keyboard compatibility

This PCB is designed to fit, therefore is compatible only with, the Kyuu keyboard and its clones.

## Licensing and disclaimer

The original PCB files of the Kyuu were made available by Quantrik (the designer of the Kyuu keyboard) himself in [a GitHub page](https://github.com/Quantrik/Kyuu). Refer to the licensing of the original files for clarification as to how to use them.

I (Gondolindrim) hold no power over nor ownership of the original files. I am just using them to design an improved version of the PCB; the license used for the modified version is the same as the license used for the files provided by Quantrik. See the **License** section of this document for clarification.

The only fundamental alteration made by me to the files was a porting to a newer KiCad version, hence the different file extensions: the `.sch`, `.brd` and `.pro` files were removed as these belong to the older KiCad version and were substituted by `.kicad_pro, .kicad_sch` and `.kicad_pcb` files. I also removed non-essential files like the`gerbers` folder (which will be released later when Jiu's final version is done), the `rescue-backups`folder (since it is redundant). Apart from these modifications, and abiding by the original license, the files are made available in the same level of abstraction as the original work. Final production files will be released in the *Release* section of the Jiu GitHub page.

## License

These files are licensed under the Creative Commons 4.0 Attribution Non-Commercial Share-Alike license. The modifications made further are licensed under the same license, which is available in the LICENSE.md file in this folder.

It is of utmost importance to note that the Jiu files are not released under the Acheron Open-Source Hardware license that is generally used for Acheron Project PCBs. This is because while AOHL is a commercial license, Kyu's original PCB files were licensed under a non-commercial copyleft license, meaning they are incompatible with AOHL. Be very weary of this because it makes both Kyu's original PCB and Jiu's PCB files unfit for profit.

## Prototype pictures

Prototypes for [version v1.1.8/v1.1.8](https://github.com/AcheronProject/Jiu/releases/tag/v1.1.8%2Fv1.1.8), kindly tested and paid for by user jubei.

![Jiu prototype picture 1](https://raw.githubusercontent.com/Gondolindrim/file_hosting/main/jiu_prototype_pictures/AL8U0zt.jpg)
![Jiu prototype picture 2](https://raw.githubusercontent.com/Gondolindrim/file_hosting/main/jiu_prototype_pictures/bhfUoML.jpg)
![Jiu prototype picture 3](https://raw.githubusercontent.com/Gondolindrim/file_hosting/main/jiu_prototype_pictures/cRJ9OSM.jpg)
![Jiu prototype picture 4](https://raw.githubusercontent.com/Gondolindrim/file_hosting/main/jiu_prototype_pictures/ewgsies.jpg)
![Jiu prototype picture 5](https://raw.githubusercontent.com/Gondolindrim/file_hosting/main/jiu_prototype_pictures/gyAFn1C.jpg)
![Jiu prototype picture 6](https://raw.githubusercontent.com/Gondolindrim/file_hosting/main/jiu_prototype_pictures/rcSDpcL.jpg)
