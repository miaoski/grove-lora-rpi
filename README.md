# grove-lora-rpi
Library for Grove LoRa module on Raspberry Pi.

## Why?
I have bought two [Grove - LoRa Radio 433 MHz](http://wiki.seeed.cc/Grove_LoRa_Radio/)
modules from Seeed.  They have provided demo code and library for Arduino which runs pretty well, 
but they don't have it for Raspberry Pi.  Maybe people, including 
[The Things Network](https://www.thethingsnetwork.org/), have working code for modules based on SX1276.
There's no reason not to implement yet another library for fun.  A bit workaround is necessary, as an AVR
preceeds SX1276 for UART to SPI (which is totally unnecessary to me) on Grove's module.

## Yet another library?
Yes. It's for fun. erazor83 has a Python library [pyRFM](https://github.com/erazor83/pyRFM) which is 
also very neat.

# License
I have "translated" most of the code from 
[Seeed-Studio's GitHub repo](https://github.com/Seeed-Studio/Grove_LoRa_433MHz_and_915MHz_RF).  
They don't have a license in the repo, but the code is copyrighted by Mike McCauley.  
I'm not a lawyer and just want to have fun.  In case of doubt, write your own library to avoid any possible 
infringement of copyright laws.
