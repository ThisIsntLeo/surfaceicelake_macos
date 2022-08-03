This EFI is for macOS on Surface Devices.
This **ONLY** works on IceLake. (10th Gen Intel)
Compatible Devices
Surface Pro 7
Surface Laptop 3 13"
Surface Laptop Go 1st Gen
Surface Book 3
Note: Due to airportitwlm (WiFi kext) having multiple kexts for different versions of macOS, there will be different EFI Folders.
HWModels:
Surface Pro 7, Surface Laptop 3 13", Surface Laptop Go 1st Gen
MacBookAir9,1
Surface Book 3 13"
MacBookPro16,3
Surface Book 3 15"
MacBookPro16,4
Min macOS:
Models with HWModel "MacBookAir9,1": Catalina (10.15.3)
Models with HWModel "MacBook16,3": Catalina (10.15.4)
Models with HWModel "MacBookPro16,4": Catalina (10.15.5)
Latest macOS Catalina: 10.15.7

PLEASE, PLEASE add SMBIOS data into config.plist, otherwise macOS will not boot but will say "This version of Mac OS X is not supported" and shut down after 30 sec.

Thanks
to OpenIntelWireless for Wifi
to Xiashangning for Keyboard, trackpad and touch

Kexts used:
https://www.playbook.com/s/thisisntleo/8Z8in34KKber4vfCph3CbRHK
