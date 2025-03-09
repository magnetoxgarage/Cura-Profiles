# Cura-Profiles
## Peopoly MagnetoX Cura Configuration
![alt text](image.png)

## ⚠️ 🚧 THESE PROFILES ARE A WORK-IN-PROGRESS 🚧

⚠️ Printer may not have proper constraints

⚠️ The Toolhead dimensions may not be correct for 'Print One at a time' (Print-by-object) printing. Use at your own risk.

## How to Use
1.) Download/clone the project

2.) On Windows, browse to: %APPDATA% (You can type into File Explorer or the Windows Run command).

On Linux distros you will likely be able to use `~/.local/share/cura`

3.) If you've installed these profiles before, delete the `cura/5.9/quality/peopoly_magnetox` folder and delete all files that begin with 'Peopoly' in the `cura/materials` folder.

4.) Paste the `cura` folder over the top of the `cura` folder that is already there.

5.) Open Cura and add your Magneto X 

6.) 🛑 ℹ️ Check the start GCODE and verify it will work for your setup

### Recommended Extensions:
+ [Klipper Settings](https://marketplace.ultimaker.com/app/cura/plugins/JJGraphiX/KlipperSettingsPlugin)
+ [Moonraker Connection](https://marketplace.ultimaker.com/app/cura/plugins/emtrax/MoonrakerConnection)
+ [Valve, a volumetric Flow limiter](https://marketplace.ultimaker.com/app/cura/plugins/friendly.ghost/valve)
+ Modify Cura to [support thumbnails in GCODE](https://docs.fluidd.xyz/features/thumbnails#cura-with-post-processing-script)

## Known Issues
+ Utilizes volumetric speed calculations with a assumed volumetric flow. This needs to be adapted for all filaments
+ Many Peopoly-specific filament settings have not been copied over
+ If using KAMP, start GCODE will need to be changed to EXTRUDER_TEMP and BED_TEMP
+ ASA profiles seem to be broken. I'm not sure why. The same seems to occur with Voron ASA profiles on Voron printers.

Pull requests are welcome!

## Sources for Data:
+ Peopoly pull request for Orca Slicer that was cancelled: https://github.com/SoftFever/OrcaSlicer/pull/5435/files
+ Voron pull request for Cura here: https://github.com/Ultimaker/Cura/pull/20023 to utilize volumetric speeds
+ Original Peopoly Magneto X pull request for Orca Slicer: https://github.com/SoftFever/OrcaSlicer/pull/3944/files
+ [Cura profiles and config documentation](https://support.ultimaker.com/s/article/1667552779530)
