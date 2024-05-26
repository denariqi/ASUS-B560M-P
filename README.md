# ASUS-B560M-P Hackintosh
- Mainboard: ASUS B560M-P
- CPU: 10th Gen Intel(R) Core(TM) i5-10400 (F)
- RAM: DDR4 2666 32GB (16GB+16GB)
- GPU: AMD RX570 4G (Sapphire)
- LAN: Intel Ethernet I219-V
- Wi-Fi: BCM94360CD
- Audio: ALC897
- Generic: MacPro7.1
- macOS: Monterey
- BASE EFI: OpencCore 9.8
# ACPI
- SSDT-EC.aml
- SSDT-PLUG.aml
- SSDT-RTCAWAC.aml
- SSDT-USB-Reset.aml
- SSDT-USBX.aml
# Drivers
- HfsPlus.efi
- OpenRuntime.efi
- ResetNvramEntry.efi
- ToggleSipEntry.efi
- OpenCanopy.efi
# Tools
- CleanNvram.efi
- CFGLock.efi
- VerifyMsrE2.efi
- OpenShell.efi
# KextS
- Lilu
- VirtualSMC
  + SMCProcessor
  + SMCSuperIO
- WhateverGreen
- AppleALC
- IntelMausi
- NVMeFix
- XHCI-unsupported
- USBPortsB560 (USBInjectAll)
- RestrictEvents
- AGPMInjector
- RadeonBoost
