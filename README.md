# B365-M-Auros-Elite-EFI-Hackintosh
B365 M Auros Elite EFI for Hackintosh

Luckily and Happily, I have finally built my first Hackintosh.

Then, my experiences are as follows:

Specifications:
- CPU: Intel Core i3-9100F 3.6 GHz Quad-Core Processor
- Motherboard: Gigabyte B365 M AORUS ELITE (rev. 1.0)
- RAM: 16 GB (2 x 8 GB) DDR4-2400 Memory
- SSD: Sandisk x300s 256GB M.2 SATA SSD
- GPU: MSI Radeon RX 570 ARMOR 4G OC

BIOS Settings:
- Save & Exit → Load Optimized Defaults
- M.I.T. → Advanced Memory Settings Extreme Memory Profile(X.M.P.): Profile1
- BIOS → Fast Boot: Disabled
- BIOS → Windows 8/10 Features: Other OS
- BIOS → LAN PXE Boot Option ROM: Disabled
- BIOS → Storage Boot Option Control: UEFI
- Peripherals → Super IO Configuration → Serial Port: Disabled
- Peripherals → Network Stack Configuration → Network Stack: Disabled
- Peripherals → USB Configuration → XHCI Hand-off: Enabled
- Chipset → Vt-d: Disabled
- Chipset → IOAPIC 24-119 Entries: Enabled

Based on the GPU you’re using change the following settings:

Dedicated graphics card:
- Peripherals → Initial Display Output: PCIe 1 Slot
- Chipset → Integrated Graphics: Disabled

SMIBIOS: iMac Pro, largely because my CPU does not have iGPU.

Kexts:
- AppleALC.kext
- IntelMausiEthernet.kext
- Lilu.kext
- SMCProcessor.kext
- SMCSuperIO.kext
- USBInjectAll.kext
- VirtualSMC.kext
- WhateverGreen.kext

What works:
- Sound
- Intel Ethernet
- USB-C Port
- USB3 Speeds
- AMD Graphics Card
- Sleep/Wake
- App Store, iBooks, iMessage, iCloud

Intallation:
- Create the macOS installer.
- Install Clover EFI to your macOS installer media.
- Download my EFI From Here
- Copy my EFI to the Clover EFI partition of your installation media.
- After all steps above finished, your macOS installation media will be ready.

That's it and I hope this post would be helpful for someone who would like to build the Hackintosh.
