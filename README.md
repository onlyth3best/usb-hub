# usb-hub


a usb hub made with help from fallout.hackclub.com:
- inputs: 1x USB-C
- outputs: 2x USB-C, 2x USB-A

### images of the pcb and the schematics:
pcb editor:
<br/>
<img width="340" height="331" alt="pcb with copper fill but not visible here for simplicity of distinction" src="https://github.com/user-attachments/assets/7f4e1168-38d9-4763-a8fb-79c2de07b26f" />
<br/>
schem:
<br/>
<img width="417" height="274" alt="schem" src="https://github.com/user-attachments/assets/dafe5ba3-f431-4a0d-8295-cd2c56681fea" />

### motivation:
My motivations were:
1) a USB-hub would be generally very useful
2) I wanted to try out another software different to KiCad, so I used EasyEDA for this one
3) --I really wanted to add the penguin on one of my projects because I haven't already--

### firmware/setup…
…is not required, all you need is the USBs you want to plug in ;DD

### poster zine:
<img width="540" height="828" alt="usbPNGπ" src="https://github.com/user-attachments/assets/dfd19d6f-5d44-46d6-8281-aacf3f0583f8" />
<br/> [usbPDFF.pdf](https://github.com/user-attachments/files/28807005/usbPDFF.pdf)




### BOM:
| ID | Name | Designator | Footprint | Quantity | Manufacturer | Part Manufacturer | Supplier | Supplier Part | Price | Link |
|----|------|------------|-----------|----------|--------------|-------------------|----------|---------------|-------|------|
| 1 | 10.0 QHHTZB6.3 | USB5, USB4 | USB-A-TH_10.0QHHTZB6.3 | 2 | 10.0 QHHTZB6.3 | SHOU HAN(深圳) | LCSC | C668591 | 0.067 | [Link](https://item.szlcsc.com/698534.html) |
| 2 | 1uF | C1, C2, C3, C5, C6, C8, C10, C11 | C0603 | 8 |  |  |  |  | 0.007 | [Link](https://item.szlcsc.com/362304.html) |
| 3 | 100uF | C4, C7, C9 | C0603 | 3 |  |  |  |  | 0.007 | [Link](https://item.szlcsc.com/362304.html) |
| 4 | 5.1k | R1, R2, R3, R4, R5, R6 | R0603 | 6 |  |  |  |  | 0.007 | [Link](https://www.mouser.in/datasheet/2/447/PYu_RT_1_to_0_01_RoHS_L_11-1669912.pdf) |
| 5 | SL2.1S | U1 | SSOP-16_L4.6-W2.6-P0.53-LS4.0-BL | 1 | SL2.1s | CoreChips(深圳市科瑞芯半导体有限公司) | LCSC | C2684433 | 0.253 | [Link](https://item.szlcsc.com/2782346.html) |
| 6 | TYPE-C 16PIN 2MD(073) | USB2, USB3, USB1 | USB-C-SMD_TYPE-C-16PIN-2MD-073 | 3 | TYPE-C 16PIN 2MD(073) | SHOU HAN(深圳) | LCSC | C2765186 | 0.074 | [Link](https://item.szlcsc.com/datasheet/TYPE-C%2016PIN%202MD(073)/2901843.html?spm=sc.gbn.xds.a___sc.gbn.hd.ss&lcsc_vid=QlQLUVBQT1I5U01NTVhYVlRZRkVSRVFReGlhRkVSRVFReGlhRkVSRVFRUW5WVlJGUVhRVEUxUkVBeEZFUXlFQW5WVlJGUVhRVEUxRkVBeEZFUXlFQW5WVlJGUVhRVEUxRkVBeEZFUXlFQW5WVlJGUVhRVEUxRkVBeEZFUXlF) |
| x | x | x | x | x | x | x | x | x | total price: 0.415 USD | x |
