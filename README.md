
# Scriptable Widgets

  

Get more widgets at www.scriptables.net

  

## Tankstellen Preise
<img height="200px" src="https://raw.githubusercontent.com/Necriso/ScriptableWidgets/main/images/tankstellenpreise.png" />

- Shows fuel prices, address and station is open or closed from a gas station next to your location
- You need an API-Key from https://creativecommons.tankerkoenig.de/

### Configuration

Configure the widget via widget parameters.

On Homescreen, long tap on widget -> edit widget -> Parameter

Add your credentials as follow:
`API-Key|Radius|fixedLocation (0 or 1)`

Example: `my-api-key|1|0`


If you want a fixed location change the configuration to this:
`API-Key|Radius|fixedLocation|latitude|longitude`

Example: `my-api-key|1|1|54.322|10.1355`

Configuration example:

<img  height="200px" src="https://raw.githubusercontent.com/Necriso/ScriptableWidgets/main/images/tankstellenpreise-config.png"  />

## Günstigste Tankstelle (DE/AT)
<img height="200px" src="https://raw.githubusercontent.com/Necriso/ScriptableWidgets/main/images/guenstigetankstelle_dark.png" />

- Shows open gas stations next to your location with the cheapest price of selected oil type first.

**German Version**
- You need an API-Key from https://creativecommons.tankerkoenig.de/

### Configuration

Configure the widget via widget parameters.

On Homescreen, long tap on widget -> edit widget -> Parameter

Add your credentials as follow:
`API-Key|Radius|fuelType`

Example: `my-api-key|1|diesel`

Supported fuel types are:
- diesel
- e5
- e10

**Austria Version**

### Configuration

Configure the widget via widget parameters.

On Homescreen, long tap on widget -> edit widget -> Parameter

Add your credentials as follow:
`fuelType`

Example: `DIE`

Supported fuel types are:
- DIE
- SUP
- GAS

## OpenWebIf (beta)
  
<img  height="200px" src="https://raw.githubusercontent.com/Necriso/ScriptableWidgets/main/images/openwebif.png"  />


- Connects to OpenWebIf API of your Enigma2 receiver
- Displays current and next program of current viewed channel
