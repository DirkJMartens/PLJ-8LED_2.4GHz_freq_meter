# PLJ-8LED_2.4GHz_freq_meter
Putting a pre-made PLJ-8LED module (2.4 GHz frequency meter) in an enclosure

- Purchased a cheap PLJ-8LD module clone online.
- Module is a 2.4 GHz frequency meter with 2 separate input ranges:
  - 100kHz to 50MHz (low frequency range) with 1 Hz resolution (not same as accuracy) 
  - 50MHz to 2.4GHz (high frequency range) with 64 Hz resolution (not same as accuracy) 
- Module requires a 12V DC input
- Has two pushbuttons to navigate menus to allow changes in settings
- Project was put in an enclosure with power switch, DC barrel jack for power, etc.
- Module has a 13MHz TCXO that drives the microcontroller that takes the measurements
- Accuracy of the module depends on this 13MHz TCXO.
- Used a GPSDO to generate a 10MHz signal and adjusted the TCXO until the meter showed 10MHz. 
