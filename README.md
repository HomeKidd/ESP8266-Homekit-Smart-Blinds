# ESP8266 based  HomeKit Smart Blind Controller
ESP8266 based  HomeKit Smart Blind Controller for Vertical and Venetian Blinds with BH1750 Light Sensor and Automatic Mode!


------
[![Instagram URL](https://img.shields.io/twitter/url/https/www.instagram.com/homekidd?label=Follow&logo=instagram&style=social)](https://www.instagram.com/homekidd) [![FaceBook URL](https://img.shields.io/twitter/url/https/www.facebook.com/HomeKiid?label=Like&logo=facebook&style=social)](https://www.facebook.com/HomeKiid) [![YouTube URL](https://img.shields.io/twitter/url/https/www.youtube.com/channel/UCkqC_6j1uyYVv7SO3jPe7KA?label=Follow&logo=youtube&style=social)](https://www.youtube.com/channel/UCkqC_6j1uyYVv7SO3jPe7KA)
------

[![GitHub All Releases](https://img.shields.io/github/downloads/HomeKidd/ESP8266-Homekit-Smart-Blinds/total?color=green)](https://github.com/HomeKidd/ESP8266-Homekit-Smart-Blinds/releases) 
[![GitHub tag (latest by date)](https://img.shields.io/github/v/tag/HomeKidd/ESP8266-Homekit-Smart-Blinds?color=yellow&label=Latest%20Release)](https://github.com/HomeKidd/ESP8266-Homekit-Smart-Blinds/releases) 
[![Donate](https://img.shields.io/badge/Donate-PayPal-blue.svg)](https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=CEYEK69ZYG69S&source=url)
<br/>
<br/>

## This project is still in development so currently not fully working and some parts (PCB, 3D printed parts) are missing yet!

For **Usage** please read the [Build Instructions](https://github.com/HomeKidd/ESP8266-Homekit-Smart-Blinds/wiki/Build-Instructions) Wiki page!<br/><br/>

## Please note that for this Project a [3D Printer](https://s.click.aliexpress.com/e/_siadIH) is ESSENTIAL!




**Features:**

* Opening / Closing Blinds
* Auto Mode _(based on Light Sensor reading)_ 
* Button Control _(Fully Closing / Opening Blinds via Button Press)_
* [BH1750](https://s.click.aliexpress.com/e/_dTwkemh) Light sensor
* ~~Adjusting End Stop~~ _(Currently not available yet)_
* Reset button 

**This HomeKit enabled Smart Blind Controller is based on [this project](https://www.candco.com.au/2019/03/10/diy-vertical-or-horizontal-blinds-automation-project/)!** 


<br/>
<br/>
<img src="https://github.com/HomeKidd/ESP8266-Homekit-Smart-Blinds/raw/master/images/blinds_mockup.PNG" class="center" width="650"/>

<br/>

**Demo:**

<br/>

[![DEMO](http://img.youtube.com/vi/kqPzY2s9m0E/0.jpg)](http://www.youtube.com/watch?v=kqPzY2s9m0E)

<br/>
<br/>

This project uses the Apple HomeKit accessory server library [ESP-HomeKit](https://github.com/maximkulkin/esp-homekit) from [@MaximKulkin](https://github.com/maximkulkin) for [ESP-OPEN-RTOS](https://github.com/SuperHouse/esp-open-rtos).<br/>

Although already forbidden by the sources and subsequent licensing, it is not allowed to use or distribute this software for a commercial purpose.<br/><br/>

<img src="https://freepngimg.com/thumb/apple_logo/25366-7-apple-logo-file.png" width="20"/> 

###### HomeKit Accessory Protocol (HAP) is Apple’s proprietary protocol that enables third-party accessories in the home (e.g., lights, thermostats and door locks) and Apple products to communicate with each other. HAP supports two transports, IP and Bluetooth LE. The information provided in the HomeKit Accessory Protocol Specification (Non-Commercial Version) describes how to implement HAP in an accessory that you create for non-commercial use and that will not be distributed or sold.

###### The HomeKit Accessory Protocol Specification (Non-Commercial Version) can be downloaded from the [HomeKit Apple Developer page.](https://developer.apple.com/homekit/)

###### Copyright © 2019 Apple Inc. All rights reserved.



