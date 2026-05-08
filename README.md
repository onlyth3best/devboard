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
| Reference  | Qty | Value | approx price in USD | links I found|
| ------------- | ------------- | ------------- | ------------- | ------------- |
| U1  | 1 | Seeed Studio XIAO RP2040 | $ 3.9 | [link](https://www.seeedstudio.com/XIAO-RP2040-v1-0-p-5026.html?srsltid=AfmBOor69gTiD1i0IEN-NgJbt-CYkVZTgTP96P1gkFrOACfPGnEJtVJv) / microcontroller board |
| D1, D2, D3  | 3 | LED / L08R5000Q1 | $ 0.1 | https://jlcpcb.com/partdetail/JLCPCBAssembly-LED_NCD0805C1/C9900035298 |
| R1, R2, R3  | 3 | resistor | $ 0.01 | https://jlcpcb.com/partdetail/TyoHM-RMC_0603_10K_JN/C5362358 |
| SW1, Sw2, SW3  | 3 | Button/Switch | $ 0.5 | [https://jlcpcb.com/partdetail/ESwitch-TL3301AF160QG/C273519 |
| BZ1  | 1 | Buzzer | % 0.5 | https://jlcpcb.com/partdetail/Jiangsu_HuanengElec-HND2310B/C2877 |

