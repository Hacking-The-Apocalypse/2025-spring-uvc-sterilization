## ESPHome Project

I'm a big fan of ESPHome - it's a nice tech stack for building small devices that use the Espressif ESP code

## Setting up ESPHome
```
python3 -m venv .venv
source .venv/bin/activate
pip3 install esphome
```

## Deploying the Project

ESPHome will deploy to the hardware. The first time this will require a direct USB connction, but subsequent requests can run OTA as long as the computer and ESP are on the same network

```
esphome run uvc.yaml
```
