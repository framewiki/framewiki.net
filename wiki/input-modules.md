# Input Modules

**Input Modules** are custom modules that slot into the deck of the [Framework Laptop 16](https://framewiki.net/framework-laptop-16), allowing users to choose how their laptop is configured. Framework said the primary inspiration for this system was market research that showed "almost exactly a 50/50 split between people who love and need numpads and people who hate them." [^1]

## Technical Details
On the Framework Laptop 16, there are 8 input module connectors. Five of them --- three on the left side and two on the right side --- are USB 2.0 compatible. The middle three, populated by the trackpad, are i2c only. Input Module firmware is based on QMK keyboard software running on the Raspberry Pi RP2040 microcontroller within the modules themselves. [^2]

## Third-Party Input Modules

Framework published electrical and mechanical information on their GitHub to allow third-party developers to design and manufacture their own Input Modules. [^3] As of September 2023, a few people are working on building their own Input Modules, but none are currently available for sale. Some examples are below:

- RGB LED Matrix Input Module by Joe Schroedl. Available on [GitHub](https://github.com/corndog2000/RGB-LED-Matrix-Input-Module). Usage instructions available on his [personal website](https://jschroedl.com/rgb-start/).

# References
[^1]: <https://frame.work/blog/introducing-the-framework-laptop-16>
[^2]: <https://github.com/FrameworkComputer/qmk_firmware>
[^3]: <https://github.com/FrameworkComputer/InputModules>
