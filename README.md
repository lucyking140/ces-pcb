# PCB Pendant
![hero image](https://github.com/user-attachments/assets/46db4de1-b9b6-4bd4-9ca0-b2762da72745)

This pendant is a PCB that I designed in KiCad from a provided circuit and printed with a CNC that flashes an LED diode. It is powered by a 3.7V coin cell battery and uses a 555 timer chip that indicates when the LED should light up. The chip uses trigger and threshold pins to indicate when the output pin should output power, which is what turns our LED on. 

## Design

Given the [provided circuit schema](https://github.com/lucyking140/ces-pcb/blob/363c9e8b32d2637fbd520404c1b6ab6e8fec69ef/555timerCES.kicad_sch), I designed my PCB with circular traces and with my capacitors and resistors in a circular shape. 

## Construction

After completing my [PCB desing in KiCad](https://github.com/lucyking140/ces-pcb/blob/363c9e8b32d2637fbd520404c1b6ab6e8fec69ef/555timerCES.kicad_pcb), I printed it using a CNC. Then, I soldered the battery holder, LED, 555 chip, and resistors and capacitors onto the board. 

I used the following component values to generate a 1.455 Hz flash:
- R1: 10 kiloOhms
- R2: 220 kiloOhms
- R3: 470 Ohms
- C1: 2.2 microFarads
- C2: 19 nanoFarads
