# hackintosh-z790-opencore
This repository contains files and information for installing and configuring macOS 14 Sonoma on my Z790 + Alder Lake PC. I've made this public for the benefit of others using similar hardware, but I make no guarantees that this configuration will work the same on your PC.

The configuration was built by following the Dortania Install Guide (https://dortania.github.io/OpenCore-Install-Guide/) using the Comet Lake configuration, combined with the steps in ChrisWayg's OpenCore Alder Lake Guide on /r/hackintosh (https://www.reddit.com/r/hackintosh/comments/sp1zgv/opencore_alder_lake_12thgen_intel_hackintosh/).

My PC had a pre-existing Windows 10 installation on a separate SSD, which allowed me to collect ACPI files and USB port mapping on the target hardware before installing macOS.

## Hardware

- MSI PRO Z790-P WIFI ATX LGA1700 Motherboard
- Intel Core i7-12700K 3.6 GHz 12-Core Processor
- Sapphire PULSE Radeon RX 6800 16 GB Video Card
- Crucial Pro 64 GB (2 x 32 GB) DDR5-5600 CL46 Memory
- Intel 660p 1.02 TB M.2-2280 PCIe 3.0 X4 NVME Solid State Drive

Full parts list: https://pcpartpicker.com/list/MDdJcH

## BIOS

_TODO: add BIOS version and settings_

## Software

- macOS Sonoma 14.5
- OpenCore 1.0.0
- _TODO: add kext versions_

## Results

What's working:
- Booting into macOS
- USB ports
- GPU acceleration
- Audio input and output
- Ethernet

What's not working (yet):
- WiFi
- Bluetooth
- AirDrop
- Sleep/wake

Performance benchmarks will be added after functional issues are resolved.

## References

- Dortania OpenCore Install Guide: https://dortania.github.io/OpenCore-Install-Guide/
- ChrisWayg's OpenCore Alder Lake Guide: https://www.reddit.com/r/hackintosh/comments/sp1zgv/opencore_alder_lake_12thgen_intel_hackintosh/
- Similar build configurations:
  - https://github.com/glekner/GIGABYTE-Z690I-Hackintosh
  - https://github.com/conversun/Hackintosh-MSI-Z790i-EDGE-13900K-6900XT-OpenCore
  - https://github.com/nphuly/alder-lake-opencore
  - https://www.reddit.com/r/hackintosh/comments/18uteuo/sonoma_on_i714700k_with_the_asrock_z90mitx_wifi/
  - https://www.reddit.com/r/hackintosh/comments/1bg0a49/success_intel_14gen_macos_sonoma/
