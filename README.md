
# Home Assitant Configuration

Welcome to my Home Assistant Configuration

You can find my Home Assistant fork with patches, updates and enhancements, as used
by me at https://github.com/jaredquinn/home-assistant.

Additionally I run Home Assistant behind an nginx reverse proxy using Lets Encrypt
for SSL certificate generation.

# My Configuration

## Smart Home Devices

* Google Home
* Amazon Echo Dot (via Home Assistant Cloud)
* Xiaomi Aqara Gateway Night Light
* Xiaomi Aqara Smart Button (x2)
* Xiaomi Aqara Temperature & Humidity Sensor
* Xiaomi Aqara Door/Window Switch
* Xiaomi Aqara Motion Detection
* YeeLight Color LED Light Bulb (x4)
* TP-Link Color LED Light Bulb
* TP-Link White LED Light Bulb
* Broadlink RM2 Pro WiFi Infra-Red Blaster
* Broadlink SP3Mini WiFi A/C Switch (x2)
* TP-Link HS100 WiFi A/C Switch
* NodeMCU w/Submersible Temperature Sensor

## Weather

* BOM Australia
* Forecast (NDK)
* Sun

## Presence

* GPSLogger
* Ping

## Additional Features

* HA Alarm
* Floorplan
* MQTT
* InfluxDB
* Facebook Messanger

## Custom Components

* Remote Control
* Flash Lights


# FLOOR PLAN

pkozul's ha-floorplan is configured, as per his instructions at https://github.com/pkozul/ha-floorplan.


# SECRETS

The secrets.yaml.dist file is generated on updates of my secrets file and does
not contain any values, only the keys.  This can be used as a starting point
for using HA Secrets.

Additionally some files are included from a 'secret' directory; these will
ultimately be migrated to the secrets.yaml file.

# ZONES

Configuration includes some sample zones for nearby places that are frequented,
if you wish to override your 'home' and 'work' zones, create files in the 
'zones' directory.

Additional "secret" zones are not included in this repository and are prefixed
as secret_* in the filename.

