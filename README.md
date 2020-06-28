# STM32_W5500_Dev


## Bug

### V1.1
- USB-C Buchse DP und DN vertauscht => Nur für Strom zu gebauchen
- USB-c buchse keine Pull Down für funktion USB-C => USB-C
- Fehlender Puffercondensator am POE Module => Starkes fiepen

## Features

- STM32F103
- W5500
- RS485 (MAX3485)
- RGBW Mosfet
- USB-C
- User LED (PC13)
- TagConnect 
- Vcc Input 5-28V
- POE Power
- Extention Port


## Pinout

| STM32 | Function | Pin    | Pin    | Function  | STM32   |
| :-----| :------- | :----- | :----- | :-------- | :----   | 
|       |   3,3V   | **1**  | **2**  | Vcc       |         |    
| PA9   |   TX1    | **3**  | **4**  | RX1       | PA10    |     
| PA2   |   TX2    | **5**  | **6**  | RX2       | PA3     |         
| PB7   |   SDA    | **7**  | **8**  | SCL       | PB6     | 
| PA6   |   MISO   | **9**  | **10** | MOSI      | PA7     |
| Pa4   |   CS     | **11** | **12** | SCK       | PA5     | 
| PB8   |   IO     | **13** | **14** | IO        | PB9     |
| PA0   |   IO     | **15** | **16** | IO        | PA1     | 
| PB2   |   IO     | **17** | **18** | N.C.      |         |        
|       |   GND    | **19** | **20** | GND       |         |                          
                       
 [ Hier Bild von Platine mit Anschluss Beschreibungen einfügen]
