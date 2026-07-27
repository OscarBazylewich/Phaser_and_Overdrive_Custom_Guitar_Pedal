# Phaser_and_Overdrive_Custom_Guitar_Pedal
This projects attemps to recreate and try to improve upon popular guitar pedals such as the MXR Phase 90 and the BOSS-OD1 by incorporating modern analog circuit design and PCB design. This repository will include an LTSpice schematic as well as 3rd party components utilized in the schematic. The same thing also applies for KiCAD.

Final Project PCB layout:  
<img width="725" height="851" alt="image" src="https://github.com/user-attachments/assets/17ca487a-03ff-42e2-bb42-c56750a9efa3" />


How to import 3rd Party Models in LTSpice:
1. Download .sub and .asy files in the LTSpice found in the LTSpice folder.
2. Place the associated files to your local LTSpice directory where the .sub files go into the sub folder and the .asy files fo into the sym folder.

note: 3rd party models might get deleted once ltspice gets updated so its recommended to have a separate folder containing all your 3rd party models then manually copying each file into the directory.

How to import 3rd party symbols, footprints, and models into KiCAD:
1. Place and extract zip files into a directory of your choosing.
2. To import symbols, go into the symbol editor and click on the preferences tab and head onto manage symbol libraries. Then, click the folder icon and look for the directiory where you placed your zip files and import files ending in .kicad_sym.
3. For footprints, go into the footprint editor and click on the preferences tab and head onto manage footprint libraries. Then, click the folder icon and look for the directiory where you placed your zip files and import files ending in .kicad_mod.


Preview of Circuit in LTSpice

<img width="1382" height="996" alt="image" src="https://github.com/user-attachments/assets/37f43ded-42a7-4dfd-a382-c153154c1a23" />

Sample Simulations of the circuit

<img width="1912" height="996" alt="image" src="https://github.com/user-attachments/assets/2930e1ff-972b-4aaf-bea7-94af7dbc0290" />

<img width="1917" height="967" alt="image" src="https://github.com/user-attachments/assets/f858d751-f43d-4b48-af7d-00467eac52c9" />


