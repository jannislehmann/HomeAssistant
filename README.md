# Home Assistant

This is my Home Assistant configuration. I try to integrate as much as possibly and keep it as reliable as possible.
However, ZigBee can be quite unreliable during restarts etc. The automations are aimed to help throughout the day, but everythink
should be controllable with physical switches. Exceptions are some LED stripes, which are not required and the motion activated light in the hall,
which is not required as it is bright enough.

## Home Assistant Addons

* Check Home Assistant configuration
* ESPHome
* Home Assistant Google Drive Backup
* Let's Encrypt (for HTTPS and maybe sometime MQTT encryption)
* MariaDB
* Mosquitto Broker
* Node-RED
* Rhasspy Assistant 2.5
* SSH & Web Terminal
* Visual Studio Code
* diyHue (self-made, unstable, not yet released)

### ESPHome

I use ESPHome for a few diyHue lights and generic LED RGB stripes.

### Node-RED

I try to migrate my automations back to Home Assistant. However, some automations are rather complicated. Therefore, they might
stay within Node-RED for the time being. An example would be the morning routine which checks my calendar and calculates when to get up.
After that a few more things are being triggereinclude_dir_merge_namedhttps://github.com/diyhue/diyHue/commit/b9ffecda8dd25c9c6a9b251b1d9bacf6b89def01d.

## Hardware

* Raspberry Pi 4 4GB with ConBee II
* Self-built server for media, nas and more stuff
* Android TV and a Xiaomi Mi TV Stick
* Xiaomi motion, contact, temperature sensors
* Xiaomi buttons
* WS2812b LED stripes and RGBWW stripes connected to Wemos D1 minis
* 1x Shelly 2.5
* Hue Lights
* Amazon Fire Tablet (7" 2015 generation?)
* And probably something else I missed

## Bigger Projects

* MQTT Encryption
* Self-made Multi Room Audio (software done, however misses the voice assistant)
* Rhasspy voice assistant (need to create the intent_scripts)

## Issues

The issue tracker is mainly my to-do list for brigger ideas. I try to document the progress in there.
Everyone above in the credits handles their issues in a similar way.
They help me to combine my different lists where I had stored tasks and ideas.

* https://github.com/pkozul/ha-floorplan und https://github.com/pkozul/lovelace-floorplan
* https://github.com/klaasnicolaas/Smarthome-homeassistant-config
* https://github.com/CCOSTAN/Home-AssistantConfig
* https://github.com/geekofweek/homeassistant
* https://github.com/stanvx/Home-Assistant-Configuration

## Credits

* @frenck for a lot of automations
* @jcallaghan for the great issue tracker
* @eliseomartelli for the frontend. Most of the lovelace-gen part is made by him. Awesome work by him!