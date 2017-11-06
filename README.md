**Sonoff Basic**
![enter image description here](http://sonoff.itead.cc/images/basicw.jpg)


**Software required**

[Esptools](https://github.com/axon18/sonoff/blob/master/esptool.zip)
[Python-2.7.13](https://github.com/axon18/sonoff/blob/master/python-2.7.13)
[Original firmware](https://github.com/axon18/sonoff/blob/master/flash_1M.bin)

 
**Instructions:**

1- connect sonoff to ftdi device
2- press button in sonoff and the connect to usb port
3- release button in sonoff
4- open prompt comand inside folder esptools and execute the next command:

 ***esptool.py -b 115200 --port COM9 write_flash --flash_freq 80m 0x000000 flash_1M.bin***

This works well in Microsoft Windows.
