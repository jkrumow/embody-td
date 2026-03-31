# TouchDesigner Embody

TD component to add json filestructure and embedded Model Context Protocol (MCP) server.

## Requirements

- Touchdesigner  >= 2025
- Python 3.11

## Installation

Add this dependency to your `requirements.txt`:

```sh
embody-td @ git+https://github.com/artcom/embody-td.git@0.1.1#egg=embody-td
```

Load the tox into your project:

1. create a baseCOMP
2. Common -> External .tox Path = `mod.mqtt_topping_td.ToxFile`
3. Common -> Enable External .tox = ON
4. Common -> Reload custom parameters = OFF
