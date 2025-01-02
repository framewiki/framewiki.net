---
guide: true
---
# Installing Current AMD Drivers

| Framework Laptop 13 | Applicable |
|---------------------|------------|
| Intel 11th Gen      | ✗          |
| Intel 12th Gen      | ✗          |
| Intel 13th Gen      | ✗          |
| AMD 7040 Series     | **✓**          |
| Intel Core Ultra 1  | ✗          |

| Framework Laptop 16 | Applicable |
|---------------------|------------|
| AMD 7040 Series     | **✓**          |

The AMD drivers included with Framework's driver bundles are quite old. Particular the graphics driver which you may want to update for the latest game compatibility or driver features. Here are some recommendations and observations from the community if you would like to install the latest graphics driver bundle from AMD.

It is recommend that you install AMD driver version 24.7.1 if you would like a stable installation based on community experience. Version 24.8.1 is also stable but includes an annoying bug where the Radeon control panel will launch randomly when the computer resumes from sleep.

There have been mixed reports of version 24.12.1 working on the latest BIOS version. Users in the Framework Discord server have reported success installing 24.12.1 after updating the BIOS of their Framework Laptop 16. But, others have reported that 24.12.1 is still failing to install. So, if you would like a stable install please use 24.7.1 or 24.8.1.

Requirements:

- BIOS version 3.05, latest at the time of writing.
- Framework driver bundle installed.

Steps:

1. Download the latest AMD Driver bundle, stable or risk it with 24.12.1.
    - 24.7.1: [https://drivers.amd.com/drivers/whql-amd-software-adrenalin-edition-24.7.1-win10-win11-july19-rdna.exe](https://drivers.amd.com/drivers/whql-amd-software-adrenalin-edition-24.7.1-win10-win11-july19-rdna.exe)
    - 24.8.1: [https://drivers.amd.com/drivers/whql-amd-software-adrenalin-edition-24.8.1-win10-win11-aug-rdna.exe](https://drivers.amd.com/drivers/whql-amd-software-adrenalin-edition-24.8.1-win10-win11-aug-rdna.exe)
    - 24.12.1: [https://drivers.amd.com/drivers/installer/24.20/whql/amd-software-adrenalin-edition-24.12.1-minimalsetup-241204_web.exe](https://drivers.amd.com/drivers/installer/24.20/whql/amd-software-adrenalin-edition-24.12.1-minimalsetup-241204_web.exe)

2. Run installer.
3. Reboot computer.

### Troubleshooting:

If you find that the driver bundle hangs or that Windows freezes while installing the AMD driver bundle then please follow these steps. Don't Panic!

1. Download Display Driver Uninstaller and the latest Framework driver bundle.
    - [https://www.guru3d.com/download/display-driver-uninstaller-download/](https://www.guru3d.com/download/display-driver-uninstaller-download/)
2. Copy DDU application and driver bundle to USB flash drive or other storage media.
3. Connect flash drive to Framework Laptop.
4. Reboot laptop into Safe Boot **without** networking.
    - Follow method #1 in this article: [https://www.digitalcitizen.life/windows-11-safe-mode/](https://www.digitalcitizen.life/windows-11-safe-mode/)
5. Run DDU picking the options to remove all AMD drivers and reboot when finished.
6. Log into Windows
7. Install Framework driver bundle to get laptop drivers installed.
8. Either install one of the stable driver versions or keep the Framework drivers.
