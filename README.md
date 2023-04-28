# FSR-bed-sensor-Lolin-ESP32-C3
This project includes everything needed to build a bed occupancy sensor:
A PCB connecting 2 FSR sensors with 2 RM063 resistors to an Lolin ESP32-C3 pico (pin compatible to Lolin ESP32-C3 mini) and a Case.
The I2C port on the Lolin ESP32-C3 can be used to connect an optional temperature sensor. The Wemos SHT-30 is the easiest option as ready made SH1.0 4Pin cables are available. You could also make your own JST-XH to JST-SH1.0 cable (Option 2). Everything has been tested and works. Make sure the JST-XH plugs are properly plugged in.
Case for PCB + Lolin ESP32-C3:
![IMG_0450](https://user-images.githubusercontent.com/680408/221266709-a9bba09b-9563-4c42-af82-83bf907763ad.PNG)
Case for Wemos SHT-30:
![Uploading IMG_0580.PNG…]()
![image](https://github.com/fhb/FSR-bed-sensor-Lolin-ESP32-C3/blob/main/PCB/V2/FSR%20Bed%20Sensor%20V2.png)


List of materials:

* 2x JST_XH 2 pins male + female connector
* 1x Wemos Lolin ESP32-C3 pico
* 2x 8er Pinleiste
* 2x 8er Buchsenleiste
* 2x RM063 Potentiometer (V2)
* 2x FSR SF15-600 10kg

Optional temperature sensor # 1:
* 1x Wemos SHT-30 (https://www.wemos.cc/en/latest/d1_mini_shield/sht30.html)
* I2C Cable 10cm für LOLIN (WEMOS) SH1.0 4Pins

Optional temperature sensor # 2: 
* JST-SH1.0 male connector --- 4 wire ---  JST-XH female + male connector 
* BME280 5V Board (I2C)

More information:
https://community.home-assistant.io/t/fsr-the-best-bed-occupancy-sensor/365795
