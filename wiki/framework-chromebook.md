---
sidecar:
    - title: Framework Laptop Chromebook Edition
      title_sm: Variant of Framework Laptop 13
    - gap: true
      table:
        - label: First Model
          value: 12th Gen Intel Core
        - label: Current Model
          value: 12th Gen Intel Core
        - label: Announced
          value: September 21, 2022
        - label: Pre-Orders Opened
          value: September 21, 2022
        - label: Began Shipping
          value: December 2022
        - label: Status
          value: 🔴 Discontinued
---
# Framework Laptop Chromebook Edition
{% include sidecar.html %}

**Framework Laptop Chromebook Edition** was a variant of [Framework Laptop 13](/framework-laptop-13) developed in partnership with Google to run ChromeOS.[^1] It was announced September 21, 2022, with pre-orders opening the same day. Devices began shipping in December of that year.

The Chromebook was built on the Framework Laptop 13 chassis. The pre-built featured an Intel Core i5-1240P CPU, 8GB of DDR4-3200 and 256GB of storage. No DIY Edition was available.[^2] Framework did not release any subsequent generations before discontinuing the Chromebook line in August 2024. It will continue to receive software updates until at least 2030.[^1]

Framework posted a knowledgebase article on August 26, 2024 explaining how to convert a Framework Laptop Chromebook Edition to a Framework Laptop 13. The article includes an exception to the company's normal practice of not commenting on future plans by stating that they "don’t currently have plans for a newer generation of Framework Laptop 13 Chromebook Edition." [^3]

## Differences From Framework Laptop 13
Chromebook Edition is built on the Framework Laptop 13 chassis with a version of [11th Gen Intel Core](/framework-laptop-13/11th-gen)'s stamped top case engraved with the Chromebook logo.[^7] Most Framework Laptop 13 parts are compatible, though separate Chromebook-specific part SKUs are also listed on the Marketplace.

Though the Chromebook mainboard uses the same CPU as the base model [Framework Laptop 13 12th Gen Intel Core](/framework-laptop-13/12th-gen), it uses a different mainboard that includes the Google Titan C security chip, which is necessary to run ChromeOS.[^1] [^4] The board is also the only Framework product to run mainline Coreboot, making it the only Framework product to run completely open-source firmware.[^5] All Framework Laptops use the ChromeOS project's open-source embedded controller firmware.[^6]

The device uses a different input cover with a ChromeOS-specific keyboard layout and different touchpad firmware that may have incompatibilities on Linux. The Chromebook's power button also lacks a fingerprint reader.

## Specs
### CPU

| Processor            | Intel Core i5-1240P[^8] [^9] |
| -------------------- | ---------------------------- | 
| Cores                | 12 (4x Golden Cove "P Cores" + 8x Gracemont "E Cores") | 
| Threads              | 16                  |                  
| L3 Cache             | 12 MB (shared)      |
| Base Clock: P Cores  | 1.7 GHz             |
| Base Clock: E Cores  | 1.2 GHz             |
| Boost Clock: P Cores | 4.4 GHz             |
| Boost Clock: E Cores | 3.3 GHz             |
| Integrated Graphics  | Intel UHD Graphics (Iris Xe when paired with dual-channel memory) |

### Connectivity
#### Expansion Cards
Framework Laptop Chromebook Edition features two Intel Thunderbolt 4 controllers integrated into the CPU.[^10] All four [expansion card](/expansion-cards) ports support USB-PD charging and Thunderbolt 4.[^2]

#### Wireless
Supports WiFi 6E. Specs pages do not include the model of the default WiFi card.[^2]

### Hardware Compatibility
#### RAM
Framework Laptop Chromebook Edition supports up to 64GB of JEDEC DDR4 SO-DIMMS.[^1]

#### SSD
Framework Laptop Chromebook Edition supports up to 1TB of M.2 2280-size NVMe SSD.[^1]

# References
[^1]: <https://frame.work/blog/introducing-the-framework-laptop-chromebook-edition> [Archived](https://web.archive.org/web/20241229142943/https://frame.work/blog/introducing-the-framework-laptop-chromebook-edition)
[^2]: <https://frame.work/products/laptop-chromebook-12-gen-intel> [Archived](https://web.archive.org/web/20241229142829/https://frame.work/products/laptop-chromebook-12-gen-intel)
[^3]: <https://knowledgebase.frame.work/converting-a-chromebook-edition-to-a-non-chromebook-framework-laptop-13-SkOttwqoA> [Archived](https://web.archive.org/web/20241229142843/https://knowledgebase.frame.work/converting-a-chromebook-edition-to-a-non-chromebook-framework-laptop-13-SkOttwqoA)
[^4]: <https://services.google.com/fh/files/misc/titan-c-chrome-os-one-pager.pdf> [Archived](https://web.archive.org/web/20241229144016/https://services.google.com/fh/files/misc/titan-c-chrome-os-one-pager.pdf)
[^5]: <https://docs.mrchromebox.tech/docs/supported-devices.html> [Archived](https://web.archive.org/web/20241226072720/https://docs.mrchromebox.tech/docs/supported-devices.html) --- See Framework Laptop Chromebook Edition under Intel Alderlake.
[^6]: <https://github.com/FrameworkComputer/EmbeddedController/blob/28238691b3980449b8abde8424bb20a6ca98d70e/README.md>
[^7]: <https://frame.work/products/top-cover-chromebook> [Archived](https://web.archive.org/web/20241223212134/https://frame.work/products/top-cover-chromebook)
[^8]: <https://ark.intel.com/content/www/us/en/ark/products/132221/intel-core-i5-1240p-processor-12m-cache-up-to-4-40-ghz.html> [Archived](https://web.archive.org/web/20241229152621/https://www.intel.com/content/www/us/en/products/sku/132221/intel-core-i51240p-processor-12m-cache-up-to-4-40-ghz/specifications.html)
[^9]: <https://www.techpowerup.com/cpu-specs/core-i5-1240p.c2583> [Archived](https://web.archive.org/web/20241229152628/https://www.techpowerup.com/cpu-specs/core-i5-1240p.c2583)
[^10]: <https://tpucdn.com/cpu-specs/images/connectivity/intel-mobile-adl.png> [Archived](https://web.archive.org/web/20241229152639/https://tpucdn.com/cpu-specs/images/connectivity/intel-mobile-adl.png)
