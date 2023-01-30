---
title: "Safety"
description: ""
lead: ""
date: 2023-01-27T08:10:40-05:00
lastmod: 2023-01-27T08:10:40-05:00
draft: true
images: []
menu:
  docs:
    parent: "configuration"
    identifier: "safety-2d72331ff643290bf9a976c4007d3877"
weight: 169
toc: true
---
| Device                                                       | Quantity | Connection        | Integration                                                  | Notes                                                        |
| ------------------------------------------------------------ | :------: | ----------------- | ------------------------------------------------------------ | ------------------------------------------------------------ |
| [Nest Protect](https://amzn.to/2KwXltd)                      |    3     | Z-Wave            | [Nest](https://www.home-assistant.io/integrations/nest/)     | Fire, Carbon Monoxide Sensors. Currently not working as Google has deprecated the API. |
| [Aqara Water Sensors](https://www.aqara.com/us/water_leak_sensor.html) |    2     | HUSBZB-1 (Zigbee) | [Zigbee](https://www.home-assistant.io/integrations/zigbee/) | Not very reliable                                            |
| [SmartThings Water Leak Sensor](https://www.samsung.com/us/smart-home/smartthings/sensors/samsung-smartthings-water-leak-sensor-gp-u999sjvlcaa/) |    1     | Zigbee            | SmartThings                                                  | Also includes temperature and humidity sensor.               |
| [Netatmo Weather Station](https://www.netatmo.com/en-us/weather/weatherstation) |    1     | Wi-Fi             | [Netatmo](https://www.home-assistant.io/integrations/netatmo/) | Indoor  CO_2, Air Quality, temperature, and Sound sensors. The outdoor module is not working. |
