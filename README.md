# ESP32-LoRa-Relay-Control-Code-and-Circuit

Video tutorial : https://youtu.be/LBzah2QMHes

This PCB is a relay controller board with LoRa, You can use this PCB mostly to control appliances like garage doors etc.
The Pcb uses:
1) ESP32 as the microcontroller
2) RYLR896 LoRa module.
3) OLED SSD13086 0.96' display
4) Other basic components.

This PCB also has a display and 4 buttons which can be used as a remote control for some device as well. You can do anything with the code design your own UI. So, in short, this project has an esp8266 which can give WiFi functionality, LoRa module, 1.8 inch TFT display, 4 push buttons for making a UI. Possibilities with the code are endless.

It can be connected to your smartphone or any computer and it makes that device LoRa-enabled messenger. Now when that will be done you would be able to message any other device using the same LoRa messenger. This all is done without the presence of 4G/LTE/3G/GSM/WiFi/SMS. Which I have done in an earlier project which you can find here: https://www.instructables.com/id/LoRa-Messenger-for-Two-Devices-for-Distances-Up-to/

There are 3 relays on board connected to pin 25/26/27 which can be customised using the selector jumpers under the ESP32 board.

![alt text](https://github.com/akarsh98/LoRa-Relay-Controller-Board/blob/master/screenshots/fpcb.JPG?raw=true)

You must check out [JLCPCB](https://jlcpcb.com/m) for ordering PCBs online for cheap!

You get 10 good quality PCBs manufactured and shipped to your doorstep for 2$ and some shipping. You will also get a discount on shipping on your first order. To design your own PCB head over to [easyEDA](https://easyeda.com/), once that is done upload your Gerber files onto [JLCPCB](https://jlcpcb.com/m) to get them manufactured with good quality and quick turnaround time.

![alt text](https://github.com/akarsh98/RadioHead-/blob/master/SCREENSHOTS/JLC_AD_APR19.jpg?raw=true)


## The Circuit in action and some other Pictures

![alt text](https://github.com/akarsh98/LoRa-Relay-Controller-Board/blob/master/screenshots/schematic.JPG?raw=true)
![alt text](https://github.com/akarsh98/LoRa-Remote-Controller-with-TFT-display-based-on-ESP8266/blob/master/screenshots/pcb_f.JPG?raw=true)
![alt text](https://github.com/akarsh98/LoRa-Remote-Controller-with-TFT-display-based-on-ESP8266/blob/master/screenshots/pcb.JPG?raw=true)
