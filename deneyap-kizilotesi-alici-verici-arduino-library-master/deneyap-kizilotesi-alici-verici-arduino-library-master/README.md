# Deneyap Infrarad Receiver Transmitter Arduino Library
[FOR TURKISH VERSION](docs/README_tr.md) ![trflag](https://github.com/deneyapkart/deneyapkart-arduino-core/blob/master/docs/tr.png)

***** Add photo ****

Arduino library for Deneyap Infrarad Receiver Transmitter

## :mag_right:Specifications 
- `Product ID` **M53**, **mpv1.0**
- `MCU` STM8S003F3, TSOP2238, IR12-21C/TR8
- `Weight` 
- `Module Dimension` 25,4 mm x 25,4 mm
- `I2C address` 0x22, 0x56, 0x26, 0x27

| Address |  | 
| :---      | :---     |
| 0x22 | default address |
| 0x56 | address when ADR1 pad is shorted |
| 0x26 | address when ADR2 pad is shorted |
| 0x27 | address when ADR1 and ADR2 pads are shorted |

## :closed_book:Documentation
[Deneyap Infrarad Receiver Transmitter](https://docs.deneyapkart.org/en/content/contentDetail/deneyap-modul-deneyap-kzlotesi-alc-ve-verici-m53)

[Deneyap Infrarad Receiver Transmitter Schematic](https://cdn.deneyapkart.org/media/upload/userFormUpload/RCUEAfKv1djiBgGqmZ3aGDLyIjuitj8l.pdf)

[Deneyap Infrarad Receiver Transmitter Mechanical Drawing](https://cdn.deneyapkart.org/media/upload/userFormUpload/nkjtUEbPHdyuWbOrYQRJaQrbdgkd5l8Q.pdf)

[Vishay TSOP2238-datasheet](https://www.vishay.com/docs/82459/tsop48.pdf)

[Everlight IR12-21C/TR8-datasheet](https://eu.mouser.com/datasheet/2/143/EVER_S_A0007423485_1-2548612.pdf)

[How to install a Arduino Library](https://docs.arduino.cc/software/ide-v1/tutorials/installing-libraries)

## :pushpin:Deneyap Infrarad Receiver Transmitter
This Arduino library allows you to use Deneyap Infrarad Receiver Transmitter with I2C peripheral. You can use this library in your projects with any Arduino compatible board with I2C peripheral.

## :globe_with_meridians:Repository Contents
- `/docs ` README_tr.md and product photos
- `/examples ` Examples with .ino extension sketches
- `/src ` Source files (.cpp .h)
- `keywords.txt ` Keywords from this library that will be highlighted in the Arduino IDE
- `library.properties ` General library properties for the Arduino package manager

## Version History
1.0.2 - added new function(I2C_ReadFirmwareData16bit), updated function(getFwVersion) and comment lines

1.0.1 - changed example file names (KizilOtesiAlici -> KizilotesiAlici, KizilOtesiVerici -> KizilotesiVerici )

1.0.0 - initial release

## :rocket:Hardware Connections
- Deneyap Infrarad Receiver Transmitter and Board can be connected with I2C cable
- or 3V3, GND, SDA and SCL pins can be connected with jumper cables

|Infrarad Receiver Transmitter| Function | Board pins | 
|:--- |   :---  | :---|
|3.3V | Power   |3.3V |      
|GND  | Ground  | GND | 
|SDA  | I2C Data  | SDA pin |
|SCL  | I2C Clock | SCL pin |
|SWIM | Debug | no connection |
|RES  | Debug | no connection |
|TX| Transmit pin | |
|RX|  Receive pin | |

## :bookmark_tabs:License Information
Please review the [LICENSE](https://github.com/deneyapkart/deneyap-kizilotesi-alici-verici-arduino-library/blob/master/LICENSE) file for license information.
