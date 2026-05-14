## Imperial44 is a compact split mechanical keyboard with three thumb keys on each half and support for hot-swap encoders on either side
*Imperial44 keeps a 40% footprint, a 44-key layout, and clean ergonomics across three versions: the wired, the Wireless Edition, and the Wireless Metal Edition*

![Imperial44 v4](images/01.jpg)

## Design philosophy
Imperial44 v4 combines futuristic styling, a compact form factor, and practical ergonomics. The wired board focuses on a feature-rich daily setup, the Wireless Edition adds Bluetooth portability, and the Wireless Metal Edition brings the same idea into a premium aluminum body.

## Features
- Split, ergonomic design
- 44 fully programmable keys, 15 additional layers for all your tasks
- Optional encoder installation on either half
- Hotswappable PCB (MX sockets) 

### Wired version 
- Powered by RP2040 and QMK firmware for the wired version
- Type-C output for connection between halves in the wired version
- Easily remap any key and customize your keyboard with [Vial](https://eh.industries/vial) 
- OLED display and active layer indicator

### Wereless Edition 
- Powered by nrf52840 and RMK/ZMK firmware
- Bluetooth connectivity for up to 6 devices
- 120 mAh battery with up to 3 weeks of use
- Type-C connection

## This repo contains all files related to this keyboard
PCB and schematic can be found [here](https://oshwlab.com/yuriiq/)

### BOM
#### Imperial44 v4

| Components | Quantity (pcs) |
| --- | ---: |
| Imperial44 v4 PCB | 1 |
| RP2040 MCU, LQFN-56 | 2 |
| MX Hotswap sockets | 44 |
| 1N4148W Diodes SOD-523F | 44 |
| Resistor 0402 5.1 kOm | 8 |
| Resistor 0402 1 kOm | 2 |
| Resistor 0402 200 Om | 2 |
| Resistor 0402 27 Om | 4 |
| Capacitor 0402 1 nF | 4 |
| Capacitor 0402 15 pF | 4 |
| Capacitor 0402 100 nF | 10 |
| Capacitor 0402 2.2 uF | 2 |
| SMD LED SK6803MINI-E-001 | 2 |
| P-Channel MOSFETs SOT-23 JSM2301S | 2 |
| SMD Tactile Switches TS-1187F-1526 | 4 |
| LDO SOT-23-3 662K | 2 |
| SpiFlash W25Q32JVSSIQ | 2 |
| SMD USB Connectors USB-TYPE-C-021 | 2 |
| SMD USB Connectors USB-TYPE-C-018 | 2 |
| SMD Crystal Resonator 12MHz XXHCCLNANF-12.000000MHZ| 2 |
| 3M bumpons (8mm) | 8 |

#### Imperial44 v4 – Wireless Edition

| Components | Quantity (pcs) |
| --- | ---: |
| Imperial44 Wireless Edition PCB | 1 |
| E73-2G4M08S1C, Module Bluetooth Modules | 2 |
| MX Hotswap sockets | 44 |
| 1N4148W Diodes SOD-523F | 44 |
| B5819WS Diode Schottky SOD-323 | 2 |
| Resistor 0402 5.1 kOm | 6 |
| Resistor 0402 100 kOm | 2 |
| Resistor 0402 806 kOm | 2 |
| Resistor 0402 2 MOm | 2 |
| Resistor 0402 10 kOm | 2 |
| Capacitor 0402 4.7 uF | 4 |
| SMD LED SK6803MINI-E-001 | 2 |
| P-Channel MOSFETs SOT-23 JSM2301S | 4 |
| MSK12CO2-SZ, SMD Slide Switches | 2 |
| LN2054Y42AMR, Linear Li-Ion Battery Charger SOT-23-5 | 2 |
| ZX-SH1.0-2PWT, SMD WIre To Board | 2 |
| AP2112K-3.3TRG1, LDO REGULATOR SOT-25-5 | 2 |
| SMD USB Connectors USB-TYPE-C-018 | 2 |
| TS5235A 250gf 025, SMD Tactile Switches | 2 |
| 3M bumpons (8mm) | 8 |

## License 

The files in this repository are licensed under a Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License.

## Useful links

- Imperial44 v4:
  - [Case for 3D printing (STL)](stls/imperial44v4)
  - [Case model for editing (STEP)](step/imperial44v4)
  - [Circuit schematic](https://oshwlab.com/yuriiq/)
  
- Imperial44 v4 – Wireless Edition:
  - [Case for 3D printing (STL)](stls/imperial44-we)
  - [Case model for editing (STEP)](step/imperial44-we)
  - [Circuit schematic](https://oshwlab.com/yuriiq/)
  - [Case model for Metal Edition (CNC)](cnc)
  
### Firmware
- [Pre-compiled files](https://github.com/ergohaven/keymap_hub)
- Source code: 
    - wired [QMK](https://github.com/ergohaven/vial-qmk)
    - wireless [RMK](https://github.com/ergohaven/rmk-eh)
    - wireless [ZMK](https://github.com/ergohaven/ergohaven-zmk)

## Availability
The complete keyboard (not a diy kit!) is available for purchase at [eh.industries](https://eh.industries/)
