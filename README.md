# Monterey on Atermiter X79 + E5-2620v2 + AMD RX6600 | OpenCore

## I made publicly available my configuration, so people struggling like I was can at least get closer to a solution.

### Check this post on Reddit, for which I made this repository:

#### https://www.reddit.com/r/hackintosh/comments/yzpjc0/success_monterey_on_atermiter_x79_e52620v2_amd/

### The hardwae this is made for:

- CPU: Xeon E5-2620 v2 | 6 cores 12 threads | 2.1Ghz turbo 2.6Ghz.
- GPU: Sapphire PULSE | AMD RX6600 8GB.
- RAM: 16GB 1066 MHz ECC DDR3 (4x4GB).
- Motherboard: Atermiter/Essenc X79G v1.3.
- BIOS revision: X79G00E - Aptio Setup Utility Version 2.15.1236.
- Ethernet Card: Realtek RTL8111.
- Wifi/BT Card: CSR 4.0 Bluetooth USB card (Qualcomm/Cambridge Silicon Radio CSR8510).

### I mad three different EFI configurations as described below:

- [EFI VirtualSMC-INSTALLATION](https://github.com/VivaPeron/EFI-OC-AtermiterX79-E5-2620v2-RX6600/tree/main/EFI%20VirtualSMC-INSTALLATION): This is for booting the installer. It has video acceleration disabled.
- [EFI VirtualSMC](https://github.com/VivaPeron/EFI-OC-AtermiterX79-E5-2620v2-RX6600/tree/main/EFI%20VirtualSMC): This one is very stable and safe to use to boot into the Monterey right after it's been installed. Includes BrcmPatchRAM.
- [EFI FakeSMC3](https://github.com/VivaPeron/EFI-OC-AtermiterX79-E5-2620v2-RX6600/tree/main/EFI%20FakeSMC3): This one replaces VirtualSMC with FakeSMC3. Includes BrcmPatchRAM.


You can test them if want. But, please, take into consideration that if your CPU, motherboard, or GPU, are different, then it might not work if you don't adapt it. The SMBIOS info like serials, UUID, etc are safe. But please change them as someone else might be using them already.
