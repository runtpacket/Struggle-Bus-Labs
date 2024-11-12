## Struggle Bus Labs V2.3824
![Struggle Bus Labs](v2.3824.png)

Come along and ride on a fantastic voyage with my Voron 2.4 350mm 3D Printer, I have named the Struggle Bus!

I hope you dont expect this to be cohert or organized.  this page is mainly for me to remeber thingds about my voron. 


## Build Log

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

## Self inflicted wounds

Chaotic labs Tap v1. Over tightened the belt holder screw. I wasn't trying. but the aluminum didn’t care.

RelaBot amazon el cheapo Rail. ummm did I forget to lube that rail. Yup! Was printing like a dream, then layer shift and it sounds Crunchy!

vivedino mgn8 400mm damn those bearing are small and all over the floor. Oh wtf they have grease ports. 

## Build Plates Wall o Shame

What can I say. Let me build a klicky probe and make art. Here are a couple of master pieces.

Plate 1
![Struggle Bus Labs](plate1.jpg)

Plate 2
![Struggle Bus Labs](plate2.jpg)

Carnage not pictured. more than a few switches that were klicky probes. they squish hard.

## Spare Parts
QTY  Description

1    [MKS Canable Pro](https://www.aliexpress.us/item/3256803818737314.html?gatewayAdapt=glo2usa4itemAdapt)

2    [Mellow Fly SB2040 V2](https://kb-3d.com/store/controllers-displays-drivers/793-mellow-fly-sb2040-v2-can-toolhead-pcb-for-voron-stealthburner-1674910664639.html)

1    [BTT EBB42](https://biqu.equipment/products/bigtreetech-ebb-36-42-can-bus-for-connecting-klipper-expansion-device?variant=39760665182306)

1    Formbot rail vivedino Linear Rail MGN9H 400mm

1    Amazon Generic Linear Rail MGN12H 400mm (in use as backer, Bearing block on printed rail, bagged in storage box A)

2    [GT2 Open Belt LL-2GT-9 (9mm wide) - 1200mm](https://west3d.com/products/gates-gt2-open-belt-ll-2gt-9-9mm-wide-voron-v0-v1-v2-switchwire)

2    [GT2 Open Belt LL-2GT-6 (6mm wide) - 2000mm](https://west3d.com/products/gates-gt2-open-belt-ll-2gt-6-6mm-wide-voron-v0-v1-v2-switchwire)

1    [BMG Extruder Components Kit](https://dfh.fm/products/extruder-full-kit)

4    F695 Bearing

4    625 Bearing

15+  Omron D2F-01L Micro Switch

1    [BAT85 Diode](https://kb-3d.com/store/electronics/169-vishay-bat85-schottky-diode-1634505566335.html)

2    [GDSTime 25X25X7 5v Fan](https://www.amazon.com/GDSTIME-Pack-25mm-Fan-25x25x7mm/dp/B08D8VNLHD)

2    [WinSinn 3010 24v](https://www.amazon.com/WINSINN-Blower-Bearing-30x10mm-Turbine/dp/B08MKLDGQR?th=1)

2    [WinSinn 4010 24v](https://www.amazon.com/WINSINN-Ender-Upgrade-Bearing-CR-10S/dp/B07DB5H6K1?th=1)

1    [RDK Cooler 4010 24v](https://www.amazon.com/Brushless-UCEC-40x40x10MM-Humidifier-Applicances/dp/B07DKXWYVM?th=1)

4    [WinSinn 5015 24v](https://www.amazon.com/WINSINN-Cooling-50x50x15mm-Extruder-Makerbot/dp/B079BPS9Q8)

1    [Voron V2.4r1 359mm Polycarbonate. from formbot kit](https://kb-3d.com/store/frame-enclosure/546-7469-acm-or-pc-panel-set-for-voron-v24-multiple-sizes.html#/270-buildsizevrn-350mm/880-materialtype-polycarbonate)

1    [Dragon Standard](https://cn.phaetus.com/dragon-hotend-st/)

1    [Steppers Online 17HS08-1004S Nema 17 Bipolar Stepper Motor 1.8deg 16Ncm(22.66oz.in) 1A Extruder Motor 42x42x20mm 4 Wires](https://www.omc-stepperonline.com/nema-17-bipolar-1-8deg-16ncm-22-6oz-in-1a-3-7v-42x42x20mm-4-wires-17hs08-1004s)

1    [Magnetic Bed Sticker 350mm](https://www.aliexpress.com/i/3256804945332621.html?gatewayAdapt=4itemAdapt)

1    [Voron AfterBurner complete Stepper and Dragon Standard](https://github.com/VoronDesign/Voron-Afterburner)

1    [Unklicky Full Kit - by Dustinspeed](https://dfh.fm/collections/voron/products/unklicky-full-kit-by-dustinspeed)

1   [Sexbolt](https://mods.vorondesign.com/detail/t1DBVlcUBbdEK6habEsVzg)

1    [Rainbow Barf PCB](https://lab4450.com/product/rainbow-barf-led/)

1    [Mellow NeoPixel RGBW Mini Button PCB Leds For Voron 2.4](https://www.aliexpress.us/item/3256804426894084.html?spm=a2g0o.order_list.order_list_main.54.1b921802dUkdyp&gatewayAdapt=glo2usa)

1    [Raspberry PI 3b](https://www.amazon.com/Raspberry-Pi-MS-004-00000024-Model-Board/dp/B01LPLPBS8)

1    [Voron ADXL345 Accelerometer Kit](https://www.etsy.com/listing/1187543541/voron-adxl345-accelerometer-kit?ref=yr_purchases&variation0=2512395495)

1    [LINNEO OPTO TAP 1.0](https://kb-3d.com/store/printer-specific-pcbs/737-linneo-opto-tap-pcb-v241-complete-524v.html)

1    SteathBurner with dragon/cw2 - hot standby


Items I used when Building My Voron
https://github.com/VoronDesign/VoronUsers/tree/main/printer_mods/samwiseg0/corner_cable_hide/STLs








