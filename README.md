
<h1 align="center">Casa Maxson
  <br>Home Assistant Configuration
</h1>

This repo contains the constantly-in-progress [Home Assistant](https://home-assistant.io/) configuration for **Casa Maxson**. Below are links to various devices currently being used, and other HA enthusists that provided inspiration and configs to help build this config. All of the code is free for you to borrow, manipulate and tinker with.

Make sure that you :star: this repo, so that you can get updates right in your notification feed.

### Dashboard:
![dashboard](https://raw.githubusercontent.com/thomasmaxson/Home-Assistant-Configuration/main/config/www/images/dashboard/dashboard.png){:target="_blank"}


#### Household Information Popups:
| [![overview](https://raw.githubusercontent.com/thomasmaxson/Home-Assistant-Configuration/main/config/www/images/dashboard/popup-details-household-overview.png)](https://raw.githubusercontent.com/thomasmaxson/Home-Assistant-Configuration/main/config/www/images/dashboard/popup-details-household-overview.png){:target="_blank"}<br>Household Overview | [![details](https://raw.githubusercontent.com/thomasmaxson/Home-Assistant-Configuration/main/config/www/images/dashboard/popup-details-household-details.png)](https://raw.githubusercontent.com/thomasmaxson/Home-Assistant-Configuration/main/config/www/images/dashboard/popup-details-household-details.png){:target="_blank"}<br>Household Details |
|:---:|:---:|
| [![temperature](https://raw.githubusercontent.com/thomasmaxson/Home-Assistant-Configuration/main/config/www/images/dashboard/popup-details-temperature.png)](https://raw.githubusercontent.com/thomasmaxson/Home-Assistant-Configuration/main/config/www/images/dashboard/popup-details-temperature.png){:target="_blank"}<br>Temperatures | [![router](https://raw.githubusercontent.com/thomasmaxson/Home-Assistant-Configuration/main/config/www/images/dashboard/popup-details-router.png)](https://raw.githubusercontent.com/thomasmaxson/Home-Assistant-Configuration/main/config/www/images/dashboard/popup-details-router.png){:target="_blank"}<br>Router |
| [![settings](https://raw.githubusercontent.com/thomasmaxson/Home-Assistant-Configuration/main/config/www/images/dashboard/popup-details-settings.png)](https://raw.githubusercontent.com/thomasmaxson/Home-Assistant-Configuration/main/config/www/images/dashboard/popup-details-settings.png){:target="_blank"}<br>Settings | [![systems](https://raw.githubusercontent.com/thomasmaxson/Home-Assistant-Configuration/main/config/www/images/dashboard/popup-details-systems.png)](https://raw.githubusercontent.com/thomasmaxson/Home-Assistant-Configuration/main/config/www/images/dashboard/popup-details-systems.png){:target="_blank"}<br>Systems |


#### Control Popups:
| [![lightoff](https://raw.githubusercontent.com/thomasmaxson/Home-Assistant-Configuration/main/config/www/images/dashboard/popup-lights-off.png)](https://raw.githubusercontent.com/thomasmaxson/Home-Assistant-Configuration/main/config/www/images/dashboard/popup-lights-off.png){:target="_blank"}<br>Mushroom Card, Lights Off | [![lightson](https://raw.githubusercontent.com/thomasmaxson/Home-Assistant-Configuration/main/config/www/images/dashboard/popup-lights-on.png)](https://raw.githubusercontent.com/thomasmaxson/Home-Assistant-Configuration/main/config/www/images/dashboard/popup-lights-on.png){:target="_blank"}<br>Mushroom Card, Lights On |
|:---:|:---:|
| [![sidebar](https://raw.githubusercontent.com/thomasmaxson/Home-Assistant-Configuration/main/config/www/images/dashboard/popup-sidebar-customizer.png)](https://raw.githubusercontent.com/thomasmaxson/Home-Assistant-Configuration/main/config/www/images/dashboard/popup-sidebar-customizer.png){:target="_blank"}<br>Sidebar Visibility Controls |

<hr>

### Hardware:
* [Raspberry Pi 4](https://www.amazon.com/dp/B0897XZDF2/){:target="_blank"}
* [Kingston A400 Internal SSD M.2](https://www.amazon.com/dp/B07P22RK1G/){:target="_blank"}
* [Argon ONE M.2 Case for Raspberry Pi 4](https://www.amazon.com/dp/B08MJ3CSW7/){:target="_blank"}
* [Nortec GoControl HUSBZB-1 USB Hub, Universal Zigbee & Z-Wave USB Gateway](https://www.amazon.com/dp/B01GJ826F8/){:target="_blank"}

<hr>

### Devices:
* Various Apple Devices (Macbooks, iPhones and iPads)
* Fire Tablet HD10

##### Media
* AppleTV
* [Amazon Echo Dot](https://www.amazon.com/gp/product/B07FZ8S74R/){:target="_blank"}
* [Amazo{:target="_blank"}n Echo](https://www.amazon.com/gp/product/B084J4KNDS/)

##### Switches / Plugs
* [Lutron Caseta Lightswitch](https://www.amazon.com/gp/product/B07SJJBTYY/){:target="_blank"}
* [Lutron Caseta Outdoor Smart Plug](https://www.amazon.com/gp/product/B08YPFFM58/){:target="_blank"}
* [Philips Hue Smart Plug](https://www.amazon.com/gp/product/B07XD578LD/){:target="_blank"}
* [MyQ Garage Door Hub](https://www.amazon.com/gp/product/B075RQVSY7/){:target="_blank"}

##### Lights
* [Philips Hue Smart Lightbulb (BR30)](https://www.amazon.com/gp/product/B07QZHMM57/){:target="_blank"}
* [Philips Hue Smart Lightbulb (A19)](https://www.amazon.com/gp/product/B01M9AU8MB/){:target="_blank"}
* [Philips Hue Smart Lightstrip (and Extension)](https://www.amazon.com/gp/product/B08CKJWSFS/){:target="_blank"}

##### Sensors
* [Aqara Door and Window Sensor](https://www.amazon.com/gp/product/B07D37VDM3/){:target="_blank"}
* [Aqara Leak Sensor](https://www.amazon.com/gp/product/B07D39MSZS/){:target="_blank"}
* [Aqara Motion Sensor](https://www.amazon.com/gp/product/B07D1CRRVF/){:target="_blank"}
* [Aqara Temperature Sensor](https://www.amazon.com/gp/product/B07D37FKGY/){:target="_blank"}
* [SONOFF SNZB-02 Temperature and Humidity Sensor](https://www.amazon.com/gp/product/B08BCJNDYQ/){:target="_blank"}

##### Climate
* [Ecobee Thermostat](https://www.amazon.com/gp/product/B07NQT85FC/){:target="_blank"}
* [Ecobee Temp and Motion Sensors](https://www.amazon.com/gp/product/B07NQVWRR3/){:target="_blank"}

<hr>

### Integrations

<details>
<summary>Click to Expand</summary>

* Node RED
* [Mushroom Cards](https://github.com/piitaya/lovelace-mushroom){:target="_blank"}
* [Alexa Media Player](https://github.com/custom-components/alexa_media_player/wiki){:target="_blank"}
* [Apple TV](https://www.home-assistant.io/integrations/apple_tv){:target="_blank"}
* [August](https://www.home-assistant.io/integrations/august){:target="_blank"}
* [Browser Mod](https://github.com/thomasloven/hass-browser_mod/blob/master/README.md){:target="_blank"}
* [Ecobee](https://www.home-assistant.io/integrations/ecobee){:target="_blank"}
* [Fully Kiosk](https://github.com/cgarwood/homeassistant-fullykiosk){:target="_blank"}
* [HACS](https://hacs.xyz/docs/configuration/start){:target="_blank"}
* [Philips Hue](https://www.home-assistant.io/integrations/hue){:target="_blank"}
* [Home Assistant iOS](https://www.home-assistant.io/integrations/ios){:target="_blank"}
* [Lutron Caséta](https://www.home-assistant.io/integrations/lutron_caseta){:target="_blank"}
* [MyQ](https://www.home-assistant.io/integrations/myq){:target="_blank"}
* [Rachio](https://www.home-assistant.io/integrations/rachio){:target="_blank"}
* [Ring](https://www.home-assistant.io/integrations/ring){:target="_blank"}
* [Zigbee Home Automation](https://www.home-assistant.io/integrations/zha){:target="_blank"}

</details>

<hr>

### Inspiration:

<details>
<summary>Click to Expand</summary>

Below are a few of my most used resources. If you like what you see here, please check them out as well!

* [Matt8707 (Mattias Persson)](https://github.com/matt8707/hass-config){:target="_blank"}
* [Slacker Labs (Jeffery Stone)](https://github.com/thejeffreystone/home-assistant-configuration/){:target="_blank"}

</details>
