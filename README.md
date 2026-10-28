# tahoe-t480
A opencore EFI for macos tahoe

## SMBIOS

The serial number, MLB, SystemUUID and ROM in `EFI/OC/config.plist` are left blank. Before booting, generate your own MacBookPro16,1 values (for example with [GenSMBIOS](https://github.com/corpnewt/GenSMBIOS)) and fill them in under `PlatformInfo > Generic`. GenSMBIOS doesn't make `ROM`; set it to your network card's MAC address.
