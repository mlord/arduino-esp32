----------------------------- Remove above -----------------------------


### Hardware:
|||||||
|:---|---|---|---|---|---|
|<B>Board</B>|ESP32 Dev Module|node32|ttgo_lora|ESP32-S2-Saola|Custom w/ ESP32-S2-WROVER 16MB|
|<B>Version/Date</B>|1.0.4|2.0.0|0badbeef|11/jul/2017|today's master|
|<B>IDE name</B>|Arduino IDE|Atom + Platform.io|IDF component|VSCode|
|<B>Flash Frequency</B>|40Mhz|80Mhz|
|<B>PSRAM enabled</B>|yes|no|
|<B>Upload Speed</B>|115200|
|<B>Computer OS</B>|Windows 10|Mac OSX|Ubuntu|

### Description:
dhcps debug messages are appearing on the Serial port, preventing the port from being used for other purposes.
These should be disabled by default, but instead are enabled.  Eg.
     dhcps: send_nak>>udp_sendto result 0


### Sketch:  (leave the backquotes for [code formatting](https://help.github.com/articles/creating-and-highlighting-code-blocks/))
```cpp

//Change the code below by your sketch
#include <Arduino.h>

void setup() {
}

void loop() {
}
```

### Debug Messages:
```
Enable Core debug level: Debug on tools menu of Arduino IDE, then put the serial output here 
```
