# USB-UART CH340 converter board Hardware design

## About the product

| ![USB-UART CH340 converter board](https://github.com/SolderedElectronics/USB-UART-CH340C-converter-board-hardware-design/blob/main/OUTPUTS/V1.1.1/333028.jpg?raw=true) |
| :----------------------------------------------------------: |
|      [Buy USB-UART CH340 converter board](https://www.solde.red/333028)      |

This small adapter converts USB communication into UART (serial) communication, and everything you might need is already on this small board. In addition to the classic UART pins that are arranged in the standard layout: DTR, RXD, TXD, VCC, CTS, GND, other pins available of the CH340 chip are also available on header: RS232, RI, DCD, DSR, RST and CTS. Indication LEDs show activity on RXT and TXD lines, and a 500mA fuse protects this programmer, the USB port of the computer that is connected, and other devices connected to it from damage.

Additionally, there is a voltage regulator and a switch on the board, and it is possible to choose the output voltage of 3.3V or 5V, depending on the device you are using. The logic of the UART signal is always 3.3V, but don't worry, 5V devices will work with 3V3 UART logic without any problems. Use a USB-C cable to connect.

## Repository contents

All Soldered Electronics hardware designed in KiCAD, and repositories are organized in the following way:

- CAD folder - contains KiCAD files (Schematics, Board, Panel Board), sorted by version. Change log lists all changes between versions.
- OUTPUTS - contains useful files, such as Bill of Materials (BOM), PDF of schematics, 3D .step file of the board and gerber files, sorted by version. 
- OUTPUTS -> Compliance - Certificates and useful legal stuff. 

## Want to contribute?

Please feel free to submit a pull request if you have any contributions. We encourage you to submit an issue or pull request if you find a bug. 

## About Soldered

<img src="https://raw.githubusercontent.com/e-radionicacom/Soldered-Generic-Arduino-Library/dev/extras/Soldered-logo-color.png" alt="soldered-logo" width="500"/>

At Soldered, we design and manufacture a wide selection of electronic products to help you turn your ideas into acts and bring you one step closer to your final project. Our products are intented for makers and crafted in-house by our experienced team in Osijek, Croatia. We believe that sharing is a crucial element for improvement and innovation, and we work hard to stay connected with all our makers regardless of their skill or experience level. Therefore, all our products are open-source. Finally, we always have your back. If you face any problem concerning either your shopping experience or your electronics project, our team will help you deal with it, offering efficient customer service and cost-free technical support anytime. Some of those might be useful for you:

- [Web Store](https://www.soldered.com/shop)
- [Tutorials & Projects](https://soldered.com/learn)
- [Community & Technical support](https://soldered.com/community)

## License info

All Soldered open-source hardware (OSH) is under The TAPR Open Hardware License. Read more in the LICENSE file. 

No warranty - all designs in this repository are distributed in the hope that they will be useful, but without any warranty. They are provided "AS IS", therefore without warranty of any kind, either expressed or implied. The entire quality and performance of what you do with the contents of this repository are your responsibility. In no event, Soldered Electronics will be liable for your damages, losses, including any general, special, incidental or consequential damage arising out of the use or inability to use the contents of this repository. 

## Have fun! 
And thank you from your fellow makers at Soldered Electronics.