
# EFI Hackintosh for MSI B760M GAMING PLUS WIFI + i7-12700KF + RX6600

<p align="center">
	<img src="https://asset.msi.com/resize/image/global/product/product_1697770219f31a9d623d8f4bf915eae1ce1891b12e.png62405b38c58fe0f07fcef2367d8a9ba1/1024.png" alt="MSI B760M GAMING PLUS WIFI" width="500"/>
</p>

## Hardware Components

- **Motherboard:** MSI B760M GAMING PLUS WIFI
- **CPU:** Intel Core i7-12700KF
- **GPU:** XFX Swft 210 RX6600 8GB GDDR6
- **Storage:** Lexar 2TB NM790 SSD PCIe Gen4 NVMe M.2
- **Cooler:** Cooler Master Hyper 620S Dual Tower CPU Air Cooler
- **PSU:** Cooler Master GX II GOLD 750 FM 750W 80plus GOLD
- **RAM:** Crucial Pro DDR5 64GB (2x32GB) 6000MHz CL40

## Working Status

### What works
- Boot with OpenCore
- AMD RX6600 GPU acceleration
- Audio (AppleALC)
- Ethernet (LucyRTL8125Ethernet)
- USB (USBMap, USBToolBox)
- Bluetooth (IntelBluetoothFirmware + IntelBTPatcher)
- NVMe SSD (Lexar NM790)
- Sleep
- SMC sensors (VirtualSMC, SMCProcessor, SMCSuperIO, SMCRadeonSensors)
- Display brightness (if applicable)
- AirDrop, Handoff, Sidecar (except features requiring T2)
- CPU Power Management (CPUFriend, CPUFriendDataProvider, SSDT-PLUG-ALT)

### What does NOT work / Limitations
- **Onboard Wi-Fi:** Not natively supported, but can be enabled using OCLP (OpenCore Legacy Patcher) or AirportItlwm.kext (with limitations)
- **T2 features:** Not available (Touch ID, Apple Pay, full FileVault, etc.)
- **Unlock with Apple Watch:** Not available
- **FaceTime/iMessage:** May require additional SMBIOS/serial configuration

## Additional Notes
- The system is stable for daily use.
- It is recommended to keep a backup of your EFI before updating OpenCore or macOS.
- For Wi-Fi support, check OCLP documentation or try AirportItlwm.kext.

---

> For help, please visit the official Dortania OpenCore Install Guide and read the documentation:
> [https://dortania.github.io/OpenCore-Install-Guide/prerequisites.html#prerequisites](https://dortania.github.io/OpenCore-Install-Guide/prerequisites.html#prerequisites)
