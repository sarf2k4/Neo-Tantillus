# Neo-Tantillus
The original Tantillus was created by sublime back in 2012 and it was famous back then. However, there were some issues with the models where the parts are mixed between imperial and metric parts leaving several parts can't fit together between printed and non-printed parts.

This Neo-Tantillus has been modified to cater new hardware which is 2018 by mix and match parts from various sources that proven to be worked by them and put into here to eliminate waste of material where as printing the parts but resulting in not able to fit together or having issues.

The configuration file for marlin also included

# Sources
There are several stl files derived from the following things from thingiverse

https://github.com/Intrinsically-Sublime/Tantillus
https://www.thingiverse.com/thing:1449869
https://www.thingiverse.com/thing:359346
https://www.thingiverse.com/thing:359344
https://www.thingiverse.com/thing:910886
https://www.thingiverse.com/thing:1707045
https://www.thingiverse.com/thing:1658075
https://www.thingiverse.com/thing:1329750
https://www.thingiverse.com/thing:16813
https://www.thingiverse.com/thing:2202854
https://www.thingiverse.com/thing:761806
https://www.thingiverse.com/thing:28054

Thanks to the above that I'm able to complete the whole package, some of which I modified them in order to further improve its functionality and practicality.

# Specification/Features
On my build, I used ramps 1.4+ as well as Arduino Mega 2560. The final specification of the Neo-Tantillus I built is the following

- Print Volume: 90 x 80 x 95mm (1)
- Bowden Extruder
- Manual Bed Leveling
- Base for storing the electronics underneath the build plate
- GT2 belt
- Leadscrew for z axis
- 2004 LCD panel
- Groove mount for e3d based hotend
- Fixed bed
- Low profile leadscrew nut mounting
- Low profile z endstop mounting
- Normal sized and small sized limit switch slot for z axis

#BOM
##Non-Printable
###Parts
You can refer to the original tantillus BOM
z axis threaded rod 170mm

smooth rod lengths
2 x 165  hotend gantry
2 x 220  motor rod
2 x 195  idler rod
2 x 230  z axis

###Screws
Frame Assembly
M3 x 10 = 16
M3 x 30 = 4
M5 x 6 = 16
M5 x 8 = 4
M5 x 10 = 12
M5 x 14 = 10
M5 x 16 = 4
M5 x 18 = 10
M5 x 30 = 4 (Countersunk)

NOTES
(1) There are 4 different print volumes depending on the setup as follows
- 80 x 90 x 100mm if you are using the stock e3d based or similar fan duct
- 70 x 90 x 100mm if you are using dual fan shroud (included in this neo-tantillus package)
- 90 x 80 x 95mm if using stock e3d based fan duct along with flipped carriage style
- 90 x 70 x 95mm if using dual fan shroud along with flipped carriage style