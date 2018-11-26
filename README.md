# MKRFOX1200-tinyGPSplus
In this project, I am trying to activate gps6mv2 module using MKRFOX 1200 board, and TinyGPSPlus library. 
Since it is not possible to import both SofwareSerial library and sigfox library simultaneously, I am using a specifically defined Serial communication in MKRFOX1200, which is named Serial1, to communicate with the gps module. 
