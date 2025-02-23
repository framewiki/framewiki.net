---
permalink: /guides/mainboard-reset
redirect_from:
    - /mainboard-reset
sidecar:
  - title: Guide Compatibility
  - title_sm: Framework Laptop 13
  - table:
    - label: Intel 11th Gen
      value: ✗ (WIP)
    - label: Intel 12th Gen
      value: ✗ (WIP)
    - label: Intel 13th Gen
      value: ✗ (WIP)
    - label: AMD 7040 Series
      value: <b>✓</b>
    - label: Intel Core Ultra 1
      value: <b>✓</b>
  - gap: true
  - title_sm: Framework Laptop 16
  - table:
    - label: AMD 7040 Series
      value: <b>✓</b>
---
# Mainboard Reset Procedures
{% include sidecar.html %}
## 11th Gen Intel Core, 12th Gen Intel Core, 13th Gen Intel Core
{% include notes/wip.html %}

## AMD 7040 Series, Intel Core Ultra Series 1, Framework Laptop 16
1. Connect the mainboard to AC power.
2. Remove the Input Cover.
3. Press the chassis intrusion switch in the center of the mainboard for 2 seconds.
4. Release the switch. Wait for the mainboard lights to blink red.
5. Repeat steps 3-4 10 times.
6. Press the power button to boot the system.
