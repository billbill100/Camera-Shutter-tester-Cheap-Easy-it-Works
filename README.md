# Camera Shutter Tester -Cheap-Easy-it-Works
ESP32 or Arduino based shutter tester using three lasers (ESP32) or two Lasers (Ardiuno).

Important note: - Both ESP32 and Arduino based Shutter Testers are available.

The ESP32 processor is superior to the Arduino in every way. Therefore the ESP32 based Shutter Tester has far greater functionality, including flash sync testing and camera diagnostics.

The Arduino version is simpler to build, so those with limited experience with microcontrollers & building electronic devices, may find this easier for a first time build.
The Arduino version uses the same processing algorythm as the ESP32 version, so gives accurate shutter meaurements, unlike most (all) of the other Arduino testers found on the interweb.

The latest versiona are Version 4 for ESP32 and Version 2 for Arduino.
The older V3 and original Arduiono documentation are in this repository for reference purposes only. although the firmware for these has been withdrawn.

The use of three lasers & three receivers (or two for Arduino) allows for correct travel time measurement for each shutter curtain of a focal plane shutter, which is most important to ensure even exposure across the frame and to detect curtain bouncing. The ESP32 version with three sensors goes much further, with camera diagnostics to detect things like slow  curtaind, shutter capping etc. It also has comprehensive Flash sync testing & diagnostics.

DIY builds that use a single sensor or Audacity simply will not work. Both shutter curtains must be set to travel at the same speed, which is simply not measurable using just one sensor. Similarly there will always be an inherent error when measuring a single light point with a sensor, which of course will be wider than a single photon. This error can be mathematically calculated and corrected using a simple algorithm, if multiple sensors are used.

The shutter tester is designed to use cheap, easy to obtain parts from Aliexpress. A guide to building a suitable enclosure is also included. The builder can change or adapt this for their needs, or indeed not use an enclosure at all. Photos of builders different ideas are included.

A comprehensive build guide thread & user group can be found on on Photrio.

https://www.photrio.com/forum/threads/build-a-shutter-tester-for-focal-plane-shutters-cheap-easy-it-works.197756/

For newbuilds, it is strongly suggested to use an ESP32 board, rather than the Arduino Nano. The ESP32 has far more functionality and only costs slightly more than the Nano.
It is slightly more complicated to build, so if it looks a bit daunting, start with the Arduino version.

Note both ESP32 and Arduino versions require a one-time pass key. This is supplied free of charge upon request.
On a new build, an authorisation code will be displayed. Send this to me via PM (Photrino is the quickest way) and a user passkey will be send by return.

I would really be grateful if you start to build the shutter tester, that you go to the Photrio thread and say hi. Also please post photos of your completed tester.

Please refer to Photrio for further build help & to let us know you are building the tester..
