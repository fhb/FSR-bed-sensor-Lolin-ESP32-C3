# FSR-bed-sensor-Lolin-ESP32-C3
PCB for 2 FSR sensors using an Lolin ESP32-C3 pico (pin compatible to Lolin ESP32-C3 mini) and an additional BME280 5V Temperature und Humidity sensor breakout board. Has been tested, it works. Make sure the JST-XH plugs get properly connected!

V1 with BME280:

![IMG_8872](https://user-images.githubusercontent.com/680408/221297438-faae9180-1a8d-4dde-a87d-81f1c281c76e.jpeg)

![IMG_0447](https://user-images.githubusercontent.com/680408/221107106-00144642-14b8-48eb-9cb0-6d315c67ed4f.PNG)

V2 with optional BME280 using the I2C JST-SH port on the Lolin C3 Pico and updated (hopefully more robust) potentiometers (RM063):

![IMG_0450](https://user-images.githubusercontent.com/680408/221266709-a9bba09b-9563-4c42-af82-83bf907763ad.PNG)


List of materials:

* 2x JST_XH 2 pins male + female connector
* 1x Wemos Lolin ESP32-C3 pico
* 2x 8er Pinleiste
* 2x 8er Buchsenleiste
* 1x 4er Pinleiste (V1)
* 1x BME280 5V Board (I2C) (V1)
* 2x ACP_CA6-H2,5 0-1MegaOhm (V1)
* 2x RM063 Potentiometer (V2)
* 2x FSR SF15-600 10kg

optional V2: 
* JST-SH1.0 male connector --- 4 wire ---  JST-XH female + male connector 
* BME280 5V Board (I2C)

More information:
https://community.home-assistant.io/t/fsr-the-best-bed-occupancy-sensor/365795

V1:

![FSR Bed Sensor V1](https://user-images.githubusercontent.com/680408/221301565-11525a0d-e8e3-448b-8b9e-4845c7cc11e4.png)

V2:

![image](https://github.com/fhb/FSR-bed-sensor-Lolin-ESP32-C3/blob/main/PCB/V2/FSR%20Bed%20Sensor%20V2.png)
