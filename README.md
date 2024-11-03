# Camera Shutter Tester -Cheap-Easy-it-Works
ESP32 or Arduino based shutter tester using three lasers (ESP32) or two Lasers (Ardiuno).

Important note: - Both ESP32 and Arduino based Shutter Testers are available.
The ESP32 processor is superior to the Arduino in every way. Therefore the ESP32 based Shutter Tester has far greater functionality, including flash sync testing and better camera diagnostics. For this reason, it is recommended to build the ESP32 Version 4 based shutter Tester.

Many people are more familiar with Arduino and may have an Arduino board available, so an Arduino version is also included. It uses the same secret algorythm to give the same accuracy as the ESP32 version, but due to limited memory and processor speed has far less functionaliy.

The latest versiona are Version 4 for ESP32 and Version 2 for Arduino.
The older V3 and original Arduiono documentation are in this repository for reference purposes only and the firmware for these is no longer available.

The use of three lasers & three receivers allows for correct travel time measurement for each shutter curtain of a focal plane shutter, which is most important to ensure even exposure across the frame and detect shutter blanking & bouncing. Flash sync can also be confirmed.

DIY builds that use a single sensor or Audacity simply will not work. Both shutter curtains must be set to travel at the same speed, which is simply not measurable using just one sensor. Similarly there will always be an inherent error when measuring a single light point with a sensor, which of course will be wider than a single photon. This error can be mathematically calculated and corrected using a simple algorithm, if multiple sensors are used.

The shutter tester is designed to use cheap, easy to obtain parts from Ebay (or cheaper still, but longer postal times, Aliexpress). It is up to the builder to decide what enclosures (if any) to use. Finished examples can be viewed on the Photrio thread.

A comprehensive build guide thread & user group can be found on on Photrio.

https://www.photrio.com/forum/threads/build-a-shutter-tester-for-focal-plane-shutters-cheap-easy-it-works.197756/

For newbuilds, it is strongly suggested to use an ESP32 board, rather than the Arduino Nano. The ESP32 has far more functionality and only costs slightly more than the Nano.

I would really be grateful if you start to build the shutter tester, that you go to the Photrio thread and say hi. Also please post photos of your completed tester.

Please refer to Photrio for further build help & to let us know you are building the tester..
