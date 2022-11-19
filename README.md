======== EFI and files ========
I made publicly available my configuration, so people struggling like I was can at least get closer to a solution. In this repo you will find three EFI folders:
- EFI VirtualSMC-INSTALLATION: This is for booting the installer. It has video acceleration disabled.
- EFI VirtualSMC: This one is very stable and safe to use to boot into the Monterey right after it's been installed. Includes BrcmPatchRAM,
- EFI FakeSMC3: This one replaces VirtualSMC with FakeSMC3. Includes BrcmPatchRAM
You can test them if want. But, please, take into consideration that if your CPU, motherboard, or GPU, are different, then it might not work if you don't adapt it. The SMBIOS info like serials, UUID, etc are safe. But please change them as someone else might be using them already.
