---
permalink: /framework-laptop-13/11th-gen
---
# Framework Laptop 13 (11th Gen Intel Core)
Batch 1 of [Framework Laptop 13](/framework-laptop-13) (11th Gen Intel Core) began shipping in August 2021.

## Specs

## Hardware Compatibility

## Reviews


## Known Issues
### RTC Battery Drain
On 11th gen Framework laptops, if the laptop is left for an extended period without being connected to external power, the RTC battery could completely discharge, preventing the laptop from booting without first charging it. Sometimes, due to an 11th gen Intel silicon bug in the subsystem that the RTC/CMOS battery powers, the laptop will not boot even when connected to power until the user performs a mainboard reset.[[1]](https://knowledgebase.frame.work/en_us/my-laptop-is-not-powering-on-ryQLXvQkt)

#### Fix
Under normal circumstances, performing a mainboard reset and charging the laptop for 24 hours (trickle-charging the RTC battery) will prevent the issue from recurring unless the laptop is left without charging for 6-8 weeks. If the RTC battery has become damaged from low voltage, it may recur sooner, making it necessary to replace it. In such cases, Framework support will send a replacement ML1220 RTC battery for free, regardless of warranty status. [[2]](https://community.frame.work/t/tradeoffs-of-refurbed-11th-gen-vs-new-12th-gen/24027/52?u=morpheus636) Users who decide to source their own cell should ensure they source a rechargable lithium ML1220 and not a standard CR1220 to avoid damaging the mainboard.

Alternatively, users can request an RTC replacement board that goes into the RTC battery holder in place of the battery and connects to the board via one soldered wire, negating the issue. [[3]](https://community.frame.work/t/rework-instructions-for-11th-gen-mainboards-to-enable-powering-the-rtc-circuit-from-the-main-battery/26922/170?u=morpheus636) [[4]](https://community.frame.work/t/rework-instructions-for-11th-gen-mainboards-to-enable-powering-the-rtc-circuit-from-the-main-battery/26922/173?u=morpheus636) They also published instructions for a board-level rework that allows the RTC battery to charge from the main system battery. [[5]](https://community.frame.work/t/rework-instructions-for-11th-gen-mainboards-to-enable-powering-the-rtc-circuit-from-the-main-battery/26922?u=morpheus636)
