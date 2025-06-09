---
permalink: /products/framework-desktop
sidecar:
    - image: /assets/framework-desktop.png
      text: Image courtesy of Framework
    - title: Framework Desktop
      title_sm: SFF Desktop PC
    - table:
        - label: Announced
          value: Feb 25, 2025
        - label: Pre-Orders Opened
          value: Feb 25, 2025
        - label: Status
          value: 🟢 Preorders Open
---
# Framework Desktop
{% include sidecar.html %}
Framework Desktop is a small-form-factor desktop PC announced on February 25, 2025 during the [Framework [2nd Gen] event](/events/2nd-gen), making it [Framework’s](/framework-computer-inc) first non-laptop product line.[^1] Preorders opened immediately following the live event, with the top-spec Framework Desktop config, featuring 128 GB of RAM, priced at $1999.

The device is Framework's only product to use soldered RAM due to bandwidth limitations. Framework said they "spent months working with AMD to explore ways around this," but were unable.[^2] They also said they intentionally made memory pricing more reasonable than competitors.

Framework Desktop can be used to locally run large language models such as Llama 3.3 70B Q6 at conversation speed.[^2]. They can also be networked into a cluster using 5 gigabit networking to run larger models. During the launch event, AMD announced they will give away 100 Framework Desktop devices to AI developers.[^1]

## Customization
Framework Desktop supports the ATX standard, allowing users to replace the mainboard with any Mini-ITX form factor mainboard, or use the Framework mainboard in any Mini ITX chassis using a standard power supply. It can also be rack-mounted, including in a 10-inch rack, using a standard rackmount case or tray.

The case is available with solid black or translucent side panel options and an optional carry handle, which Framework emphasized as useful for traveling to LAN parties.[^1] It also adds a new option for cosmetic customization in the form of tiles on the front panel. Framework sells tiles in a variety of colors and designs, and the tiles can be 3d printed, so users can design custom options. The tiles are purely cosmetic and have no electrical connection available.

Any standard 120mm fan is compatible with the Framework Desktop cooler. In the configurator, Black or RGB fans designed with Cooler Master, and Noctua NF-A12x25 HS-PWM fans are available.[^2]

## Specs
### CPU

| Processor           | AMD Ryzen AI Max 385       | AMD Ryzen AI Max 395+      |
| ------------------- | -------------------------- | -------------------------- |
| Cores               | 8                          | 16                         |
| Threads             |                            |                            |                        
| L3 Cache            |                            |                            |
| Base Clock          |                            |                            |
| Boost Clock         |                            |                            |
| Integrated Graphics | AMD Radeon 8050S           | AMD Radeon 8060S           |

### Power Supply
Framework Desktop includes a semi-custom Flex ATX 400W developed with taiwanese power supply manufacturer FSP.[^2] The PSU uses a 40mm fan from Delta, which supports 0 RPM operation, meaning it stays off at low load. It is a non-modular power supply with a 24-pin ATX and 8-pin CPU power cables. There are no MOLEX, SATA or PCI-E power connectors to "make the Power Supply visually cleaner."[^4]

### Connectivity

#### Rear IO
The Framework Desktop mainboard includes two USB-A ports, two USB-C ports, one HDMI port, two DisplayPort Ports, and one 5 Gigabit ethernet port.[^1]

#### Expansion Cards
Framework Desktop includes two expansion card slots on the front of the case.[^2]

#### PCIe
Framework Desktop includes one PCI-E 4.0 4x slot.[^2] The slot is 4x physical and electrical, and is closed-back so you cannot insert a physically longer connector.

#### Wireless
Framework Desktop includes an AMD RZ717 wireless module with support for Wi-Fi 7.[^2]

## Hardware Compatibility
#### RAM
Framework Desktop uses soldered LPDDR5x memory rather than SO-DIMMs, "to enable the massive 256GB/s memory bandwidth that Ryzen AI Max delivers."[^2] Configurations are available with up to 128 GB of RAM.

#### SSD
Framework Desktop supports up to two NVMe M.2 2280 SSDs.[^2] The chassis does not have any 2.5” or 3.5” drive bays, and no SATA ports are present on the mainboard.

# References
[^1]: <https://www.youtube.com/watch?v=-8k7jTF_JCg> [Archived](http://web.archive.org/web/20250402013005/https://www.youtube.com/watch?v=-8k7jTF_JCg) 
[^2]: <https://frame.work/blog/introducing-the-framework-desktop> [Archived](https://web.archive.org/web/20250415185536/https://frame.work/blog/introducing-the-framework-desktop) 
[^3]: <https://frame.work/desktop?tab=specs> [Archived](http://web.archive.org/web/20250401005454/https://frame.work/desktop?tab=specs)
[^4]: <https://frame.work/blog/framework-desktop-deep-dive-power-supply> [Archived](http://web.archive.org/web/20250527125330/https://frame.work/blog/framework-desktop-deep-dive-power-supply) 
