# Dell m3800 OpenCore [No longer supported by the author]

This is a OpenCore EFI folder for Dell m3800 with 4k display (2015 model) screen ready to work with 10.15.x and 11.x
[#f03c15]So far that 

Works:
+ 3D accelelation (2GB vram + framebuffer patched: 160MB bios, 48MB),
+ Wifi (switched to compatible one),
+ Blutooth (patched),
+ Sound keys (F1-F3 keys)
+ HDMI/DVI video
+ HDMI audio
+ DVI video/audio (4k/60Hz)
+ 60Hz in most of the hi-res sceens (known bug: 4k/60Hz setting for internal screen starts flickering for unknown reaseons)
+ Keyboard
+ Battery
+ Part of multimedia keys (volume)
+ night shift
+ camera
+ disabled Nvidia
+ Toughable screen
+ SD card reader
+ screen brightness (+ keys)
+ Touchpad with guestures 
+ fullly USB patch -> replaced USBInjectAll.kext

Should work, but not fully tested yet:
- sleep & wake on battery and AC power,
- Lid close sleep & wakesup after Lid open
- Deep sleep

Does not work yet/Still to do:
- light sensor

Did not check it yet:
- iMessage, FaceTime

Known issues:
- 4k/60Hz internal screen - flickers - solution to to install SwitchResX app and create the custom resoltion 4k with 57Hz refresh rate (repeat it for the scanale ref)
- sound issues - system startup with headset plug in causes internal sound not working
- after wakeup from sleep performace issues occures

OpenCore version:
- 0.7.1

Supports clean Apple "Software update.." 
- ![image](https://user-images.githubusercontent.com/70687019/111694675-781f6d80-8832-11eb-981b-f870b8d9d3ce.png)

 
OpenCore tutorial:
https://dortania.github.io/OpenCore-Install-Guide/config-laptop.plist/haswell.html#starting-point
