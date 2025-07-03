## Struggle Bus Labs V2.3824
![Struggle Bus Labs](v2.3824.png)

Come along and ride on a fantastic voyage with my Voron 2.4 350mm 3D Printer, I have named the Struggle Bus!

I hope you dont expect this to be cohert or organized.  this page is mainly for me to remeber thingds about my voron. 


## Build Log
Starting to prep for a toolhead change. Either XOl or Dragon Burner. Eitehr one will need filament cutter and runout sensor. Had an issues with end of sppol not coming of and jaming. this leaves the dub switch based fila runout in a good state. need to work on that. but next up  is https://github.com/bythorsthunder/Voron_Mods/tree/main/Wristwatch_Extruder_BMG


tonight I was playing with Multi Color printing. I tried all slicers each had littel quirks with thier setup for doing this. While researching I stumbled up 
[Single Extruder Tool Changer MMU with single exrtuder](https://github.com/strayr/klipper-fake-toolchanger/blob/main/README.md)

Setup is straight forward. Upload the klipper-fake-toolchanger.crg and add the include. then set up how many exturders in your slicer. no need to put M600 in for tool changer code as it will take care of that in th macro. Pretty slick. 

## My Build
Hoping to add the following to my machine this week
https://github.com/Thomas-3D/Front_Decontaminator
and an ERCF V2 with Happyhare in the future
https://github.com/moggieuk/Happy-Hare

[Formbot Voron 2.4R1 350mm Kit.](https://www.formbot3d.com/products/voron-24-pro-corexy-3d-printer-kit-with-hdmi-5-touch-screen?VariantsId=10486)

Dragon Std hot End, I print a lot of PLA. 5/11/2024 managed to kill both dragons. 1 grub screw fubared and on the other I snapped a nozzle off. Voron community helped me out and got me parts fast. now I am using a Bambu Labs Clone hotend. 

old mgn9's and mgn 12 will be as backer rod's to mitigate thermal expansion. 

Planning to use CPAP Fan for remote cooling with a 2.4 Top hat with rear umbilical

[Voron R2 Updates](https://github.com/VoronDesign/Voron-2/releases)

Frame Black. Primary printed parts color is black with KVP Galaxy Blue and Polymaker blue accents. I am using vinyl flat cap (blue and black) as rail fillers/cable covers.

X and Y upgraded to West 3d Berserker’s. [X rail](https://west3d.com/products/berserker-mgn12h-1r-300-350-400-linear-rails-viking-skis-with-carriages?variant=43506758025428) and [y Rails](https://west3d.com/products/berserker-mgn9h-1r-150-300-350-400-linear-rails-viking-skis-with-carriages?variant=43506738856148)

Z rails are Formbot vivedino's. The Berserker's were nice and clean when they arrived. I cleaned with ISO and lubed the rails with EP2. So far I have used 1/4 of the syringe. Lots left for maintenance. 

# Door Hinges
[Snap Latch removeable hinges ](https://www.printables.com/model/702768-kit-for-removable-panelsdoors-for-voron-v2trident-)

Finding the right hinges was a journey on the stuggle bus. A fun struggle as I had to try 5-6 hingle mods to get to a happy spot. I only like the snapping latches on the doors, for the panel I use magnetic panels clips and love them. My only issue is I sometimes forget about them and pull the panel off. So I have to hunt the floor for the clips. 

The Snap Latch removal hinges worked ok after a while. I am now using these The Pinned lift off hinges. https://www.printables.com/model/631351-vhb-lift-off-hinges-for-voron-trident-or-24
 

# Panel's

[Printed Solid ACM Panel Kit](https://www.printedsolid.com/products/voron-v2-panel-set-made-from-aluminum-composite-material)

Have not touched the stock PC Panels. Might use them in the future for another build.

# Printer Display 
[BTT LCD12864](https://www.printables.com/model/351939-voron-24-lcd-display-mod)

[BTT LCD12864 GitHub](https://github.com/bigtreetech/MINI-12864)

Stock Display panel didn't stay in down position and felt floppy.  very happy with this design. 

# Webcam

[Wansview 1080P web cam](https://github.com/runtpacket/Struggle-Bus-Labs/tree/main/Mods/WebCAM/wansview-1080p-camera-mount-model_files)

Pretty impressed with this $9 amazon special. Made me recall how crazy web cam prices got during covid. It would have been a $250 camera then. Lol

# Lighting

[2x270mm Disco on stick](https://github.com/VoronDesign/Voron-Hardware/tree/master/Daylight/Disco_on_a_stick_XXL)

[Disco Mount and Baffles](https://www.printables.com/model/315479-daylight-on-a-stick-mount)

Those worked well but I needed better diffusion. Printed these in Clear PLA. Will they hold up in a heated chamber? We shall See https://www.printables.com/model/617749-daylight-on-a-stick-diffuser
Need a couple of these to mount them https://www.printables.com/model/536772-daylight-on-a-stick-mount other places the stock daylight clip worked better. 

[Rainbow Barf](https://wiki.kb-3d.com/en/home/linneo/voron/harnesses/RainbowBarfLEDHarness)

# Filament Runout Sensor

[BTT Smart Filament Sensor](https://github.com/bigtreetech/smart-filament-detection-module/tree/master/V1.0)

Needs lubed and shimmed. Turned off as I need to troubleshoot false positives..
got into troubleshooting. wow was figuring it out a pita. of course once I got it working. I find the perfect how to guide and mounts. https://github.com/VoronDesign/VoronUsers/tree/main/printer_mods/Empusas/BTT_Filament_Motion_Sensor_Mount


# Klipper add-ons

[Jontek2 better Print Start](https://github.com/jontek2/A-better-print_start-macro)

[Kamps](https://github.com/kyleisah/Klipper-Adaptive-Meshing-Purging)

[LED effects](https://github.com/julianschill/klipper-led_effect)

# Fans

[Nevermore v5 Duo](https://github.com/nevermore3d/Nevermore_Micro/tree/master/V5_Duo)

[Resmed CPAP Fan mod by OverLord6920](https://github.com/runtpacket/Struggle-Bus-Labs/tree/main/Mods/CPAP%20FAN)

[Ellis bed Fans](https://github.com/VoronDesign/VoronUsers/tree/master/printer_mods/Ellis/Bed_Fans)

# Probe

[Chaotic Labs Tap v1](https://github.com/Chaoticlab/CNC-Tap-for-Voron)

1/29/2024 - During gantry rail upgrade I hulked a screw on the belt holder. sometimes I don’t know my own strength. Special not CL v2 is incompatible with the Mellow Fly Canbus board. Need to go through parts I may have a printed tap and all the bits and pieces needed to get back to printing. 

2/19/204 - Ended up with a work around in place. I put a dab of super glue on the screw threads. it's working fine and I got a decent belt tune according to kippain-Shake and tune. Printed like a dream for a week and then it looked like wavy lines and under extrustion. found toolhead had a wobble. tore down to tap and foudn 1 screw loose. put blue thread locker on and tighened. 1 week later same issue. I hate tearing down to Tap. everytime I do i end up crimpin cables or havingt o buy something I borked. tonight I had to swap the hotend out. I think the dragon end I had on (reminder for self CHT nozzle) has a bad thermistor as I was getting Heater extruder not heating at expected rate. pid tune calibration didn't help (reminder to self fans on). items borked: X endstop wire broke at switch leg. So I went sensorless homing as it was on my todo list. I only installed endstop with canbus becuase I was already running cables. (remind one day remove the endstops and wiring and relocation pieces). hardest part was following directions. could not understand the one section on driver tuning. got help on discord. worked though those issues. tried to make a spare TAP wire. As i have broken them twice now. no success need to check wiring when my eyes are better. So far I like sensorless homing. even if the homing speed is SLOW. it's less wires for me to break. Oy yeah remider to self. SB FAN board is not screwed in. If you screw it in it doesn't work. get some button head 10mm I think the socket heads are too tall and stop it from fully seating. 

IMPORTANT! If you use a SB 2 Piece toolboard. You this https://www.printables.com/model/642001-voron-stealthburner-sb2209-misalignment-protector

# CanBUS

[Esotericals canbus guide](https://github.com/Esoterical/voron_canbus)

[BIGTREETECH U2C V2.1](https://github.com/bigtreetech/U2C)

[Mellow Fly SB2040 v1 KB3D Guide](https://wiki.kb-3d.com/home/mellow/voron/mellow_sb2040)

[Mellow SB2040v1](https://github.com/Mellow-3D/Fly-SB2040)

Mellow Fly SB2040 V2 released the magic smoke. I had just started a print and watched the printer start to home when I saw the smoke. Opened up the stealth burner to find a capacitor was missing. It looked to be cold soldered. This led to a mosfit spewing it's guts. Fast replacement thanks to KB3D.

The Mellow Fly SB2040 v1 and v2 are incompatible with the Chaotics Labs CNC Tap V2. 

IF you use any SB toolhead board thats 2 piece you NEED this! (you can kill the boards if you misalign, this saves you from yourself) https://www.printables.com/model/642001-voron-stealthburner-sb2209-misalignment-protector

# Umbilical

I built my umbilical cable using 2mm PTFE alongside the SB2040 Canbus cable inside 1/8" Sleeving. So far I find the PTFE to be perfect. 

[No Longer use - A Drive pg7 Mount](https://www.printables.com/model/312008-voron-24-a-drive-pg7-umbilical-mount)

[Minsekt Y Endstop relocation](https://github.com/VoronDesign/VoronUsers/tree/master/printer_mods/Minsekt/Rear_Umbilical/Y_Endstop_Relocation)

[Z Chain relocation](https://www.printables.com/model/279739-voron-can-bus-z-chain-move)

# Flex Plate Holder

[Voron V2.4 Flex Plate Holder by KeiranSolaris](https://www.printables.com/model/163992-voron-v24-flex-plate-holder)

# Panel Clips

[Magnetic Panel Clip for Voron 2.4 by FunFunboy](https://www.printables.com/model/84734-magnetic-panel-clip-for-voron-24)

# Skirt 

[Hexagon skirt inserts by Tom van der Geest](https://www.printables.com/model/648945-voron-24-skirt-insert)

# Misc

Z belt Covers are done. https://www.printables.com/model/479809-voron-24-z-belt-covers

Purge Bucket and Nozzle brush With plate Stop https://www.printables.com/model/479809-voron-24-z-belt-covers 
goes very well with https://www.printables.com/model/346782-voron-24-bed-alignment-stop-updated
 
## Coming Soon

[2.4 Tophat](https://www.printables.com/model/571759-voron-24-trident-magnetic-tophat-35mm-66mm-beta-re)

[CPAP for Voron 2.4 and Stealthburner](https://github.com/ogland/Printer-mods/tree/main/V2/CPAP)

[Rear Umbilical Passthrough](https://github.com/tanaes/whopping_Voron_mods/tree/f64cd56fe2baac4348ac56e3d0e70f4577013d7e/umbilical_passthrough)

[Skirt Buttons](https://www.fysetc.com/products/fysetc-hot-key-board-voron-skirt-button-pcb-voron-skirt-klipper-pre-installed-pcb-board-with-neopixel-led-for-voron-v2-4-trident-switchwire-3d-printers)

[Replacing SB2040 V1 with SB2040 V2](https://github.com/Mellow-3D/Fly-SB2040/tree/main/V2/Hardware)

[Exhaust to Basement Window](TBD)

[Reusing old mng9 / mgn12 rails as backers](https://github.com/VoronDesign/VoronUsers/tree/master/printer_mods/whoppingpochard/extrusion_backers)

## Changes I am considering 

[The Filter](https://github.com/nateb16/VoronUsers/tree/master/printer_mods/nateb16/THE_FILTER)

[Monolith Panels](https://github.com/CloakedWayne/Monolith_Panels/blob/main/Images/distant_view.png)

[Clicky Clacky Door](https://github.com/tanaes/whopping_Voron_mods/tree/main/clickyclacky_door)

[The Filter]([https://github.com/tanaes/whopping_Voron_mods/tree/main/clickyclacky_door](https://www.printables.com/model/334276-the-filter-for-voron-24))
[jst hub for the filter](https://www.printables.com/model/512527-jst-hub-for-the-filter)

[Wago and jst bed mount 2020](https://www.printables.com/model/512516-wago-and-jst-bed-mount-for-2020)

## Tools I like
[GT2 Belt Tensioner](https://github.com/Diyshift/3D-Printer/blob/main/GT2%20Belt%20Tension%20Meter/Manual/GT2_Tensiometer_Manual.pdf)

