# Control a boiler with effect block inputs
Collection of files and information on how to control effect blocking of a boiler that has external input for effect blocking.

The ESPhome will add *select.effect_block_level* to Home Assistant with the options:

 - None - means that no relay is active
 - A - means that relay A is active and relay B is inactive
 - B - means that relay A is inactive and relay B is active
 - A+B - means that both relay A and relay B are active

| File | Description |
|--|--|
|automations.yaml  | The Home Assistant automations included in total solution |
|boilercontrol.yaml  | The ESPHome config file for the ESP8266 microcontroller |
|README.md  | This readme file... 😉 |

**My config has the following hardware components:**
| Hardware | Description |
|--|--|
|1 x NodeMCU v3|Microcontroller dev board|
|1 x 2-ch Relay board|The relays controlled by ESP8266 connected to boiler input|
|5 x DS18B20|Dallas 1-wire temperature sensors to measure boiler temperatures|

To-do:

 - [ ] Add schematics
