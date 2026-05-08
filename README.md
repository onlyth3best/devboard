# devboard
a project for Fallout, made with help from stasis.hackclub.com/starter-projects/devboard
<br/> /kicad has relevant KiCad files, /3dmodels has the .STEP files, /prod has gerber files~
<br/>
<br/> "_A development board is a specially designed printed circuit board (PCB) that integrates a microcontroller or microprocessor along with essential components such as input/output pins, power supply interfaces, USB connectors, LEDs, and often onboard sensors._" ([source](https://regentelectronics.com/microcontrollers/what-is-a-development-board-introduction-types-and-applications))
<br/>
<br/>
<img width="1234" height="1162" alt="3d model" src="https://github.com/user-attachments/assets/570f8f33-88ab-48ca-ac09-4169da12091c" />
<img width="300" height="660" alt="pcb editor" src="https://github.com/user-attachments/assets/a84ecda0-ac98-4b52-b42e-2df32b509cc2" />
<img width="939" height="658" alt="schematics" src="https://github.com/user-attachments/assets/d94d43e9-a3d2-4dee-9128-a593b5eea717" />

<br/> Setup guide:
<br/>  - the only setup needed in this sense, if I understand correctly, is using the files in this repo to upload to JLCPCB or something similar in order to receive a physical version…
<br/>
<br/> Motivation:
<br/>  - Since I started hardware very very recently, I wanted to try my hand at something that was a little more challenging than a regular pcb but still within the realm of KiCad work. Additionally, I find routing very fun to do, hence why I had a lot of fun with this project in certain parts.

<img width="540" height="828" alt="DevboardZine" src="https://github.com/user-attachments/assets/c66fe2dd-9528-4c80-bb63-e738891184bc" />

<br/> BOM:
<br/>
| Reference  | Qty | Value | approx price in USD | links I found, not sure if they're all 100% correct though :heavysob: |
| ------------- | ------------- | ------------- | ------------- | ------------- |
| C1, C10 | 2 | C_0402_1005Metric | 0.02 | [links](https://www.lcsc.com/search?q=0402+capacito) |
| C2, C3, C4, C5, C6, C7, C8, C9, C11, C12 | 10 | C_0402_1005Metric | 0.10| [links](https://www.lcsc.com/search?q=0402+capacito) |
| C13, C14 | 2 | C_0402_1005Metric | 0.02 | [links](https://www.lcsc.com/search?q=0402+capacito) |
| C15, C16 | 2 | C_0402_1005Metric | 0.02 | [links](https://www.lcsc.com/search?q=0402+capacito) |
| J1 | 1 | USB_C_Receptacle_HRO_TYPE-C-31-M-12 | 0.10–0.25 | [links](https://www.lcsc.com/product-detail/USB-Type-C_Korean-Hroparts-Elec-TYPE-C-31-M-12_C165948.html) |
| J2, J3 | 2 | PinHeader_1x20_P2.54mm_Vertical | 0.20–0.80 | [links](https://www.lcsc.com/search?q=1x20+2.54mm+pin+header) |
| J4 | 1 | R_0402_1005Metric | 0.01 | [links](https://www.lcsc.com/search?q=0402+resistor) |
| R1, R2 | 2 | R_0402_1005Metric | 0.02 | [links](https://www.digikey.com/en/products/filter/resistor-kits/129) |
| R3, R4 | 2 | R_0402_1005Metric | 0.02 | [links](https://www.digikey.com/en/products/filter/resistor-kits/129) |
| R5, R7 | 2 | R_0402_1005Metric | 0.02 | [links](https://www.digikey.com/en/products/filter/resistor-kits/129) |
| R6 | 1 | R_0402_1005Metric | 0.01 | [links](https://www.digikey.com/en/products/filter/resistor-kits/129) |
| SW1 | 1 | SW_Push_SPST_NO_Alps_SKRK | 0.10–0.50 | [links](https://www.lcsc.com/search?q=Alps+SKRK) |
| U1 | 1 | QFN-56-1EP_7x7mm_P0.4mm_EP3.2x3.2mm | 1.00–2.00 | links |
| U3 | 1 | SOIC-8_5.3x5.3mm_P1.27mm | 0.30–0.80 | links |
| U4 | 1 | TO-92_Inline | 0.05–0.30 | links |
| Y1 | 1 | Crystal_SMD_3225-4Pin_3.2x2.5mm | 0.05–0.20  | links |

