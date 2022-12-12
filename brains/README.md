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

Cobmine microcontrollers with wireless cpabilities like ESP8266 and ESP32 with multiple sesnors and relays use Raspberry pi as a server for main control and Home Assistant with ESPHome https://www.home-assistant.io/  https://esphome.io/ as a software to link it all. Here is a good example https://youtu.be/iufph4dF3YU



## General Setup (Current status to be updated)

We use Raspberry pi 4 (8gb Ram version) as a main computer for Home Assistant and followed installation instructions from here https://www.home-assistant.io/installation/raspberrypi 

As the wireless boards for ESPHome so far tested different versions of ESP8266: NodeMCU v1.1 and Wemos D1 mini, Wemos D1 mini pro. All boards seem to work as expected. They could be reprogrammed over wifi, after flashing them via USB connected directly to raspberry pi server. Followed different tutorials here from ESPHome and Home Assitant websites specific for the boards and sensors. 

Currently we just use power banks or usb power from raspberry but ideally each sensor cluster should have it's own local power sourse.  
We plan to make each wireles cluster of sensors individually powered with supercapacitors as a battery and solar panel or tiny water turbine as a generator. Each wireless board will be calibrated to take advantage of the 'deep sleep' power mode to only fully wake up when it needs to log data or when triggered by a sensor. 

Home Assistant is the great platform that will allow to collect and diplay data, together with ESPHome it will allow flexibility and scalability for the smart systems in Ablution Block and we will add constantly more sensors and controls as we experiment with different climate and water technologies.  





