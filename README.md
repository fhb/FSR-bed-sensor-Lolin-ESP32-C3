# FSR-bed-sensor-Lolin-ESP32-C3
PCB for 2 FSR sensors using an Lolin ESP32-C3 pico (pin compatible to Lolin ESP32-C3 mini) and an additional BME280 5V Temperature und Humidity sensor breakout board. Has been tested, it works. Make sure the JST-XH plugs get properly connected!

V1 with BME280:

![IMG_0447](https://user-images.githubusercontent.com/680408/221107106-00144642-14b8-48eb-9cb0-6d315c67ed4f.PNG)

V2 with optional BME280 using the I2C JST-SH port on the Lolin C3 Pico and updated (hopefully more robust) potentiometers (RM063)

![IMG_0450](https://user-images.githubusercontent.com/680408/221266709-a9bba09b-9563-4c42-af82-83bf907763ad.PNG)


List of materials:

* 2x JST_XH 2Pin Buchsen
* 1x Wemos Lolin ESP32-C3 pico
* 2x 8er Pinleiste
* 2x 8er Buchsenleiste
* 1x 4er Pinleiste (V1)
* 1x BME280 5V Board (I2C) (V1)
* 2x ACP_CA6-H2,5 0-1MegaOhm (V1)
* 2x RM063 Potentiometer (V2)
* 2x FSR SF15-600 10kg

optional V2: 
* JST-SH1.0 ==> JST-XH Kabel
* JST_XH 2Pin Buchse
* BME280 5V Board (I2C)

More information:
https://community.home-assistant.io/t/fsr-the-best-bed-occupancy-sensor/365795

V1

![a421b668a833dec9ba023b53496f0ecf3098bdd8](https://user-images.githubusercontent.com/680408/221107430-2546456b-8db6-4fad-9abd-55f161b516e7.jpeg)

V2

![image](https://github.com/fhb/FSR-bed-sensor-Lolin-ESP32-C3/blob/main/PCB/V2/FSR%20Bed%20Sensor%20V2.png)
