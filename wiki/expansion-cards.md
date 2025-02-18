---
sidecar:
  - image: /assets/expansion-card.png
    text: Image courtesy of Framework
  - title: Expansion Cards
    title_sm: Customization Option
  - table:
    - label: Compatibility
      value: |
        • <a href="/products/framework-laptop-13">Framework Laptop 13</a>
        • <a href="/products/framework-laptop-16">Framework Laptop 16</a>

---
# Expansion Cards
{% include sidecar.html %}
**Expansion Cards** are custom form factor USB-C adapters that enable customizable and hot-swappable I/O on Framework laptops. The cards lock into Expansion Card Bays on [Framework Laptop 13](/framework-laptop-13) and [Framework Laptop 16](/framework-laptop-16).

Expansion Cards are standard USB-C adapters, so they can be used with any host device that supports the applicable parts of the USB-C specification. [^1]

## Official Expansion Cards

### USB-C Expansion Card

The [USB-C Expansion Card](https://frame.work/products/usb-c-expansion-card) acts as a simple passthrough of the USB-C port on the mainboard.

The USB-C Expansion Card was available only in aluminium initially, however plastic varieties in orange, green, lavender, and red were introduced alongside the [Framework Laptop 13 (Intel Core Ultra Series 1)](/framework-laptop-13/core-ultra-1).

### USB-A Expansion Card

The [USB-A Expansion Card](https://frame.work/products/usb-a-expansion-card) supports up to USB 3.2 Gen 2 10 Gbit/s speeds.

### HDMI Expansion Card

The [HDMI Expansion Card](https://frame.work/products/hdmi-expansion-card-3rd-gen) supports HDMI 2.0b. The HDMI Expansion Card uses a Parade PS186 DisplayPort 1.4a to HDMI 2.0b Protocol Converter internally for converting the DisplayPort Alt Mode signal output by the laptop to the HDMI protocol.

The BETA HDMI (2nd Gen) Expansion Card includes hardware and software tweaks to address an issue preventing some laptop components from properly entering a low power state when they should. [^7] [^9] The BETA HDMI (2nd Gen) Expansion Card was only available to batch 1 pre-order customers of the [Framework Laptop 13 (13th Gen Intel Core)](/framework-laptop-13/13th-gen).

The HDMI (3rd Gen) Expansion Card includes minor tweaks to improve compatibility with certain external monitors. [^9]

The HDMI (1st Gen) Expansion Card can be converted into a HDMI (3rd Gen) Expansion Card through soldering and firmware updates following the [HDMI Expansion Card power saving rework (Beta)](https://guides.frame.work/Guide/HDMI+Expansion+Card+power+saving+rework+(Beta)/193?lang=en) guide.

### Ethernet Expansion Card

The [Ethernet Expansion Card](https://frame.work/products/ethernet-expansion-card) features an RJ45 jack connected through a Realtek RTL8156 controller to allow 2.5Gbit/s speeds.

The Ethernet Expansion Card is the only official expansion card to not sit flush with the laptop and features clear plastic housing.

### DisplayPort Expansion Card

The [DisplayPort Expansion Card](https://frame.work/products/displayport-2nd-gen-expansion-card) Passes through DisplayPort signals from the laptop using USB-C DisplayPort Alt Mode.

The DisplayPort (2nd Gen) Expansion Card ships with optimized firmware to address an issue preventing some laptop components from properly entering a low power state when they should. [^7] [^8]

The DisplayPort (1st Gen) Expansion Card can be updated to the optimized firmware following the [DisplayPort Expansion Card Power Saving Firmware Update](https://guides.frame.work/Guide/DisplayPort+Expansion+Card+Power+Saving+Firmware+Update/194?lang=en) guide.

### MicroSD Expansion Card

The [MicroSD Expansion Card](https://frame.work/products/microsd-expansion-card) supports MicroSD UHS-I and UFS cards.

### SD Expansion Card

The [SD Expansion Card](https://frame.work/products/sd-expansion-card) supports UHS-I and UHS-II cards.

### Audio Expansion Card

The [Audio Expansion Card](https://frame.work/products/audio-expansion-card) Features a 3.5mm headphone jack connected to a Conexant CX31993 USB Audio CODEC. [^6]

Supports both input and output. Allows for a headphone jack on the [Framework Laptop 16](/framework-laptop-16) and offers greater audio quality than the headphone jack on the [Framework Laptop 13](/framework-laptop-13).

### Storage Expansion Card

The [Storage Expansion Card (2nd Gen)](https://frame.work/products/storage-expansion-card-2nd-gen) uses the Phison U17 Flash controller and Hynix V6 NAND due to the Micron N28 NAND, which was used by the 1st Gen card, being discontinued. [^10] [^11] 

The 250GB (2nd Gen) Storage Expansion Card is rated at 1000 MB/s read and 800 MB/s write. The 1TB (2nd Gen) Storage Expansion Card is rated at 1000 MB/s read and 800 MB/s write.

The 250GB (1st Gen) Storage Expansion Card is rated at 1000 MB/s read and 375 MB/s write. [^10] The 1TB (1st Gen) Storage Expansion Card is rated at 1000 MB/s read and 1000 MB/s write. [^10]

Early batches of the 1TB (1st Gen) Storage Expansion Card suffered from thermal throttling issues that could be resolved by installing a thermal pad following the [1TB Expansion Card Throttling](https://guides.frame.work/Guide/1TB+Expansion+Card+Throttling/105) guide.


## Third-Party Expansion Cards
Framework published electrical and mechanical templates on their GitHub to enable third-party developers to design and manufacture their own cards. [^2] Some examples are below:

- UART card by [Josh Cook](https://community.frame.work/u/josh_cook/). Available on [GitHub](https://github.com/jyancat/UART-Expansion-Card) or [for purchase](https://lectronz.com/products/uart-expansion-card)
- ESP32-S3 card by [Spacehuhn](https://www.youtube.com/watch?v=IML9c_MsyQU). Available on [GitHub](https://github.com/SpacehuhnTech/framework) or [for purchase](https://spacehuhn.store/products/framework-esp32-s3-expansion-card)
- Snack Drawer V2 by [XenoCow](https://community.frame.work/u/XenoCow). Available [for purchase](https://layers3d.square.site/) as files or completed part.[^3]
- Snack Drawer Lite by [XenoCow](https://community.frame.work/u/XenoCow). Available [for download](https://drive.protonmail.com/urls/W2XVGGM1R8#evo86FpGID76).[^4]
- openCom LTE card by [Liberated Embedded Systems](https://liberatedsystems.co.uk). Discontinued but [open-source](https://git.liberatedsystems.co.uk/jacob.eva/opencom-lte).[^5]
- DongleHider+ by [LeoDJ](https://github.com/LeoDJ). Available on [GitHub](https://github.com/LeoDJ/FW-EC-DongleHiderPlus)
- EC Card 2 Embedded Controller Closed Case Debugging card by [DHowett](https://github.com/dhowett). Available on his [Gitlab](https://gitlab.howett.net/DHowett/framework-ec-debug-card).[^13]

# References
[^1]: <https://community.frame.work/t/expansion-cards-compatible-with-other-devices/990/2?u=morpheus636> [Archived](http://web.archive.org/web/20250114044406/https://community.frame.work/t/expansion-cards-compatible-with-other-devices/990/2?u=morpheus636) 
[^2]: <https://github.com/FrameworkComputer/ExpansionCards> [Archived](http://web.archive.org/web/20250114032422/https://github.com/FrameworkComputer/ExpansionCards) 
[^3]: <https://community.frame.work/t/the-snack-drawer-v2-back-in-snacktion/18442> [Archived](http://web.archive.org/web/20250110172850/https://community.frame.work/t/the-snack-drawer-v2-back-in-snacktion/18442) 
[^4]: <https://community.frame.work/t/lite-snack-drawer-simple-free-ready-for-snacks/8451> [Archived](https://web.archive.org/web/20250114032837/https://community.frame.work/t/lite-snack-drawer-simple-free-ready-for-snacks/8451) 
[^5]: <https://liberatedsystems.co.uk/newsletters/opencom_lte_cancellation/> [Archived](https://web.archive.org/web/20250114050547/https://liberatedsystems.co.uk/newsletters/opencom_lte_cancellation/) 
[^6]: <https://community.frame.work/t/whats-inside-the-audio-expansion-card/37850/15> [Archived](http://web.archive.org/web/20250110053906/https://community.frame.work/t/whats-inside-the-audio-expansion-card/37850/15) 
[^7]: <https://frame.work/blog/getting-ready-to-ship-13th-gen-and-announcing-power-saving-expansion-cards> [Archived](http://web.archive.org/web/20250114033918/https://frame.work/blog/getting-ready-to-ship-13th-gen-and-announcing-power-saving-expansion-cards) 
[^8]: <https://knowledgebase.frame.work/displayport-expansion-card-generations-BylqCuwDn> [Archived](http://web.archive.org/web/20250110053953/https://knowledgebase.frame.work/displayport-expansion-card-generations-BylqCuwDn) 
[^9]: <https://knowledgebase.frame.work/hdmi-expansion-card-generations-Sk7AQKUv2> [Archived](https://web.archive.org/web/20250114051834/https://knowledgebase.frame.work/hdmi-expansion-card-generations-Sk7AQKUv2) 
[^10]: <https://frame.work/blog/storage-expansion-cards> [Archived](http://web.archive.org/web/20250114034719/https://frame.work/blog/storage-expansion-cards) 
[^11]: <https://twitter.com/FrameworkPuter/status/1778081340564639855>
[^12]: <https://frame.work/blog/introducing-the-new-framework-laptop-13-with-intel-core-ultra-series-1-processors> [Archived](http://web.archive.org/web/20250114032925/https://frame.work/blog/introducing-the-new-framework-laptop-13-with-intel-core-ultra-series-1-processors) 
[^13]: <https://www.howett.net/posts/2023-04-framework-ec-card/> [Archived](http://web.archive.org/web/20240910172919/https://www.howett.net/posts/2023-04-framework-ec-card/) 
