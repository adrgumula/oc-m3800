# Dell m3800 OpenCore

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
+ Keyboard
+ Battery
+ Part of multimedia keys (volume)
+ night shift
+ camera
+ disabled Nvidia
+ Toughable screen
+ 4k/60Hz internal screen - BigSur / no screen flickering
+ light sensor
+ SD card reader
+ screen brightness (+ keys)
+ Touchpad with guestures 

Should work, but not fully tested yet:
- sleep & wake on battery and AC power,
- Lid close sleep & wakesup after Lid open
- Deep sleep

Does not work yet/Still to do:
- replace USBInjectAll.kext to full USB patch 

Did not check it yet:
- iMessage, FaceTime

Known issues:
- sound issues - system startup with headset plug in causes internal sound not working
- after wakeup from sleep performace issues occures

OpenCore version:
- 0.6.5

Supports clean Apple "Software update.." 
- ![image](https://user-images.githubusercontent.com/70687019/111694675-781f6d80-8832-11eb-981b-f870b8d9d3ce.png)

 
OpenCore tutorial:
https://dortania.github.io/OpenCore-Install-Guide/config-laptop.plist/haswell.html#starting-point
