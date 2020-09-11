# Brduino-Nano

Brduino-Nano is a 'jeux de mots Vis-à-vis' [Arduino-Nano](https://store.arduino.cc/arduino-nano).

It is an open-source project that brings the Arduino-Nano form-factor into this century. :sunglasses:  

Whereas the Arduino Nano is based on the [8-Bit ATmega328](https://www.microchip.com/wwwproducts/en/ATmega328) controller from [Microchip](https://www.microchip.com/), the Brduino Nano is based on the [32-Bit Arm Cortex M4](https://developer.arm.com/ip-products/processors/cortex-m/cortex-m4) from [NXP](https://www.nxp.com/part/MK22FN512VLH12#/). The footprint of the Arduino-Nano and the Brduino-Nano are identical, as a matter of fact for plenty of applications the Brduino-Nano is a drop-in replacement for the Arduino-Nano. 

=== image here ===

Below a quick comparison of the Arduino-Nano against the Brduino-Nano :

|  | Arduino-Nano | Brduino-Nano |        
|---|:---|:---|
| Microcontroller | [ATmega328](https://www.microchip.com/wwwproducts/en/ATmega328) | [MK22FN512VLH12](https://www.nxp.com/part/MK22FN512VLH12#/) |
| Architecture | 8-Bit AVR | 32-Bit Cortex M4 |
| Operating Voltage |  5 V | 3.3 V |
| Flash Memory | 32 KB | 512 KB |
| SRAM | 2 KB | 128 KB |
| Clock Speed | 16 MHz | 120 MHz |
| DAC | N/A | 1 x 12 Bit |
| Timers | 2 x 8 Bit / 1 x 16 Bit | 1 x 16 Bit|
| ADC | 1 x 10 Bit | 2 x 16 Bit |
| Analog IN Pins | 8 | 8 |
| DC Current per I/O Pins |	40 mA (I/O Pins) | ? |
| Input Voltage | 7-12 V | 5 V |
| Digital I/O Pins | 22 (6 of which are PWM) | 22 (? of which are PWM) |
| PWM Output | 	6 | ? |
| Power Consumption | 19 mA | ? |
| PCB Size | 18 x 45 mm | 18 x 45 mm |
| Weight |	7 g | 7 g |

The Brduino ofcourse doesn't use the ugly [arduino IDE](https://www.arduino.cc/en/main/software) but the [eclipse](https://www.eclipse.org/) based [MCUXpresso](https://www.nxp.com/design/software/development-software/mcuxpresso-software-and-tools-/mcuxpresso-integrated-development-environment-ide:MCUXpresso-IDE) :stuck_out_tongue_winking_eye:.

Connecting from your IDE to the Brduino is done via a [JLink](https://www.segger.com/products/debug-probes/j-link/models/model-overview/), but we advise to go for the [JLink Pro](https://www.segger.com/products/debug-probes/j-link/models/j-link-pro/) in combination with the [10-Pin Needle Adapter](https://www.segger.com/products/debug-probes/j-link/accessories/adapters/10-pin-needle-adapter/) as the Brduino holds such a connector.

The project is realized in [Altium Designer](https://www.altium.com/altium-designer/), but, as the gerbers are included in the repo, you can produce the Brduino yourself without having Altium license(s), or alternatively you can contact [Thomas Arul](thomasarul@likom.com.my) at [Likom](http://www.likom.com.my/) to get a quote for these things. 

