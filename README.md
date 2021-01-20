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

Does not work yet/Still to do:
- replace USBInjectAll.kext to full USB patch 

Did not check it yet:
- iMessage, FaceTime (did not chacked it)
- Sleeping, Lid (you can enable EnableLidWake.kext)

Known issues:
- sound issues - system startup with headset plug in causes internal sound not working

OpenCore version:
- 0.6.5
 
OpenCore tutorial:
https://dortania.github.io/OpenCore-Install-Guide/config-laptop.plist/haswell.html#starting-point
