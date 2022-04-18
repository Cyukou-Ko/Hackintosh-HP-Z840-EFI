# Hackintosh-HP-Z840-EFI

OpenCore Hackintosh EFI file for HP Z840. Please refer to the detailed: https://www.bertonhu.com/2021/12/24/HP-Z840-Hackintosh-Big-Sur.html

## Ver
* OpenCore: 0.7.9
* macOS: Big Sur 11.6.5

## Known Issues
1. Sidecar not working: According to some feedback from Reddit Hackintosh threat, Sidecar relies on the iGPU to work, but the Xeon family does not have an iGPU component.
2. After enabled FileVault, the Bluetooth keyboard cannot be used in the unlock screen when the operating system is booting.
3. About This Mac menu does not display the CPU model number properly.
