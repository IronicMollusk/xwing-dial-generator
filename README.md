# xwing-dial-generator
Uses python to convert maneuver dial arrays into printable stl files.

## Basic Instructions
-Make sure you have blender installed
-Download the zip by clicking code > download zip
-Extract the zip to a folder of your choice.
-Open TIEsf.json in a text editor.
see this awesome github repository for ship dial information:
```
https://github.com/guidokessels/xwing-data2
```
Most ships are at the top of any of the files found in data/pilots/faction name. open the appropriate ship file, and towards the top, find the "dial" property. copy everything between the square brackets ("[ ]"), including the square brackets themselves. paste inside the TIEsf.json file, replacing whats in there already. save-as or rename the TIEsf.json file to match the name of your ship.
-Open dialGenerator.blend in blender, navigte to the "Scripting" tab at the top, and run the script using the play button toward the top, or use alt+p.
-It will take a couple seconds, and your outputted atl file should be in the /output folder. if you want to dive into the finer settings, feel free to poke around the script in blender at your own risk. 
