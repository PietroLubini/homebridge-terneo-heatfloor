# homebridge-terneo-heatfloor
Homebridge plugin for Terneo floor heaters http://terneo.ua/ which work
with local API and doesnt require terneo cloud access.

![Demo 1](images/IMG_7583.PNG)![Demo 2](images/IMG_7584.PNG)![Demo 3](images/IMG_7585.PNG)

# Installation

1. Install homebridge using. Please refer to official documentation how to do it.
2. Install this plugin using: npm install -g homebridge-terneo-heatfloor
3. Update your configuration file

# Configuration

Add to your configuration file:

```
{
    "accessory": "TerneoHeatfloor",
    "name": "Теплый пол",
    "ip": "192.168.1.90",
    "serial": "160025001143504D3130342D000159"
}
```

- `accessory` – always must be "TerneoHeatfloor"
- `name` – give a name for this accessory
- `ip` – ip address of your device
- `serial` – serial number of your device

## Where i can get ip address?

Please refer to terneo official documentation how to obtain ip address of your device.
You also can obtain it on your router.

## Where i can get serial number of my device?

When you obtain ip address, open in your browser address `http://<ip>`, for example
`http://192.168.1.90`

![Obtain serial number](images/sn.png)

Copy long line of text in `S/N`

# Policy

The author is not responsible for the use and consequences of use of this software.

License
----

MIT