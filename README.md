### macOS Sonoma

macos Sonoma 14.5 (23F79)

OpenCore 1.0.0

### Hardware

- CPU: Intel i5-12490F
- Motherboard: ASUS TX GAMING B760M WIFI D4
- RAM: 32G @ DDR4
- SSD: WD_BLACK SN850X @ 1T
- Ethernet: MCX4121A-ACAT
- GPU: AMD Radeon™ RX 6800 XT
- Display: Studio Display

### What works

- macOS Sonoma
- Wi-Fi & Bluetooth
- USB, all ports.
- Sleep/Wake
- Studio Display (via FIBBR TF-VRA DisplayPort to USB-C Cable)
  - Camera
  - Speaker
  - Microphone
  - Brightness

### How to use

1. Make your USB installer with [OpenCore Guide](https://dortania.github.io/OpenCore-Install-Guide/installer-guide/).
2. Generate SMBIOS via [OCAuxiliaryTools](https://github.com/ic005k/OCAuxiliaryTools).

| ProvideCurrentCpuinfo |         |
| --------------------- | ------- |
| P-cores + E-cores     | Enbale  |
| P-cores               | Disable |

**You CAN NOT use SMBIOS from this repository, it MUST be unique for every macOS installation.**

### BIOS Settings

| VT-d               | Enabled  |
| ------------------ | -------- |
| XHCI-Hand-Off      | Enabled  |
| Above 4G Decoding  | Enabled  |
| Fast Boot          | Disabled |
| CSM                | Disabled |
| Secure Boot        | Disabled |
| Resize Bar Support | Enabled  |

### Thanks/Credits

- [OpenCore](https://dortania.github.io/OpenCore-Install-Guide/)
- [OCAuxiliaryTools](https://github.com/ic005k/OCAuxiliaryTools)

- [oldweek](https://github.com/oldweek/ASUS-TX-B760m-hackintosh)