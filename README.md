# Z390-Hackintosh-Joost
Joost's EFI for Hackintosh on Z390 Designare, i7, RX 570, 32GB RAM and Fenvi T919

![alt test](/Pictures/Z390info.png)
![alt test](Pictures/HackintoshJoost.png)

# Latest Changes:
1. Updated succesfully to Supplemental Update for 10.15.4
2. ...

# EFI ZIP file:
Will upload later.

# PC specifications:
- Processor: Intel Core i7 9700K, 9th Gen (Code name: Coffee Lake)
- Motherboard: Gigabyte Z390 Designare
- Sound card (onboard): ALC 1220-VB audio controller
- SSD storage: Crucial Crucial MX500, 1TB 
- Graphic card: Sapphire Nitro+ Radeon RX 570 4GD5
- OS installed: Catalina 10.15.X dualbooted with Windows 10 Pro
- Fenvi T919 for WiFi/Bluetooth, AirDrop etc.

# Prerequisites:
Everything I did went according @CaseySJ his outstanding guides on:
https://www.tonymacx86.com/threads/success-gigabyte-designare-z390-thunderbolt-3-i7-9700k-amd-rx-580.267551/

# Notes:
- I didn’t change/add anything to 'Library/Extensions' folder. For kexts, I only used the 'EFI/CLOVER/kexts/Other/' folder.

# Kexts:
Make sure (!) you are using the latest kexts from the internet: 

- FakeSMC.kext (Only install FakeSMC.kext, nothing else)
https://bitbucket.org/RehabMan/os-x-fakesmc-kozlek/downloads/
- USBInjectAll.kext
https://bitbucket.org/RehabMan/os-x-usb-inject-all/downloads/
- Lilu.kext
https://github.com/acidanthera/Lilu/releases
- WhateverGreen.kext
https://github.com/acidanthera/WhateverGreen/releases

For convenvience purposes, use either Clover Configurator or Hackintool to mount EFI and update the Kexts.

# BIOS Settings (from tonymacx86.com):
https://www.tonymacx86.com/threads/success-gigabyte-designare-z390-thunderbolt-3-i7-9700k-amd-rx-580.267551/

# Work Procedure:
https://www.tonymacx86.com/threads/success-gigabyte-designare-z390-thunderbolt-3-i7-9700k-amd-rx-580.267551/
 
# Updating Hackintosh
https://www.tonymacx86.com/threads/success-gigabyte-designare-z390-thunderbolt-3-i7-9700k-amd-rx-580.267551/
- In general; watch others do first to see if they succeed: 
- Make sure first to install the latest Kext files
- Install latest Clover; but first make sure that this works according other users. Latest Clover build:
https://github.com/CloverHackyColor/CloverBootloader/releases

# Confirmed working
-	CPU, RAM, Fans, etc.
- Video
-	Ethernet
-	Sound
- AirDrop (Fenvi)
- WiFi (Fenvi)
- Bluetooth (Fenvi)
- Install apps by authorizing from Apple Watch

# Extras
- Hide unneeded volumes in Clover with Clover Configurator. I've hide the following volumes:

![alt test](/Pictures/HideVolumes.png)

# Resources
https://www.tonymacx86.com/threads/success-gigabyte-designare-z390-thunderbolt-3-i7-9700k-amd-rx-580.267551/
https://github.com/CloverHackyColor/CloverBootloader/releases
https://www.tonymacx86.com/resources/clover-configurator.429/ 
https://hackintosh.gitbook.io 
https://www.tonymacx86.com/threads/how-to-create-a-macos-catalina-public-beta-installation-usb.278188/
https://www.tonymacx86.com/threads/unibeast-install-macos-mojave-on-any-supported-intel-based-pc.259381/#uefi_settings
