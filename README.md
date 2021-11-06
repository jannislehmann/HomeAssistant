# Home Assistant

This is my Home Assistant configuration. I try to integrate as much as possibly and keep it as reliable as possible.
However, ZigBee can be quite unreliable during restarts etc. The automations are aimed to help throughout the day, but everythink
should be controllable with physical switches. Exceptions are some LED stripes, which are not required and the motion activated light in the hall,
which is not required as it is bright enough.

## Home Assistant Addons

* Check Home Assistant configuration
* ESPHome
* Emulated Hue
* Grocy (only for trying out chores)
* Home Assistant Google Drive Backup
* Let's Encrypt (for HTTPS and maybe sometime MQTT encryption)
* MariaDB
* Mosquitto Broker
* SSH & Web Terminal
* Visual Studio Code

### ESPHome

I use ESPHome for a few diyHue lights and generic LED RGB stripes.

## Hardware

* Raspberry Pi 4 4GB with ConBee II
* Self-built unRAID server for media, nas and more stuff
* Android TV and a Fire TV Stick 4k
* Xiaomi motion, contact, temperature sensors
* Xiaomi buttons
* WS2812b LED stripes and RGBWW stripes connected to Wemos D1 minis
* Hue Lights
* Amazon Fire Tablet (7" 2015 generation)

## Bigger Projects

* MQTT Encryption
* Self-made Multi Room Audio
* Rhasspy voice assistant - project got scraped due to using multiple HomePod Minis and therefore giving Siri a try

## Issues

The issue tracker is mainly my to-do list for bigger ideas. I try to document the progress in there.
Everyone above in the credits handles their issues in a similar way.
They help me to combine my different lists where I had stored tasks and ideas.

* https://github.com/klaasnicolaas/Smarthome-homeassistant-config
* https://github.com/CCOSTAN/Home-AssistantConfig
* https://github.com/geekofweek/homeassistant
* https://github.com/stanvx/Home-Assistant-Configuration

## Credits

* @frenck for a lot of automations
* @jcallaghan for the great issue tracker
* @eliseomartelli for the frontend. Most of the lovelace-gen part is made by him. Awesome work by him!