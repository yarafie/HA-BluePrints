# Z2M 2.0.0 Compatible HA-BluePrints
In Z2M 2.0.0 the sensor.\<DEVICE\>_action is deprecated.
See below link for further information
https://github.com/Koenkk/zigbee2mqtt/discussions/24198

Credit goes to original authors, not sure where most have come from.
Notable mention goes to damru https://github.com/damru/ha-blueprints
which I based my blueprints from his blueprints.
These blueprints have been tested and work for all my devices and will work with z2m > 2.0.0 (Hopefully :)).

Current Devices Supported by each blueprint:
--------------------------------------------
# z2m-IKEA-rodret_E2201-tradfri_E1743-somrig_E2213-control_anything.yaml
* model: RODRET wireless dimmer/power switch (E2201)
* model: TRADFRI on/off switch (E1743)
* model: SOMRIG shortcut button (E2213)

<a href="https://my.home-assistant.io/redirect/blueprint_import/?blueprint_url=https%3A%2F%2Fgithub.com%2Fyarafie%2FHA-BluePrints%2Fblob%2Fmain%2Fz2m-+IKEA-rodret_E2201-tradfri_E1743-somrig_E2213-control_anything.yaml" target="_blank" rel="noreferrer noopener"><img src="https://my.home-assistant.io/badges/blueprint_import.svg" alt="Open your Home Assistant instance and show the blueprint import dialog with a specific blueprint pre-filled." /></a>


# z2m-IKEA-rodret_E2201-tradfri_E1743-somrig_E2213-control_light.yamlmodel: RODRET wireless dimmer/power switch (E2201)
* model: TRADFRI on/off switch (E1743)
* model: SOMRIG shortcut button (E2213)
* Very Basic Integration

<a href="https://my.home-assistant.io/redirect/blueprint_import/?blueprint_url=https%3A%2F%2Fgithub.com%2Fyarafie%2FHA-BluePrints%2Fblob%2Fmain%2Fz2m-+IKEA-rodret_E2201-tradfri_E1743-somrig_E2213-control_light.yaml" target="_blank" rel="noreferrer noopener"><img src="https://my.home-assistant.io/badges/blueprint_import.svg" alt="Open your Home Assistant instance and show the blueprint import dialog with a specific blueprint pre-filled." /></a>


# z2m-IKEA-styrbar_E2001_E2002.yaml
* model: STYRBAR remote control (E2001/E2002)

<a href="https://my.home-assistant.io/redirect/blueprint_import/?blueprint_url=https%3A%2F%2Fgithub.com%2Fyarafie%2FHA-BluePrints%2Fblob%2Fmain%2Fz2m-+IKEA-styrbar_E2001_E2002.yaml" target="_blank" rel="noreferrer noopener"><img src="https://my.home-assistant.io/badges/blueprint_import.svg" alt="Open your Home Assistant instance and show the blueprint import dialog with a specific blueprint pre-filled." /></a>

## Changelog: 
* 19, April 2025: Strybar Blueprint was expanded to add an optional looping for any of the long button presses. This needs to be enabled in the blueprint. 
Two safe guards were added in order to stop any infinite loops, a count was added to loop a finite number of times and also a timeout was added to stop the wait for the release of button. 
Additionaly, virtual double press actions was also added to any of the buttons which also needs to be exposed.

# z2m-IKEA-tradfri_shortcut_button_E1812-control_anything.yaml
* model: TRADFRI shortcut button (E1812)

<a href="https://my.home-assistant.io/redirect/blueprint_import/?blueprint_url=https%3A%2F%2Fgithub.com%2Fyarafie%2FHA-BluePrints%2Fblob%2Fmain%2Fz2m-+IKEA-tradfri_shortcut_button_E1812-control_anything.yaml" target="_blank" rel="noreferrer noopener"><img src="https://my.home-assistant.io/badges/blueprint_import.svg" alt="Open your Home Assistant instance and show the blueprint import dialog with a specific blueprint pre-filled." /></a>


# z2m-IKEA-tradfri_shortcut_button_E1812-control_light.yaml
* model: TRADFRI shortcut button (E1812)

<a href="https://my.home-assistant.io/redirect/blueprint_import/?blueprint_url=https%3A%2F%2Fgithub.com%2Fyarafie%2FHA-BluePrints%2Fblob%2Fmain%2Fz2m-+IKEA-tradfri_shortcut_button_E1812-control_light.yaml" target="_blank" rel="noreferrer noopener"><img src="https://my.home-assistant.io/badges/blueprint_import.svg" alt="Open your Home Assistant instance and show the blueprint import dialog with a specific blueprint pre-filled." /></a>


# z2m-TUYA-moes_ERS-10TZBVK-AA-smart_knob.yaml
* model: Smart knob (ERS-10TZBVK-AA)

<a href="https://my.home-assistant.io/redirect/blueprint_import/?blueprint_url=https%3A%2F%2Fgithub.com%2Fyarafie%2FHA-BluePrints%2Fblob%2Fmain%2Fz2m-+TUYA-moes_ERS-10TZBVK-AA-smart_knob.yaml" target="_blank" rel="noreferrer noopener"><img src="https://my.home-assistant.io/badges/blueprint_import.svg" alt="Open your Home Assistant instance and show the blueprint import dialog with a specific blueprint pre-filled." /></a>


# z2m-TUYA-tuya_ts0041-1_button_wireless_scene_switch.yaml
* model: Wireless switch with 1 button (TS0041)

<a href="https://my.home-assistant.io/redirect/blueprint_import/?blueprint_url=https%3A%2F%2Fgithub.com%2Fyarafie%2FHA-BluePrints%2Fblob%2Fmain%2Fz2m-+TUYA-tuya_ts0041-1_button_wireless_scene_switch.yaml" target="_blank" rel="noreferrer noopener"><img src="https://my.home-assistant.io/badges/blueprint_import.svg" alt="Open your Home Assistant instance and show the blueprint import dialog with a specific blueprint pre-filled." /></a>


# z2m-TUYA-tuya_ts0044-moes_ZT-SR-EU4-4_button_wireless_scene_switch.yaml
* model: Star Ring 4 Gang Scene Switch (ZT-SR-EU4)
* model: Wireless switch with 4 buttons (TS0044)

<a href="https://my.home-assistant.io/redirect/blueprint_import/?blueprint_url=https%3A%2F%2Fgithub.com%2Fyarafie%2FHA-BluePrints%2Fblob%2Fmain%2Fz2m-+TUYA-tuya_ts0044-moes_ZT-SR-EU4-4_button_wireless_scene_switch.yaml" target="_blank" rel="noreferrer noopener"><img src="https://my.home-assistant.io/badges/blueprint_import.svg" alt="Open your Home Assistant instance and show the blueprint import dialog with a specific blueprint pre-filled." /></a>
