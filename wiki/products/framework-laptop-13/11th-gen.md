---
permalink: /products/framework-laptop-13/11th-gen
redirect_from:
    - /framework-laptop-13/11th-gen
sidecar:
    - title: Framework Laptop 13
      title_sm: 11th Gen Intel Core
    - table:
        - label: Announced
          value: February 25, 2021
        - label: Pre-Orders Opened
          value: May 13, 2021
        - label: Began Shipping
          value: August 2021
        - label: Status
          value: 🔴 Discontinued
---
# Framework Laptop 13 (11th Gen Intel Core)
{% include sidecar.html %}
**Framework Laptop 13 (11th Gen Intel Core)** is [Framework](/framework-computer-inc)'s first product, announced February 25, 2021. [^6] Preorders opened on May 13, 2021 [^7], with Batch 1 shipping in August of that same year. [^8] It went in-stock on December 3, 2021. [^9]

It was discontinued after the launch of [Framework Laptop 13 (12th Gen Intel Core)](/framework-laptop-13/12th-gen).

## Specs
### CPU

| Processor           | Intel Core i5-1135G7[^10] | Intel Core i7-1165G7[^11] | Intel Core i7-1185G7[^12] |
| ------------------- | -------------------- | -------------------- | -------------------- |
| Cores               | 4 (4x Golden Cove)   | 4 (4x Golden Cove)   | 4 (4x Golden Cove)   |
| Threads             | 8                    | 8                    | 8                    |                          
| Cache               | 8 MB (shared)        | 12 MB (shared)       | 12 MB (shared)       |
| Base Clock          | 2.4 GHz              | 2.8 GHz              | 3.0 GHz              |
| Boost Clock         | 4.2 GHz              | 4.7 GHz              | 4.8 GHz              |
| Integrated Graphics | Iris Xe Graphics 80EU when paired with dual channel memory. Otherwise, Intel UHD Graphics. | Iris Xe Graphics 96EU when paired with dual channel memory. Otherwise, Intel UHD Graphics. | Iris Xe Graphics 96EU when paired with dual channel memory.  Otherwise, Intel UHD Graphics. |

### Connectivity
#### Expansion Cards
Framework Laptop 13 (11th gen Intel Core) features two Intel Thunderbolt 4 controllers integrated into the CPU [^13]. All four [expansion card](/expansion-cards) ports support USB-PD charging and USB4. Framework Laptop 13 (11th gen Intel Core) failed to pass Thunderbolt certification. [^14]

#### Wireless
11th Gen comes with the Intel Wi-Fi 6 AX201 vPro card on pre-built models or the Intel Wi-Fi 6E AX210 Wi-Fi card on DIY edition models.

## Hardware Compatibility
### RAM
Framework Laptop 13 (11th Gen Intel Core) supports JEDEC DDR4 SO-DIMMS up to 32 GB 3200 MT/s. XMP speeds are not supported. [^15]

### SSD
Framework Laptop 13 (11th Gen Intel Core) supports M.2 2280-size NVMe SSDs. M.2 SATA drives are not supported. [^16]

## Reviews

Reviewers included Lori Grunin from CNET [^17], Gordon Ung from PCWorld [^18], Luke Larson from Digital Trends [^19], and Linus Sebastian from Linus Media Group [^20].

Linus Sebastian stated in his review "now I want to invest" (timestamp 10:46) and subsequently invested $224,998.37 in Framework. [^21]

## Known Issues
### RTC Battery Drain
On 11th gen Framework laptops, if the laptop is left for an extended period without being connected to external power, the RTC battery could completely discharge, preventing the laptop from booting without first charging it. Sometimes, due to an 11th gen Intel silicon bug in the subsystem that the RTC/CMOS battery powers, the laptop will not boot even when connected to power until the user performs a mainboard reset.[^1]

#### Fix
Under normal circumstances, performing a mainboard reset and charging the laptop for 24 hours (trickle-charging the RTC battery) will prevent the issue from recurring unless the laptop is left without charging for 6-8 weeks. If the RTC battery has become damaged from low voltage, it may recur sooner, making it necessary to replace it. In such cases, Framework support will send a replacement ML1220 RTC battery for free, regardless of warranty status. [^2] Users who decide to source their own cell should ensure they source a rechargable lithium ML1220 and not a standard CR1220 to avoid damaging the mainboard.

Alternatively, users can request an RTC replacement board that goes into the RTC battery holder in place of the battery and connects to the board via one soldered wire, negating the issue. [^3] [^4] They also published instructions for a board-level rework that allows the RTC battery to charge from the main system battery. [^5]

# References
[^1]: <https://knowledgebase.frame.work/en_us/my-laptop-is-not-powering-on-ryQLXvQkt> [Archived](https://web.archive.org/web/20250114051142/https://knowledgebase.frame.work/en_us/my-laptop-is-not-powering-on-ryQLXvQkt) 
[^2]: <https://community.frame.work/t/tradeoffs-of-refurbed-11th-gen-vs-new-12th-gen/24027/52?u=morpheus636> [Archived](https://web.archive.org/web/20250114034350/https://community.frame.work/t/tradeoffs-of-refurbed-11th-gen-vs-new-12th-gen/24027/52?u=morpheus636) 
[^3]: <https://community.frame.work/t/rework-instructions-for-11th-gen-mainboards-to-enable-powering-the-rtc-circuit-from-the-main-battery/26922/170?u=morpheus636> [Archived](http://web.archive.org/web/20250114015730/https://community.frame.work/t/rework-instructions-for-11th-gen-mainboards-to-enable-powering-the-rtc-circuit-from-the-main-battery/26922/170?u=morpheus636) 
[^4]: <https://community.frame.work/t/rework-instructions-for-11th-gen-mainboards-to-enable-powering-the-rtc-circuit-from-the-main-battery/26922/173?u=morpheus636> [Archived](http://web.archive.org/web/20250114042524/https://community.frame.work/t/rework-instructions-for-11th-gen-mainboards-to-enable-powering-the-rtc-circuit-from-the-main-battery/26922/173?u=morpheus636) 
[^5]: <https://community.frame.work/t/rework-instructions-for-11th-gen-mainboards-to-enable-powering-the-rtc-circuit-from-the-main-battery/26922?u=morpheus636> [Archived](http://web.archive.org/web/20250110213342/https://community.frame.work/t/rework-instructions-for-11th-gen-mainboards-to-enable-powering-the-rtc-circuit-from-the-main-battery/26922?u=morpheus636) 
[^6]: <https://frame.work/blog/introducing-the-framework-laptop> [Archived](http://web.archive.org/web/20250114042935/https://frame.work/blog/introducing-the-framework-laptop) 
[^7]: <https://frame.work/blog/framework-laptop-starting-at-999-pre-orders-are> [Archived](https://web.archive.org/web/20250114035557/https://frame.work/blog/framework-laptop-starting-at-999-pre-orders-are) 
[^8]: <https://frame.work/blog/the-framework-laptop-is-now-shipping-and-press-reviews> [Archived](http://web.archive.org/web/20250114035853/https://frame.work/blog/the-framework-laptop-is-now-shipping-and-press-reviews) 
[^9]: <https://frame.work/blog/finally-in-stock-with-expedited-and-carbon-offset> [Archived](http://web.archive.org/web/20250114040042/https://frame.work/blog/finally-in-stock-with-expedited-and-carbon-offset) 
[^10]: <https://ark.intel.com/content/www/us/en/ark/products/208658/intel-core-i5-1135g7-processor-8m-cache-up-to-4-20-ghz.html> [Archived](http://web.archive.org/web/20241004070042/https://ark.intel.com/content/www/us/en/ark/products/208658/intel-core-i5-1135g7-processor-8m-cache-up-to-4-20-ghz.html) 
[^11]: <https://ark.intel.com/content/www/us/en/ark/products/208921/intel-core-i7-1165g7-processor-12m-cache-up-to-4-70-ghz-with-ipu.html> [Archived](http://web.archive.org/web/20240927073551/https://ark.intel.com/content/www/us/en/ark/products/208921/intel-core-i7-1165g7-processor-12m-cache-up-to-4-70-ghz-with-ipu.html) 
[^12]: <https://ark.intel.com/content/www/us/en/ark/products/208664/intel-core-i7-1185g7-processor-12m-cache-up-to-4-80-ghz-with-ipu.html> [Archived](http://web.archive.org/web/20241120003803/https://ark.intel.com/content/www/us/en/ark/products/208664/intel-core-i7-1185g7-processor-12m-cache-up-to-4-80-ghz-with-ipu.html) 
[^13]: <https://tpucdn.com/cpu-specs/images/connectivity/intel-mobile-tgl-u.png> [Archived](https://web.archive.org/web/20250114043546/https://tpucdn.com/cpu-specs/images/connectivity/intel-mobile-tgl-u.png) 
[^14]: <https://frame.work/blog/framework-laptops-are-now-thunderbolt-4-certified> [Archived](http://web.archive.org/web/20250114043556/https://frame.work/blog/framework-laptops-are-now-thunderbolt-4-certified) 
[^15]: <https://knowledgebase.frame.work/what-memory-dram-parts-are-compatible-with-the-framework-laptop-ry_jbS8Ru> [Archived](http://web.archive.org/web/20250110070613/https://knowledgebase.frame.work/what-memory-dram-parts-are-compatible-with-the-framework-laptop-ry_jbS8Ru) 
[^16]: <https://knowledgebase.frame.work/what-storage-ssd-parts-are-compatible-with-the-framework-laptop-rJOOeHU0_> [Archived](http://web.archive.org/web/20250114025142/https://knowledgebase.frame.work/what-storage-ssd-parts-are-compatible-with-the-framework-laptop-rJOOeHU0_) 
[^17]: <https://www.cnet.com/tech/computing/framework-laptop-review-a-functional-and-futureproof-13-inches/> [Archived](http://web.archive.org/web/20250110070711/https://www.cnet.com/tech/computing/framework-laptop-review-a-functional-and-futureproof-13-inches/) 
[^18]: <https://www.youtube.com/watch?v=QmyAUIo79EU> [Archived](http://web.archive.org/web/20250114025149/https://www.youtube.com/watch?v=QmyAUIo79EU) 
[^19]: <https://www.digitaltrends.com/computing/framework-laptop-review/> [Archived](https://web.archive.org/web/20250114025454/https://www.digitaltrends.com/computing/framework-laptop-review/) 
[^20]: <https://www.youtube.com/watch?v=0rkTgPt3M4k> [Archived](http://web.archive.org/web/20250114030032/https://www.youtube.com/watch?v=0rkTgPt3M4k) 
[^21]: <https://www.youtube.com/watch?v=LSxbc1IN9Gg> [Archived](http://web.archive.org/web/20250114044908/https://www.youtube.com/watch?v=LSxbc1IN9Gg) 
