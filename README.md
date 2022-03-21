# ESP32-ESP-NOW-Sensor-Network
This repo contains code and details on ESP NOW Protocol and How to connect multiple ESP32 together and transmit sensor data between multiple ESP32 to form a sensor Network.
So In this project we are using two ESP32 with (DHT sensor) sensors to collect data and send it to another main/parent ESP32.
Parent/Main ESP32 works as a Access Point so that child ESP32 with sensors can connect with it & it works as web server as well so that we can access web server from our web browser and read data of child ESP32s.

The basic block diagram and schmatics for child ESP32 is attached in repo.
There are basically 3 codes.
1. Get_ESP32_MAC_Address.ino : This will be uploaded to parent ESP32 to get its MAC Address.
2. ESP32_ESP_NOW_Data_Send.ino : This will be uploaded to child ESP32 with sensors and you need to provide the MAC address of parent in it.
3. ESP_Now_Web_server.ino : This will be uploaded to parent ESP32 which will recieve data from child ESP32 and it will broadcast the data using webserver.


Get your PCBs from : PCBgogo coupon: https://www.pcbgogo.com/thanks2021.html                                                                        
PCBgogo: https://www.pcbgogo.com/promo/from_electronic_GURU                                                                                              
PCBgogo is the experienced quick-turn small-volume PCB prototype and turnkey PCB assembly manufacturer,
offering 12 &amp; 24 hours expedited PCB prototype service for PCB and PCB assembly.
PCBgogo fast PCB prototypes manufacturing and assembling is a good choice.
