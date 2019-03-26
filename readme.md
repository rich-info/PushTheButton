## PushTheButton

A button with almost infinite possibilities.
PushTheButton is a combination of a ESP8266 ESP-12F low power dev board with a WS2812B (Addressable RGB) LED all in one. 
The wifi module also has on-board memory functions. The switch is structured as follows.

![PushTheButton](https://github.com/rich-info/PushTheButton/blob/master/img/button.jpg)

As soon as the button is pressed, the Wifi module (ESP-12F) connects to the WLAN router and sends an HTTP request to a predefined URL. For example, you can call an IFTTT applet by pressing the button. IFTTT can then perform different actions.

![IFTTT](https://github.com/rich-info/PushTheButton/blob/master/img/ifttt.jpg)

A short demo video:
[![A short demo video](https://github.com/rich-info/PushTheButton/blob/master/img/demo-video.jpg)](https://youtu.be/SldVIySn8x4)


## Installation

Run command lines to get all codes

```
git clone https://github.com/AprilBrother/APixel.git
cd APixel
git submodule init
git submodule update
```

## Related links

https://rich-informatik.de/projekt-push-the-button

https://www.hackster.io/noelportugal/ifttt-smart-button-e11841

http://wiki.aprbrother.com/wiki/APixel  
