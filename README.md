# RCM-hardware-D1

v1.0

* 1.75 by 1.575 inches, 44.45 by 40.0 millimeters
* 2 motors (one L293D)
* 2 servos OR qwiic connector
* Qwiic-Compatible
* runs on 4 NiMH AAs
* battery monitoring
* uses a Wemos D1 mini with esp8266 CPU

The goal of this project is to make the cheapest [RCM board](https://github.com/rcmgames).

Program with [RCMv2](https://github.com/rcmgames/rcmv2)

The RCM D1 uses a Wemos D1 mini v4.0.0 esp8266 board. 

Use the AVR versions of JMotor functions not the ESP32 versions.

## Options for purchasing

* send the gerbers to a PCB manufacturer of your choice

## Components
Solder by hand to assemble your boards.
| part | links | quantity | notes |
| ----- | ----- | ----- | ----- |
| RCM D1 circuit board | see options for purchasing above | 1 | |
| Wemos D1 mini with esp8266 | [link](https://www.wemos.cc/en/latest/d1/d1_mini.html) | 1 | |
| L293D | [digikey](https://www.digikey.com/en/products/detail/texas-instruments/L293DNE/379724) | 1 | |
| 16 pin IC socket | | 1 | optional |
| 18k resistor | [0.13 inch long resistor](https://www.digikey.com/en/products/detail/stackpole-electronics-inc/RNMF14FTC18K0/2617300) | 1 | R1 |
| 10k resistor | [0.13 inch long resistor](https://www.digikey.com/en/products/detail/yageo/MFR-12FTF52-10K/9133815) | 1 | R2 |
| 47uF capacitor | | 1 | |
| Qwiic connector (JST SH) | [digikey](https://www.digikey.com/en/products/detail/jst-sales-america-inc/SM04B-SRSS-TB/926710) | 1 | optional, for qwiic connector |
| 2x3 male header pins | | 1 | for servos |
| 2 female header pins | | 2 | for motors |
| 8 female header pins | | 2 | often included with the wemos D1 |
| 8 male header pins | | 2 | often included with the wemos D1 |
| battery wires | [JST RCY](https://www.amazon.com/dp/B00Z04QFN2/) or battery plug of your choice | 1 | |

![photo of assembled board](https://github.com/RCMgames/RCM-hardware-D1/blob/4e2fc0ec890348c75a8239374bd78f8cda3d46ad/Photos/image%201.JPG)

## Acknowledgements

The RCM D1 was originally created for [PNW Assistive Technology's RC car project](https://github.com/PNW-AT/rc-car-car)

Thanks for the WemosD1 Kicad footprints! https://github.com/rubienr/wemos-d1-mini-kicad

