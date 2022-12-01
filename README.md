# Lenovo-Thinkpad-X1-Tablet-Gen-2-Hackintosh
** **DISCLAIMER** **

This is not a build suitable for novice users, Do not attempt to use this EFI if you don't even have the basics of Hackintosh, I'm not here to babystep you on how Hackintosh works or where to download Mac OS (You should have this prerequisite knowledge before proceeding to here. This repositry is only limited to technical discussions related to this Specific Device. Now that's out of the way, if you have any inputs/improvements/further development, you're more than welcomed to bring it here :)

** **NOTE** **
Please generate your own SMBIOS values (Serial, UUID, MLB, ROM) before using this EFI. SMBIOS model is MacBook10,1 (I have deleted them due to privacy reasons). After that, you should be able to use Apple Services (iMessage, FaceTime, App Store, iTunes Store, etc...)

**Current Booted Version** : Opencore 0.8.6

**Current Status** : Beta build WIP (still needs development)

**Supported OS** : Big Sur / Monterey / Ventura

**Machine Specs** :
- CPU: i5-7Y54/ i5-7Y57 / i7-7Y75
- GPU: Intel HD615
- Screen: 12" FHD+ 2160x1440
- Memory: 8GB 
- Wifi & BT: AC8265

**What's working** :
- GPU acceleration (Intel HD615)
- Intel Wifi & Bluetooth
- USB attached Keyboard & Trackpoint
- USB ports
- Audio
- Sleep & Wake
- Built-in Micro SD Card reader
- Brightness Control
- iMessage, FaceTime, App Store, iTunes Store (After generating your own SMBIOS values)

**What's currently not working** :
- Touch Screen (Connected through I2C protocol)
- USB attached trackpad
- Both Cameras (Front facing & rear facing) (Connected through I2C protocol)


