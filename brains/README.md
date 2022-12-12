# A section dedicated to the brains of the Ablution block

In order to keep track of the efficiency of the Ablution block and being able to fine tune systems and programs them we would like to use some kind of IoT system. 

Smart system to control ablution block should include but not limited to:  

* water usage meter 
* heating smart contloller
* Multiple sensors data logging
* Seasonal optimal settings for systems
* Lighting smart controller
* general use logging

Technology to make it happen: 

Cobmine microcontrollers with wireless cpabilities like ESP8266 and ESP32 with multiple sesnors and relays use a open source and powerfull main computer like Raspberry pi for main control and Home Assistant with ESPHome https://www.home-assistant.io/ as a software to link it all. 

## General Setup (Current status to be updated)

We use Raspberry pi 4 (8gb Ram version) as a main computer for Home Assistant and followed installation instructions from here https://www.home-assistant.io/installation/raspberrypi 

As the wireless boards for ESPHome so far tested different versions of ESP8266: NodeMCU v1.1 and Wemos D1 mini, Wemos D1 mini pro. All boards seem to work as expected. They could be reprogrammed over wifi, after flashing them via USB connected directly to raspberry pi server. Followed different tutorials here from ESPHome and Home Assitant websites specific for the boards and sensors. 

Home Assistant is the great platform that will allow to collect and diplay data, together with ESPHome it will allow ultimate flexibility and scalability for the smart systems in Ablution Block. 





As the main platform for 








