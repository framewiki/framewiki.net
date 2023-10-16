---
permalink: /framework-laptop-13/11th-gen
wip: true
---
# Framework Laptop 13 (11th Gen Intel Core)

Framework Laptop 13 (11th Gen Intel Core) is [Framework](/framework-computer-inc)'s first product, announced February 25, 2021. [^6] Preorders opened on May 13, 2021 [^7], with Batch 1 shipping in August of that same year. [^8] It went in-stock on December 3, 2021. [^9]

It was disconinued after the launch of [Framework Laptop 13 (12th Gen Intel Core)](/framework-laptop-13/12th-gen)

## Specs
### CPU

| Processor           | Intel Core i5-1135G7 | Intel Core i7-1165G7 | Intel Core i7-1185G7 |
| ------------------- | -------------------- | -------------------- | -------------------- |
| Cores               |                      |                      |                      |
| Threads             |                      |                      |                      |                          
| L3 Cache            |                      |                      |                      |
| Base Clock          |                      |                      |                      |
| Boost Clock         |                      |                      |                      |
| Integrated Graphic  |                      |                      |                      |

### Connectivity
## Hardware Compatibility
### RAM
### SSD
## Reviews
## Known Issues
### RTC Battery Drain
On 11th gen Framework laptops, if the laptop is left for an extended period without being connected to external power, the RTC battery could completely discharge, preventing the laptop from booting without first charging it. Sometimes, due to an 11th gen Intel silicon bug in the subsystem that the RTC/CMOS battery powers, the laptop will not boot even when connected to power until the user performs a mainboard reset.[^1]

#### Fix
Under normal circumstances, performing a mainboard reset and charging the laptop for 24 hours (trickle-charging the RTC battery) will prevent the issue from recurring unless the laptop is left without charging for 6-8 weeks. If the RTC battery has become damaged from low voltage, it may recur sooner, making it necessary to replace it. In such cases, Framework support will send a replacement ML1220 RTC battery for free, regardless of warranty status. [^2] Users who decide to source their own cell should ensure they source a rechargable lithium ML1220 and not a standard CR1220 to avoid damaging the mainboard.

Alternatively, users can request an RTC replacement board that goes into the RTC battery holder in place of the battery and connects to the board via one soldered wire, negating the issue. [^3] [^4] They also published instructions for a board-level rework that allows the RTC battery to charge from the main system battery. [^5]

# References
[^1]: <https://knowledgebase.frame.work/en_us/my-laptop-is-not-powering-on-ryQLXvQkt>
[^2]: <https://community.frame.work/t/tradeoffs-of-refurbed-11th-gen-vs-new-12th-gen/24027/52?u=morpheus636>
[^3]: <https://community.frame.work/t/rework-instructions-for-11th-gen-mainboards-to-enable-powering-the-rtc-circuit-from-the-main-battery/26922/170?u=morpheus636>
[^4]: <https://community.frame.work/t/rework-instructions-for-11th-gen-mainboards-to-enable-powering-the-rtc-circuit-from-the-main-battery/26922/173?u=morpheus636>
[^5]: <https://community.frame.work/t/rework-instructions-for-11th-gen-mainboards-to-enable-powering-the-rtc-circuit-from-the-main-battery/26922?u=morpheus636>
[^6]: <https://frame.work/blog/introducing-the-framework-laptop>
[^7]: <https://frame.work/blog/framework-laptop-starting-at-999-pre-orders-are>
[^8]: <https://frame.work/blog/the-framework-laptop-is-now-shipping-and-press-reviews>
[^9]: <https://frame.work/blog/finally-in-stock-with-expedited-and-carbon-offset>
