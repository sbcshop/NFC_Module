# NFC_Module
The NFC module is an excellent solution for enthusiasts, makers, and developers who want to harness the power of NFC technology, whether it's for prototyping or building advanced applications, the NFC module delivers the functionality, reliability, and flexibility needed for a wide range of projects.
The term "NFC" refers to a short-range, high-frequency wireless communication technology that is mostly used in mobile or portable devices. It enables radio connection to be established by just touching two phones together or keeping them a few millimeters apart. Holding two devices together and using a wireless communication link for the final few centimeters makes choosing a target straightforward. Induction-coupling, which uses magnetic induction between two loop antennas operating at a frequency of 13.56MHZ with data rates ranging from 106 kbit/s to 424 kbit/s, is the primary communication method used in NFC. 

### Features:
- Adopt special base station RF chip, stable performance, good compatibility
- Both Read/Write operation possible
- Integrated Antenna
- Communication Interface: TTL
- Support Protocols like ISO14443B, ISO18092
- Contactless card supports like NTAG213, Mifare one S50, Mifare one S70, ultralight, FM11RF08

### Specifications:
- NFC Module Frequency: 13.56MHz
- Reading Distance: >50mm (The effective distance is related to the IC card and the use environment)
- Reading Time: <200ms
- Output Format: TTL
- Size: 28.9 x 28.9mm
- Supply: 5V DC
- Operating Current: 50mA
- Operating Temperature: -15°C to +55°C
- Storage Temperature: -20°C to +70°C

## Getting Started with NFC module
### Pinout 

### Hardware Connection

Here you will need NFC module with any USB to TTL converter, for this guide we are using one which available [here](https://shop.sb-components.co.uk/products/usb-ttl?variant=40312245059667).

|USB to TTL (CP2102 Variants) | NFC Module | Function |
|---|---|---|
|VCC | 5V | Positive Supply |
|GND | GND | Ground |
|TXD | TXD | UART Connection | 
|RXD | RXD | UART Connection |

|USB to TTL (CH340 Variants) | NFC Module | Function |
|---|---|---|
|VCC | 5V | Positive Supply |
|GND | GND | Ground |
|TXD | RXD | UART Connection | 
|RXD | TXD | UART Connection |

**Note:** Do cross connection of UART pins if module don't repond or showing connection failed with your USB to TTL.

- Once connection done then connect converter to USB port of PC/Laptop and verify your COM Port through device manager


