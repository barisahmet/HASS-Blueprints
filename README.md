# HASS-Blueprints

Personal Home Assistant blueprints.

## Overview

This repository contains a collection of personal Home Assistant blueprints designed to simplify and enhance your smart home automations. Each blueprint provides ready-to-use automation logic for common scenarios.

---

## Motion Lights with mmWave Sensor

**Blueprint file:** [`motion-lights-mmwave.yaml`](https://github.com/barisahmet/HASS-Blueprints/blob/main/motion-lights-mmwave.yaml)

**Home Assistant Blueprint Import Link:**  
[![Import Blueprint](https://my.home-assistant.io/badges/automation.svg)](https://my.home-assistant.io/redirect/blueprint_import/?repository_url=https://github.com/barisahmet/HASS-Blueprints/blob/main/motion-lights-mmwave.yaml)

Automate lighting using a mmWave motion sensor for precise and reliable presence detection. This blueprint allows lights to turn on when motion is detected and off after a user-defined delay, leveraging the advanced capabilities of mmWave technology.

### Features

- Automatic light control based on mmWave motion detection
- Configurable delay before turning lights off
- Works with any Home Assistant-compatible mmWave sensor and smart lights
- Easy setup through the Home Assistant UI

### Requirements

- Home Assistant (latest version recommended)
- Integrated mmWave motion sensor
- Supported smart lights or switches

### Installation

1. Click the **Import Blueprint** button above, or manually download/copy [`motion-lights-mmwave.yaml`](https://github.com/barisahmet/HASS-Blueprints/blob/main/motion-lights-mmwave.yaml) to your Home Assistant `/config/blueprints/automation/` directory.
2. In Home Assistant, go to **Settings > Automations & Scenes > Blueprints**.
3. Click **Import Blueprint**, then select or paste the YAML file.
4. Create a new automation based on this blueprint and configure the required entities (motion sensor, target lights, delay time).

### Inputs

- **Motion Sensor:** Select your mmWave binary_sensor entity.
- **Target Lights:** Choose which lights or switches to control.
- **No Motion Wait:** Set the duration to wait after no motion is detected before turning off the lights.

### Example Usage

1. Go to Automations > Create Automation > Start with a Blueprint.
2. Select “Motion Lights with mmWave Sensor.”
3. Fill in your motion sensor, lights, and delay duration.

---

## License

This repository is released under the [MIT License](LICENSE).
