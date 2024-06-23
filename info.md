# Customized DeLonghi PAC N90 AC
This HomeAssistant integration is very specific to my own needs. I built a ESP8266 controller that sends infrared signals to the AC unit. This controller has a REST API, also created by myself.

## Adding the integration

...is currently only possible by editing the configuration.yaml:

```
climate:
  - platform: "delonghi_pac_n90_customized"
    name: "My DeLonghi AC unit"
    base_url: "http://esp-ir-remote.local"
```
