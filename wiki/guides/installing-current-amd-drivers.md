---
permalink: /guides/installing-current-amd-drivers
redirect_from:
  - /installing-current-amd-drivers
sidecar:
  - title: Guide Compatibility
  - title_sm: Framework Laptop 13
  - table:
    - label: Intel 11th Gen
      value: ✗
    - label: Intel 12th Gen
      value: ✗
    - label: Intel 13th Gen
      value: ✗
    - label: AMD 7040 Series
      value: <b>✓</b>
    - label: Intel Core Ultra 1
      value: ✗
  - gap: true
  - title_sm: Framework Laptop 16
  - table:
    - label: AMD 7040 Series
      value: <b>✓</b>

---
# Installing Current AMD Drivers
{% include sidecar.html %}

The AMD drivers included with Framework's driver bundles are generally updated only when a new BIOS version is released, meaning they can be out of date. It may be useful to update the graphics driver for the latest game compatibility or driver features. However, Framework's official recommendation is that users run the drivers included in the driver bundle for their device.[^2]

Community members have found AMD driver version 24.7.1 to be stable.[^1] Version 24.8.1 is also generally stable but includes a bug where the Radeon control panel will launch randomly when the computer resumes from sleep.

There have been mixed reports of version 24.12.1 working on the latest BIOS version. Users in the Framework Discord server have reported success installing 24.12.1 after updating the BIOS of their Framework Laptop 16. But, others have reported that 24.12.1 is still failing to install. So, if you would like a stable install please use 24.7.1 or 24.8.1. [[citation needed]](/framewiki:citation-needed)

## Requirements

- BIOS version 3.05 (latest at the time of writing)
- Framework driver bundle installed

## Steps

1. Download the latest AMD Driver bundle, stable or risk it with 24.12.1.
    - 24.7.1: <https://drivers.amd.com/drivers/whql-amd-software-adrenalin-edition-24.7.1-win10-win11-july19-rdna.exe>
    - 24.8.1: <https://drivers.amd.com/drivers/whql-amd-software-adrenalin-edition-24.8.1-win10-win11-aug-rdna.exe>
    - 24.12.1: <https://drivers.amd.com/drivers/installer/24.20/whql/amd-software-adrenalin-edition-24.12.1-minimalsetup-241204_web.exe>

2. Run installer.
3. Reboot computer.

## Troubleshooting

If you find that the driver bundle hangs or that Windows freezes while installing the AMD driver bundle:

1. Download Display Driver Uninstaller and the latest Framework driver bundle from <https://www.guru3d.com/download/display-driver-uninstaller-download>
2. Copy DDU application and driver bundle to USB flash drive or other storage media.
3. Connect flash drive to Framework Laptop.
4. Reboot laptop into Safe Boot **without** networking.
    - Follow method #1 in this article: <https://www.digitalcitizen.life/windows-11-safe-mode>
5. Run DDU picking the options to remove all AMD drivers and reboot when finished.
6. Log into Windows
7. Install Framework driver bundle to get laptop drivers installed.
8. Either install one of the stable driver versions or keep the Framework drivers.

# References
[^1]: <https://community.frame.work/t/frwk16-amd-software-adrenalin-edition-24-9-1-issues/58567> [Archived](https://web.archive.org/web/20250114032425/https://community.frame.work/t/frwk16-amd-software-adrenalin-edition-24-9-1-issues/58567) 
[^2]: <https://community.frame.work/t/frwk16-amd-software-adrenalin-edition-24-9-1-issues/58567/3> [Archived](https://web.archive.org/web/20250114044837/https://community.frame.work/t/frwk16-amd-software-adrenalin-edition-24-9-1-issues/58567/3) 
