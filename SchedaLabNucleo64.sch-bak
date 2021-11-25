EESchema Schematic File Version 4
EELAYER 30 0
EELAYER END
$Descr A4 11693 8268
encoding utf-8
Sheet 1 3
Title ""
Date ""
Rev ""
Comp ""
Comment1 ""
Comment2 ""
Comment3 ""
Comment4 ""
$EndDescr
Text GLabel 8685 1065 1    50   Input ~ 10
VPWM
$Comp
L Diode:BAT54W D1
U 1 1 61B13E4C
P 10490 1270
F 0 "D1" V 10444 1399 50  0000 L CNN
F 1 "BAT54W" V 10535 1399 50  0000 L CNN
F 2 "Package_TO_SOT_SMD:SOT-323_SC-70" H 10490 1095 50  0001 C CNN
F 3 "https://assets.nexperia.com/documents/data-sheet/BAT54W_SER.pdf" H 10490 1270 50  0001 C CNN
	1    10490 1270
	0    1    1    0   
$EndComp
$Comp
L power:+3V3 #PWR04
U 1 1 61B13E52
P 10490 985
F 0 "#PWR04" H 10490 835 50  0001 C CNN
F 1 "+3V3" H 10505 1158 50  0000 C CNN
F 2 "" H 10490 985 50  0001 C CNN
F 3 "" H 10490 985 50  0001 C CNN
	1    10490 985 
	1    0    0    -1  
$EndComp
$Comp
L Device:R R3
U 1 1 61B13E58
P 10120 1520
F 0 "R3" H 10190 1566 50  0000 L CNN
F 1 "200" H 10190 1475 50  0000 L CNN
F 2 "Resistor_SMD:R_1206_3216Metric_Pad1.30x1.75mm_HandSolder" V 10050 1520 50  0001 C CNN
F 3 "~" H 10120 1520 50  0001 C CNN
	1    10120 1520
	0    -1   -1   0   
$EndComp
Wire Wire Line
	10490 1120 10490 985 
Text GLabel 10670 1520 2    50   Output ~ 10
PWM
Wire Wire Line
	9140 1620 9140 1805
Wire Wire Line
	9140 1805 9900 1805
Wire Wire Line
	9900 1805 9900 1520
Wire Wire Line
	9900 1520 9835 1520
Wire Wire Line
	9235 1620 9140 1620
Wire Wire Line
	9970 1520 9900 1520
Connection ~ 9900 1520
Wire Wire Line
	10490 1420 10490 1520
Wire Wire Line
	10490 1520 10270 1520
Wire Wire Line
	10490 1520 10670 1520
Connection ~ 10490 1520
Text Notes 10560 1920 0    50   ~ 10
Buffer PWM\n
Wire Notes Line
	7855 715  10270 715 
Wire Notes Line
	10270 1965 7855 1965
Wire Notes Line
	7855 1965 7855 720 
Wire Notes Line
	10275 1965 11040 1965
Wire Notes Line
	11040 1965 11040 715 
Wire Notes Line
	11040 715  10275 715 
$Comp
L Analog_Switch:TS5A3159ADBVR U2
U 1 1 61BB6AD1
P 8685 1520
F 0 "U2" H 8685 1762 50  0000 C CNN
F 1 "TS5A3159ADBVR" H 8685 1671 50  0000 C CNN
F 2 "Package_TO_SOT_SMD:SOT-23-6" H 8685 1220 50  0001 C CNN
F 3 "http://www.ti.com/lit/ds/symlink/ts5a3159a.pdf" H 8685 1520 50  0001 C CNN
	1    8685 1520
	-1   0    0    1   
$EndComp
$Comp
L power:GND #PWR07
U 1 1 61BC4B5D
P 8145 1650
F 0 "#PWR07" H 8145 1400 50  0001 C CNN
F 1 "GND" H 8150 1477 50  0000 C CNN
F 2 "" H 8145 1650 50  0001 C CNN
F 3 "" H 8145 1650 50  0001 C CNN
	1    8145 1650
	1    0    0    -1  
$EndComp
$Comp
L power:+5V #PWR05
U 1 1 61BC5456
P 8145 1245
F 0 "#PWR05" H 8145 1095 50  0001 C CNN
F 1 "+5V" H 8160 1418 50  0000 C CNN
F 2 "" H 8145 1245 50  0001 C CNN
F 3 "" H 8145 1245 50  0001 C CNN
	1    8145 1245
	1    0    0    -1  
$EndComp
Wire Wire Line
	8385 1320 8145 1320
Wire Wire Line
	8145 1320 8145 1245
Wire Wire Line
	8145 1650 8145 1520
Wire Wire Line
	8145 1520 8385 1520
Wire Wire Line
	8685 1065 8685 1120
Wire Wire Line
	8985 1420 9235 1420
Text Notes 7400 7500 0    50   ~ 10
Scheda esercitazioni laboratorio elettronica industriale
Text Notes 8150 7650 0    50   ~ 10
19/11/2021
Text Notes 10550 7650 0    50   ~ 10
3.1
Text Notes 7050 6850 0    50   ~ 0
Scheda per le esercitazioni del laboratorio di elettronica indutriale all'università di Padova rivisitata\n\nAutore: Buso Simone\n
$Sheet
S 630  690  1060 625 
U 619AFB42
F0 "Sheet2SchedaLab" 50
F1 "sheet2schedalab.sch" 50
$EndSheet
Text Notes 730  1055 0    50   ~ 10
Interfacce ADC e DAC
$Sheet
S 635  1695 1055 620 
U 61A490E9
F0 "Sheet3SchedaLab" 50
F1 "sheet3schedalab.sch" 50
$EndSheet
Text Notes 900  2060 0    50   ~ 10
Dispositivi I2C
$Comp
L Audio:MSGEQ7 U3
U 1 1 61A63DAE
P 9150 3185
F 0 "U3" H 9150 3866 50  0000 C CNN
F 1 "MSGEQ7" H 9150 3775 50  0000 C CNN
F 2 "Package_DIP:DIP-8_W7.62mm_LongPads" H 9150 3185 50  0001 C CNN
F 3 "http://mix-sig.com/images/datasheets/MSGEQ7.pdf" H 9150 3185 50  0001 C CNN
	1    9150 3185
	1    0    0    -1  
$EndComp
$Comp
L power:+5V #PWR03
U 1 1 61A651D8
P 2550 800
F 0 "#PWR03" H 2550 650 50  0001 C CNN
F 1 "+5V" H 2565 973 50  0000 C CNN
F 2 "" H 2550 800 50  0001 C CNN
F 3 "" H 2550 800 50  0001 C CNN
	1    2550 800 
	1    0    0    -1  
$EndComp
$Comp
L power:GND #PWR06
U 1 1 61A66348
P 2550 1300
F 0 "#PWR06" H 2550 1050 50  0001 C CNN
F 1 "GND" H 2555 1127 50  0000 C CNN
F 2 "" H 2550 1300 50  0001 C CNN
F 3 "" H 2550 1300 50  0001 C CNN
	1    2550 1300
	1    0    0    -1  
$EndComp
$Comp
L Device:C C1
U 1 1 61A66B5A
P 2200 1050
F 0 "C1" H 2315 1096 50  0000 L CNN
F 1 "100nF" H 2315 1005 50  0000 L CNN
F 2 "Capacitor_SMD:C_1206_3216Metric_Pad1.33x1.80mm_HandSolder" H 2238 900 50  0001 C CNN
F 3 "~" H 2200 1050 50  0001 C CNN
	1    2200 1050
	1    0    0    -1  
$EndComp
$Comp
L Device:C C2
U 1 1 61A6726E
P 2550 1050
F 0 "C2" H 2665 1096 50  0000 L CNN
F 1 "100nF" H 2665 1005 50  0000 L CNN
F 2 "Capacitor_SMD:C_1206_3216Metric_Pad1.33x1.80mm_HandSolder" H 2588 900 50  0001 C CNN
F 3 "~" H 2550 1050 50  0001 C CNN
	1    2550 1050
	1    0    0    -1  
$EndComp
$Comp
L Device:C C3
U 1 1 61A67A20
P 2900 1050
F 0 "C3" H 3015 1096 50  0000 L CNN
F 1 "100nF" H 3015 1005 50  0000 L CNN
F 2 "Capacitor_SMD:C_1206_3216Metric_Pad1.33x1.80mm_HandSolder" H 2938 900 50  0001 C CNN
F 3 "~" H 2900 1050 50  0001 C CNN
	1    2900 1050
	1    0    0    -1  
$EndComp
Wire Wire Line
	2550 1300 2550 1250
Wire Wire Line
	2550 1250 2900 1250
Wire Wire Line
	2900 1250 2900 1200
Connection ~ 2550 1250
Wire Wire Line
	2550 1250 2550 1200
Wire Wire Line
	2200 1200 2200 1250
Wire Wire Line
	2200 1250 2550 1250
Wire Wire Line
	2200 900  2200 850 
Wire Wire Line
	2200 850  2550 850 
Wire Wire Line
	2550 850  2550 800 
Wire Wire Line
	2550 850  2550 900 
Connection ~ 2550 850 
Wire Wire Line
	2550 850  2900 850 
Wire Wire Line
	2900 850  2900 900 
$Comp
L Device:LED D3
U 1 1 61A6AFD3
P 5000 1550
F 0 "D3" V 5039 1432 50  0000 R CNN
F 1 "LED" V 4948 1432 50  0000 R CNN
F 2 "LED_SMD:LED_1206_3216Metric_Pad1.42x1.75mm_HandSolder" H 5000 1550 50  0001 C CNN
F 3 "~" H 5000 1550 50  0001 C CNN
	1    5000 1550
	0    -1   -1   0   
$EndComp
$Comp
L Device:R R1
U 1 1 61A6DE65
P 3700 1100
F 0 "R1" H 3770 1146 50  0000 L CNN
F 1 "100" H 3770 1055 50  0000 L CNN
F 2 "Resistor_SMD:R_1206_3216Metric_Pad1.30x1.75mm_HandSolder" V 3630 1100 50  0001 C CNN
F 3 "~" H 3700 1100 50  0001 C CNN
	1    3700 1100
	1    0    0    -1  
$EndComp
$Comp
L Device:R R2
U 1 1 61A6E5C1
P 5000 1100
F 0 "R2" H 5070 1146 50  0000 L CNN
F 1 "60R4" H 5070 1055 50  0000 L CNN
F 2 "Resistor_SMD:R_1206_3216Metric_Pad1.30x1.75mm_HandSolder" V 4930 1100 50  0001 C CNN
F 3 "~" H 5000 1100 50  0001 C CNN
	1    5000 1100
	1    0    0    -1  
$EndComp
$Comp
L Device:CP C4
U 1 1 61A6FA9D
P 4050 1300
F 0 "C4" H 4168 1346 50  0000 L CNN
F 1 "10uF" H 4168 1255 50  0000 L CNN
F 2 "Capacitor_THT:CP_Radial_D5.0mm_P2.50mm" H 4088 1150 50  0001 C CNN
F 3 "~" H 4050 1300 50  0001 C CNN
	1    4050 1300
	1    0    0    -1  
$EndComp
$Comp
L Device:CP C5
U 1 1 61A70632
P 5350 1350
F 0 "C5" H 5468 1396 50  0000 L CNN
F 1 "10uF" H 5468 1305 50  0000 L CNN
F 2 "Capacitor_THT:CP_Radial_D5.0mm_P2.50mm" H 5388 1200 50  0001 C CNN
F 3 "~" H 5350 1350 50  0001 C CNN
	1    5350 1350
	1    0    0    -1  
$EndComp
$Comp
L Device:LED D2
U 1 1 61A71AFB
P 3700 1550
F 0 "D2" V 3739 1432 50  0000 R CNN
F 1 "LED" V 3648 1432 50  0000 R CNN
F 2 "LED_SMD:LED_1206_3216Metric_Pad1.42x1.75mm_HandSolder" H 3700 1550 50  0001 C CNN
F 3 "~" H 3700 1550 50  0001 C CNN
	1    3700 1550
	0    -1   -1   0   
$EndComp
Wire Wire Line
	4050 1150 4050 850 
Wire Wire Line
	4050 850  3700 850 
Wire Wire Line
	3700 850  3700 950 
Wire Wire Line
	3700 1250 3700 1400
Wire Wire Line
	3700 1700 3700 1800
Wire Wire Line
	3700 1800 4050 1800
Wire Wire Line
	4050 1800 4050 1450
Wire Wire Line
	5000 1400 5000 1250
Wire Wire Line
	5000 950  5000 850 
Wire Wire Line
	5000 850  5350 850 
Wire Wire Line
	5350 850  5350 1200
Wire Wire Line
	5350 1500 5350 1800
Wire Wire Line
	5350 1800 5000 1800
Wire Wire Line
	5000 1800 5000 1700
$Comp
L power:GND #PWR08
U 1 1 61A75628
P 3700 1900
F 0 "#PWR08" H 3700 1650 50  0001 C CNN
F 1 "GND" H 3705 1727 50  0000 C CNN
F 2 "" H 3700 1900 50  0001 C CNN
F 3 "" H 3700 1900 50  0001 C CNN
	1    3700 1900
	1    0    0    -1  
$EndComp
$Comp
L power:GND #PWR09
U 1 1 61A76353
P 5000 1900
F 0 "#PWR09" H 5000 1650 50  0001 C CNN
F 1 "GND" H 5005 1727 50  0000 C CNN
F 2 "" H 5000 1900 50  0001 C CNN
F 3 "" H 5000 1900 50  0001 C CNN
	1    5000 1900
	1    0    0    -1  
$EndComp
$Comp
L power:+5V #PWR01
U 1 1 61A76913
P 3700 750
F 0 "#PWR01" H 3700 600 50  0001 C CNN
F 1 "+5V" H 3715 923 50  0000 C CNN
F 2 "" H 3700 750 50  0001 C CNN
F 3 "" H 3700 750 50  0001 C CNN
	1    3700 750 
	1    0    0    -1  
$EndComp
$Comp
L power:+3V3 #PWR02
U 1 1 61A7726A
P 5000 750
F 0 "#PWR02" H 5000 600 50  0001 C CNN
F 1 "+3V3" H 5015 923 50  0000 C CNN
F 2 "" H 5000 750 50  0001 C CNN
F 3 "" H 5000 750 50  0001 C CNN
	1    5000 750 
	1    0    0    -1  
$EndComp
Wire Wire Line
	5000 750  5000 850 
Connection ~ 5000 850 
Wire Wire Line
	3700 750  3700 850 
Connection ~ 3700 850 
Wire Wire Line
	5000 1900 5000 1800
Connection ~ 5000 1800
Wire Wire Line
	3700 1900 3700 1800
Connection ~ 3700 1800
$Comp
L Connector_Generic:Conn_02x19_Odd_Even J7
U 1 1 61A7BC48
P 2350 4350
F 0 "J7" H 2400 5467 50  0000 C CNN
F 1 "Conn_02x19_Odd_Even" H 2400 5376 50  0000 C CNN
F 2 "Connector_PinSocket_2.54mm:PinSocket_2x19_P2.54mm_Vertical" H 2350 4350 50  0001 C CNN
F 3 "~" H 2350 4350 50  0001 C CNN
	1    2350 4350
	-1   0    0    -1  
$EndComp
$Comp
L Connector_Generic:Conn_02x19_Odd_Even J10
U 1 1 61A7EC14
P 4250 4350
F 0 "J10" H 4300 5467 50  0000 C CNN
F 1 "Conn_02x19_Odd_Even" H 4300 5376 50  0000 C CNN
F 2 "Connector_PinSocket_2.54mm:PinSocket_2x19_P2.54mm_Vertical" H 4250 4350 50  0001 C CNN
F 3 "~" H 4250 4350 50  0001 C CNN
	1    4250 4350
	-1   0    0    -1  
$EndComp
$Comp
L power:GND #PWR020
U 1 1 61A847F0
P 1350 4550
F 0 "#PWR020" H 1350 4300 50  0001 C CNN
F 1 "GND" H 1355 4377 50  0000 C CNN
F 2 "" H 1350 4550 50  0001 C CNN
F 3 "" H 1350 4550 50  0001 C CNN
	1    1350 4550
	1    0    0    -1  
$EndComp
Wire Wire Line
	1700 4450 2050 4450
Text GLabel 2700 4950 2    50   Output ~ 10
DAC1(1)
Text GLabel 1900 3550 0    50   Input ~ 10
ADC2(12)
Text GLabel 1700 4450 0    50   BiDi ~ 10
SDA
Text GLabel 1700 4250 0    50   BiDi ~ 10
SCL
Wire Wire Line
	2650 4450 2550 4450
Text GLabel 4600 3650 2    50   Input ~ 10
ADC2(11)
Text GLabel 4600 4450 2    50   Input ~ 10
ADC2(12)
Wire Wire Line
	2550 4350 2650 4350
Text GLabel 3700 3950 0    50   Output ~ 10
DAC1(2)
Text GLabel 3850 4550 0    50   Output ~ 10
VPWM
$Comp
L power:+5V #PWR010
U 1 1 619B489A
P 9150 2425
F 0 "#PWR010" H 9150 2275 50  0001 C CNN
F 1 "+5V" H 9165 2598 50  0000 C CNN
F 2 "" H 9150 2425 50  0001 C CNN
F 3 "" H 9150 2425 50  0001 C CNN
	1    9150 2425
	1    0    0    -1  
$EndComp
$Comp
L power:GND #PWR011
U 1 1 619C0186
P 9950 2575
F 0 "#PWR011" H 9950 2325 50  0001 C CNN
F 1 "GND" H 9955 2402 50  0000 C CNN
F 2 "" H 9950 2575 50  0001 C CNN
F 3 "" H 9950 2575 50  0001 C CNN
	1    9950 2575
	1    0    0    -1  
$EndComp
$Comp
L power:GND #PWR016
U 1 1 619C0E96
P 9150 4075
F 0 "#PWR016" H 9150 3825 50  0001 C CNN
F 1 "GND" H 9155 3902 50  0000 C CNN
F 2 "" H 9150 4075 50  0001 C CNN
F 3 "" H 9150 4075 50  0001 C CNN
	1    9150 4075
	1    0    0    -1  
$EndComp
$Comp
L Device:C C8
U 1 1 619C1F33
P 9900 3675
F 0 "C8" H 10015 3721 50  0000 L CNN
F 1 "100nF" H 10015 3630 50  0000 L CNN
F 2 "Capacitor_SMD:C_1206_3216Metric_Pad1.33x1.80mm_HandSolder" H 9938 3525 50  0001 C CNN
F 3 "~" H 9900 3675 50  0001 C CNN
	1    9900 3675
	1    0    0    -1  
$EndComp
$Comp
L Device:C C9
U 1 1 619C3718
P 8550 3725
F 0 "C9" H 8665 3771 50  0000 L CNN
F 1 "33pF" H 8665 3680 50  0000 L CNN
F 2 "Capacitor_SMD:C_1206_3216Metric_Pad1.33x1.80mm_HandSolder" H 8588 3575 50  0001 C CNN
F 3 "~" H 8550 3725 50  0001 C CNN
	1    8550 3725
	1    0    0    -1  
$EndComp
$Comp
L Device:R R7
U 1 1 619C3E9D
P 8300 3485
F 0 "R7" H 8370 3531 50  0000 L CNN
F 1 "200k" H 8370 3440 50  0000 L CNN
F 2 "Resistor_SMD:R_1206_3216Metric_Pad1.30x1.75mm_HandSolder" V 8230 3485 50  0001 C CNN
F 3 "~" H 8300 3485 50  0001 C CNN
	1    8300 3485
	0    -1   -1   0   
$EndComp
Wire Wire Line
	9900 3525 9900 3485
Wire Wire Line
	9900 3485 9650 3485
Wire Wire Line
	9150 3685 9150 3895
Wire Wire Line
	9900 3825 9900 3895
Wire Wire Line
	9900 3895 9150 3895
Connection ~ 9150 3895
Wire Wire Line
	9150 3895 9150 4075
Wire Wire Line
	8650 3485 8550 3485
Wire Wire Line
	8550 3485 8550 3575
Wire Wire Line
	8450 3485 8550 3485
Connection ~ 8550 3485
$Comp
L power:GND #PWR014
U 1 1 619DCDF2
P 8550 3930
F 0 "#PWR014" H 8550 3680 50  0001 C CNN
F 1 "GND" H 8555 3757 50  0000 C CNN
F 2 "" H 8550 3930 50  0001 C CNN
F 3 "" H 8550 3930 50  0001 C CNN
	1    8550 3930
	1    0    0    -1  
$EndComp
$Comp
L power:+5V #PWR013
U 1 1 619DD478
P 8060 3420
F 0 "#PWR013" H 8060 3270 50  0001 C CNN
F 1 "+5V" H 8075 3593 50  0000 C CNN
F 2 "" H 8060 3420 50  0001 C CNN
F 3 "" H 8060 3420 50  0001 C CNN
	1    8060 3420
	1    0    0    -1  
$EndComp
Wire Wire Line
	8060 3420 8060 3485
Wire Wire Line
	8060 3485 8150 3485
Wire Wire Line
	8550 3930 8550 3875
Wire Wire Line
	9150 2425 9150 2525
$Comp
L Device:C C6
U 1 1 619E5458
P 9575 2525
F 0 "C6" V 9323 2525 50  0000 C CNN
F 1 "100nF" V 9414 2525 50  0000 C CNN
F 2 "Capacitor_SMD:C_1206_3216Metric_Pad1.33x1.80mm_HandSolder" H 9613 2375 50  0001 C CNN
F 3 "~" H 9575 2525 50  0001 C CNN
	1    9575 2525
	0    1    1    0   
$EndComp
Wire Wire Line
	9725 2525 9950 2525
Wire Wire Line
	9950 2525 9950 2575
Wire Wire Line
	9425 2525 9150 2525
Connection ~ 9150 2525
Wire Wire Line
	9150 2525 9150 2685
Text GLabel 9780 2885 2    50   Input ~ 0
STROBE
Wire Wire Line
	9780 2885 9650 2885
Text GLabel 9780 2985 2    50   Input ~ 0
RST
Wire Wire Line
	9780 2985 9650 2985
$Comp
L Device:C C7
U 1 1 619F766A
P 8415 3185
F 0 "C7" V 8163 3185 50  0000 C CNN
F 1 "1nF" V 8254 3185 50  0000 C CNN
F 2 "Capacitor_SMD:C_1206_3216Metric_Pad1.33x1.80mm_HandSolder" H 8453 3035 50  0001 C CNN
F 3 "~" H 8415 3185 50  0001 C CNN
	1    8415 3185
	0    1    1    0   
$EndComp
$Comp
L Device:R R4
U 1 1 619F8331
P 7765 2885
F 0 "R4" V 7558 2885 50  0000 C CNN
F 1 "22k" V 7649 2885 50  0000 C CNN
F 2 "Resistor_SMD:R_1206_3216Metric_Pad1.30x1.75mm_HandSolder" V 7695 2885 50  0001 C CNN
F 3 "~" H 7765 2885 50  0001 C CNN
	1    7765 2885
	0    1    1    0   
$EndComp
$Comp
L Device:R R5
U 1 1 619F8B2A
P 7775 3185
F 0 "R5" V 7982 3185 50  0000 C CNN
F 1 "22k" V 7891 3185 50  0000 C CNN
F 2 "Resistor_SMD:R_1206_3216Metric_Pad1.30x1.75mm_HandSolder" V 7705 3185 50  0001 C CNN
F 3 "~" H 7775 3185 50  0001 C CNN
	1    7775 3185
	0    -1   -1   0   
$EndComp
$Comp
L Connector:AudioJack3 J1
U 1 1 619F9BF5
P 7055 3085
F 0 "J1" H 7037 3410 50  0000 C CNN
F 1 "AudioJack3" H 7037 3319 50  0000 C CNN
F 2 "Connector_Audio:Jack_3.5mm_CUI_SJ1-3533NG_Horizontal" H 7055 3085 50  0001 C CNN
F 3 "~" H 7055 3085 50  0001 C CNN
	1    7055 3085
	1    0    0    -1  
$EndComp
Wire Wire Line
	8565 3185 8650 3185
Wire Wire Line
	7925 3185 8140 3185
Wire Wire Line
	7915 2885 8140 2885
Wire Wire Line
	8140 2885 8140 3185
Connection ~ 8140 3185
Wire Wire Line
	8140 3185 8265 3185
Wire Wire Line
	7625 3185 7410 3185
Wire Wire Line
	7515 3085 7515 2885
Wire Wire Line
	7515 2885 7615 2885
$Comp
L power:GND #PWR015
U 1 1 61A2F967
P 7450 3945
F 0 "#PWR015" H 7450 3695 50  0001 C CNN
F 1 "GND" H 7455 3772 50  0000 C CNN
F 2 "" H 7450 3945 50  0001 C CNN
F 3 "" H 7450 3945 50  0001 C CNN
	1    7450 3945
	1    0    0    -1  
$EndComp
$Comp
L Connector:AudioJack3 J2
U 1 1 619C7E61
P 7050 3670
F 0 "J2" H 7032 3995 50  0000 C CNN
F 1 "AudioJack3" H 7032 3904 50  0000 C CNN
F 2 "Connector_Audio:Jack_3.5mm_CUI_SJ1-3533NG_Horizontal" H 7050 3670 50  0001 C CNN
F 3 "~" H 7050 3670 50  0001 C CNN
	1    7050 3670
	1    0    0    -1  
$EndComp
Wire Wire Line
	7255 2985 7450 2985
Connection ~ 7410 3185
Wire Wire Line
	7410 3185 7255 3185
Wire Wire Line
	7450 2985 7450 3570
Wire Wire Line
	7255 3085 7335 3085
Wire Wire Line
	7250 3570 7450 3570
Connection ~ 7450 3570
Wire Wire Line
	7450 3570 7450 3945
Wire Wire Line
	7410 3770 7250 3770
Wire Wire Line
	7410 3185 7410 3770
Wire Wire Line
	7250 3670 7335 3670
Wire Wire Line
	7335 3670 7335 3085
Connection ~ 7335 3085
Wire Wire Line
	7335 3085 7515 3085
Wire Notes Line
	11050 2150 11050 4500
Wire Notes Line
	6650 4500 6650 2150
Text Notes 10300 4450 0    50   ~ 10
Spectrum Divider
Wire Wire Line
	1350 4550 1350 4350
Wire Wire Line
	1350 4350 2050 4350
Wire Wire Line
	2050 4250 1700 4250
Wire Wire Line
	1900 3550 2050 3550
Wire Wire Line
	2650 4350 2650 4450
Connection ~ 2650 4350
Wire Wire Line
	3700 3950 3950 3950
Wire Wire Line
	3700 4050 3950 4050
Wire Wire Line
	3700 4150 3950 4150
Wire Wire Line
	3200 3850 3950 3850
Wire Wire Line
	3950 4550 3850 4550
Wire Wire Line
	4600 4450 4450 4450
Wire Wire Line
	4450 3650 4600 3650
Text GLabel 4600 4850 2    50   Input ~ 10
ADC2(5)
Wire Wire Line
	4600 4850 4450 4850
Wire Wire Line
	2700 4950 2550 4950
Text GLabel 10590 3285 2    50   Input ~ 10
ADC2(5)
$Comp
L Diode:BAT54W D4
U 1 1 61A90386
P 10410 3035
F 0 "D4" V 10364 3164 50  0000 L CNN
F 1 "BAT54W" V 10455 3164 50  0000 L CNN
F 2 "Package_TO_SOT_SMD:SOT-323_SC-70" H 10410 2860 50  0001 C CNN
F 3 "https://assets.nexperia.com/documents/data-sheet/BAT54W_SER.pdf" H 10410 3035 50  0001 C CNN
	1    10410 3035
	0    1    1    0   
$EndComp
$Comp
L power:+3V3 #PWR012
U 1 1 61A9038C
P 10410 2750
F 0 "#PWR012" H 10410 2600 50  0001 C CNN
F 1 "+3V3" H 10425 2923 50  0000 C CNN
F 2 "" H 10410 2750 50  0001 C CNN
F 3 "" H 10410 2750 50  0001 C CNN
	1    10410 2750
	1    0    0    -1  
$EndComp
$Comp
L Device:R R6
U 1 1 61A90392
P 10040 3285
F 0 "R6" H 10110 3331 50  0000 L CNN
F 1 "200" H 10110 3240 50  0000 L CNN
F 2 "Resistor_SMD:R_1206_3216Metric_Pad1.30x1.75mm_HandSolder" V 9970 3285 50  0001 C CNN
F 3 "~" H 10040 3285 50  0001 C CNN
	1    10040 3285
	0    -1   -1   0   
$EndComp
Wire Wire Line
	10410 2885 10410 2750
Wire Wire Line
	10410 3185 10410 3285
Wire Wire Line
	10410 3285 10190 3285
Wire Wire Line
	10410 3285 10590 3285
Connection ~ 10410 3285
Wire Wire Line
	9650 3285 9700 3285
Wire Notes Line
	6650 2150 11050 2150
Wire Notes Line
	6650 4500 11050 4500
Text GLabel 3870 4450 0    50   Input ~ 0
STROBE
Text GLabel 2610 4050 2    50   Input ~ 0
RST
Wire Wire Line
	3950 4450 3870 4450
Wire Wire Line
	2610 4050 2550 4050
Wire Wire Line
	2550 3750 3200 3750
Wire Wire Line
	3200 3750 3200 3850
Connection ~ 3200 3850
Wire Wire Line
	2650 4350 3200 4350
Wire Wire Line
	3200 3850 3200 4350
Wire Wire Line
	2550 4250 3050 4250
Wire Wire Line
	3050 4250 3050 4200
Wire Wire Line
	2550 4150 2900 4150
Wire Wire Line
	2900 4150 2900 4100
$Comp
L power:GND #PWR019
U 1 1 61A0C78F
P 3200 4450
F 0 "#PWR019" H 3200 4200 50  0001 C CNN
F 1 "GND" H 3205 4277 50  0000 C CNN
F 2 "" H 3200 4450 50  0001 C CNN
F 3 "" H 3200 4450 50  0001 C CNN
	1    3200 4450
	1    0    0    -1  
$EndComp
$Comp
L power:+3V3 #PWR017
U 1 1 61A0D21F
P 2900 4100
F 0 "#PWR017" H 2900 3950 50  0001 C CNN
F 1 "+3V3" H 2915 4273 50  0000 C CNN
F 2 "" H 2900 4100 50  0001 C CNN
F 3 "" H 2900 4100 50  0001 C CNN
	1    2900 4100
	1    0    0    -1  
$EndComp
$Comp
L power:+5V #PWR018
U 1 1 61A0DD3D
P 3050 4200
F 0 "#PWR018" H 3050 4050 50  0001 C CNN
F 1 "+5V" H 3065 4373 50  0000 C CNN
F 2 "" H 3050 4200 50  0001 C CNN
F 3 "" H 3050 4200 50  0001 C CNN
	1    3050 4200
	1    0    0    -1  
$EndComp
Wire Wire Line
	3200 4350 3200 4450
Connection ~ 3200 4350
$Comp
L Connector_Generic:Conn_02x02_Odd_Even J6
U 1 1 61A332DB
P 4150 6000
F 0 "J6" H 4200 6217 50  0000 C CNN
F 1 "Conn_02x02_Odd_Even" H 4200 6126 50  0000 C CNN
F 2 "Connector_PinHeader_2.54mm:PinHeader_2x02_P2.54mm_Vertical" H 4150 6000 50  0001 C CNN
F 3 "~" H 4150 6000 50  0001 C CNN
	1    4150 6000
	1    0    0    -1  
$EndComp
$Comp
L Connector_Generic:Conn_02x02_Odd_Even J9
U 1 1 61A344ED
P 4150 6600
F 0 "J9" H 4200 6817 50  0000 C CNN
F 1 "Conn_02x02_Odd_Even" H 4200 6726 50  0000 C CNN
F 2 "Connector_PinHeader_2.54mm:PinHeader_2x02_P2.54mm_Vertical" H 4150 6600 50  0001 C CNN
F 3 "~" H 4150 6600 50  0001 C CNN
	1    4150 6600
	1    0    0    -1  
$EndComp
$Comp
L power:GND #PWR021
U 1 1 61A35A81
P 4850 6900
F 0 "#PWR021" H 4850 6650 50  0001 C CNN
F 1 "GND" H 4855 6727 50  0000 C CNN
F 2 "" H 4850 6900 50  0001 C CNN
F 3 "" H 4850 6900 50  0001 C CNN
	1    4850 6900
	1    0    0    -1  
$EndComp
Wire Wire Line
	4450 6000 4850 6000
Wire Wire Line
	4850 6000 4850 6100
Wire Wire Line
	4450 6600 4850 6600
Connection ~ 4850 6600
Wire Wire Line
	4450 6100 4850 6100
Connection ~ 4850 6100
Wire Wire Line
	4850 6100 4850 6600
Wire Wire Line
	4450 6700 4850 6700
Wire Wire Line
	4850 6600 4850 6700
Connection ~ 4850 6700
Wire Wire Line
	4850 6700 4850 6900
$Comp
L power:GND #PWR023
U 1 1 61A4CC41
P 2300 7450
F 0 "#PWR023" H 2300 7200 50  0001 C CNN
F 1 "GND" H 2305 7277 50  0000 C CNN
F 2 "" H 2300 7450 50  0001 C CNN
F 3 "" H 2300 7450 50  0001 C CNN
	1    2300 7450
	-1   0    0    -1  
$EndComp
Wire Wire Line
	2300 7450 2300 7300
Wire Wire Line
	2300 7300 2700 7300
Wire Wire Line
	2700 5900 2550 5900
Wire Wire Line
	2550 6000 2700 6000
Connection ~ 2700 6000
Wire Wire Line
	2700 6000 2700 5900
Wire Wire Line
	2550 6100 2700 6100
Connection ~ 2700 6100
Wire Wire Line
	2700 6100 2700 6000
Wire Wire Line
	2550 6200 2700 6200
Connection ~ 2700 6200
Wire Wire Line
	2700 6200 2700 6100
Wire Wire Line
	2550 6300 2700 6300
Connection ~ 2700 6300
Wire Wire Line
	2700 6300 2700 6200
Wire Wire Line
	2550 6400 2700 6400
Connection ~ 2700 6400
Wire Wire Line
	2700 6400 2700 6300
Wire Wire Line
	2550 6500 2700 6500
Wire Wire Line
	2700 6400 2700 6500
Connection ~ 2700 6500
Wire Wire Line
	2700 6500 2700 6600
Wire Wire Line
	2550 6600 2700 6600
Connection ~ 2700 6600
Wire Wire Line
	2700 6600 2700 6700
Wire Wire Line
	2550 6700 2700 6700
Connection ~ 2700 6700
Wire Wire Line
	2700 6700 2700 6800
Wire Wire Line
	2550 6800 2700 6800
Connection ~ 2700 6800
Wire Wire Line
	2700 6800 2700 6900
Wire Wire Line
	2550 6900 2700 6900
Connection ~ 2700 6900
Wire Wire Line
	2700 6900 2700 7000
Wire Wire Line
	2550 7000 2700 7000
Connection ~ 2700 7000
Wire Wire Line
	2700 7000 2700 7100
Wire Wire Line
	2550 7100 2700 7100
Connection ~ 2700 7100
Wire Wire Line
	2700 7100 2700 7300
Wire Wire Line
	2300 7300 1950 7300
Wire Wire Line
	1950 6000 2050 6000
Connection ~ 2300 7300
Wire Wire Line
	2050 6200 1950 6200
Connection ~ 1950 6200
Wire Wire Line
	2050 6400 1950 6400
Connection ~ 1950 6400
Wire Wire Line
	2050 6600 1950 6600
Connection ~ 1950 6600
Wire Wire Line
	2050 6800 1950 6800
Connection ~ 1950 6800
Wire Wire Line
	2050 7000 1950 7000
Connection ~ 1950 7000
Text GLabel 1750 5900 0    50   Input ~ 10
ADC2(3)
Text GLabel 3700 4050 0    50   Input ~ 10
ADC2(3)
Text GLabel 3700 4150 0    50   Input ~ 10
ADC2(4)
Text GLabel 1750 6100 0    50   Input ~ 10
ADC2(4)
Text GLabel 1750 6300 0    50   Output ~ 10
PWM
Wire Wire Line
	1950 6200 1950 6000
Wire Wire Line
	1950 7300 1950 7000
Wire Wire Line
	1950 7000 1950 6800
Wire Wire Line
	1950 6800 1950 6600
Wire Wire Line
	1950 6600 1950 6400
Wire Wire Line
	1950 6400 1950 6200
$Comp
L Connector_Generic:Conn_02x13_Odd_Even J8
U 1 1 61A30BAA
P 2350 6500
F 0 "J8" H 2400 7317 50  0000 C CNN
F 1 "Conn_02x13_Odd_Even" H 2400 7226 50  0000 C CNN
F 2 "Connector_PinHeader_2.54mm:PinHeader_2x13_P2.54mm_Vertical" H 2350 6500 50  0001 C CNN
F 3 "~" H 2350 6500 50  0001 C CNN
	1    2350 6500
	-1   0    0    -1  
$EndComp
Text GLabel 1750 6700 0    50   Output ~ 10
ODAC1(2)
Text GLabel 1750 6500 0    50   Output ~ 10
ODAC1(1)
Wire Wire Line
	2050 6700 1750 6700
Wire Wire Line
	2050 6500 1750 6500
Wire Wire Line
	2050 6300 1750 6300
Wire Wire Line
	2050 6100 1750 6100
Wire Wire Line
	2050 5900 1750 5900
Text GLabel 1750 7100 0    50   Input ~ 10
ExtIn2
Text GLabel 1750 6900 0    50   Input ~ 10
ExtIn1
Wire Wire Line
	2050 6900 1750 6900
Wire Wire Line
	1750 7100 2050 7100
Text GLabel 3800 6650 0    50   Output ~ 10
ALERT
Wire Wire Line
	3800 6650 3900 6650
Wire Wire Line
	3900 6650 3900 6600
Wire Wire Line
	3900 6600 3950 6600
Wire Wire Line
	3950 6700 3900 6700
Wire Wire Line
	3900 6700 3900 6650
Connection ~ 3900 6650
Text GLabel 3800 6050 0    50   Output ~ 10
ExtDAC_OUT
Wire Wire Line
	3800 6050 3900 6050
Wire Wire Line
	3900 6050 3900 6100
Wire Wire Line
	3900 6100 3950 6100
Wire Wire Line
	3900 6050 3900 6000
Wire Wire Line
	3900 6000 3950 6000
Connection ~ 3900 6050
$Comp
L Connector:Conn_01x02_Male J5
U 1 1 61D2647F
P 5550 6000
F 0 "J5" H 5658 6181 50  0000 C CNN
F 1 "Conn_01x02_Male" H 5658 6090 50  0000 C CNN
F 2 "Connector_PinHeader_2.54mm:PinHeader_1x02_P2.54mm_Vertical" H 5550 6000 50  0001 C CNN
F 3 "~" H 5550 6000 50  0001 C CNN
	1    5550 6000
	1    0    0    -1  
$EndComp
$Comp
L Connector:Conn_01x02_Male J3
U 1 1 61D2724B
P 5550 6350
F 0 "J3" H 5658 6531 50  0000 C CNN
F 1 "Conn_01x02_Male" H 5658 6440 50  0000 C CNN
F 2 "Connector_PinHeader_2.54mm:PinHeader_1x02_P2.54mm_Vertical" H 5550 6350 50  0001 C CNN
F 3 "~" H 5550 6350 50  0001 C CNN
	1    5550 6350
	1    0    0    -1  
$EndComp
$Comp
L Connector:Conn_01x02_Male J4
U 1 1 61D31A12
P 5550 6700
F 0 "J4" H 5658 6881 50  0000 C CNN
F 1 "Conn_01x02_Male" H 5658 6790 50  0000 C CNN
F 2 "Connector_PinHeader_2.54mm:PinHeader_1x02_P2.54mm_Vertical" H 5550 6700 50  0001 C CNN
F 3 "~" H 5550 6700 50  0001 C CNN
	1    5550 6700
	1    0    0    -1  
$EndComp
$Comp
L power:GND #PWR022
U 1 1 61D3C61D
P 6000 6900
F 0 "#PWR022" H 6000 6650 50  0001 C CNN
F 1 "GND" H 6005 6727 50  0000 C CNN
F 2 "" H 6000 6900 50  0001 C CNN
F 3 "" H 6000 6900 50  0001 C CNN
	1    6000 6900
	1    0    0    -1  
$EndComp
Wire Wire Line
	6000 6000 5750 6000
Wire Wire Line
	5750 6100 6000 6100
Connection ~ 6000 6100
Wire Wire Line
	6000 6100 6000 6000
Wire Wire Line
	5750 6350 6000 6350
Connection ~ 6000 6350
Wire Wire Line
	6000 6350 6000 6100
Wire Wire Line
	5750 6450 6000 6450
Connection ~ 6000 6450
Wire Wire Line
	6000 6450 6000 6350
Wire Wire Line
	5750 6700 6000 6700
Wire Wire Line
	6000 6450 6000 6700
Connection ~ 6000 6700
Wire Wire Line
	6000 6700 6000 6800
Wire Wire Line
	5750 6800 6000 6800
Connection ~ 6000 6800
Wire Wire Line
	6000 6800 6000 6900
$Comp
L SchedaLabNucleo64-rescue:LM6134-LibreriaLucky U1
U 4 1 619DEEDD
P 9325 1270
F 0 "U1" H 9535 1501 50  0000 C CNN
F 1 "LM6134" H 9535 1410 50  0000 C CNN
F 2 "Package_SO:SOIC-14_3.9x8.7mm_P1.27mm" H 10475 810 50  0001 C CNN
F 3 "" H 9355 1380 50  0001 C CNN
	4    9325 1270
	1    0    0    -1  
$EndComp
Text GLabel 2150 850  0    50   UnSpc ~ 0
V+
Text GLabel 2150 1250 0    50   UnSpc ~ 0
V-
Wire Wire Line
	2150 850  2200 850 
Connection ~ 2200 850 
Wire Wire Line
	2150 1250 2200 1250
Connection ~ 2200 1250
$Comp
L Connector:Conn_01x05_Male SPC1
U 1 1 61CB9ED5
P 8870 5130
F 0 "SPC1" H 8978 5511 50  0000 C CNN
F 1 "Conn_01x05_Male" H 8978 5420 50  0000 C CNN
F 2 "Connector_PinHeader_2.54mm:PinHeader_1x05_P2.54mm_Vertical" H 8870 5130 50  0001 C CNN
F 3 "~" H 8870 5130 50  0001 C CNN
	1    8870 5130
	1    0    0    -1  
$EndComp
Text GLabel 9170 5330 2    50   Input ~ 0
+5V
Text GLabel 9170 5230 2    50   Input ~ 0
GND
Text GLabel 9170 4930 2    50   Input ~ 0
RST
Text GLabel 9170 5030 2    50   Input ~ 0
STROBE
Text GLabel 9170 5130 2    50   Input ~ 0
OSPC
Text GLabel 9700 3265 1    50   Input ~ 0
OSPC
Wire Wire Line
	9700 3265 9700 3285
Connection ~ 9700 3285
Wire Wire Line
	9700 3285 9890 3285
Wire Wire Line
	9170 4930 9070 4930
Wire Wire Line
	9070 5030 9170 5030
Wire Wire Line
	9070 5130 9170 5130
Wire Wire Line
	9070 5230 9170 5230
Wire Wire Line
	9070 5330 9170 5330
$EndSCHEMATC
