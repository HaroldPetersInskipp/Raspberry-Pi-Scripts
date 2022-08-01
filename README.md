# Raspberry-Pi-Scripts
Scripts for use with Raspberry Pi devices

## Install unofficial-builds of Node.js for Node-RED
Armv6lNodeX.X.X.sh will install node.js version X.X.X on Arm6 based Raspberry Pi devices, such as the Pi Zero W. This may work on other devices, but is untested.

Or run one of the below commands:

### Node v16.6.1
```sh
$ wget -O - https://raw.githubusercontent.com/HaroldPetersInskipp/Raspberry-Pi-Scripts/main/Armv6lNode16.6.1.sh | bash
```
### Node v16.11.1
```sh
$ wget -O - https://raw.githubusercontent.com/HaroldPetersInskipp/Raspberry-Pi-Scripts/main/Armv6lNode16.11.1.sh | bash
```
### Node v16.16.0
```sh
$ wget -O - https://raw.githubusercontent.com/HaroldPetersInskipp/Raspberry-Pi-Scripts/main/Armv6lNode16.16.0.sh | bash
```

### Important
If you get an error like `/usr/bin/env: 'node-red-pi': No such file or directory` when you try to start Node-RED.

Run `sudo ln -s /opt/nodejs/lib/node_modules/node-red/bin/node-red-pi /usr/bin/node-red-pi` to fix it. Otherwise ignore this.
