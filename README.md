# Kingroon KP3S 3.0 Prusa Profile
Prusa Slicer profiles for Kingroon KP3S 3.0 (Titan Extruder) includes BLTouch.

## How to use
* Place **'Kingroon.idx'**, **'Kingroon.ini'** & the **'Kingroon'** folder in: *"C:\Program Files\Prusa3D\PrusaSlicer\resources\profiles"*.

* *'Kingroon'* should now show up in the 'Other Vendors' section of the Configuration Wizard.

* Select this, and choose from either *'Kingroon KP3S 3.0'* or *'Kingroon KP3S BLTouch'*.

* You can select configurations for *0.3mm, 0.4mm, 0.5mm & 0.6mm* nozzles.

* Select the filament profiles you want to enable from the next screen, then change any other settings and click *Finish*.

* The KP3S is now added to Prusa as a printer, I have also included a custom buildplate and bed texture with a 10mm grid to aid in object placement.

* I have included an alternate bed texture that doesn't have the X and Y axis helper. 
  * To use this, change lines *23* and *32* in *'Kingroon.ini'* from ```bed_texture = kp3s.svg``` to ```bed_texture = kp3s-alt.svg```

&nbsp;

I have only tested these profiles with Marlin firmware, but they should still work with the stock firmware.

If you are still running stock firmware, I *strongly* suggest upgrading to Marlin, as the stock firmware isn't that great.

* A link to the Marlin firmware for KP3S can be found [here.](https://github.com/bdwilson/KP3S)

* A guide to installing the firmware can be found [here.](https://kingroon.com/blogs/3d-print-101/how-to-set-up-marlin-firmware-for-the-kingroon-kp3s-3d-printer)


## Profile Information

### Kingroon KP3S 3.0
* Vendor: Kingroon
* Extruder: Titan Direct Drive
* Nozzles: 0.3mm, 0.4mm, 0.5mm & 0.6mm
* Print Profiles:
  * 0.06mm ULTRADETAIL  *(0.3mm & 0.4mm nozzles only)*
  * 0.08mm SUPERDETAIL
  * 0.10mm HIGHDETAIL
  * 0.12mm DETAIL
  * 0.16mm OPTIMAL
  * 0.20mm NORMAL
  * 0.24mm DRAFT  *(0.4mm, 0.5mm & 0.6mm nozzles only)*
  * 0.28mm SUPERDRAFT  *(0.4mm, 0.5mm & 0.6mm nozzles only)*
  * 0.36mm CHUNKY  *(0.5mm & 0.6mm nozzles only)*
  * 0.44mm SUPERCHUNKY  *(0.6mm nozzle only)*
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
* Nozzles: 0.3mm, 0.4mm, 0.5mm & 0.6mm
* Print Profiles:
  * 0.06mm ULTRADETAIL  *(0.3mm & 0.4mm nozzles only)*
  * 0.08mm SUPERDETAIL
  * 0.10mm HIGHDETAIL
  * 0.12mm DETAIL
  * 0.16mm OPTIMAL
  * 0.20mm NORMAL
  * 0.24mm DRAFT  *(0.4mm, 0.5mm & 0.6mm nozzles only)*
  * 0.28mm SUPERDRAFT  *(0.4mm, 0.5mm & 0.6mm nozzles only)*
  * 0.36mm CHUNKY  *(0.5mm & 0.6mm nozzles only)*
  * 0.44mm SUPERCHUNKY  *(0.6mm nozzle only)*
* Print Speeds:
  * STANDARD
  * SPEED
  * HIGH SPEED
  * SUPER SPEED
* Upgrades: BLTouch auto bed leveling sensor
* Firmware: Stock / Marlin 2.1.1

## License
This work is licensed under a Creative Commons Attribution-NonCommercial 4.0 International License - see the [LICENSE.md](https://github.com/RyanT95/KP3S-Prusa/blob/main/LICENSE) file for details.
