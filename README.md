# Calculator-TV-killer
This is going to be an open source battery powered calculator further more containing a IR LED To turn off LED's and such.

Calculator-TV-killer
This is my second GitHub repo so it is a work in progress but I built this calculator for schoool and to just have fun
If you have any ideas or concerns I am fully open to critisism just leave a comment! :)


CALCULATOR-TV-KILLER
GRAYSONS MACRO MACHINE is a 16 key calculator. It also has A IR LED to turn off tv's, and uses arduino IDE code

Features:
2 peice 3d printed case. Custom colors ooooohhh.
1 IR LEDs. these should work as a TV killer for TV's.
5 Keys!
CADModel:



It has 2 seperate printed pieces. The base where the PCB sits, and the top cover.


Schematic:
<img width="3507" height="2480" alt="image" src="https://github.com/user-attachments/assets/dc42e26d-059f-4bde-ab0a-734e1a3eec96" />


Made in KiCAd.



PCB:

<img width="524" height="635" alt="image" src="https://github.com/user-attachments/assets/1b0ed64b-2747-4b52-9045-7860caa8c3e4" />


3d file of the PCB (With components =>)


<img width="445" height="561" alt="image" src="https://github.com/user-attachments/assets/5945d136-fe8c-4396-9d7a-9ec8b2e4bfd6" />


Here's my PCB! It was made in KiCad.



Firmware Overview
This hackpad uses QMK firmware for everything.

I might add more in the future! That's it for now

BOM:

"Id";"Designator";"Footprint";"Quantity";"Designation";"Supplier and ref";
1;"D18,D8,D7,D9,D14,D2,D4,D6,D12,D17,D10,D3,D13,D11,D15,D16";"DIOAD753W49L380D172B";16;"1N4148";;;
2;"SW5,SW2,SW1,SW7,SW3,SW/1,SW0,SW-1,SW6,SW_DEL1,SW=1,SW+1,SW4,SW9,SW*1,SW8";"SW_Cherry_MX_1.00u_PCB";16;"SW_Push";;;
3;"Q1";"TO-92L_Inline";1;"NPN";;;
4;"R1";"R_Axial_DIN0204_L3.6mm_D1.6mm_P5.08mm_Horizontal";1;"4.7 Kohms";;;
5;"R2";"R_Axial_DIN0204_L3.6mm_D1.6mm_P5.08mm_Horizontal";1;"39 ohms";;;
6;"Brd1";"MODULE_DM-OLED096-636";1;"SSD1306";;;
7;"U1";"XIAO-RP2040-DIP";1;"XIAO-RP2040-DIP";;;
8;"D1";"LED_D5.0mm_IRGrey";1;"Super-bright 5mm IR LED - 940nm";;;

(Above is the CSV version of the BOM and below is just normal)

Here should be everything you need to make this hackpad

16x Cherry MX Blue Switches $7.00

16x DSA Keycaps that have "1-9 and zero and +,-,DIvide, del, and =" $0.00 will 3d print

4x M3x5x4 Heatset inserts $9.00 in kit with bolts

4x M3x16mm SHCS Bolts

16X 1N4148 Diode $6.00

1x XIAO RP2040 $4.00

1X SSD1306 0.96 inch 128X64 pixel IC2 OLED $7.00

2X Resistors 1, 39 ohm and 1, 4.7 K ohms $9.00

1X Super-bright 5mm IR LED - 940nm   $0.75 from https://www.adafruit.com/product/387?srsltid=AfmBOopKEtXa5r7NFesDsghJSTXoIFfyz0MSlwi3U7XEUNElIbBDi-1RI1c 

1X 2N2222A NpN transistor $9.00

1x Case (2 printed parts)

1x Usb-C to Usb-C lanyard for powering $5.50

Links to parts:

(Key switches: https://www.amazon.com/Fejwlvs-Pre-Lubricated-Dustproof-Mechanical-Keyboards、MX/dp/B0GFLWMHY3/ref=sr_1_5_sspa?crid=3TJCBFA8PGTQK&dib=eyJ2IjoiMSJ9.MUELtzarVPh1NqYa3EK1EJX_g7YVVKb-c7MwhJsWGQ344GIhIl-PX6bq-dzCIrdG2ZZSXJkA5gzC0x911H3jToB145t_VOCoupObny0bRJfZM-_c-W2LrwPkR_oeFhJsg147z1ndf54UBGYbY7ICptbjB0E-_0nWCnNexu8NyoJ7gpnpGRNZTVOjRBUkvVUtIj_MfOLu_XL7Y48IlwUBEG8ISojdYuzAm5yTf8BuM1A.fPJX89Ir0riDGDDwBn1CHYfFr8JJkA3AthyHhh7_-Gg&dib_tag=se&keywords=Cherry%2BMX%2BSwitches%2Bassortment&qid=1770771376&sprefix=cherry%2Bmx%2Bswitches%2Bassortment%2Caps%2C311&sr=8-5-spons&sp_csd=d2lkZ2V0TmFtZT1zcF9tdGY&th=1)

(M3 SCREWS: https://www.amazon.com/VGBUY-600pcs-Assortment-Printer-Stainless/dp/B0D1XJ766V/ref=sr_1_3?crid=DU098LO3QODD&dib=eyJ2IjoiMSJ9.Du6eKz-vfO0otk5mZ1epwb26hK4HILY0qCvZQ6E4-VgU6e89cluUXjtjfZIvUGbF9NxRdzD5YhClawBfZFMASpfWCuKk22x7URdzAubaEadEBMZ6Rh09zVvdqkRiFQFjiRSGrwzi5Qe1ccEfKJeyasZTVNNAr9eHwwp1YlTueobPvoCKJ3l9Rvi7OVN7y6AQWVRzJQ41PTKSk8AiO-tfXMYKcVn9QrPtTXP5sRsfFuM.wu_jUhdkO1ThY-q4n_EelO83HTC5mmx34PS2apULzZo&dib_tag=se&keywords=m3%2Bscrew%2Bkit&qid=1770772225&sprefix=m3%2B%2Caps%2C393&sr=8-3&th=1)

(Diode's: https://www.amazon.com/EEEEE-Switching-MILLIAMP-Electronic-Silicon/dp/B0FC289DVH/ref=sr_1_3?adgrpid=187993647764&dib=eyJ2IjoiMSJ9.09kb66VxlBzN6HV_K6vi9c3BtsT_GWIPLEMOancfoBooOv5sAhUe0KJrpccH8oIJbFJ1coaWUnv1i5DlAVBA3kbCZuk955cUs34FZ8ectndBFcRl1BKHD615JLLndPvKXpMQibx0KPeYs7Pfwm11T47iHx91AOU_NtuFRmZ-S6ZTVdhFIRA6xDMAZ3EsCo7A4Mc5Ceq0WJoWEiMsRLqAt-2GGjcp-vMOh658Zf6EMaQ.i8j7rV67SDP0j3WiHW-2NAeSR0HlO6Gm_Qic2Eam-7s&dib_tag=se&hvadid=779642773176&hvdev=c&hvexpln=0&hvlocphy=1015431&hvnetw=g&hvocijid=17401088717729557827--&hvqmt=e&hvrand=17401088717729557827&hvtargid=kwd-1460322120&hydadcr=3018_13539028_2128636&keywords=1n4148%2Bdiode&mcid=f2eeec0b3b1a399ca0829126fa611e7c&qid=1770772333&sr=8-3&th=1)

(Xiao rp2040: https://www.seeedstudio.com/XIAO-RP2040-v1-0-p-5026.html?srsltid=AfmBOopbY1dPG0hkWRmuq-8IblETa4FKZI_A_LwXS7W4cyi72GPG5dC0)

(Oled: https://www.amazon.com/HiLetgo-Serial-128X64-Display-Color/dp/B06XRBYJR8/ref=sr_1_14?dib=eyJ2IjoiMSJ9.-ICP_fsWugdKDgQgSChofrz_cxu5gXXrIqC7Oti8ouBA6k22EBIip1KIDQkzeUzAM3TIGEcGFmhTq4kUNLDraTARmFcZWe2e5xJTCVNmV0Zqru5ayaqTzVTfmVSKK1vPKlhdlyfTbvsVwAUeM8U0_QspdKzwU3r-hVGchVoB8YxghW9QmqtIMhSRpyuK1w3d92oOKPxZLqb7Dx4uWkj8t7PktWAoiKCEelgmlDdEpgs.bLAaVfHUDtO_f-E_t68LlBmzt6VLDGur_D5G8TdRrvM&dib_tag=se&keywords=ssd1306%2Boled%2Bdisplay&qid=1770772525&sr=8-14&th=1)

(Resistors: https://www.amazon.com/ALLECIN-4W-Film-Resistor-Kit/dp/B0CDWW5BFH/ref=sr_1_2_sspa?crid=2GFJNXM111L61&dib=eyJ2IjoiMSJ9.QqtzmCG7CKt6OW1fHgTb26uI1Fk5beBArSayNzxiB8Q5PfdVBH_fHO-i8Oq2qY-fWR7yyRFHSOeC2RmG0E7w0mtYXMe7donOE8TLqFJXOTNzKCJuCvEQlzEzyaf3O-5D_cGpYC_4Fr3yk3Cr-o6ynATg4hoUh2RQ702TuOH8x5eLmKRUgMbPIwMs_D7sSJRQNzIp690U9bqkzdZqwfkoHmcEW4ZQApPpl7A3RfpMR0I.rNj68d3atHfDnVFBy4if--2BnhPglSZ4rxG2vOnEO3s&dib_tag=se&keywords=resistor%2Bkit&qid=1770772812&sprefix=resistorr%2Bkit%2Caps%2C245&sr=8-2-spons&sp_csd=d2lkZ2V0TmFtZT1zcF9hdGY&th=1)

(Transistors: https://www.amazon.com/ALLECIN-BJT-Transistor-Kit-Transistors/dp/B0C1V82313/ref=sr_1_6_sspa?adgrpid=185130291583&dib=eyJ2IjoiMSJ9.VsgPg0CpoSmLDBqmaiKemioTeubimeA5gbMHrCVETlLHuISg-KQ_TrgB12GRq8EUaYy89mM0c8-gk-RRM7sUZ8OY_KPwAymbrb3ne8DceQ6rNBHwQu6SpnO7aX1fF-uOq3RHPGw6mCcCi4gI_n7mZHaYhRP6ijxiwM2Nf_gKmGpQ-FS1_OmSGLsohkzApgw1RSXm4t1kRg-nTRCBaIXqIqptj6rTDNmtVQwazBJiD4g.agcjYWhGehzE-07sqCxWXgNTTte9UZ4l36FKaob2p5g&dib_tag=se&hvadid=779721006957&hvdev=c&hvexpln=0&hvlocphy=1015431&hvnetw=g&hvocijid=13743219906590360801--&hvqmt=e&hvrand=13743219906590360801&hvtargid=kwd-323540961971&hydadcr=24632_13858459_8069&keywords=2n2222a+npn+transistor&mcid=a2ab655ea30438a0a56edb22fa9e6f95&qid=1770773008&sr=8-6-spons&sp_csd=d2lkZ2V0TmFtZT1zcF9tdGY&psc=1)

(Usb-C to Usb-C: https://www.amazon.com/Keychain-Braided-Charging-1Phone17-Samsung/dp/B0FP2BCDQ1?th=1)

JOKE TIMMEEEEEE
What happenes when you eat tinfoil



you...sheet metal :)
