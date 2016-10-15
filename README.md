## LM3886 amplifier

This PCB is for an LM3886 amplifier, based on schematics by Carlos.  
Pin 11 is removed to allow routing.

### Dimensions of parts

100nF caps: 15mm spacing, 18x5.5mm L x W  
2200uF caps: 7.5mm spacing, 18mm diameter  
3.3nF caps: 7.5mm spacing, 10x3mm L x W  
3.3uF caps: 22.5mm spacing, 26.5x11mm L x W  
330pF cap: 5mm spacing, 7.5x4mm L x W  

1W resistors: L=10mm (raised above PCB to provide cooling)  
other resistors: L=10mm

### Remaining parts

Feedback resistor (2k) is placed on chip terminals (3, 9)  
Resistor RM (10k) is placed on chip terminals (8, 4)  
Short the pads A1 and A2 using a wire  
The 2.2uF input cap is too big to fit on the board. Place it and the 15k resistor somewhere convenient instead (e.g. on the RCA connector)  
The Zobel network is placed on the speaker terminals  
