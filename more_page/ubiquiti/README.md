## Ubiquiti UniFi 
## More_page for dwains-theme
##### Created by Ruben Dijk
---

### Installation (dwains-theme)
- Install [Unifigateway](https://github.com/custom-components/sensor.unifigateway) from [HACS](https://hacs.xyz).
- Manually install the next custom component from https://github.com/RubenDijk/homeassistant
- Copy the my_unifi to your custom component folder.
- Copy the file `unifi.yaml`  to your `<config dir>/dwains-theme/addons/more_page/ubiquiti` directory.
- Configure your `more_page.yaml` file in `<config dir>/dwains-theme/configs` with config below.
- Add unifi controller (Home-Assistant integration)
- Restart Home Assistant.

### Usage
To use this add-on in your Dwains Theme, add the following to your `more_page.yaml` file:

````yaml
# Example more_page.yaml entry
more_page:
    addons:
      - name: Ubiquiti UniFi
        icon: 'mdi:router-network'
        path: 'dwains-theme/addons/more_page/ubiquiti/unifi.yaml'
````
Add the following sensors to your config [Sensors](https://github.com/RubenDijk/dwains-theme-addons/blob/master/more_page/ubiquiti/sensors.md/)

### Screenshots:
**Light theme:**<br>
![light](https://github.com/RubenDijk/dwains-theme-addons/blob/master/more_page/ubiquiti/Unifi%20light_mode.png "Light")

---

**Dark theme:**<br>
![dark](https://github.com/RubenDijk/dwains-theme-addons/blob/master/more_page/ubiquiti/Unifi%20dark_mode.png "Dark")

### Links:
* https://github.com/dwainscheeren/lovelace-dwains-theme
* https://www.home-assistant.io/integrations/unifi/
* https://hacs.xyz/
* https://github.com/RubenDijk/homeassistant

#### 1.0.0
- First release
#### 1.0.1
- Add new sensors for the Wan card and Wlan card
- Add custom slider card
- Add icons for sensors
- Add buttons to your webpage of the controller, Alerts gateway and Firmware update
- Change positions sensor Wan and WWW

---

If you like my work please feel free to buy me a coffee

<a href="https://www.buymeacoffee.com/RubenDijk" target="_blank"><img src="https://www.buymeacoffee.com/assets/img/custom_images/white_img.png" alt="Buy Me A Coffee"></a>
