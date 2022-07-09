# Elston's ESPHome Setup

This repo contains the config files of all my ESPHome devices, that will be integrated with Home Assistant.

## Description

This is a work in progress.

## Getting Started

### Dependencies and Components

- Python 3.10
- Poetry
- NodeMCUv2 (ESP8266)

### Installing

To set up, run the following command:

```
$ poetry install
```

This will install all the dependencies needed in the pyproject.toml file.

### Executing program

#### Steps to run irrf-remote

- Connect the NodeMCU to your device to get ready to flash the firmware.
- Run the folllowing command:

```
esphome run irrf-remote/elstonb_irrfremote.yaml
```

## Authors

[Elston Aw](mailto:elston@elstonayx.co?subject=[GitHub]%20Elston-ESPHome)

## Acknowledgments

- [Reverse Engineering RF Remote Controller Instructables](https://www.instructables.com/Reverse-Engineer-RF-Remote-Controller-for-IoT/)
