# espkey
A portable hyperlocal wireless social experiment

![](https://raw.githubusercontent.com/antimatter15/espkey/master/images/wifi.png)

## Bill of Materials


| Name                                   | USD  | Description                                                                                                                                                                 |                                                                                                                                                         | 
|----------------------------------------|------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------| 
| ESP8266 ESP-12F                        | 1.3  | The ESP8266 serves as the brains for the entire project. It's a little programmable module with integrated WiFi capabilities and 4MB of integrated flash storage.          | https://www.aliexpress.com/item/ESP8266-ESP12E-ESP12F-Remote-Serial-Port-WIFI-Wireless-Module-3-3V-SPI-For-Arduino-Wireless-Transceiver/32995430963.html | 
| AMS1117-3.3V SOT-223 Regulator         | 0.02 | The ESP8266 operates off 3.3V, but USB supplies 5V. This regulator component allows the ESP8266 to run off of USB power.                                                   | https://www.aliexpress.com/item/100PCS-AMS1117-1-2V-1-5V-1-8V-2-5V-3-3V-5-0V-ADJ-AMS1117/32868342007.html                                                | 
| 47uF SMD 1206 Capacitor                | 0.05 | This capacitor works in conjunction with the regulator to make sure that the ESP8266 has a nice clean power source.                                                        | https://www.aliexpress.com/item/100pcs-1206-SMD-Chip-Multilayer-Ceramic-Capacitor-0-5pF-100uF-10pF-100pF-1nF-10nF-15nF-100nF/32966490820.html            | 
| USB Type A Through Hole Male Connector | 0.07 | This is the actual connector end that plugs into a battery pack. Theoretically we could use one of those PCB connectors, but having a real one makes it feel a lot nicer.  | https://www.aliexpress.com/item/Promotion-R227-11-10pcs-White-USB-A-male-USB-plug-USB-plug-curved-needle-plate/32783474982.html                          | 
| 3D Printed Enclosure                   | 0.12 | The cost is computed based on the assumption that PLA costs about $20 per kg.                                                                                              |                                                                                                                                                          | 
| Custom PCB                             | 0.1  | This cost assumes we're buying 200 panelized PCBs for $20.                                                                                                                 |                                                                                                                                                          | 


## Tools and Supplies

The ShoutKey is designed to be really cheap. With some lead time associated with shipping from China, it can be made for well under $2 each. Its soul is the ESP8266 ESP-12F module, which costs as little as $1.30. 


## PCB Design

![](https://raw.githubusercontent.com/antimatter15/espkey/master/images/schematic.png)

![](https://raw.githubusercontent.com/antimatter15/espkey/master/images/top.svg)
![](https://raw.githubusercontent.com/antimatter15/espkey/master/images/bottom.svg)

The PCB was designed in EasyEDA. The source files can be found in the `pcb/` directory. 

## Necessary Tools

We'll need an FTDI USB Serial adapter module.


## Flashing

