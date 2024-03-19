# Camera Shutter Tester -Cheap-Easy-it-Works
ESP32 based shutter tester using three lasers. Based on the Arduino platform, but using a much faster processor, the ESP32.

The use of three lasers & three receivers allows for correct travel time measurement for each shutter curtain of a focal plane shutter, which is most important to ensure even exposure across the frame and detect shutter blanking & bouncing. Flash sync can also be confirmed.

DIY builds that use a single sensor or Audacity simply will not work. Both shutter curtains must be set to travel at the same speed, which is simply not measurable using just one sensor. Similarly there will always be an inherent error when measuring a single light point with a sensor, which of course will be wider than a single photon. This error can be mathematically calculated and corrected using a simple algorithm, if multiple sensors are used.

The shutter tester is designed to use cheap, easy to obtain parts from Ebay (or cheaper still, but longer postal times, Aliexpress). It is up to the builder to decide what enclosures (if any) to use. Finished examples can be viewed on the Photrio thread.

A comprehensive build guide thread & user group can be found on on Photrio.

https://www.photrio.com/forum/threads/build-a-shutter-tester-for-focal-plane-shutters-cheap-easy-it-works.197756/

For newbuilds, it is strongly suggested to use an ESP32 board, rather than the Arduino Nano. The ESP32 has far more functionality and only costs slightly more than the Nano.

I would really be grateful if you start to build the shutter tester, that you go to the Photrio thread and say hi. Also please post photos of your completed tester.

Please refer to Photrio for further build help & to let us know you are building the tester..
