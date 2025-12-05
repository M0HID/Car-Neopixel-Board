# L12

A WLED controller for automotive use, in a small, compact form factor!
<!-- <img width="800" height="800" alt="image" src="https://github.com/user-attachments/assets/39ac8dde-5d62-4a3a-8a3b-83e27b269cae" /> -->
(Check out WLED [here](https://github.com/wled/WLED)!)
## ⚙️ Features:
- < 50x50mm total footprint
- Onboard ESP32
- USB-C for both power and flashing
- JTAG pins broken out
- 4 sets of outputs for 4 seperate strips
- Onboard XL4015 buck converter to convert 12V -> 5V

## 🔧 Installation:
1. In a web browser, open https://install.wled.me/
2. Bridge the `boot` solder jumper using a paperclip, then plug it into your computer
3. Press `install` on the webpage, select the ESP32 Device, and follow the instructions there!

## 📷 Gallery
Check out the PCB on [KiCanvas](https://kicanvas.org/?github=https%3A%2F%2Fgithub.com%2FM0HID%2FCar-Neopixel-Board)!
| Description | Image |
|------------|--------|
| PCB Front | <img width="795" height="773" alt="image" src="https://github.com/user-attachments/assets/370227ed-6131-466c-a66a-65344d7af5b4" /> |
||<img width="602" height="721" alt="image" src="https://github.com/user-attachments/assets/5b7ff3c5-9552-4e81-89f3-43bf6f149d87" />|
| PCB Back | <img width="802" height="898" alt="image" src="https://github.com/user-attachments/assets/9b7a1c26-a375-465a-8d3d-00f749c4f913" /> |
||<img width="616" height="744" alt="image" src="https://github.com/user-attachments/assets/0918257f-3df5-40fe-bede-0a98849e5db3" />
| Board full | <img width="1052" height="798" alt="image" src="https://github.com/user-attachments/assets/657ddeaa-f386-4a39-80a7-04cb840e9109" /> |


## 🔢 BOM
The boards are designed so that one can be installed in all 4 doors of the car, with the final one going in the dashboard as the 'Master' controller

### Capacitors

| Item | Quantity x5 | Part Number | Supplier / Link | Price |
|------|------------|------------|----------------|-------|
| 100 nF capacitor | 3 | C1591 | [link](https://www.lcsc.com/product-detail/C1591.html) | 0.26 |
| 1 µF capacitor | 3 | C15849 | [link](https://www.lcsc.com/product-detail/C15849.html) | 0.25 |
| 22 µF capacitor | 2 | C86295 | [link](https://www.lcsc.com/product-detail/C86295.html) | 0.15 |
| 220 µF capacitor | 1 | C125977 | [link](https://www.lcsc.com/product-detail/C125977.html) | 1.04 |
| 330 µF capacitor | 1 | C249985 | [link](https://www.lcsc.com/product-detail/C249985.html) | 1.57 |

### Resistors

| Item | Quantity x5 | Part Number | Supplier / Link | Price |
|------|------------|------------|----------------|-------|
| 5.1 kΩ resistor | 2 | C23186 | [link](https://www.lcsc.com/product-detail/C23186.html) | 0.11 |
| 10 kΩ resistor | 1 | C25804 | [link](https://www.lcsc.com/product-detail/C25804.html) | 0.10 |
| 22 Ω resistor | 2 | C23345 | [link](https://www.lcsc.com/product-detail/C23345.html) | 0.10 |
| 62 Ω resistor | 4 | C23222 | [link](https://www.lcsc.com/product-detail/C23222.html) | 0.12 |
| 1 kΩ resistor | 1 | C21190 | [link](https://www.lcsc.com/product-detail/C21190.html) | 0.10 |
| 3.3 kΩ resistor | 1 | C22978 | [link](https://www.lcsc.com/product-detail/C22978.html) | 0.11 |

### Diodes

| Item | Quantity x5 | Part Number | Supplier / Link | Price |
|------|------------|------------|----------------|-------|
| SS54 Schottky diode | 3 | C22452 | [link](https://www.lcsc.com/product-detail/C22452.html) | 0.87 |

### Inductors

| Item | Quantity x5 | Part Number | Supplier / Link | Price |
|------|------------|------------|----------------|-------|
| APH1265 inductor | 1 | C5349639 | [link](https://www.lcsc.com/product-detail/C5349639.html) | 2.00 |

### Connectors

| Item | Quantity x5 | Part Number | Supplier / Link | Price |
|------|------------|------------|----------------|-------|
| USB Type-C port | 1 | C165948 | [link](https://www.lcsc.com/product-detail/C165948.html) | 0.88 |
| 2-pin terminal block | 4 | C709041 | [link](https://www.lcsc.com/product-detail/C709041.html) | 3.67 |

### ICs / Modules

| Item | Quantity x5 | Part Number | Supplier / Link | Price |
|------|------------|------------|----------------|-------|
| Level shifter | 1 | C2675672 | [link](https://www.lcsc.com/product-detail/C2675672.html) | 5.73 |
| Buck converter | 1 | C51661 | [link](https://www.lcsc.com/product-detail/C51661.html) | 3.27 |
| Voltage regulator | 1 | C6186 | [link](https://www.lcsc.com/product-detail/C6186.html) | 0.83 |
| ESP32 module | 1 | C2913199 | [link](https://www.lcsc.com/product-detail/C2913199.html) | 25.97 |

### LEDs

| Item | Quantity | Supplier / Link | Price | Notes |
|------|----------|----------------|-------|-------|
| Full Colors 90 cm LED strip | 4 | [link](https://www.aliexpress.com/item/1005004940479033.html) | 28.32 |  |
| Full Colors 110 cm LED strip | 1 | [link](https://www.aliexpress.com/item/1005004940479033.html) | 7.71 |  |
| Full Colors LED strip pack (alternative) | 6 | – | 34.50 | Includes 4×75 cm, 1×90 cm, 1×25 cm (driver side dashboard) |

### PCB (JLCPCB)

| Item | Quantity | Supplier / Link | Price | Notes |
|------|----------|----------------|-------|-------|
| PCB | 5 | [JLCPCB](https://jlcpcb.com) | 3.50 | Standard options for 2-layer board |

<img width="704" height="662" alt="image" src="https://github.com/user-attachments/assets/302f7537-6937-4ebf-951f-3cf34bfc4901" />
