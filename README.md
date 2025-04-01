# Machinist X99 PR9 + Intel Xeon E5 2620v3 + GTX 750TI

![about-12 3 1](https://raw.githubusercontent.com/nilsen-daniel/EFI-X99-PR9-INTEL-XEON-E5-2620V3/refs/heads/main/Images/SpecsX99.png)

**Latest working macOS**: 10.13.6 (17G14033) - Need to open app store and itunes before to show up the update option
<br>
**Current OpenCore**: 1.0.4

## Attention 
Update **config.plist** in PlatformInfo > Generic with YOUR informations.
<br><br>
*1. MLB (Board Serial)
<br>
2. ROM (Mac Address)
<br>
3. SystemSerialNumber (Serial)
<br>
4. SystemUUID (SmUUID)*

Please use [*genSMBIOS*](https://github.com/corpnewt/GenSMBIOS/archive/refs/heads/master.zip) for generate values for above itens.
<br>
Please use [*ProperTree*](https://github.com/corpnewt/ProperTree/archive/refs/heads/master.zip) for configure/edit your config.plist.

## Complete hardware specs
- Xeon E5 2620V3
- Machinist X99 PR9
- GTX-750TI 2GB PCYes
- 2x 8Gb DDR4 2667Mhz Kllisre

## What works
- macOS High Sierra
- Audio
- HDMI
- All USB ports
- Everything iCloud related (Drive, iMessage, Facetime, unlock with Apple Watch, etc)
- Shutdown/Reboot/Update to newer macOS builds over time

## What doesn't work
- Sleep Mode
- The Rest I Dont Know Yet

## Kexts used:
- CpuTscSync.kext
- Lilu.kext
- RealtekRTL8111.kext - Working with 2.4.2
- SMCSuperIO.kext
- SMCProcessor.kext
- RestrictEvents.kext
- USBMapLegacy.kext
- VirtualSMC.kext
- VoodooHDA.kext
- WhateverGreen.kext

## Mapped USB
![about-12 3 1](https://raw.githubusercontent.com/nilsen-daniel/EFI-X99-PR9-INTEL-XEON-E5-2620V3/refs/heads/main/Images/USBmap.png)

## Thanks/Credits
- [Opencore Team](https://dortania.github.io/getting-started/)
- [luchina-gabriel BASE-EFI-INTEL-HEDT-4THGEN-X99-HASWELL-E](https://github.com/luchina-gabriel/BASE-EFI-INTEL-HEDT-4THGEN-X99-HASWELL-E-PUBLIC)

## Best Place To Learn And Best Community On Discord - Universo Hackintosh
- [Access Discord](https://discord.universohackintosh.com.br)
