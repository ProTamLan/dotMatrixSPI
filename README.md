# Dot Matrix SPI
Using the STM32F303K8 and SPI communication protocol to output on a Dot Matrix

Tools: 
- STM32F303K8 - USB Data Cable
- Breadboard 
- 5 Jumper Wires 
- Dot Matrix (Module: MAX7219) (Cascaded: 4 Units) (By: HiLetgo)

The code is based on: <a href ="https://controllerstech.com/cascading-dot-matrix-and-stm32/"> max_matrix_stm32 </a> 

## Possiblities
-  Displaying Text (Directional Scroll Method)
-  Adjusting String Scroll Generation Speed

![image](https://github.com/ProTamLan/dotMatrixSPI/assets/75819639/5d5c6df5-31fa-4802-9c6d-0cc6dccc724c)


## Necessary Changes
-  File I2C mistype, update to SPI file names

## Wiring Configuration
-VCC, GND, DOUT, CS, CLK
<img src="![wiresetup](https://github.com/ProTamLan/dotMatrixSPI/assets/75819639/7cd860e0-4442-40df-960c-dfdd61bf38e9)" width="500" height="450">
