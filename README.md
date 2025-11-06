# TRMNL Home Assistant sensors
[![Open your Home Assistant instance and open this repository inside the Home Assistant Community Store.](https://my.home-assistant.io/badges/hacs_repository.svg)](https://my.home-assistant.io/redirect/hacs_repository/?owner=bbronisz&repository=trmnl_ha_sensors&category=integration)
[![Open your Home Assistant instance and start setting up this integration.](https://my.home-assistant.io/badges/config_flow_start.svg)](https://my.home-assistant.io/redirect/config_flow_start/?domain=trmnl_ha_sensors)

Use your **TRMNL** display to monitor your Home Assistance instance sensors.

This lightweight Home Assistant integration delivers your data to the TRMNL E-Ink display via the included plugin, for low-power, glanceable monitoring in your home.

[![Hassfest Workflow Status](https://img.shields.io/github/actions/workflow/status/bbronisz/trmnl_ha_sensors/hassfest.yaml?label=Hassfest&style=for-the-badge&colorA=000&colorB=fff)](https://github.com/bbronisz/trmnl_ha_sensors/actions/workflows/hassfest.yaml)
[![hacs Workflow Status](https://img.shields.io/github/actions/workflow/status/bbronisz/trmnl_ha_sensors/hacs.yaml?label=hacs&style=for-the-badge&colorA=000&colorB=fff)](https://github.com/bbronisz/trmnl_ha_sensors/actions/workflows/hacs.yaml)
[![Release](https://img.shields.io/github/v/release/bbronisz/trmnl_ha_sensors?style=for-the-badge&colorA=000&colorB=fff)](https://github.com/bbronisz/trmnl_ha_sensors/releases)


## What It Does

Send live sensor data (temperature, humidity, and more) to a TRMNL E-Ink display. Works with a few simple installation steps.

## Features

- Compatible with temperature, humidity, pressure, wind speed, precipitation
- Custom labels for rooms/locations
- Plugin included

## Quickstart Guide

### Step 1: Install custom Integration via HACS

[![Open your Home Assistant instance and open this repository inside the Home Assistant Community Store.](https://my.home-assistant.io/badges/hacs_repository.svg)](https://my.home-assistant.io/redirect/hacs_repository/?owner=bbronisz&repository=trmnl_ha_sensors&category=integration)

<details><summary>Manual setup instructions</summary>

1. Open Home Assistant and navigate to **HACS > Integrations**.
1. Click the three-dot menu (⋮) in the top-right corner and choose **Custom repositories**.
1. Add this repository URL `https://github.com/bbronisz/trmnl_ha_sensors` as a **"Integration"** type.

</details>

### Step 2: Fork Recipe to Your TRMNL Playlist

1. **Visit:** https://usetrmnl.com/recipes/46862/install
1. Click `Fork` to add it to your **TRMNL playlist**.
1. Go to your **TRMNL playlist** and locate **Home Assistant Sensors**.
1. Click `Edit` on the **Home Assistant Sensors** settings icon.
1. Set the `refresh rate` to **15 minutes** (or whatever suits you best).
1. **Copy** the `Webhook URL`, **you'll need this to complete** the Home Assistant integration.

### Step 3: Setup Home Assistant Integration

After a restart of Home Assistant, this integration is configurable by via
1. `Add Integration` at `Devices & Services` like any core integration.
1. Select `TRMNL Home Sensors` and follow the instructions.
1. The `TRMNL Webhook URL` field is the `Webhook URL` you copied earlier.

[![Open your Home Assistant instance and start setting up this integration.](https://my.home-assistant.io/badges/config_flow_start.svg)](https://my.home-assistant.io/redirect/config_flow_start/?domain=trmnl_ha_sensors)

---

This is a fork of: [Tilman Griesel's: TRMNL Weather Station](https://github.com/TilmanGriesel/ha_trmnl_weather_station).
