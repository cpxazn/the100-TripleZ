# WORK IN PROGRESS

# the100 Triple Z Mod
After building and using The 100 for a bit, I noticed that one of the weak points of the printer is that the bed is balanced in the center on two lead screws and the only supports for the bed are the two LM8UUs holding onto the front two rods. Those bearings have some slight play, otherwise they would bind. After using a few different probes, and taking screw tilts after every prints, I noticed that all four bed corners are constantly changing in height after every print. Another issue is that when printing speed boats, I noticed that the front LM8UUs are wobbling up and down constantly, which means the bed is also wobbling up and down during the print which will compromise quality.

I'm hoping that triple Zs would address this issue, however this will not come cheap because introducing another stepper and the ability to move each Z stepper individually will require a more expensive mainboard. 

This also comes with an additional benefit however. Since there are three lead screws, it should be possible to enable automatic bed leveling like the Trident and the Rook 180.

I tried to design it so that it is easy for anyone with The 100 to adopt this mod. Unfortunately a few big pieces must be reprinted if you already have printed them. This includes the three bed pieces and the two front bottom frames.

One of the main challenges that I am facing right now is placement of the electronics because the mainboards will be larger, and the extra Z stepper takes quite a bit of space. May have to design a tray mounted on top of the power supply.

Other General Improvements
- Front bottom frame pieces
  - Uses heat inserts to attach the feet
  - Can now secure the two vertical rods using screws through heat inserts
  - Heat insert slots located all throughout the frame to allow easy modification
- Feet
  - Has slot for M5 nut to allow attaching rubber feet
- Bed Left/Right
  - Uses heat inserts to secure LM8UU bearings
  - No longer requires supports to print
  - Supports Prusa Mini bed
- Bed Center
  - Supports Ender 2 Pro and KP3S bed

This is the current list of WIP BOM
- A Mainboard that can control 6 steppers individually. Some examples, BTT Octopus, BTT Manta M8P, MKS Monster8.
- 8mm Diameter, 300mm length linear rod
- Additional stepper motor
- Additional lead screw (200mm length, 8mm diameter, 2mm pitch) and coupler
- Additional LM8UU
- M3x5x5mm Heat Inserts
- Assorted M3 screws

# the100 Printer
[the100 Github](https://github.com/MSzturc/the100)
