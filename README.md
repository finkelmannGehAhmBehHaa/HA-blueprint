# Blueprint collection for Home Assistant

A collection of usefull home-assistant blueprints. All Zigbee Automation (like the ikea) are for Zigbee2MQTT.

## Motion Lux 

- `motion_lux.yaml`

Turns on a light or scene when motion is detected, based on time for day/night settings,
but only if the luminance is below a specified threshold. If luminance is above the threshold,
the automation does nothing. Allows toggling between using scenes or directly controlling the light.

[![Open your Home Assistant instance and show the blueprint import dialog with a specific blueprint pre-filled.](https://my.home-assistant.io/badges/blueprint_import.svg)](https://my.home-assistant.io/redirect/blueprint_import/?blueprint_url=https%3A%2F%2Fgithub.com%2FfinkelmannGehAhmBehHaa%2FHA-blueprint%2Fblob%2Fmain%2Fmotion_lux.yaml)

## Toggel switch time based 

- `toggel_sw_time_based.yaml`

Automatically toggles adaptive lighting sleep mode on and off at specified times.

[![Open your Home Assistant instance and show the blueprint import dialog with a specific blueprint pre-filled.](https://my.home-assistant.io/badges/blueprint_import.svg)](https://my.home-assistant.io/redirect/blueprint_import/?blueprint_url=https%3A%2F%2Fgithub.com%2FfinkelmannGehAhmBehHaa%2FHA-blueprint%2Fblob%2Fmain%2Ftoggel_sw_time_based.yaml)

## Toggel light time based 

- `toggel_light_time_based.yaml`

Automatically toggel a light at specified times.

[![Open your Home Assistant instance and show the blueprint import dialog with a specific blueprint pre-filled.](https://my.home-assistant.io/badges/blueprint_import.svg)](https://my.home-assistant.io/redirect/blueprint_import/?blueprint_url=https%3A%2F%2Fgithub.com%2FfinkelmannGehAhmBehHaa%2FHA-blueprint%2Fblob%2Fmain%2Ftoggel_light_time_based.yaml)

## Ikea 4 button remote 2 lights 

- `ikea_remote_4_button_2_lights.yaml`

Controls two seperate lights with a switch given as device. The On and Off buttons controll one light and the left and right buttons the other. A long press dose dimm the light.

[![Open your Home Assistant instance and show the blueprint import dialog with a specific blueprint pre-filled.](https://my.home-assistant.io/badges/blueprint_import.svg)](https://my.home-assistant.io/redirect/blueprint_import/?blueprint_url=https%3A%2F%2Fgithub.com%2FfinkelmannGehAhmBehHaa%2FHA-blueprint%2Fblob%2Fmain%2Fikea_remote_4_button_2_lights.yaml)

## Ikea 4 button remote set brightness 

- `ikea_remote_4_button_1_light_set_brightness.yaml`

Controls a light with a switch given as device. The On and Off buttons controll one light. A long press dimms it. The short and long press on the left and right buttons will set the brightness to a configured value.

[![Open your Home Assistant instance and show the blueprint import dialog with a specific blueprint pre-filled.](https://my.home-assistant.io/badges/blueprint_import.svg)](https://my.home-assistant.io/redirect/blueprint_import/?blueprint_url=https%3A%2F%2Fgithub.com%2FfinkelmannGehAhmBehHaa%2FHA-blueprint%2Fblob%2Fmain%2Fikea_remote_4_button_1_light_set_brightness.yaml)

## Ikea 4 button remote 1 light and actions 

- `ikea_remote_4_button_1_light_and_actions.yaml`

Controls a light with a switch given as device. The On and Off buttons controll one light. A long press dimms it. The short and long press on the left and right buttons will exectue a customizable action.

[![Open your Home Assistant instance and show the blueprint import dialog with a specific blueprint pre-filled.](https://my.home-assistant.io/badges/blueprint_import.svg)](https://my.home-assistant.io/redirect/blueprint_import/?blueprint_url=https%3A%2F%2Fgithub.com%2FfinkelmannGehAhmBehHaa%2FHA-blueprint%2Fblob%2Fmain%2Fikea_remote_4_button_1_light_and_actions.yaml)


## Ikea 2 button remote 1 light 

- `ikea_remote_2_button_1_light.yaml`

Controls a light with a switch given as device. The On and Off buttons controll one light. A long press dimms it.

[![Open your Home Assistant instance and show the blueprint import dialog with a specific blueprint pre-filled.](https://my.home-assistant.io/badges/blueprint_import.svg)](https://my.home-assistant.io/redirect/blueprint_import/?blueprint_url=https%3A%2F%2Fgithub.com%2FfinkelmannGehAhmBehHaa%2FHA-blueprint%2Fblob%2Fmain%2Fikea_remote_4_button_1_light_and_actions.yaml)
