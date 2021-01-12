# Jiu PCB

*Jiu* is a replacement PCB for the Kyuu keyboard by Quantrik. The name is a reference to the original name as *Kyuu* is the word for the algarism nine in japanese and *Jiu* expresses the same algarism in chinese.

Jiu runs with an STM32F072CxT MCU, and is QMK and VIA compatible.

## Licensing and disclaimer

These files were made available by Quantrik (the designer of the Kyuu keyboard) himself in [a GitHub page](https://github.com/Quantrik/Kyuu). Refer to the licensing of the original files for clarification as to how to use them.

I (Gondolindrim) hold no power over nor ownership of the original files. I am just using them to design an improved version of the PCB; the license used for the modified version is the same as the license used for the files provided by Quantrik. See the **License** section of this document for clarification.

The only fundamental alteration made by me to the files was a porting to a newer KiCad version, hence the different file extensions. I also removed non-essential files like the `gerbers` folder (which will be released later when Yuuk's final version is done), the `rescue-backups` folder (since it is redundant), the `.sch`, `.brd` and `.pro` files as these belong to the older KiCad version. Apart from these modifications, and abiding by the original license, the files are made available in the same level of abstraction as the original work. Final production files will be released in the *release* section of the Jiu GitHub page.

## License

These files are licensed under the Creative Commons 4.0 Attribution Non-Commercial Share-Alike license. The modifications made further are licensed under the same license, which is available in the `LICENSE.md` file in this folder.
