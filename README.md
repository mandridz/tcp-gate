

# tcp-gate
Supports TCP commands on the HomeBridge platform.


## Installation
1. Install homebridge using: npm install -g homebridge
2. Install this plugin using: npm install -g homebridge-tcp-gate
3. Update your configuration file. See sample-config.json in this repository for a sample.


## Configuration
"accessories": [
 {
  "accessory": "tcp-gate",
  "address": "127.0.0.1",
  "port": 1234
 }
]
