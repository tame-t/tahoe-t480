# tahoe-t480
A opencore EFI for macos tahoe on the thinkpad t480,
this is a modified version of this EFI https://github.com/tame-t/macos-15-t480,
there are many improvement of it that a made for battery performance, battery life, video streaming, sleep, etc.

## SMBIOS
The serial number, MLB, SystemUUID and ROM in `EFI/OC/config.plist` are left blank. Before booting, generate your own MacBookPro16,1 values (for example with [GenSMBIOS](https://github.com/corpnewt/GenSMBIOS)) and fill them in under `PlatformInfo > Generic`. GenSMBIOS doesn't make `ROM`; set it to your network card's MAC address.

## WIFI
You will need to use oclp mod to get wifi working https://github.com/laobamac/OCLP-Mod/releases/tag/3.1.9,
this is a more detail guide https://github.com/5T33Z0/OCLP4Hackintosh/blob/main/Enable_Features/AirportItllwm_Sequoia.md

## Disclaimer
This EFI is made for my ThinkPad t480, I'm not promising that its going to work for your device,
and i am not responsible for causing harm to your device in anyway.

My ThinkPad pro
<img width="1920" height="1080" alt="Screenshot 2026-10-28 at 11 06 47" src="https://github.com/user-attachments/assets/6e5364c5-906e-4e05-a1b6-40afc8377a56" />
