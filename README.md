# FSR-bed-sensor-Lolin-ESP32-C3
This project includes everything needed to build a bed occupancy sensor inspired by https://community.home-assistant.io/t/fsr-the-best-bed-occupancy-sensor/365795:
One PCB design for connecting two FSR sensors to an Lolin ESP32-C3 pico (pin compatible to Lolin ESP32-C3 mini) and a case for it. There are also two options to add a temperature sensor using the I2c port on the Lolin ESP32-C3. Everything has been tested and works. Make sure the JST-XH plugs are properly plugged in. 

List of materials:

* 2x JST_XH 2 pins male + female connector
* 1x Wemos Lolin ESP32-C3 pico
* 2x 8er Pinleiste
* 2x 8er Buchsenleiste
* 2x RM063 Potentiometer (V2)
* 2x FSR SF15-600 10kg


![IMG_0450](https://user-images.githubusercontent.com/680408/221266709-a9bba09b-9563-4c42-af82-83bf907763ad.PNG)
![image](https://github.com/fhb/FSR-bed-sensor-Lolin-ESP32-C3/blob/main/PCB/V2/FSR%20Bed%20Sensor%20V2.png)
![IMG_9154](https://user-images.githubusercontent.com/680408/235236418-75ce9934-639b-4f9c-8574-40758e27a00b.jpeg)
![IMG_9149](https://user-images.githubusercontent.com/680408/235236445-df8e15e3-aad9-4bba-a3b2-22417b6d44f4.jpeg)


Option 1:The Wemos SHT-30 is the easiest option as ready made SH1.0 4Pin cables are available, that's the option I ended up using and designing a case for.
* 1x Wemos SHT-30 (https://www.wemos.cc/en/latest/d1_mini_shield/sht30.html)
* I2C Cable 10cm für LOLIN (WEMOS) SH1.0 4Pins

![IMG_0580](https://user-images.githubusercontent.com/680408/235232285-8df83e33-caee-40f7-8dae-9fccd3ab1728.PNG)

Option 2: You could also make your own JST-XH to JST-SH1.0 cable and solder a JST-XH connector to a BME280 5V Board. 
* JST-SH1.0 male connector --- 4 wire ---  JST-XH female + male connector 
* BME280 5V Board (I2C)
