# ASUS-FX504GD-Hackintosh
my modify config that work with FX504GD i5 model
> Archive EFI 
    https://drive.google.com/drive/folders/1PhjAvpW_ok6pH14waik0sjYFQl8xssbo
> My laptop issue
    webcam not working even in windows so i cant test it

<img src="https://github.com/pnapt/ASUS-FX504GD-Hackintosh/blob/main/placeholder01.png"/>

## Disclaimer
> Do as your own risk

# Info
**My Setup/configuration**
| Specs | Details |
|------------|-------------------------------|
| Model | ASUS FX504GD |
| BIOS Ver | 322 |
| macOS | Big Sur Version 11.5.2 (Build 20G95) |
| Dual boot OS | Windows 10 21H1 |
| Processor | Intel Core i5 8300H |
| Memory | 2x8GB DDR4 2666MHz |
| Boot Drive | WD Black SN750 500 GB |
| iGPU | Intel UHD Graphics 630 |
| dGPU | NVIDIA GeForce GTX 1050 |
| Wifi | Intel Wireless-AC 9560 |

**More Laptop info**
| Hardware | Details |
|------------|-------------------------------|
| Sound | Realtek ALC255 |
| HDD 2.5 | 1TB |

**Works**
- [x] Ethernet(LAN) 
- [x] Wifi (sometime wont work in 1st boot)
- [x] Intel UHD Graphics 630 + HDMI (sometime wont work in 1st boot) ___Audio Not Tested!___
- [x] Screen brightness + fnkeys
- [x] Audio (Speaker + Internal Mic + Headphone + External Mic) 
- [x] All USB Port
- [x] M.2 NVME + 2.5" HDD
- [x] Battery status
- [x] Sleep/Wake
- [x] Shutdown
- [x] Build in Keyboard
- [x] Webcam
- [x] trackpad+gestures

**Not work**
- [ ] dGPU (of course apple have ended support)
- [ ] Bluetooth 
**Bugs**
in commit

## Opencore config setups
SMbios MacbookPro15,2

**More info**
- https://dortania.github.io/OpenCore-Install-Guide/  

**Misc Fixes**
- Fix Dualboot timezone: https://www.tonymacx86.com/threads/fix-incorrect-time-in-windows-osx-dual-boot.133719/  

# Credit
## Thanks to

**People who made opencore project and kext**
https://github.com/acidanthera/ for Opencore

**People who made config for this laptop**
- https://github.com/PoomSmart for guide fx504 
    Repo:https://github.com/PoomSmart/ASUS-FX504GE-Hackintosh
- https://github.com/wilsomwong for made cool EFI 
    Repo:https://github.com/wilsomwong/Asus-TUF-FX504GE-Hackintosh
- https://github.com/dongcodebmt for guide opencore laptop 
    Repo:https://github.com/dongcodebmt/VX5-591G-OpenCore
- https://github.com/RobyRew for new hdmi patch fx504 
    Repo:https://github.com/RobyRew/ASUS-FX504GE-Hackintosh_OpenCore
