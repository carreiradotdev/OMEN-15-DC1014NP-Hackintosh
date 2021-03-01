# HP OMEN 15-DCxxxx MAC-OSX CATALINA GUIDE

#### Laptop Specs

- Intel(R) Core i5-8300H
- Intel(R) UHD 630
- Nvidia GeForce GTX 1650 (Turing GPUs have no support in Mac OS)
- Intel(R) Dual Band Wireless-AC 9560
- NVME and Sata hdd

#### What works:
- [x] Intel GPU.
- [x] Display w/ brightness control.
- [x] Keyboard
- [x] USB with Fast Charging
- [x] Wifi + Bluetooth features
- [x] Battery.
- [x] Power management.
- [x] Webcam.
- [x] Audio.
- [TODO] Sleep.

#### What doesn't work:
- ── Nvidia GeForce GTX 1650 (Turing GPUs have no support in Mac OS)
- ── Touchpad
- ── Sleep

#### Known bugs:
- ── For some reason, my MX Master 3 doesn't connect to Bluetooth. Airpods seem to work fine.

#### Kext
Kexts in **Bold** are required to boot to the installer:
- ── **VirtualSMC**
- ── **Lilu**
- ── **WhateverGreen**
- ── **VoodooPS2Controller** (Rehabman Kext for the mouse and keyboard)
- ── AppleALC (with codec injection number 13)
- ── SMCBatteryManager.kext
- ── SMCSuperIO
- ── SMCProcessor.kext 
- ── NoTouchID
- ── [IntelBluetoothFirmware](https://github.com/OpenIntelWireless/IntelBluetoothFirmware)
- ── [WIFI](https://github.com/OpenIntelWireless/itlwm) (You have to build it yourself)

You can download them [here](https://dortania.github.io/vanilla-laptop-guide/OpenCore/ktext.html)

#### Clover Setup

Use the lastest version of Clover (version i am using is v5.0 r5119)
- ── Clover UEFI
- ── AptioMemoryFix
- ── EmuVariableUEFI
- ── Script to target volume
- ── APFS and HFS+ Driver

