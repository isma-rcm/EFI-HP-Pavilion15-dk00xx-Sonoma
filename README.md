# EFI-HP-Pavilion15-dk00xx-Sonoma

Opencore v. 1.0.3

## 🚀 Computer Characteristics

- Model HP Pavilion 15 dk0017ns
- Processor Core i7-9750H
- Memory ddr4 40GB  
- GPU GTX 1650 y iGPU UHD 630 (used in Hackintosh UHD 630)

## 📦 Working 
- Facetime
- Usb Ports
- Ethernet
- Wifi and Bluetooth
- Brightness Keys
- Battery (porcentage)
- Keyboard
- Speakers and microphone
- Audio Jack port
- Web Cam

## ✖️📦 NOT Working 
- Trackpad

## Necessary programs
- Explorer++ https://explorerplusplus.com/
- BalenaEtcher https://etcher.balena.io/
- miniTool Partion Wizard Free https://www.partitionwizard.com/

## Intructions
 1.- Download image vanilla Sonoma from Olarilla page 
 2.- With BalenaEtcher flash image in usb 16gb
 3.- Open minitool Partion Wizard -> search your USB -> Select the partition call EFI (Fat32) -> click right and change the Letter -> Select any letter and click in Aply
 4.- Open Explorer++ like Administrator and seach your USB call EFI, delete folder EFI and replace with the folder EFI from this github
 5.- Configuration your bios https://dortania.github.io/OpenCore-Install-Guide/config-HEDT/ivy-bridge-e.html#intel-bios-settings
 6.- Install Sonoma in your Computer