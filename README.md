
<h1 align="center">Casa Maxson
  <br>Home Assistant Configuration
</h1>

This repo contains the constantly-in-progress [Home Assistant](https://home-assistant.io/) configuration for **Casa Maxson**. Below are links to various devices currently being used, and other HA enthusists that provided inspiration and configs to help build this config. All of the code is free for you to borrow, manipulate and tinker with.

Make sure that you :star: this repo, so that you can get updates right in your notification feed.

### Dashboard:
![dashboard](https://raw.githubusercontent.com/thomasmaxson/Home-Assistant-Configuration/main/config/www/images/dashboard/lovelace-dashboard-1.png)


#### Household Information Popups:
| [![household](https://raw.githubusercontent.com/thomasmaxson/Home-Assistant-Configuration/main/config/www/images/dashboard/popup-details-household-1.png)](https://raw.githubusercontent.com/thomasmaxson/Home-Assistant-Configuration/main/config/www/images/dashboard/popup-details-household-1.png)<br>Entities Popup | [![temperature](https://raw.githubusercontent.com/thomasmaxson/Home-Assistant-Configuration/main/config/www/images/dashboard/popup-details-temperature.png)](https://raw.githubusercontent.com/thomasmaxson/Home-Assistant-Configuration/main/config/www/images/dashboard/popup-details-temperature.png)<br>Temperature Popup |
|:---:|:---:|
| [![settings](https://raw.githubusercontent.com/thomasmaxson/Home-Assistant-Configuration/main/config/www/images/dashboard/popup-details-settings-1.png)](https://raw.githubusercontent.com/thomasmaxson/Home-Assistant-Configuration/main/config/www/images/dashboard/popup-details-settings-1.png)<br>Settings Popup | [![systems](https://raw.githubusercontent.com/thomasmaxson/Home-Assistant-Configuration/main/config/www/images/dashboard/popup-details-system.png)](https://raw.githubusercontent.com/thomasmaxson/Home-Assistant-Configuration/main/config/www/images/dashboard/popup-details-system.png)<br>Systems Popup |


#### Control Popups:
| [![dimmer1](https://raw.githubusercontent.com/thomasmaxson/Home-Assistant-Configuration/main/config/www/images/dashboard/popup-light-dimmer-color.png)](https://raw.githubusercontent.com/thomasmaxson/Home-Assistant-Configuration/main/config/www/images/dashboard/popup-light-dimmer-color.png)<br>Light Dimmer with Colors | [![dimmer2](https://raw.githubusercontent.com/thomasmaxson/Home-Assistant-Configuration/main/config/www/images/dashboard/popup-light-dimmer-color.png)](https://raw.githubusercontent.com/thomasmaxson/Home-Assistant-Configuration/main/config/www/images/dashboard/popup-light-dimmer-color.png)<br>Light Dimmer |
|:---:|:---:|
| [![switch](https://raw.githubusercontent.com/thomasmaxson/Home-Assistant-Configuration/main/config/www/images/dashboard/popup-light-switch.png)](https://raw.githubusercontent.com/thomasmaxson/Home-Assistant-Configuration/main/config/www/images/dashboard/popup-light-switch.png)<br>Light Switch | [![sidebar](https://raw.githubusercontent.com/thomasmaxson/Home-Assistant-Configuration/main/config/www/images/dashboard/popup-sidebar-customizer-1.png)](https://raw.githubusercontent.com/thomasmaxson/Home-Assistant-Configuration/main/config/www/images/dashboard/popup-sidebar-customizer-1.png)<br>Sidebar Visibility Controls |

<hr>

### Hardware:
* [Raspberry Pi 4](https://www.amazon.com/dp/B0897XZDF2/)
* [Kingston A400 Internal SSD M.2](https://www.amazon.com/dp/B07P22RK1G/)
* [Argon ONE M.2 Case for Raspberry Pi 4](https://www.amazon.com/dp/B08MJ3CSW7/)
* [Nortec GoControl HUSBZB-1 USB Hub, Universal Zigbee & Z-Wave USB Gateway](https://www.amazon.com/dp/B01GJ826F8/)

<hr>

### Devices:
* Various Apple Devices (Macbooks, iPhones and iPads)
* Fire Tablet HD10

##### Media
* AppleTV
* [Amazon Echo Dot](https://www.amazon.com/gp/product/B07FZ8S74R/)
* [Amazon Echo](https://www.amazon.com/gp/product/B084J4KNDS/)

##### Switches / Plugs
* [Lutron Caseta Lightswitch](https://www.amazon.com/gp/product/B07SJJBTYY/)
* [Lutron Caseta Outdoor Smart Plug](https://www.amazon.com/gp/product/B08YPFFM58/)
* [Philips Hue Smart Plug](https://www.amazon.com/gp/product/B07XD578LD/)
* [MyQ Garage Door Hub](https://www.amazon.com/gp/product/B075RQVSY7/)

##### Lights
* [Philips Hue Smart Lightbulb (BR30)](https://www.amazon.com/gp/product/B07QZHMM57/)
* [Philips Hue Smart Lightbulb (A19)](https://www.amazon.com/gp/product/B01M9AU8MB/)
* [Philips Hue Smart Lightstrip (and Extension)](https://www.amazon.com/gp/product/B08CKJWSFS/)

##### Sensors
* [Aqara Door and Window Sensor](https://www.amazon.com/gp/product/B07D37VDM3/)
* [Aqara Leak Sensor](https://www.amazon.com/gp/product/B07D39MSZS/)
* [Aqara Motion Sensor](https://www.amazon.com/gp/product/B07D1CRRVF/)
* [Aqara Temperature Sensor](https://www.amazon.com/gp/product/B07D37FKGY/)
* [SONOFF SNZB-02 Temperature and Humidity Sensor](https://www.amazon.com/gp/product/B08BCJNDYQ/)

##### Climate
* [Ecobee Thermostat](https://www.amazon.com/gp/product/B07NQT85FC/)
* [Ecobee Temp and Motion Sensors](https://www.amazon.com/gp/product/B07NQVWRR3/)

<hr>

### Integrations

<details>
<summary>Click to Expand</summary>

* Node RED | Router, controller, switch and access point |
* [Alexa Media Player](https://github.com/custom-components/alexa_media_player/wiki)
* [Apple TV](https://www.home-assistant.io/integrations/apple_tv)
* [August](https://www.home-assistant.io/integrations/august)
* [Browser Mod](https://github.com/thomasloven/hass-browser_mod/blob/master/README.md)
* [Ecobee](https://www.home-assistant.io/integrations/ecobee)
* [Fully Kiosk](https://github.com/cgarwood/homeassistant-fullykiosk)
* [HACS](https://hacs.xyz/docs/configuration/start)
* [Philips Hue](https://www.home-assistant.io/integrations/hue)
* [Home Assistant iOS](https://www.home-assistant.io/integrations/ios)
* [Lutron Caséta](https://www.home-assistant.io/integrations/lutron_caseta)
* [MyQ](https://www.home-assistant.io/integrations/myq)
* [Rachio](https://www.home-assistant.io/integrations/rachio)
* [Ring](https://www.home-assistant.io/integrations/ring)
* [Zigbee Home Automation](https://www.home-assistant.io/integrations/zha)  

</details>

<hr>

### Inspiration:

<details>
<summary>Click to Expand</summary>

Below are a few of my most used resources. If you like what you see here, please check them out as well!

* [Matt8707 (Mattias Persson)](https://github.com/matt8707/hass-config)
* [Slacker Labs (Jeffery Stone)](https://github.com/thejeffreystone/home-assistant-configuration/)

</details>