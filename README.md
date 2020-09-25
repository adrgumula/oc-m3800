# Dell m3800 OpenCore

This is a OpenCore EFI folder for Dell m3800 with 4k display screen ready to work with 10.15.6
[#f03c15]So far that 

Works:
+ 3D accelelation,
+ Wifi (switched to compatible one),
+ Blutooth,
+ Sound (F1-F3 keys)
+ HDMI video,
+ HDMI audio
+ DVI video/audio
+ Keyboard
+ Tought pad (fully)
+ Battery
+ Part of multimedia keys (volume)
+ screen brightness (+ keys)
+ night shift
+ camera
+ disabled Nvidia


Does not work:
- SD card reader
- iMessage, FaceTime (did not chacked it)
- Toughable screen

Known issues:
- screen flickes while using scalable resolutions on internal laptop screen
- allows to boot BigSur installator, but it crashes during prefinal installation while booting "Preinstall"
- BigSur boot (kernel panic)
 
 
 OpenCore tutorial:
 https://dortania.github.io/OpenCore-Install-Guide/config-laptop.plist/haswell.html#starting-point
