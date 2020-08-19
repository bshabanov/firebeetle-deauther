# firebeetle-deauther

Modified version of [esp8266_deauther](https://github.com/SpacehuhnTech/esp8266_deauther).

Work with Firebeetle esp8266 with 0.91 OLED Screen.  
It is adapted to fit on 128x32 screen, and its added some more information when selecting Devices to attack.

In order to work properly you must follow next steps:

  1. First compile and export sketch as binary where ESP8266 lib is version 2.0.0 (neede for wifi_send_pkt_freedom). For compiling use this guide     https://github.com/wi-fi-analyzer/esp8266_deauther. You may need to add custom flag when compiling ESP8266 v2.0.0, the flag is **-fno-threadsafe-statics** and need to be placed on **compiler.cpp.flags**
  2. Install latest version of ESP8266 (currently 2.7.2)
  3. Upload bin directly to firebeetle via terminal
