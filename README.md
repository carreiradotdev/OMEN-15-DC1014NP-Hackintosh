# HP OMEN 15-DCxxxx MAC-OSX CATALINA GUIDE

#### Laptop Specs

- Intel(R) Core i5-9300H
- Intel(R) UHD 630
- Nvidia GeForce GTX 1650 (Turing GPUs have no support in Mac OS)
- Intel(R) Dual Band Wireless-AC 9560
- NVMe 

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

#### What doesn't work:
- ── Nvidia GeForce GTX 1650 (Turing GPUs have no support in Mac OS)
- ── ~~Touchpad~~ (As of 1/03/2021, Touchpad is working with one finger, buttons are still unresponsive.)
- ── Sleep

#### Known bugs:
- ── For some reason, my MX Master 3 doesn't connect to Bluetooth. Airpods seem to work fine.

#### Kext
Kexts in **Bold** are required to boot to the installer:
- ── **VirtualSMC**
- ── **Lilu**
- ── **WhateverGreen**
- ── AppleALC (with codec injection number 13)
- ── SMCBatteryManager.kext
- ── SMCSuperIO
- ── SMCProcessor.kext 
- ── NoTouchID
- ── [IntelBluetoothFirmware](https://github.com/OpenIntelWireless/IntelBluetoothFirmware)
- ── [WIFI](https://github.com/OpenIntelWireless/itlwm)
