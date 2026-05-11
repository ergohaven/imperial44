## Imperial44 is a compact split mechanical keyboard with three thumb keys on each half and support for hot-swap encoders on either side
*Imperial44 keeps a 40% footprint, a 44-key layout, and clean ergonomics across three versions: the wired, the Wireless Edition, and the Wireless Metal Edition*

![Imperial44 v4](images/01.jpg)

## Design philosophy
Imperial44 v4 combines futuristic styling, a compact form factor, and practical ergonomics. The wired board focuses on a feature-rich daily setup, the Wireless Edition adds Bluetooth portability, and the Wireless Metal Edition brings the same idea into a premium aluminum body.

## Features
- 44 programmable keys and 15 layers
- Hot-swap MX switch support
- Optional encoder installation on either half
- OLED display and active layer indicator on the wired v4
- Bluetooth connectivity for up to 6 devices on wireless editions
- ZMK firmware for wireless editions and QMK/Vial for the wired board
- 120 mAh battery with up to 3 weeks of use on wireless editions
- Magnetic mounting ring for the Universal Tilt System
- Type-C connection and cable included

## This repo contains all files related to this keyboard
PCB and schematic can be found in the project materials and the product pages below

### BOM
#### Imperial44 v4
| Components | Quantity (pcs) |
| --- | ---: |
| PCB board | 1 |
| RP2040 MCU, LQFN-56| 2 |
| MX Hotswap sockets | 44 |
| 1N4148W Diodes (SOD-123) | 44 |
| Male Pin Header Connector: 11 Pins, 2.54mm, 90 degree | 2 |
| Female Header Sockets: 11 Pins, 2.54mm, 90 degree | 2 |
| Female Header Sockets: 9 Pins, 2.54mm, 90 degree | 2 |
| Socket SH1.0 5 Pins, 1.00mm | 4 |
| Cable connector SH1.0 5 Pins, 1mm, 100mm, double head | 2 |
| 1 - 100 kOhm resistors (0805) | 2 |
| USB Type-C daughterboard: 1.6mm thick | 2 |
| M2x4 Screws | 32 |
| M3x5 Inserts | 10 |
| M3x4 Screws | 10 |
| Magnets (5х10х2mm) | 4 |
| 3M bumpons (8mm) | 4 |

#### Imperial44 v4 – Wireless Edition
| Components | Quantity (pcs) |
| --- | ---: |
| Encoder PCB | 1 |
| Encoder EC11 | 1 |
| Encoder cap | 1 |
| Male Pin Header Connector: 9 Pins, 2.54mm, 90 degree | 1 |
| 1N4148W Diodes (SOD-123) | 1 |
| LED SK6812 mini-e | 1 |
| Magnets (5х10х2mm) | 2 |
| 3M bumpons (8mm) | 2 |

## License 

The files in this repository are licensed under a Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License.

## Useful links

- Imperial44 v4:
  - [Case for 3D printing (STL)](stl/wired)
  - [Case model for editing (STEP)](step/wired)
  - [Circuit schematic](https://oshwlab.com/yuriiq/)
  
- Imperial44 v4 – Wireless Edition:
  - [Case for 3D printing (STL)](stl/wireless)
  - [Case model for editing (STEP)](step/wireless)
  - [Circuit schematic](https://oshwlab.com/yuriiq/)
  - [Case model for Metal Edition (CNC)](cnc/wireless)
  
### Firmware
- [Pre-compiled files](https://github.com/ergohaven/keymap_hub)
- Source code: 
    - wired [QMK](https://github.com/ergohaven/vial-qmk)
    - wireless [RMK](https://github.com/ergohaven/rmk-eh)
    - wireless [ZMK](https://github.com/ergohaven/ergohaven-zmk)

## Availability
The complete keyboard (not a diy kit!) is available for purchase at [eh.industries](https://eh.industries/)
