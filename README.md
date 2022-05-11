# klipper-configs

Klipper configuration for my heavily modified Ender3.

This repo serves primarily as an easy way to back up my configs and move them between computers.
Do not directly use these configs on your printer without careful review because you will probably break something.
I'll do my best to note the potentially dangerous settings here, but no guarantee.

- Belted Z mod - https://github.com/kevinakasam/BeltDrivenEnder3
- SKR V1.3
- TMC2208 drivers in UART mode on XYZ
- LV8729 driver on Extruder
- BLTouch V3 - ***5V output*** significantly improved my probe repeatability. ***Verify your controller supports 5V logic before using this!***
- Direct drive BMG style extruder
- Triangle labs V6 hotend
- Stock steppers
- Y stepper - ***MOVEMENT HAS BEEN REVERSED!*** I flipped it around trying to prevent belt rub.
- OEM Extruder stepper is now on Z, OEM Z stepper is the direct drive stepper. (Note: this requires a shorter X axis motor/end stop mount)

Originally based on a reddit post by /u/VonThing. Some bits remain, probably mostly the pin definitions.
Inspiration for splitting the config files taken from https://github.com/fl0r1s/cr10_klipper

########################################

> Originally posted on https://www.reddit.com/r/klippers/comments/csjzid/sample_config_for_ender_3_bltouch_v30_skr_v13/  
> (c) VonThing 2019  
> Licensed under CC-BY-SA-4.0 https://choosealicense.com/licenses/cc-by-sa-4.0/  
> Redistributions MUST include this copyright notice and the same license terms.
