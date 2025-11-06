# TRMNL Home Assistant sensors
[![Open your Home Assistant instance and open this repository inside the Home Assistant Community Store.](https://my.home-assistant.io/badges/hacs_repository.svg)](https://my.home-assistant.io/redirect/hacs_repository/?owner=bbronisz&repository=trmnl-weather-station&category=integration)
[![Open your Home Assistant instance and start setting up this integration.](https://my.home-assistant.io/badges/config_flow_start.svg)](https://my.home-assistant.io/redirect/config_flow_start/?domain=trmnl_weather_station)

Use your **TRMNL** display to monitor **live CO₂ levels and up to six custom sensors** from your **Netatmo** or other supported stations.

This lightweight Home Assistant integration delivers your data to the TRMNL E-Ink display via the included plugin, for low-power, glanceable monitoring in your home.

Don't know what a TRMNL display is? You can [learn more about it here](https://usetrmnl.com?ref=griesel). If you find Home Assistant Weather Station useful, [leaving a star](https://github.com/bbronisz/trmnl-weather-station) would be lovely and will help others discover this integration too.

![product](https://github.com/bbronisz/trmnl-weather-station/blob/main/docs/product.png?raw=true)

[![Hassfest Workflow Status](https://img.shields.io/github/actions/workflow/status/bbronisz/trmnl_weather_station/hassfest.yaml?label=Hassfest&style=for-the-badge&colorA=000&colorB=fff)](https://github.com/bbronisz/trmnl-weather-station/actions/workflows/hassfest.yaml)
[![hacs Workflow Status](https://img.shields.io/github/actions/workflow/status/bbronisz/trmnl-weather-station/hacs.yaml?label=hacs&style=for-the-badge&colorA=000&colorB=fff)](https://github.com/bbronisz/trmnl-weather-station/actions/workflows/hacs.yaml)
[![Release](https://img.shields.io/github/v/release/bbronisz/trmnl-weather-station?style=for-the-badge&colorA=000&colorB=fff)](https://github.com/bbronisz/trmnl-weather-station/releases)


## What It Does

Send live sensor data (temperature, humidity, and more) to a TRMNL E-Ink display. Works with Netatmo and other Home Assistant-compatible devices with a few simple installation steps.

## Features

- Compatible with temperature, humidity, pressure, wind speed, precipitation
- Custom labels
- Plugin included

## Quickstart Guide

### Step 1: Install custom Integration via HACS

[![Open your Home Assistant instance and open this repository inside the Home Assistant Community Store.](https://my.home-assistant.io/badges/hacs_repository.svg)](https://my.home-assistant.io/redirect/hacs_repository/?owner=bbronisz&repository=trmnl-weather-station&category=integration)

<details><summary>Manual setup instructions</summary>

1. Open Home Assistant and navigate to **HACS > Integrations**.
1. Click the three-dot menu (⋮) in the top-right corner and choose **Custom repositories**.
1. Add this repository URL `https://github.com/bbronisz/trmnl-weather-station` as a **"Integration"** type.

</details>

### Step 2: Fork Recipe to Your TRMNL Playlist

1. **Visit:** https://usetrmnl.com/recipes/46862/install
1. Click `Fork` to add it to your **TRMNL playlist**.
1. Go to your **TRMNL playlist** and locate **Home Assistant Weather Station**.
1. Click `Edit` on the **Home Assistant Weather Station** settings icon.
1. Set the `refresh rate` to **15 minutes** (or whatever suits you best).
1. **Copy** the `Webhook URL`, **you'll need this to complete** the Home Assistant integration.

### Step 3: Setup Home Assistant Integration

After a restart of Home Assistant, this integration is configurable by via
1. `Add Integration` at `Devices & Services` like any core integration.
1. Select `TRMNL Weather Station` and follow the instructions.
1. The `TRMNL Webhook URL` field is the `Webhook URL` you copied earlier.

[![Open your Home Assistant instance and start setting up this integration.](https://my.home-assistant.io/badges/config_flow_start.svg)](https://my.home-assistant.io/redirect/config_flow_start/?domain=trmnl_weather_station)

![product dark](https://github.com/bbronisz/trmnl-weather-station/blob/main/docs/product_dark.png?raw=true)

---

### Home Assistant Setup Demo
**Note:** This recording is from version 0.3 and slightly outdated. The current configuration is simpler and more flexible.

![setup_speedrun](https://github.com/bbronisz/trmnl-weather-station/blob/main/docs/setup/ha_setup_speedrun.gif?raw=true)

---

This is a fork of: [Tilman Griesel's: TRMNL Weather Station](https://github.com/TilmanGriesel/ha_trmnl_weather_station).
