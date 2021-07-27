# One Xplayer (OXP) Hackintosh
Project to implement macOS support on the One Xplayer

Initial support for macOS version 10.15.4 and above.

If you see anything that could be added or changed don't hesitate to make a pull request.


## *** NOTICE ***
### Initial support of macOS on the One Xplayer has been achieved. Not for use yet as a daily driver. 
### Currently the Intel 11th generation CPU with integrated Intel Xe GPU is not supported by macOS.
### Do not update kexts labeled as "custom" manually, instead wait for us to update. Kexts have been modified to support the currently unsupported 11th gen chipset. Once 11th gen devices are supported natively we will remove this restriction.
### You may experience occasional sluggishness in the OS or when using the Toucscreen or Track Pad. This is due to a lack of graphics acceleration. Please do not file an issue on this as it is a known issue. 

## One Xplayer Specifications:

| Model: | i5-1135G7 | i7-1165G7 | i7-1185G7 |
|---|----------|----------|----------|
|CPU| quad core 1.1-4.2 Ghz| quad core 1.1-4.7 Ghz| quad core 1.2-4.8 Ghz|
|GPU|Xe 80 EU | Xe 96 EU | Xe 96 EU |
|RAM| 16 GB | 16 GB | 16 GB |
|SSD| 512GB NVME | 1TB NVME | 2TB NVME |
|WiFi| Intel WiFi 6 | Intel WiFi 6 | Intel WiFi 6 |
|Batt| 15,300 mAH | 15,300 mAH | 15,300 mAH |
|USB| 2x USB-C, Thunderbolt 4 | 2x USB-C, Thunderbolt 4 | 2x USB-C, Thunderbolt 4 |
|   | 1x USB-A, Type USB 3.0 | 1x USB-A, Type USB 3.0 | 1x USB-A, Type USB 3.0 |


## Instruction Guides

### [Chapter 1) Quick Start Install](https://github.com/THEDEVIOUS1/One_Mix_Yoga_4_Hackintosh/blob/main/1-QuickStart.md)
### [Chapter 2) BootCamp Install](https://github.com/THEDEVIOUS1/One_Mix_Yoga_4_Hackintosh/blob/main/2-BootCamp.md)
### [Chapter 3) Quirks & Fixes](https://github.com/THEDEVIOUS1/One_Mix_Yoga_4_Hackintosh/blob/main/3-quirks&fixes.md)
### [Chapter 4) Additional Drivers](https://github.com/THEDEVIOUS1/One_Mix_Yoga_4_Hackintosh/blob/main/4-drivers.md)
### [Chapter 5) Booting Other OS's with OpenCore](https://github.com/THEDEVIOUS1/One_Mix_Yoga_4_Hackintosh/blob/main/5-OtherOS%26OC.md)
### [Chapter 6) Other Operating Systems](https://github.com/THEDEVIOUS1/One_Mix_Yoga_4_Hackintosh/blob/main/6-OtherOS.md)


## What works 

- macOS 10.15.4 and above
- Wi-Fi native Intel support
- Fan
- USB
- Preliminary HIDPI support without Graphics Acceleration
- Battery
- Trackpad
- TouchScreen / Stylus
- Keyboard
- Windows Boot Support From OpenCore Bootloader
- Audio: Internal Speakers & Headphone Jack
- Recovery
- FileVault
- Bluetooth
- Brightness Keys (This won't actually work until GPU Acceleration is achieved)



## What doesn't work

- Graphic Acceleration including 4K support & rotation (display stuck in portrait mode)
- Audio: Built-in Microphone
- Brightness Adjustment
- Power Management
- Sleep / Wake
- Thunderbolt: Video currently unsupported, Audio Untested
- Fingerprint Sensor
- SDcard (working on possible fix)


## Credits
Special thanks to [@balopez83](https://github.com/balopez83) for all of his assistance <br>
