TeamWin Recovery Project

Device configuration for TP-LINK Neffos X1 Max (TP903a)
=====================================

Basic   | Spec Sheet
-------:|:-------------------------
CHIPSET | MTK Helio P10 MT6755
CPU     | 4x 1.2 GHz & 4x 2.0 GHz ARM Cortex A53 CPU
GPU     | ARM mali-T860 MP2 728MHz
Memory  | 3 GB / 4 GB
Shipped Android Version | Android 6.0 (Marshmallow)
Storage | 16 GB / 32 GB
MicroSD | Up to 128 GB
Battery | 3000 mAh
Dimensions | 152.8 x 76 x 7.85 mm
Display | 1920 x 1080 pixels 5.5" (403.8 PPI )
Rear Camera  | 13.0 MP
Front Camera | 5.0 MP
Release Date | September 2016

![TP-LINK Neffos X1 Max](http://www.neffos.com/res/images/products/X1Max_un_Dark_Grey_default.png "TP-LINK Neffos X1 Max")

How to compile the image
=====================================
You can get the minimal OMNI source [from here](https://github.com/minimal-manifest-twrp/platform_manifest_twrp_omni).
The full HowTo can be found [here](https://forum.xda-developers.com/showthread.php?t=1943625).

TWRP Functional Checklist
=====================================

Blocking checks
- [ ] Correct screen/recovery size
- [ ] Working Touch, screen
- [ ] Backup to internal/microSD
- [ ] Restore from internal/microSD
- [ ] reboot to system
- [ ] ADB

Medium checks
- [ ] update.zip sideload
- [ ] UI colors (red/blue inversions)
- [ ] Screen goes off and on
- [ ] F2FS/EXT4 Support, exFAT/NTFS where supported
- [ ] all important partitions listed in mount/backup lists
- [ ] backup/restore to/from external (USB-OTG) storage
- [ ] backup/restore to/from adb (https://gerrit.omnirom.org/#/c/15943/)
- [ ] decrypt /data
- [ ] Correct date

Minor checks
- [ ] MTP export
- [ ] reboot to bootloader
- [ ] reboot to recovery
- [ ] poweroff
- [ ] battery level
- [ ] temperature
- [ ] encrypted backups
- [ ] input devices via USB (USB-OTG) - keyboard, mouse and disks
- [ ] USB mass storage export
- [ ] set brightness
- [ ] vibrate
- [ ] screenshot
- [ ] partition SD card
