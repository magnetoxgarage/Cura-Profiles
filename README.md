# Cura-Profiles
## Peopoly MagnetoX Cura Configuration
![alt text](image.png)

## ⚠️ 🚧 THESE PROFILES ARE A WORK-IN-PROGRESS 🚧

They may not have proper constraints and the toolhead dimensions may not be correct for single object printing. Use at your own risk.

## How to Use
1.) Download/clone the project

2.) On Windows, browse to: %APPDATA% (You can type into File Explorer or the Windows Run command)

3.) Paste the cura folder over the top of the cura folder that is already there.

4.) Open Cura and add your MagnetoX 

5.) 🛑 ℹ️ Check the start GCODE and verify it will work for your setup

## Known Issues
+ ASA profiles seem to be broken. I'm not sure why yet.
+ The printer name is always MagnetoX #2 for me. Not sure why that is either.
+ Cura log shows ``NameError: name 'skirt' is not defined`` due to the values for ``adhesion_type`` (Code [in MagnetoX.def.json]([url](https://github.com/magnetoxgarage/Cura-Profiles/blob/d16a877ba92a25e53f93f191fc5c56f3ea2a9b6c/cura/5.9/definitions/MagnetoX.def.json#L34-L38)))

Pull requests are welcome!
