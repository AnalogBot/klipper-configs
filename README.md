# klipper-configs

custom Ender 3 build

- SKR V1.3 board
- stock steppers
- TMC2208 drivers in UART mode
- BLTouch V3
- Ender3 stock display
- BMG style extruder

########################################

AnalogBot's Klipper config, modified from /u/VonThing Reddit post

Originally posted on https://www.reddit.com/r/klippers/comments/csjzid/sample_config_for_ender_3_bltouch_v30_skr_v13/  
(c) VonThing 2019  
Licensed under CC-BY-SA-4.0 https://choosealicense.com/licenses/cc-by-sa-4.0/  
Redistributions MUST include this copyright notice and the same license terms.

########################################  
Inspiration for config break up taken from https://github.com/fl0r1s/cr10_klipper

#### changelog
- switched to builtin safe z-homing
- disabled power menu
- disabled filament runout sensor
- microsteps from 16 -> 32
- mesh leveling from 3,3 -> 5,5 and centered on bed
- virtual sd card support
- reordered menus
- various calibrations/offsets for my setup
- broke config sections into separte files
