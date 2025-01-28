# USB-UART CH340 converter board Hardware Design

## About the Product

| ![USB-UART CH340 converter board Image](https://solde.red/333028/image) |
| :----------------------------------------------------------: |
| [Buy USB-UART CH340 converter board](https://www.solde.red/333028) |

This small USBUART adapter converts USB communication into UART (serial) communication, and everything you might need is already on this small board. In addition to the classic UART pins that are arranged in the standard layout: DTR, RXD, TXD, VCC, CTS, GND, other pins available of the CH340 chip are also available on header: RS232, RI, DCD, DSR, RST and CTS. Indication LEDs show activity on RXT and TXD lines, and a 500mA fuse protects this programmer, the USB port of the computer that is connected, and other devices connected to it from damage.

Additionally, there is a voltage regulator and a switch on the board, and it is possible to choose the output voltage of 3.3V or 5V, depending on the device you are using. The logic of the UART signal is always 3.3V, but don’t worry, 5V devices will work with 3V3 UART logic without any problems. Use a USB-C cable to connect.

---

## Repository Contents

This repository contains all design files for USB-UART CH340 converter board, organized as follows:

- **`CAD` folder**: Contains KiCAD design files, including:
  - Schematics
  - PCB layout
  - Panel PCB layout
  - Source 3D files in Fusion360, if any
  - All files are sorted by version with a detailed change log.
- **`OUTPUTS` folder**: Includes all production-ready files, such as:
  - Bill of Materials (BOM) and interactive BOM (iBOM)
  - PDF versions of schematics
  - 3D `.step` file of the board
  - 3D-printable models
  - Gerber files for PCB manufacturing
  - Image of the pinout of the board
  - Product image
  - Compliance, legal and generic sales documents

Refer to the `Change Log` in the CAD folder for details about updates between versions.

---

## Learn More About the Product

Beyond the repository, explore the following resources:

### Soldered Verify

<img src="https://raw.githubusercontent.com/SolderedElectronics/Soldered-Resources-Repo/6f55c41a17e9bb5a67ade86c7f5ef8254db4fe6f/images/soldered_verify_purple.svg" width="300" alt="Soldered Verify Logo" align="left">

The **Soldered Verify** system ensures every board you purchase from Soldered is fully functional. It also provides access to exclusive test data for your product. To get started, find the unique Soldered Verify ID on your product's packaging and enter the ID on the [Soldered Verify page](https://soldered.com/verify/) to access test results and additional product details.

### Soldered Community

<img src="https://github.com/SolderedElectronics/Soldered-Resources-Repo/blob/main/images/Soldered%20Community%20Logo.png?raw=true" width="300" alt="soldered-verify-logo" align="left">

Soldered Community is your go-to place for technical support. Our engineers track and answer all questions posted there, and it’s a great space for the maker community. Get answers to your questions and solutions for your challenges at [Soldered Community](https://soldered.com/community).

### solde.red

solde.red is an ultimate URL shortener and information hub. Access it by typing solde.red/ followed by your product SKU, e.g., [solde.red/333000](https://solde.red/333000), to find getting-started guides, datasheets, open-source hardware and software files, certifications, images, pinouts, and more. Read more about the shortener [here](https://solde.red/info/).

---

## Contributing

Contributions are welcome! Here’s how you can get involved:

- Submit pull requests to enhance the design or fix issues.
- Report bugs or problems by opening an issue.

We encourage community collaboration to make this product even better.

---

## About Soldered

<img src="https://github.com/SolderedElectronics/Soldered-Resources-Repo/blob/main/images/Soldered-logo-color.png?raw=true" alt="soldered-logo" width="500"/>

[Soldered for Makers](https://soldered.com) specializes in designing and manufacturing electronic products tailored for enthusiasts, ranging from hobbyists to professionals. Our portfolio includes electronic boards, sensors, and actuators that are widely utilized in fields such as microelectronics, mechatronics, robotics, programming, and IoT. Every product we offer is designed in-house and built upon open-source hardware and software platforms. Proudly certified and manufactured within the European Union, our catalog likely includes the product you need for your project.

We complement these products with comprehensive tutorials and manuals, product descriptions, schematics, programming codes, and project examples. Our round-the-clock [customer and technical support](https://soldered.com/community) is available for all our products, irrespective of the sales channel. Soldered’s success and services reflect our maker community’s unwavering [trust](https://www.trustpilot.com/review/soldered.com), for which we are deeply grateful. Join our community and create using Soldered products.

---

## License

All Soldered open-source hardware (OSH) is under The TAPR Open Hardware License. Read more in the LICENSE file located in this repository.

**Disclaimer:**

No warranty - all designs in this repository are distributed in the hope that they will be useful, but without any warranty. They are provided "AS IS", therefore without warranty of any kind, either expressed or implied. The entire quality and performance of what you do with the contents of this repository are your responsibility. In no event Soldered Electronics will be liable for your damages, or losses, including any general, special, incidental, or consequential damage arising out of the use or inability to use the contents of this repository. 

---

## Have fun!

Thank you for your support from your fellow makers at Soldered Electronics.

Happy Making!