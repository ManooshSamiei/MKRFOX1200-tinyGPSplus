# MKRFOX1200-tinyGPSplus
In this project I want to run gps6mv2 module using MKRFOX 1200 board and TinyGPSPlus library.
During my project, I found some codes about how to use TinyGPS library, the previous version of TinyGPSPlus library, to connect GPS modules to MKRFOX1200 boards. However, I did not find any applicable code to exploit the newer version, TinyGPSPlus library, with MKRFOX1200.
Apparently, we cannot use SoftwareSerial library with SigFox library in our code. Instead we can make use of another Serial communication named Serial1.  
