EESchema Schematic File Version 4
EELAYER 30 0
EELAYER END
$Descr A4 11693 8268
encoding utf-8
Sheet 1 1
Title ""
Date ""
Rev ""
Comp ""
Comment1 ""
Comment2 ""
Comment3 ""
Comment4 ""
$EndDescr
$Comp
L Device:Battery BT1
U 1 1 60702E26
P 600 1650
F 0 "BT1" H 708 1696 50  0000 L CNN
F 1 "Charge" H 708 1605 50  0000 L CNN
F 2 "Zimprich:Anschlussklemme_2P_RM5,08" V 600 1710 50  0001 C CNN
F 3 "~" V 600 1710 50  0001 C CNN
	1    600  1650
	1    0    0    -1  
$EndComp
$Comp
L charge_pcb-rescue:FUSE-Zimprich-charge_pcb-rescue F1
U 1 1 60704371
P 1250 1450
F 0 "F1" H 1250 1690 50  0000 C CNN
F 1 "5A" H 1250 1599 50  0000 C CNN
F 2 "Zimprich:Fuseholder_Reichelt_PL112000" H 1250 1450 60  0001 C CNN
F 3 "" H 1250 1450 60  0000 C CNN
	1    1250 1450
	1    0    0    -1  
$EndComp
Wire Wire Line
	600  2900 600  1850
$Comp
L charge_pcb-rescue:BC548BTA-dk_Transistors-Bipolar-BJT-Single-charge_pcb-rescue Q1
U 1 1 60711074
P 3350 2100
F 0 "Q1" H 3538 2153 60  0000 L CNN
F 1 "BC547C" H 3538 2047 60  0000 L CNN
F 2 "digikey-footprints:TO-92-3_Formed_Leads" H 3550 2300 60  0001 L CNN
F 3 "https://media.digikey.com/pdf/Data%20Sheets/ON%20Semiconductor%20PDFs/BC546-50.pdf" H 3550 2400 60  0001 L CNN
F 4 "BC548BTACT-ND" H 3550 2500 60  0001 L CNN "Digi-Key_PN"
F 5 "BC548BTA" H 3550 2600 60  0001 L CNN "MPN"
F 6 "Discrete Semiconductor Products" H 3550 2700 60  0001 L CNN "Category"
F 7 "Transistors - Bipolar (BJT) - Single" H 3550 2800 60  0001 L CNN "Family"
F 8 "https://media.digikey.com/pdf/Data%20Sheets/ON%20Semiconductor%20PDFs/BC546-50.pdf" H 3550 2900 60  0001 L CNN "DK_Datasheet_Link"
F 9 "/product-detail/en/on-semiconductor/BC548BTA/BC548BTACT-ND/4553029" H 3550 3000 60  0001 L CNN "DK_Detail_Page"
F 10 "TRANS NPN 30V 0.1A TO-92" H 3550 3100 60  0001 L CNN "Description"
F 11 "ON Semiconductor" H 3550 3200 60  0001 L CNN "Manufacturer"
F 12 "Active" H 3550 3300 60  0001 L CNN "Status"
	1    3350 2100
	1    0    0    -1  
$EndComp
Wire Wire Line
	3450 2900 3450 2300
Wire Wire Line
	3450 1450 3450 1500
$Comp
L Device:R R4
U 1 1 60712C09
P 3450 1650
F 0 "R4" H 3520 1696 50  0000 L CNN
F 1 "4k7" H 3520 1605 50  0000 L CNN
F 2 "Resistor_THT:R_Axial_DIN0207_L6.3mm_D2.5mm_P7.62mm_Horizontal" V 3380 1650 50  0001 C CNN
F 3 "~" H 3450 1650 50  0001 C CNN
	1    3450 1650
	1    0    0    -1  
$EndComp
Wire Wire Line
	3450 1800 3450 1850
$Comp
L Device:R R3
U 1 1 60713C5E
P 3000 2100
F 0 "R3" H 3070 2146 50  0000 L CNN
F 1 "4k7" H 3070 2055 50  0000 L CNN
F 2 "Resistor_THT:R_Axial_DIN0207_L6.3mm_D2.5mm_P7.62mm_Horizontal" V 2930 2100 50  0001 C CNN
F 3 "~" H 3000 2100 50  0001 C CNN
	1    3000 2100
	0    1    1    0   
$EndComp
Text GLabel 2470 2185 3    50   Input ~ 0
pinChargeEnable
Connection ~ 3450 1850
Wire Wire Line
	3450 1850 3450 1900
Connection ~ 3450 2900
Wire Wire Line
	4350 1950 4800 1950
$Comp
L charge_pcb-rescue:HEADER_2-Zimprich-charge_pcb-rescue J3
U 1 1 607207B7
P 6400 750
F 0 "J3" V 6445 622 60  0000 R CNN
F 1 "Power Switch" V 6550 1050 60  0000 R CNN
F 2 "TerminalBlock:TerminalBlock_bornier-2_P5.08mm" H 6400 750 60  0001 C CNN
F 3 "" H 6400 750 60  0000 C CNN
	1    6400 750 
	0    -1   -1   0   
$EndComp
$Comp
L charge_pcb-rescue:HEADER_2-Zimprich-charge_pcb-rescue J2
U 1 1 60721ABE
P 5800 750
F 0 "J2" V 5845 622 60  0000 R CNN
F 1 "Battery" V 5950 900 60  0000 R CNN
F 2 "TerminalBlock:TerminalBlock_bornier-2_P5.08mm" H 5800 750 60  0001 C CNN
F 3 "" H 5800 750 60  0000 C CNN
	1    5800 750 
	0    -1   -1   0   
$EndComp
$Comp
L charge_pcb-rescue:FUSE-Zimprich-charge_pcb-rescue F2
U 1 1 60732011
P 6450 1100
F 0 "F2" V 6350 900 50  0000 L CNN
F 1 "10A" V 6450 900 50  0000 L CNN
F 2 "Zimprich:Fuseholder_Reichelt_PL112000" H 6450 1100 60  0001 C CNN
F 3 "" H 6450 1100 60  0000 C CNN
	1    6450 1100
	0    1    1    0   
$EndComp
$Comp
L power:GND #PWR02
U 1 1 607340F0
P 5850 850
F 0 "#PWR02" H 5850 600 50  0001 C CNN
F 1 "GND" H 5855 677 50  0000 C CNN
F 2 "" H 5850 850 50  0001 C CNN
F 3 "" H 5850 850 50  0001 C CNN
	1    5850 850 
	1    0    0    -1  
$EndComp
$Comp
L power:GND #PWR01
U 1 1 60734664
P 3450 2900
F 0 "#PWR01" H 3450 2650 50  0001 C CNN
F 1 "GND" H 3455 2727 50  0000 C CNN
F 2 "" H 3450 2900 50  0001 C CNN
F 3 "" H 3450 2900 50  0001 C CNN
	1    3450 2900
	1    0    0    -1  
$EndComp
Wire Wire Line
	3450 2900 4800 2900
$Comp
L Diode:MBR745 D4
U 1 1 60735AE0
P 6500 2400
F 0 "D4" V 6454 2480 50  0000 L CNN
F 1 "MBR1045" V 6545 2480 50  0000 L CNN
F 2 "Package_TO_SOT_THT:TO-220-2_Vertical" H 6500 2225 50  0001 C CNN
F 3 "http://www.onsemi.com/pub_link/Collateral/MBR735-D.PDF" H 6500 2400 50  0001 C CNN
	1    6500 2400
	0    1    1    0   
$EndComp
Wire Wire Line
	5150 2900 5150 3250
Wire Wire Line
	5150 3250 5950 3250
Wire Wire Line
	6500 3250 6500 2900
$Comp
L Diode:1N4148 D3
U 1 1 60738085
P 4800 2350
F 0 "D3" V 4754 2430 50  0000 L CNN
F 1 "NOT USE" V 4845 2430 50  0000 L CNN
F 2 "Diode_THT:D_DO-35_SOD27_P7.62mm_Horizontal" H 4800 2175 50  0001 C CNN
F 3 "https://assets.nexperia.com/documents/data-sheet/1N4148_1N4448.pdf" H 4800 2350 50  0001 C CNN
	1    4800 2350
	0    1    1    0   
$EndComp
Wire Wire Line
	4800 2200 4800 1950
Wire Wire Line
	4800 2500 4800 2900
Connection ~ 4800 2900
Wire Wire Line
	4800 2900 5150 2900
$Comp
L charge_pcb-rescue:BC548BTA-dk_Transistors-Bipolar-BJT-Single-charge_pcb-rescue Q3
U 1 1 6073AD5E
P 7800 2050
F 0 "Q3" H 7988 2103 60  0000 L CNN
F 1 "BC547C" H 7988 1997 60  0000 L CNN
F 2 "digikey-footprints:TO-92-3_Formed_Leads" H 8000 2250 60  0001 L CNN
F 3 "https://media.digikey.com/pdf/Data%20Sheets/ON%20Semiconductor%20PDFs/BC546-50.pdf" H 8000 2350 60  0001 L CNN
F 4 "BC548BTACT-ND" H 8000 2450 60  0001 L CNN "Digi-Key_PN"
F 5 "BC548BTA" H 8000 2550 60  0001 L CNN "MPN"
F 6 "Discrete Semiconductor Products" H 8000 2650 60  0001 L CNN "Category"
F 7 "Transistors - Bipolar (BJT) - Single" H 8000 2750 60  0001 L CNN "Family"
F 8 "https://media.digikey.com/pdf/Data%20Sheets/ON%20Semiconductor%20PDFs/BC546-50.pdf" H 8000 2850 60  0001 L CNN "DK_Datasheet_Link"
F 9 "/product-detail/en/on-semiconductor/BC548BTA/BC548BTACT-ND/4553029" H 8000 2950 60  0001 L CNN "DK_Detail_Page"
F 10 "TRANS NPN 30V 0.1A TO-92" H 8000 3050 60  0001 L CNN "Description"
F 11 "ON Semiconductor" H 8000 3150 60  0001 L CNN "Manufacturer"
F 12 "Active" H 8000 3250 60  0001 L CNN "Status"
	1    7800 2050
	1    0    0    -1  
$EndComp
Text GLabel 7025 2220 3    50   Input ~ 0
pinBatterySwitch
$Comp
L Device:R R5
U 1 1 6073CDAC
P 7450 2050
F 0 "R5" V 7657 2050 50  0000 C CNN
F 1 "4k7" V 7566 2050 50  0000 C CNN
F 2 "Resistor_THT:R_Axial_DIN0207_L6.3mm_D2.5mm_P7.62mm_Horizontal" V 7380 2050 50  0001 C CNN
F 3 "~" H 7450 2050 50  0001 C CNN
	1    7450 2050
	0    -1   -1   0   
$EndComp
$Comp
L Device:R R6
U 1 1 60740775
P 7900 1600
F 0 "R6" H 7970 1646 50  0000 L CNN
F 1 "4k7" H 7970 1555 50  0000 L CNN
F 2 "Resistor_THT:R_Axial_DIN0207_L6.3mm_D2.5mm_P7.62mm_Horizontal" V 7830 1600 50  0001 C CNN
F 3 "~" H 7900 1600 50  0001 C CNN
	1    7900 1600
	1    0    0    -1  
$EndComp
Wire Wire Line
	7000 1450 7250 1450
Wire Wire Line
	6500 2900 7275 2900
Connection ~ 6500 2900
Wire Wire Line
	6500 2900 6500 2550
Wire Wire Line
	7900 1750 7900 1800
Connection ~ 7900 1800
Wire Wire Line
	7900 1800 7900 1850
Connection ~ 7900 2900
$Comp
L Device:CP C1
U 1 1 607607AB
P 9015 2200
F 0 "C1" H 9133 2246 50  0000 L CNN
F 1 "100uF" H 9133 2155 50  0000 L CNN
F 2 "Zimprich:Elko_vert_11.2x6.3mm_RM2.5" H 9053 2050 50  0001 C CNN
F 3 "~" H 9015 2200 50  0001 C CNN
	1    9015 2200
	1    0    0    -1  
$EndComp
Wire Wire Line
	9015 2050 9015 1450
Wire Wire Line
	9015 2350 9015 2900
$Comp
L Connector:Screw_Terminal_01x02 J1
U 1 1 607FC1A2
P 6095 6540
F 0 "J1" H 6250 6530 50  0000 L CNN
F 1 "Main_PCB2" H 6200 6430 50  0000 L CNN
F 2 "Connector_JST:JST_XH_B2B-XH-A_1x02_P2.50mm_Vertical" H 6095 6540 50  0001 C CNN
F 3 "~" H 6095 6540 50  0001 C CNN
	1    6095 6540
	1    0    0    -1  
$EndComp
Text GLabel 5895 6540 0    50   Input ~ 0
pinBatterySwitch
Text GLabel 5895 6640 0    50   Input ~ 0
pinChargeEnable
Wire Wire Line
	600  1450 1000 1450
$Comp
L charge_pcb-rescue:DIODE-Lötpad_2,5mm-charge_pcb-rescue D5
U 1 1 608CEAE9
P 7450 1450
F 0 "D5" H 7450 1642 40  0000 C CNN
F 1 "SB1240" H 7450 1566 40  0000 C CNN
F 2 "Diode_THT:D_DO-41_SOD81_P10.16mm_Horizontal" H 7450 1450 60  0001 C CNN
F 3 "" H 7450 1450 60  0000 C CNN
	1    7450 1450
	1    0    0    -1  
$EndComp
Wire Wire Line
	7650 1450 7900 1450
Wire Wire Line
	7000 1600 7000 1450
Wire Wire Line
	5750 850  5750 1150
Wire Wire Line
	6350 850  6350 1150
Wire Wire Line
	6350 1150 5750 1150
Wire Wire Line
	6450 1350 6450 1600
Wire Wire Line
	6450 1600 7000 1600
Wire Wire Line
	6450 1600 6450 2250
Wire Wire Line
	6450 2250 6500 2250
Connection ~ 6450 1600
$Comp
L Diode:MBR745 D1
U 1 1 60702097
P 1095 2260
F 0 "D1" V 1049 2340 50  0000 L CNN
F 1 "MBR1045" V 1140 2340 50  0000 L CNN
F 2 "Package_TO_SOT_THT:TO-220-2_Vertical" H 1095 2085 50  0001 C CNN
F 3 "http://www.onsemi.com/pub_link/Collateral/MBR735-D.PDF" H 1095 2260 50  0001 C CNN
	1    1095 2260
	0    1    1    0   
$EndComp
$Comp
L Device:R R9
U 1 1 60730CD6
P 1620 1940
F 0 "R9" H 1690 1986 50  0000 L CNN
F 1 "4.7kO" H 1690 1895 50  0000 L CNN
F 2 "Resistor_THT:R_Axial_DIN0207_L6.3mm_D2.5mm_P7.62mm_Horizontal" V 1550 1940 50  0001 C CNN
F 3 "~" H 1620 1940 50  0001 C CNN
	1    1620 1940
	1    0    0    -1  
$EndComp
$Comp
L Device:LED D6
U 1 1 6073C265
P 1620 2240
F 0 "D6" V 1659 2122 50  0000 R CNN
F 1 "LED" V 1568 2122 50  0000 R CNN
F 2 "LED_THT:LED_D1.8mm_W3.3mm_H2.4mm" H 1620 2240 50  0001 C CNN
F 3 "~" H 1620 2240 50  0001 C CNN
	1    1620 2240
	0    -1   -1   0   
$EndComp
Wire Wire Line
	3450 1450 4350 1450
Wire Wire Line
	7300 2050 7275 2050
Wire Wire Line
	7025 2050 7025 2220
$Comp
L Device:R R10
U 1 1 60AB9B49
P 7275 2435
F 0 "R10" V 7482 2435 50  0000 C CNN
F 1 "4k7" V 7391 2435 50  0000 C CNN
F 2 "Resistor_THT:R_Axial_DIN0207_L6.3mm_D2.5mm_P7.62mm_Horizontal" V 7205 2435 50  0001 C CNN
F 3 "~" H 7275 2435 50  0001 C CNN
	1    7275 2435
	1    0    0    -1  
$EndComp
Wire Wire Line
	7275 2585 7275 2900
Connection ~ 7275 2900
Wire Wire Line
	7275 2900 7900 2900
Wire Wire Line
	7275 2285 7275 2050
Connection ~ 7275 2050
Wire Wire Line
	7275 2050 7025 2050
Wire Wire Line
	8405 2325 7900 2325
Wire Wire Line
	7900 2250 7900 2325
Connection ~ 7900 2325
Wire Wire Line
	7900 2325 7900 2900
$Comp
L Connector:Screw_Terminal_01x02 J8
U 1 1 60AA2A4C
P 8505 2525
F 0 "J8" V 8377 2605 50  0000 L CNN
F 1 "Start" V 8468 2605 50  0000 L CNN
F 2 "Connector_JST:JST_XH_B2B-XH-A_1x02_P2.50mm_Vertical" H 8505 2525 50  0001 C CNN
F 3 "~" H 8505 2525 50  0001 C CNN
	1    8505 2525
	0    1    1    0   
$EndComp
Wire Wire Line
	7900 1800 8505 1800
Wire Wire Line
	8505 1800 8505 2325
$Comp
L Transistor_FET:IRF9540N Q4
U 1 1 60B1B32A
P 8725 1250
F 0 "Q4" H 8929 1296 50  0000 L CNN
F 1 "IRF9540N" H 8929 1205 50  0000 L CNN
F 2 "Package_TO_SOT_THT:TO-220-3_Vertical" H 8925 1175 50  0001 L CIN
F 3 "http://www.irf.com/product-info/datasheets/data/irf9540n.pdf" H 8725 1250 50  0001 L CNN
	1    8725 1250
	1    0    0    1   
$EndComp
Wire Wire Line
	8525 1250 8505 1250
Wire Wire Line
	8505 1250 8505 1800
Connection ~ 8505 1800
Wire Wire Line
	8825 1050 7900 1050
Wire Wire Line
	7900 1050 7900 1450
Connection ~ 7900 1450
$Comp
L Device:R R11
U 1 1 60C5823D
P 2615 2250
F 0 "R11" V 2822 2250 50  0000 C CNN
F 1 "4k7" V 2731 2250 50  0000 C CNN
F 2 "Resistor_THT:R_Axial_DIN0207_L6.3mm_D2.5mm_P7.62mm_Horizontal" V 2545 2250 50  0001 C CNN
F 3 "~" H 2615 2250 50  0001 C CNN
	1    2615 2250
	1    0    0    -1  
$EndComp
Wire Wire Line
	1500 1450 1620 1450
Wire Wire Line
	1500 1450 1500 1695
Wire Wire Line
	1500 1695 1095 1695
Wire Wire Line
	1095 1695 1095 2110
Connection ~ 1500 1450
Wire Wire Line
	1095 2410 1095 2900
Wire Wire Line
	600  2900 1095 2900
Connection ~ 1095 2900
Wire Wire Line
	1620 1790 1620 1450
Wire Wire Line
	1620 2390 1620 2900
Wire Wire Line
	1095 2900 1620 2900
Connection ~ 1620 2900
Wire Wire Line
	2470 2100 2470 2185
Connection ~ 2615 2100
Wire Wire Line
	2615 2100 2470 2100
Wire Wire Line
	2615 2100 2850 2100
Wire Wire Line
	2615 2400 2615 2900
Connection ~ 2615 2900
Wire Wire Line
	2615 2900 3450 2900
$Comp
L Mechanical:MountingHole_Pad H2
U 1 1 6073E1F7
P 11850 1050
F 0 "H2" H 11950 1099 50  0000 L CNN
F 1 "MountingHole_Pad" H 11950 1008 50  0000 L CNN
F 2 "MountingHole:MountingHole_3.2mm_M3_DIN965_Pad_TopBottom" H 11850 1050 50  0001 C CNN
F 3 "~" H 11850 1050 50  0001 C CNN
	1    11850 1050
	1    0    0    -1  
$EndComp
$Comp
L Mechanical:MountingHole_Pad H4
U 1 1 6073E5C5
P 11850 2000
F 0 "H4" H 11950 2049 50  0000 L CNN
F 1 "MountingHole_Pad" H 11950 1958 50  0000 L CNN
F 2 "MountingHole:MountingHole_3.2mm_M3_DIN965_Pad_TopBottom" H 11850 2000 50  0001 C CNN
F 3 "~" H 11850 2000 50  0001 C CNN
	1    11850 2000
	1    0    0    -1  
$EndComp
$Comp
L Mechanical:MountingHole_Pad H3
U 1 1 6073E399
P 11850 1550
F 0 "H3" H 11950 1599 50  0000 L CNN
F 1 "MountingHole_Pad" H 11950 1508 50  0000 L CNN
F 2 "MountingHole:MountingHole_3.2mm_M3_DIN965_Pad_TopBottom" H 11850 1550 50  0001 C CNN
F 3 "~" H 11850 1550 50  0001 C CNN
	1    11850 1550
	1    0    0    -1  
$EndComp
$Comp
L Mechanical:MountingHole_Pad H1
U 1 1 6073B4AE
P 11850 550
F 0 "H1" H 11950 599 50  0000 L CNN
F 1 "MountingHole_Pad" H 11950 508 50  0000 L CNN
F 2 "MountingHole:MountingHole_3.2mm_M3_DIN965_Pad_TopBottom" H 11850 550 50  0001 C CNN
F 3 "~" H 11850 550 50  0001 C CNN
	1    11850 550 
	1    0    0    -1  
$EndComp
$Comp
L charge_pcb-rescue:GND-Lötpad_2,5mm-charge_pcb-rescue #PWR0104
U 1 1 60746896
P 11850 2100
F 0 "#PWR0104" H 11850 1850 60  0001 C CNN
F 1 "GND" H 11855 1919 60  0000 C CNN
F 2 "" H 11850 2100 60  0000 C CNN
F 3 "" H 11850 2100 60  0000 C CNN
	1    11850 2100
	1    0    0    -1  
$EndComp
$Comp
L charge_pcb-rescue:GND-Lötpad_2,5mm-charge_pcb-rescue #PWR0103
U 1 1 60746674
P 11850 1650
F 0 "#PWR0103" H 11850 1400 60  0001 C CNN
F 1 "GND" H 11855 1469 60  0000 C CNN
F 2 "" H 11850 1650 60  0000 C CNN
F 3 "" H 11850 1650 60  0000 C CNN
	1    11850 1650
	1    0    0    -1  
$EndComp
$Comp
L charge_pcb-rescue:GND-Lötpad_2,5mm-charge_pcb-rescue #PWR0102
U 1 1 607463A7
P 11850 1150
F 0 "#PWR0102" H 11850 900 60  0001 C CNN
F 1 "GND" H 11855 969 60  0000 C CNN
F 2 "" H 11850 1150 60  0000 C CNN
F 3 "" H 11850 1150 60  0000 C CNN
	1    11850 1150
	1    0    0    -1  
$EndComp
$Comp
L charge_pcb-rescue:GND-Lötpad_2,5mm-charge_pcb-rescue #PWR0101
U 1 1 6073E8B8
P 11850 650
F 0 "#PWR0101" H 11850 400 60  0001 C CNN
F 1 "GND" H 11855 469 60  0000 C CNN
F 2 "" H 11850 650 60  0000 C CNN
F 3 "" H 11850 650 60  0000 C CNN
	1    11850 650 
	1    0    0    -1  
$EndComp
Wire Wire Line
	4350 1450 4350 1550
Wire Wire Line
	3450 1850 4050 1850
$Comp
L Transistor_FET:IRF9540N Q2
U 1 1 60B519B7
P 4250 1750
F 0 "Q2" H 4454 1796 50  0000 L CNN
F 1 "IRF9540N" H 4454 1705 50  0000 L CNN
F 2 "Package_TO_SOT_THT:TO-220-3_Vertical" H 4450 1675 50  0001 L CIN
F 3 "http://www.irf.com/product-info/datasheets/data/irf9540n.pdf" H 4250 1750 50  0001 L CNN
	1    4250 1750
	1    0    0    1   
$EndComp
Wire Wire Line
	4050 1850 4050 1750
$Comp
L charge_pcb-rescue:INA226-Sense_I2C U1
U 1 1 60EF0E1B
P 5700 2400
F 0 "U1" V 5746 1972 50  0000 C CNN
F 1 "INA226" V 5655 1972 50  0000 C CNN
F 2 "Current_sense:INA226" H 5700 2850 50  0001 C CNN
F 3 "" H 5700 2850 50  0001 C CNN
	1    5700 2400
	0    -1   -1   0   
$EndComp
$Comp
L power:+3.3V #PWR05
U 1 1 60F0BD0F
P 6050 2850
F 0 "#PWR05" H 6050 2700 50  0001 C CNN
F 1 "+3.3V" H 6065 3023 50  0000 C CNN
F 2 "" H 6050 2850 50  0001 C CNN
F 3 "" H 6050 2850 50  0001 C CNN
	1    6050 2850
	-1   0    0    1   
$EndComp
Wire Wire Line
	5750 1150 5750 1950
Connection ~ 5750 1150
Wire Wire Line
	5600 1950 4800 1950
Connection ~ 4800 1950
Wire Wire Line
	5950 2850 5950 3250
Connection ~ 5950 3250
Wire Wire Line
	5950 3250 6500 3250
NoConn ~ 5350 2850
NoConn ~ 5450 2850
NoConn ~ 5650 2850
Wire Wire Line
	1620 2900 2615 2900
Text GLabel 1700 1250 2    50   Output ~ 0
V_Charge
Wire Wire Line
	1700 1250 1500 1250
Wire Wire Line
	1500 1250 1500 1450
Text GLabel 5550 2850 3    50   Output ~ 0
V_Charge
Text GLabel 8800 1700 0    50   Input ~ 0
V_Bat
Wire Wire Line
	8825 1450 8900 1450
Wire Wire Line
	8800 1700 8900 1700
Wire Wire Line
	8900 1700 8900 1450
Connection ~ 8900 1450
Wire Wire Line
	8900 1450 9015 1450
$Comp
L charge_pcb-rescue:INA226-Sense_I2C U2
U 1 1 60F60520
P 9650 4950
F 0 "U2" H 9650 5525 50  0000 C CNN
F 1 "INA226" H 9650 5434 50  0000 C CNN
F 2 "Current_sense:INA226" H 9650 5400 50  0001 C CNN
F 3 "" H 9650 5400 50  0001 C CNN
	1    9650 4950
	1    0    0    -1  
$EndComp
Connection ~ 1620 1450
Connection ~ 3450 1450
Wire Wire Line
	2850 1450 3450 1450
Wire Wire Line
	1620 1450 2450 1450
$Comp
L charge_pcb-rescue:DIODE-Lötpad_2,5mm-charge_pcb-rescue D2
U 1 1 6071023D
P 2650 1450
F 0 "D2" H 2650 1642 40  0000 C CNN
F 1 "SB1240" H 2650 1566 40  0000 C CNN
F 2 "Diode_THT:D_DO-41_SOD81_P10.16mm_Horizontal" H 2650 1450 60  0001 C CNN
F 3 "" H 2650 1450 60  0000 C CNN
	1    2650 1450
	1    0    0    -1  
$EndComp
$Comp
L Connector:Screw_Terminal_01x02 J10
U 1 1 60FC516E
P 10300 6000
F 0 "J10" V 10500 5950 50  0000 C CNN
F 1 "Mot_Left" V 10400 5950 50  0000 C CNN
F 2 "TerminalBlock:TerminalBlock_bornier-2_P5.08mm" H 10300 6000 50  0001 C CNN
F 3 "~" H 10300 6000 50  0001 C CNN
	1    10300 6000
	0    1    1    0   
$EndComp
$Comp
L power:GND #PWR020
U 1 1 60FE4056
P 10300 5800
F 0 "#PWR020" H 10300 5550 50  0001 C CNN
F 1 "GND" H 10305 5627 50  0000 C CNN
F 2 "" H 10300 5800 50  0001 C CNN
F 3 "" H 10300 5800 50  0001 C CNN
	1    10300 5800
	-1   0    0    1   
$EndComp
Wire Wire Line
	10100 5000 10200 5000
$Comp
L power:GND #PWR018
U 1 1 60FF05EA
P 8950 5300
F 0 "#PWR018" H 8950 5050 50  0001 C CNN
F 1 "GND" H 8955 5127 50  0000 C CNN
F 2 "" H 8950 5300 50  0001 C CNN
F 3 "" H 8950 5300 50  0001 C CNN
	1    8950 5300
	1    0    0    -1  
$EndComp
Wire Wire Line
	9200 5200 8950 5200
Wire Wire Line
	8950 5200 8950 5300
$Comp
L power:+3.3V #PWR019
U 1 1 60FF5DE1
P 9200 5300
F 0 "#PWR019" H 9200 5150 50  0001 C CNN
F 1 "+3.3V" H 9215 5473 50  0000 C CNN
F 2 "" H 9200 5300 50  0001 C CNN
F 3 "" H 9200 5300 50  0001 C CNN
	1    9200 5300
	-1   0    0    1   
$EndComp
Text GLabel 9200 4800 0    50   Input ~ 0
V_Bat
$Comp
L charge_pcb-rescue:INA226-Sense_I2C U6
U 1 1 6100FDBD
P 7850 4950
F 0 "U6" H 7850 5525 50  0000 C CNN
F 1 "INA226" H 7850 5434 50  0000 C CNN
F 2 "Current_sense:INA226" H 7850 5400 50  0001 C CNN
F 3 "" H 7850 5400 50  0001 C CNN
	1    7850 4950
	1    0    0    -1  
$EndComp
$Comp
L Connector:Screw_Terminal_01x02 J9
U 1 1 6100FDC9
P 8500 6000
F 0 "J9" V 8700 5950 50  0000 C CNN
F 1 "Mot_Right" V 8600 5950 50  0000 C CNN
F 2 "TerminalBlock:TerminalBlock_bornier-2_P5.08mm" H 8500 6000 50  0001 C CNN
F 3 "~" H 8500 6000 50  0001 C CNN
	1    8500 6000
	0    1    1    0   
$EndComp
$Comp
L power:GND #PWR017
U 1 1 6100FDD0
P 8500 5800
F 0 "#PWR017" H 8500 5550 50  0001 C CNN
F 1 "GND" H 8505 5627 50  0000 C CNN
F 2 "" H 8500 5800 50  0001 C CNN
F 3 "" H 8500 5800 50  0001 C CNN
	1    8500 5800
	-1   0    0    1   
$EndComp
Wire Wire Line
	8300 5000 8400 5000
Wire Wire Line
	8400 5300 8400 5800
$Comp
L power:GND #PWR015
U 1 1 6100FDD8
P 7150 5300
F 0 "#PWR015" H 7150 5050 50  0001 C CNN
F 1 "GND" H 7155 5127 50  0000 C CNN
F 2 "" H 7150 5300 50  0001 C CNN
F 3 "" H 7150 5300 50  0001 C CNN
	1    7150 5300
	1    0    0    -1  
$EndComp
Wire Wire Line
	7400 5200 7150 5200
Wire Wire Line
	7150 5200 7150 5300
$Comp
L power:+3.3V #PWR016
U 1 1 6100FDE0
P 7400 5300
F 0 "#PWR016" H 7400 5150 50  0001 C CNN
F 1 "+3.3V" H 7415 5473 50  0000 C CNN
F 2 "" H 7400 5300 50  0001 C CNN
F 3 "" H 7400 5300 50  0001 C CNN
	1    7400 5300
	-1   0    0    1   
$EndComp
Text GLabel 7400 4800 0    50   Input ~ 0
V_Bat
$Comp
L charge_pcb-rescue:INA226-Sense_I2C U5
U 1 1 610169E3
P 6100 4950
F 0 "U5" H 6100 5525 50  0000 C CNN
F 1 "INA226" H 6100 5434 50  0000 C CNN
F 2 "Current_sense:INA226" H 6100 5400 50  0001 C CNN
F 3 "" H 6100 5400 50  0001 C CNN
	1    6100 4950
	1    0    0    -1  
$EndComp
$Comp
L Connector:Screw_Terminal_01x02 J7
U 1 1 610169EF
P 6750 6000
F 0 "J7" V 6950 5950 50  0000 C CNN
F 1 "Mow1" V 6850 5950 50  0000 C CNN
F 2 "TerminalBlock:TerminalBlock_bornier-2_P5.08mm" H 6750 6000 50  0001 C CNN
F 3 "~" H 6750 6000 50  0001 C CNN
	1    6750 6000
	0    1    1    0   
$EndComp
$Comp
L power:GND #PWR014
U 1 1 610169F6
P 6750 5800
F 0 "#PWR014" H 6750 5550 50  0001 C CNN
F 1 "GND" H 6755 5627 50  0000 C CNN
F 2 "" H 6750 5800 50  0001 C CNN
F 3 "" H 6750 5800 50  0001 C CNN
	1    6750 5800
	-1   0    0    1   
$EndComp
Wire Wire Line
	6550 5000 6650 5000
Wire Wire Line
	6650 5300 6650 5800
$Comp
L power:GND #PWR012
U 1 1 610169FE
P 5400 5400
F 0 "#PWR012" H 5400 5150 50  0001 C CNN
F 1 "GND" H 5405 5227 50  0000 C CNN
F 2 "" H 5400 5400 50  0001 C CNN
F 3 "" H 5400 5400 50  0001 C CNN
	1    5400 5400
	1    0    0    -1  
$EndComp
Wire Wire Line
	5650 5200 5400 5200
$Comp
L power:+3.3V #PWR013
U 1 1 61016A06
P 5650 5300
F 0 "#PWR013" H 5650 5150 50  0001 C CNN
F 1 "+3.3V" H 5665 5473 50  0000 C CNN
F 2 "" H 5650 5300 50  0001 C CNN
F 3 "" H 5650 5300 50  0001 C CNN
	1    5650 5300
	-1   0    0    1   
$EndComp
Text GLabel 5650 4800 0    50   Input ~ 0
V_Bat
$Comp
L Connector:Screw_Terminal_01x02 J6
U 1 1 6101A2DE
P 4950 6000
F 0 "J6" V 5150 5950 50  0000 C CNN
F 1 "Mow2" V 5050 5950 50  0000 C CNN
F 2 "TerminalBlock:TerminalBlock_bornier-2_P5.08mm" H 4950 6000 50  0001 C CNN
F 3 "~" H 4950 6000 50  0001 C CNN
	1    4950 6000
	0    1    1    0   
$EndComp
$Comp
L power:GND #PWR011
U 1 1 6101A2E5
P 4950 5800
F 0 "#PWR011" H 4950 5550 50  0001 C CNN
F 1 "GND" H 4955 5627 50  0000 C CNN
F 2 "" H 4950 5800 50  0001 C CNN
F 3 "" H 4950 5800 50  0001 C CNN
	1    4950 5800
	-1   0    0    1   
$EndComp
Wire Wire Line
	4850 5300 4850 5800
$Comp
L power:GND #PWR07
U 1 1 6101A2ED
P 3600 5300
F 0 "#PWR07" H 3600 5050 50  0001 C CNN
F 1 "GND" H 3605 5127 50  0000 C CNN
F 2 "" H 3600 5300 50  0001 C CNN
F 3 "" H 3600 5300 50  0001 C CNN
	1    3600 5300
	1    0    0    -1  
$EndComp
Wire Wire Line
	3600 5200 3600 5300
$Comp
L charge_pcb-rescue:INA226-Sense_I2C U3
U 1 1 6101EF8F
P 2550 4950
F 0 "U3" H 2550 5525 50  0000 C CNN
F 1 "INA226" H 2550 5434 50  0000 C CNN
F 2 "Current_sense:INA226" H 2550 5400 50  0001 C CNN
F 3 "" H 2550 5400 50  0001 C CNN
	1    2550 4950
	1    0    0    -1  
$EndComp
$Comp
L Connector:Screw_Terminal_01x02 J4
U 1 1 6101EF9B
P 3200 6000
F 0 "J4" V 3400 5950 50  0000 C CNN
F 1 "Mow3" V 3300 5950 50  0000 C CNN
F 2 "TerminalBlock:TerminalBlock_bornier-2_P5.08mm" H 3200 6000 50  0001 C CNN
F 3 "~" H 3200 6000 50  0001 C CNN
	1    3200 6000
	0    1    1    0   
$EndComp
$Comp
L power:GND #PWR06
U 1 1 6101EFA2
P 3200 5800
F 0 "#PWR06" H 3200 5550 50  0001 C CNN
F 1 "GND" H 3205 5627 50  0000 C CNN
F 2 "" H 3200 5800 50  0001 C CNN
F 3 "" H 3200 5800 50  0001 C CNN
	1    3200 5800
	-1   0    0    1   
$EndComp
Wire Wire Line
	3000 5000 3100 5000
Wire Wire Line
	3100 5300 3100 5800
$Comp
L power:GND #PWR03
U 1 1 6101EFAA
P 1850 5300
F 0 "#PWR03" H 1850 5050 50  0001 C CNN
F 1 "GND" H 1855 5127 50  0000 C CNN
F 2 "" H 1850 5300 50  0001 C CNN
F 3 "" H 1850 5300 50  0001 C CNN
	1    1850 5300
	1    0    0    -1  
$EndComp
Wire Wire Line
	2100 5200 1850 5200
Wire Wire Line
	1850 5200 1850 5300
$Comp
L power:+3.3V #PWR04
U 1 1 6101EFB2
P 2100 5300
F 0 "#PWR04" H 2100 5150 50  0001 C CNN
F 1 "+3.3V" H 2115 5473 50  0000 C CNN
F 2 "" H 2100 5300 50  0001 C CNN
F 3 "" H 2100 5300 50  0001 C CNN
	1    2100 5300
	-1   0    0    1   
$EndComp
Text GLabel 2100 4800 0    50   Input ~ 0
V_Bat
Wire Wire Line
	8300 4850 8300 4050
Wire Wire Line
	3000 4850 3000 4050
Wire Wire Line
	6550 4850 6550 4050
Text GLabel 9200 5000 0    50   BiDi ~ 0
SCL0
Text GLabel 7400 5000 0    50   BiDi ~ 0
SCL0
Text GLabel 5750 2850 3    50   BiDi ~ 0
SCL0
Text GLabel 5850 2850 3    50   BiDi ~ 0
SDA0
Text GLabel 9200 5100 0    50   BiDi ~ 0
SDA0
Text GLabel 7400 5100 0    50   BiDi ~ 0
SDA0
Text GLabel 5650 5100 0    50   BiDi ~ 0
SDA1
Wire Wire Line
	3000 4050 4750 4050
Connection ~ 4750 4050
$Comp
L power:+3.3V #PWR08
U 1 1 6101A2F5
P 3850 5300
F 0 "#PWR08" H 3850 5150 50  0001 C CNN
F 1 "+3.3V" H 3865 5473 50  0000 C CNN
F 2 "" H 3850 5300 50  0001 C CNN
F 3 "" H 3850 5300 50  0001 C CNN
	1    3850 5300
	-1   0    0    1   
$EndComp
Wire Wire Line
	3850 5200 3600 5200
Wire Wire Line
	4750 5000 4850 5000
Wire Wire Line
	4750 4850 4750 4050
$Comp
L charge_pcb-rescue:INA226-Sense_I2C U4
U 1 1 6101A2D2
P 4300 4950
F 0 "U4" H 4300 5525 50  0000 C CNN
F 1 "INA226" H 4300 5434 50  0000 C CNN
F 2 "Current_sense:INA226" H 4300 5400 50  0001 C CNN
F 3 "" H 4300 5400 50  0001 C CNN
	1    4300 4950
	1    0    0    -1  
$EndComp
Text GLabel 3850 5100 0    50   BiDi ~ 0
SDA1
Text GLabel 3850 4800 0    50   Input ~ 0
V_Bat
Text GLabel 2100 5100 0    50   BiDi ~ 0
SDA1
Text GLabel 2100 5000 0    50   BiDi ~ 0
SCL1
Text GLabel 3850 5000 0    50   BiDi ~ 0
SCL1
Text GLabel 5650 5000 0    50   BiDi ~ 0
SCL1
NoConn ~ 9200 4600
NoConn ~ 9200 4900
NoConn ~ 9200 4700
NoConn ~ 7400 4600
NoConn ~ 7400 4700
NoConn ~ 7400 4900
NoConn ~ 5650 4600
NoConn ~ 5650 4700
NoConn ~ 5650 4900
NoConn ~ 3850 4600
NoConn ~ 3850 4700
NoConn ~ 3850 4900
NoConn ~ 2100 4600
NoConn ~ 2100 4700
NoConn ~ 2100 4900
$Comp
L Connector:Screw_Terminal_01x06 J5
U 1 1 610EC238
P 4400 6750
F 0 "J5" H 4480 6742 50  0000 L CNN
F 1 "Main_PCB1" H 4480 6651 50  0000 L CNN
F 2 "Connector_JST:JST_XH_B6B-XH-A_1x06_P2.50mm_Vertical" H 4400 6750 50  0001 C CNN
F 3 "~" H 4400 6750 50  0001 C CNN
	1    4400 6750
	1    0    0    -1  
$EndComp
Text GLabel 4200 6650 0    50   BiDi ~ 0
SDA1
Text GLabel 4200 6550 0    50   BiDi ~ 0
SCL1
Text GLabel 4200 6850 0    50   BiDi ~ 0
SDA0
Text GLabel 4200 6750 0    50   BiDi ~ 0
SCL0
$Comp
L power:+3V3 #PWR010
U 1 1 610F6650
P 4200 7050
F 0 "#PWR010" H 4200 6900 50  0001 C CNN
F 1 "+3V3" V 4215 7178 50  0000 L CNN
F 2 "" H 4200 7050 50  0001 C CNN
F 3 "" H 4200 7050 50  0001 C CNN
	1    4200 7050
	0    -1   -1   0   
$EndComp
$Comp
L power:GND #PWR09
U 1 1 610F7927
P 4200 6950
F 0 "#PWR09" H 4200 6700 50  0001 C CNN
F 1 "GND" V 4205 6822 50  0000 R CNN
F 2 "" H 4200 6950 50  0001 C CNN
F 3 "" H 4200 6950 50  0001 C CNN
	1    4200 6950
	0    1    1    0   
$EndComp
$Comp
L Connector:Screw_Terminal_01x02 J11
U 1 1 61119123
P 10600 1500
F 0 "J11" V 10800 1450 50  0000 C CNN
F 1 "DC/DC1" V 10700 1450 50  0000 C CNN
F 2 "TerminalBlock:TerminalBlock_bornier-2_P5.08mm" H 10600 1500 50  0001 C CNN
F 3 "~" H 10600 1500 50  0001 C CNN
	1    10600 1500
	1    0    0    -1  
$EndComp
Wire Wire Line
	9600 1450 9600 1600
Wire Wire Line
	9600 4050 8300 4050
Connection ~ 9015 1450
Wire Wire Line
	9015 1450 9600 1450
Connection ~ 8300 4050
Wire Wire Line
	9600 4050 10100 4050
Wire Wire Line
	10100 4050 10100 4850
Connection ~ 9600 4050
Wire Wire Line
	10400 1600 9600 1600
Connection ~ 9600 1600
Wire Wire Line
	9600 1600 9600 2000
Connection ~ 9600 2000
Wire Wire Line
	9600 2000 9600 4050
$Comp
L Diode:MBR745 D11
U 1 1 61172E61
P 10200 5150
F 0 "D11" V 10246 5070 50  0000 R CNN
F 1 "MBR1045" V 10155 5070 50  0000 R CNN
F 2 "Package_TO_SOT_THT:TO-220-2_Vertical" H 10200 4975 50  0001 C CNN
F 3 "http://www.onsemi.com/pub_link/Collateral/MBR735-D.PDF" H 10200 5150 50  0001 C CNN
	1    10200 5150
	0    -1   -1   0   
$EndComp
Wire Wire Line
	10200 5300 10200 5800
$Comp
L Diode:MBR745 D10
U 1 1 611BB14A
P 8400 5150
F 0 "D10" V 8446 5070 50  0000 R CNN
F 1 "MBR1045" V 8355 5070 50  0000 R CNN
F 2 "Package_TO_SOT_THT:TO-220-2_Vertical" H 8400 4975 50  0001 C CNN
F 3 "http://www.onsemi.com/pub_link/Collateral/MBR735-D.PDF" H 8400 5150 50  0001 C CNN
	1    8400 5150
	0    -1   -1   0   
$EndComp
$Comp
L Diode:MBR745 D9
U 1 1 611BD572
P 6650 5150
F 0 "D9" V 6696 5070 50  0000 R CNN
F 1 "MBR1045" V 6605 5070 50  0000 R CNN
F 2 "Package_TO_SOT_THT:TO-220-2_Vertical" H 6650 4975 50  0001 C CNN
F 3 "http://www.onsemi.com/pub_link/Collateral/MBR735-D.PDF" H 6650 5150 50  0001 C CNN
	1    6650 5150
	0    -1   -1   0   
$EndComp
$Comp
L Diode:MBR745 D7
U 1 1 611C5F6B
P 3100 5150
F 0 "D7" V 3146 5070 50  0000 R CNN
F 1 "MBR1045" V 3055 5070 50  0000 R CNN
F 2 "Package_TO_SOT_THT:TO-220-2_Vertical" H 3100 4975 50  0001 C CNN
F 3 "http://www.onsemi.com/pub_link/Collateral/MBR735-D.PDF" H 3100 5150 50  0001 C CNN
	1    3100 5150
	0    -1   -1   0   
$EndComp
$Comp
L Diode:MBR745 D8
U 1 1 611C808C
P 4850 5150
F 0 "D8" V 4896 5070 50  0000 R CNN
F 1 "MBR1045" V 4805 5070 50  0000 R CNN
F 2 "Package_TO_SOT_THT:TO-220-2_Vertical" H 4850 4975 50  0001 C CNN
F 3 "http://www.onsemi.com/pub_link/Collateral/MBR735-D.PDF" H 4850 5150 50  0001 C CNN
	1    4850 5150
	0    -1   -1   0   
$EndComp
Connection ~ 6550 4050
Wire Wire Line
	6550 4050 8300 4050
Wire Wire Line
	4750 4050 6550 4050
Wire Wire Line
	5400 5200 5400 5400
Wire Wire Line
	10400 2000 10399 2000
$Comp
L Connector:Screw_Terminal_01x02 J12
U 1 1 6111C7DE
P 10599 1900
F 0 "J12" V 10799 1850 50  0000 C CNN
F 1 "DC/DC2" V 10699 1850 50  0000 C CNN
F 2 "TerminalBlock:TerminalBlock_bornier-2_P5.08mm" H 10599 1900 50  0001 C CNN
F 3 "~" H 10599 1900 50  0001 C CNN
	1    10599 1900
	1    0    0    -1  
$EndComp
Wire Wire Line
	10399 1900 9432 1900
Wire Wire Line
	9432 1900 9432 2900
Wire Wire Line
	7900 2900 9015 2900
Connection ~ 9015 2900
Wire Wire Line
	9015 2900 9432 2900
Connection ~ 10399 2000
Wire Wire Line
	10399 2000 9600 2000
Wire Wire Line
	10400 1500 9432 1500
Wire Wire Line
	9432 1500 9432 1900
Connection ~ 9432 1900
$EndSCHEMATC
