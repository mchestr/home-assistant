# Home Assistant Configuration

[Home Assistant Core](https://home-assistant.io/) running on [my Kubernetes cluster](https://github.com/mchestr/home-cluster).  This configuration is read and persisted within Home Assistant.

## Automations

The majority of the automations are found in [automations](./automations) directory using native Home Assistant yaml automations. 
A few more complex automations are done via [AppDaemon](https://appdaemon.readthedocs.io/en/latest/), those are located in [AppDaemon Repo](https://github.com/mchestr/appdaemon).

## Smart Home Devices

| Device | Quantity | Type | Affiliate | Recommend? |
|--------|----------|------|--------------|---------|
| HUSBZB | 1 | Zigbee/ZWave 2-in-1 Controller |[link](https://amzn.to/3wCaQ5L)| ✅ (although quite pricey now...) |
| Aqara Motion Sensor | 1 | Zigbee Motion Sensor | [link](https://amzn.to/3Ga0GN0) | ✅ |
| Aqara Water Leak Sensor | 2 | Zigbee Water Leak Sensor | [link](https://amzn.to/387R2he) | ✅ |
| Aqara Magic Cube | 1 | Zigbee Magic Cube Thing | [link](https://amzn.to/3LDlYDG) | 〰️ (have not found a good use for it) |
| Aqara Window Sensor  | 10 | Zigbee Window Sensor | [link](https://amzn.to/3lAAXE4) | ✅ |
| Aqara Vibration Sensor | 4 | Zigbee Vibration Sensor | [link](https://amzn.to/3LEMBID) | 〰️ (have not found a good use for them yet...) |
| SONOFF SNZB-03 Motion Sensor | 2 | Zigbee Motion Sensor | [link](https://amzn.to/3yUrWgS) | 〰️ (prefer aqara) |
| SONOFF SNZB-02 Temperature/Humidity Sensor | 1 | Zigbee Temp/Humidity Sensor | [link](https://amzn.to/39GZSD8) | ✅ |
| SONOFF S31 Smart Plug | 2 | Wi-Fi Smart Plug | [link](https://amzn.to/3lxf5JJ) | ✅ Flashed with [Tasmota](https://tasmota.github.io/docs/)|
| August Smart Lock Pro | 1 | Wi-Fi/Z-Wave Door Lock | [link](https://amzn.to/3G9ejvI) | ✅ |
| Zooz ZEN76 | 3 | Z-Wave Light Switch | [link](https://amzn.to/3MCMVsw) | ✅ |
| Zooz ZEN71 | 11 | Z-Wave Light Switch | [link](https://amzn.to/3LEMYmv) | ✅ |
| Hue White Light | 2 | Zigbee Light Bulb | [link](https://amzn.to/3sRswIj) | ✅ |
| Hue Color Light | 1 | Zigbee Light Bulb | [link](https://amzn.to/3LCdDjN) | ✅ |
| Hue Go | 1 | Zigbee Light | [link](https://amzn.to/3MJnWUv) | ✅ |
| Sinope Heated Floor Thermostat | 1 | Zigbee Heated Floor Thermostst | [link](https://amzn.to/38CHxqN) | ✅ |
| Nest Themostat | 1 | Wi-Fi Thermostat | [link](https://amzn.to/3LwY252) | 〰️ (in the future I would probably go for a non-cloud connected thermostat)
| Google Hello | 1 | Wi-Fi DoorBell | [link](https://store.google.com/ca/config/nest_doorbell_wired?hl=en-GB) | 〰️ (requires subscription, would prefer non-cloud connected in the future) |
| Roomba 960 | 1 | Smart Vacuum | [link](https://amzn.to/3NltowO) | ❌ (better smart vacuums available now, but it still works nicely after 5 years) |
| Dreame L10 Pro | 1 | Smart Vacuum | [link](https://amzn.to/3GoDOcV) | Undecided, haven't had it long enough |
| MyQ Garage Door Opener | 1 | Wi-Fi Garage Door Opener | [link](https://www.myq.com/) | ✅ (came with house, no complaints so far after 2 years) |
| TP-Link HS200 | 1 | Wi-Fi Light Switch | [link](https://amzn.to/38DSs3x) | ✅ (cheap, works, although I will probably replace with Zooz in the future) |
| TP-Link HS105 | 1 | Wi-Fi Smart Plug | [link](https://amzn.to/39NXMBz) | 〰️ (sonoff seem to be cheaper, both work well)  |
| SONOFF GK-200MP2-B | 1 | Wi-Fi Camera | [link](https://amzn.to/3MHTiL6) | 〰️ (works fine, but Home Assistant integration is hit and miss with PtZ) |

## Lovelace UI

Currently using [Lovelave Minimalist](https://ui-lovelace-minimalist.github.io/UI/) for all UIs. Dashboards are made to look nice on 
a mobile phone, as that is the main interface used by family members and myself.

## Screenshots

Main Dashboard
![Main Dashboard](https://user-images.githubusercontent.com/1817506/169753202-218afb4c-806e-47c9-9f89-5c1f3dfb96dc.png?raw=true)

Lights Dashboard
![Lights Dashboard](https://user-images.githubusercontent.com/1817506/169753477-0c4a22d5-2cde-4f34-9b5f-c9ff561fc7f3.png?raw=true)

Health Dashboard
![Health Dashboard](https://user-images.githubusercontent.com/1817506/169753639-478f68ec-f36b-4c32-ac4d-12f0147cef36.png)
