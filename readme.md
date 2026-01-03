# RoastESP32-Nodemcu32S
Modifying https://github.com/hokoon/RoastESP32 to work on a cloned ESP32-Nodemcu32S board.

Please Use ESP32_TC4.ino
For Arduino Board Choose:
ESP32 DEV Kit

Wireing:
- For MAX6675 CS pin:
* GPIO32 -> CS MAX6675[TC1]
* GPIO33 -> CS MAX6675[TC2]
* GPIO25 -> CS MAX6675[TC3]
* GPIO26 -> CS MAX6675[TC4]
-  Note: All MAX6675:
 *  MAX6675 to  EPS32
 *  VCC     ->  3.3V
 *  GND     ->  GND
 *  SCK     ->  GPIO 18/SCK  
 *  SO      ->  GPIO 19/SO

## Case for Single TC2(Bean Temp) - Preview (For K-Type Interface)
<img src="https://github.com/Andykun233/Roast32-Nodemcu32S/blob/8a4803b3764ac33c06b382250f7b97d56b2a08e4/Single-Port-Case/Single-Port-Case-ViewinBambooLab.png" width="1080">

## 3D Print With PETG - Preview (For K-Type Interface)
<img src="https://github.com/Andykun233/Roast32-Nodemcu32S/blob/a9332d4de974fbbc2adc89b516f871bce635ddcb/Single-Port-Case/3DprintoutwithPETG.jpg" width="1080">
