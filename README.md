# Camera-Shutter-tester-Cheap-Easy-it-Works
Arduino or ESP32 based shutter tester using two lasers. 

The use of two lasers & two receivers allows for correct travel time measurement for each shutter curtain of a focal plane shutter, which is most important to ensure even exposure across the frame and without shutter blanking. Flash sync can also be confirmed. Note the ESP32 version uses 3 Lasers (or 5, if both horizontal & vertical curtain measurement is required).

Diy builds that use a single sensor or Audacity simply will not work. Both shutter curtains must be set to travel at the same speed, which is simply not possible using just one sensor, nor are the errors that occur when trying to measure a single light point, able to be mathmatically calculated without multiple sensors. This is why, 3 or five sensors are used for this Shutter Tester.

The shutter tester is designed to use cheap, easy to obtain parts from Ebay (or cheaper still, but longer postal times, from Aliexpress).

A comprehenive build guide thread & user group can be found on on Photrio.

https://www.photrio.com/forum/threads/build-a-shutter-tester-for-focal-plane-shutters-cheap-easy-it-works.197756/

For newbuilds, it is strongly suggested to use an ESP32 board, rather than the Arduino Nano. The ESP32 has far more functionality and only costs slightly more than the Nano.

I would really be grateful if you start to build the shutter tester, that you go to the Photrio thread and say hi. Also please post photos of your completed tester.

Please refer to Photrio for further build help & to let us know you are buildingthe tester..
