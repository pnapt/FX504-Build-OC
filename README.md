## ASUS-FX504GD-Hackintosh
> my config on asus fx504gd

(/image.png)

## Disclaimer
> Do as your own risk
## Info
**My Setup/configuration**
| Specs | Details |
|------------|-------------------------------|
| Model | ASUS FX504GD |
| BIOS Ver | 320 |
| macOS | Big Sur Version 11.5.2 (Build 20G95) |
| Dual boot OS | Windows 10 21H1 |
| Processor | Intel Core i5 8300H |
| Memory | 2x8GB DDR4 2666MHz |
| Boot Drive | WD Black SN750 500 GB |
| iGPU | Intel UHD Graphics 630 |
| dGPU | NVIDIA GeForce GTX 1050 |
| Wifi | Intel Wireless-AC 9560 |
**More Laptop info**
| Specs | Details |
|------------|-------------------------------|
| Sound | Realtek ALC255 |
| HDD 2.5 | 1TB |
**What works**
- [x] Intel UHD Graphics 630 + HDMI ___Audio Not Tested!___
- [x] Screen brightness + fnkeys
- [x] Audio (Speaker + Internal Mic + Headphone + External Mic)
- [x] All USB Port
- [x] LAN + Wifi
- [x] M.2 NVME + 2.5" HDD
- [x] Battery status
- [x] Sleep/Wake
- [x] Keyboard + TouchPad gestures
- [ ] Webcam
**Not work**
- [ ] dGPU
- [ ] Bluetooth
**Bugs**
- [ ] Wifi sometime not work
- [ ] Hdmi sometime not work

## Opencore config setups
SMbios MacbookPro15,2
**More info**
https://dortania.github.io/OpenCore-Install-Guide/  

**Misc Fixes**
Fix Dualboot timezone: https://www.tonymacx86.com/threads/fix-incorrect-time-in-windows-osx-dual-boot.133719/  

## Credit
# Thanks to
**People who made opencore project and kext**
https://github.com/acidanthera/ for Opencore
**People who made config for this laptop**
https://github.com/PoomSmart for guide fx504 
    Repo:https://github.com/PoomSmart/ASUS-FX504GE-Hackintosh
https://github.com/wilsomwong for made cool EFI 
    Repo:https://github.com/wilsomwong/Asus-TUF-FX504GE-Hackintosh
https://github.com/dongcodebmt for guide opencore laptop 
    Repo:https://github.com/dongcodebmt/VX5-591G-OpenCore
https://github.com/RobyRew for new hdmi patch fx504 
    Repo:https://github.com/RobyRew/ASUS-FX504GE-Hackintosh_OpenCore