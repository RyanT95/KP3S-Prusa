# Kingroon KP3S 3.0 & KP3S Pro S1 Prusa Profiles
PrusaSlicer profiles for Kingroon KP3S 3.0 (Titan Extruder) & KP3S Pro S1, also includes a version for BLTouch.

![Logo](https://github.com/RyanT95/KP3S-Prusa/blob/main/_screenshots/banner.PNG)

[Image Showcase!](https://github.com/RyanT95/KP3S-Prusa/edit/main/README.md#images)

## How to use
* Download the [latest release.](https://github.com/RyanT95/KP3S-Prusa/releases/latest)

* Extract the ZIP and move the **'Kingroon.idx'** & **'Kingroon.ini'** files and the **'Kingroon'** folder to: ```<PRUSA-INSTALL-DIR>\Prusa3D\PrusaSlicer\resources\profiles```

* *'Kingroon'* should now show up in the *'Other Vendors'* section of the Configuration Wizard.

* Select this, and choose from either *'Kingroon KP3S 3.0'*, *'Kingroon KP3S BLTouch'*, *'Kingroon KP3S Pro S1'* or *'Kingroon KP3S Pro S1 BLTouch'*.

* You can select configurations for *0.2mm, 0.3mm, 0.4mm, 0.5mm & 0.6mm* nozzles.

* Select the filament profiles you want to enable from the next screen, then change any other settings and click *Finish*.

* The KP3S is now added to Prusa as a printer, I have also included a custom buildplate and bed texture with a 10mm grid to aid in object placement.

* For the KP3S 3.0, I have included an alternate bed texture that doesn't have the X and Y axis helper, and an alternate bed model & texture for the original Kingroon build plate. 
  * To use the alternate texture, change lines *34* and *53* in *'Kingroon.ini'* from ```bed_texture = kp3s.svg``` to ```bed_texture = kp3s-alt.svg```
  * To use the Kingroon texture, change lines *29* and *48* in *'Kingroon.ini'* from ```bed_model = kp3s_bed.stl``` to ```bed_model = kp3s_bed_original.stl```, and lines *34* and *53* from ```bed_texture = kp3s.svg``` to ```bed_texture = kp3s-original.svg```
  
  ![Logo](https://github.com/RyanT95/KP3S-Prusa/blob/main/_screenshots/5.PNG)

## How to update
* Extract the ZIP and move the **'Kingroon.idx'** & **'Kingroon.ini'** files and the **'Kingroon'** folder to: ```<PRUSA-INSTALL-DIR>\Prusa3D\PrusaSlicer\resources\profiles```

* Open PrusaSlicer, go to 'Configuration' and click 'Check for Configuration Updates'.
![Logo](https://github.com/RyanT95/KP3S-Prusa/blob/main/_screenshots/4.PNG)

## Firmware
I have only tested these profiles with Marlin firmware, but they should still work with the stock firmware.

If you are still running stock firmware, I *strongly* suggest upgrading to Marlin, as the stock firmware isn't that great.

* A link to the Marlin firmware for KP3S can be found [here.](https://github.com/bdwilson/KP3S)

* A guide to installing the firmware can be found [here.](https://kingroon.com/blogs/3d-print-101/how-to-set-up-marlin-firmware-for-the-kingroon-kp3s-3d-printer)


## Profile Information

### Kingroon KP3S 3.0
* Vendor: Kingroon
* Extruder: Titan Direct Drive
* Nozzles: 0.2mm, 0.3mm, 0.4mm, 0.5mm & 0.6mm
* Print Profiles:
  * 0.06mm ULTRADETAIL	*(0.2mm nozzle only)*
  * 0.08mm SUPERDETAIL	*(0.2mm & 0.3mm nozzles only)*
  * 0.10mm HIGHDETAIL	*(0.2mm, 0.3mm & 0.4mm nozzles only)*
  * 0.12mm DETAIL		*(0.2mm, 0.3mm, 0.4mm & 0.5mm nozzles only)*
  * 0.16mm OPTIMAL
  * 0.20mm NORMAL		*(0.3mm, 0.4mm, 0.5mm & 0.6mm nozzles only)*
  * 0.24mm DRAFT		*(0.4mm, 0.5mm & 0.6mm nozzles only)*
  * 0.28mm SUPERDRAFT	*(0.4mm, 0.5mm & 0.6mm nozzles only)*
  * 0.36mm CHUNKY		*(0.5mm & 0.6mm nozzles only)*
  * 0.44mm SUPERCHUNKY	*(0.6mm nozzle only)*
* Print Speeds:
  * STANDARD
  * SPEED
  * HIGH SPEED
  * SUPER SPEED
* Upgrades: None
* Firmware: Stock / Marlin 2.1.1

### Kingroon KP3S BLTouch
* Vendor: Kingroon
* Extruder: Titan Direct Drive
* Nozzles: 0.2mm, 0.3mm, 0.4mm, 0.5mm & 0.6mm
* Print Profiles:
  * 0.06mm ULTRADETAIL	*(0.2mm nozzle only)*
  * 0.08mm SUPERDETAIL	*(0.2mm & 0.3mm nozzles only)*
  * 0.10mm HIGHDETAIL	*(0.2mm, 0.3mm & 0.4mm nozzles only)*
  * 0.12mm DETAIL		*(0.2mm, 0.3mm, 0.4mm & 0.5mm nozzles only)*
  * 0.16mm OPTIMAL
  * 0.20mm NORMAL		*(0.3mm, 0.4mm, 0.5mm & 0.6mm nozzles only)*
  * 0.24mm DRAFT		*(0.4mm, 0.5mm & 0.6mm nozzles only)*
  * 0.28mm SUPERDRAFT	*(0.4mm, 0.5mm & 0.6mm nozzles only)*
  * 0.36mm CHUNKY		*(0.5mm & 0.6mm nozzles only)*
  * 0.44mm SUPERCHUNKY	*(0.6mm nozzle only)*
* Print Speeds:
  * STANDARD
  * SPEED
  * HIGH SPEED
  * SUPER SPEED
* Upgrades: BLTouch auto bed leveling sensor
* Firmware: Stock / Marlin 2.1.1

### Kingroon KP3S Pro S1
* Vendor: Kingroon
* Extruder: Titan Direct Drive
* Nozzles: 0.3mm, 0.4mm, 0.5mm & 0.6mm
* Print Profiles:
  * 0.06mm ULTRADETAIL	*(0.2mm nozzle only)*
  * 0.08mm SUPERDETAIL	*(0.2mm & 0.3mm nozzles only)*
  * 0.10mm HIGHDETAIL	*(0.2mm, 0.3mm & 0.4mm nozzles only)*
  * 0.12mm DETAIL		*(0.2mm, 0.3mm, 0.4mm & 0.5mm nozzles only)*
  * 0.16mm OPTIMAL
  * 0.20mm NORMAL		*(0.3mm, 0.4mm, 0.5mm & 0.6mm nozzles only)*
  * 0.24mm DRAFT		*(0.4mm, 0.5mm & 0.6mm nozzles only)*
  * 0.28mm SUPERDRAFT	*(0.4mm, 0.5mm & 0.6mm nozzles only)*
  * 0.36mm CHUNKY		*(0.5mm & 0.6mm nozzles only)*
  * 0.44mm SUPERCHUNKY	*(0.6mm nozzle only)*
* Print Speeds:
  * STANDARD
  * SPEED
  * HIGH SPEED
  * SUPER SPEED
* Upgrades: None
* Firmware: Stock / Marlin 2.1.1

### Kingroon KP3S Pro S1 BLTouch
* Vendor: Kingroon
* Extruder: Titan Direct Drive
* Nozzles: 0.3mm, 0.4mm, 0.5mm & 0.6mm
* Print Profiles:
  * 0.06mm ULTRADETAIL	*(0.2mm nozzle only)*
  * 0.08mm SUPERDETAIL	*(0.2mm & 0.3mm nozzles only)*
  * 0.10mm HIGHDETAIL	*(0.2mm, 0.3mm & 0.4mm nozzles only)*
  * 0.12mm DETAIL		*(0.2mm, 0.3mm, 0.4mm & 0.5mm nozzles only)*
  * 0.16mm OPTIMAL
  * 0.20mm NORMAL		*(0.3mm, 0.4mm, 0.5mm & 0.6mm nozzles only)*
  * 0.24mm DRAFT		*(0.4mm, 0.5mm & 0.6mm nozzles only)*
  * 0.28mm SUPERDRAFT	*(0.4mm, 0.5mm & 0.6mm nozzles only)*
  * 0.36mm CHUNKY		*(0.5mm & 0.6mm nozzles only)*
  * 0.44mm SUPERCHUNKY	*(0.6mm nozzle only)*
* Print Speeds:
  * STANDARD
  * SPEED
  * HIGH SPEED
  * SUPER SPEED
* Upgrades: BLTouch auto bed leveling sensor
* Firmware: Stock / Marlin 2.1.1


## Images
#### KP3S - Original
![Logo](https://github.com/RyanT95/KP3S-Prusa/blob/main/_screenshots/kp3s-original.PNG)

#### KP3S - Default
![Logo](https://github.com/RyanT95/KP3S-Prusa/blob/main/_screenshots/kp3s.PNG)

#### KP3S - Alternate 1
![Logo](https://github.com/RyanT95/KP3S-Prusa/blob/main/_screenshots/kp3s-alt1.PNG)

#### KP3S - Alternate 2
![Logo](https://github.com/RyanT95/KP3S-Prusa/blob/main/_screenshots/kp3s-alt2.PNG)

#### KP3S - Alternate 3
![Logo](https://github.com/RyanT95/KP3S-Prusa/blob/main/_screenshots/kp3s-alt3.PNG)

#### Pro S1 - Default
![Logo](https://github.com/RyanT95/KP3S-Prusa/blob/main/_screenshots/kp3spros1.PNG)

#### Pro S1 - Alternate 1
![Logo](https://github.com/RyanT95/KP3S-Prusa/blob/main/_screenshots/kp3spros1-alt1.PNG)


## License
This work is licensed under a Creative Commons Attribution-NonCommercial 4.0 International License - see the [LICENSE.md](https://github.com/RyanT95/KP3S-Prusa/blob/main/LICENSE) file for details.
