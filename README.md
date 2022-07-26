# Raspberry-Pi-Scripts
Scripts for use with Raspberry Pi devices

## Install unofficial-builds of Node.js
Armv6lNodeX.X.X.sh will install node.js version X.X.X on Arm6 based Raspberry Pi devices, such as the Pi Zero W. This may work on other devices, but is untested.

### Important
If you get an error like `/usr/bin/env: 'node-red-pi': No such file or directory` when you try to start Node-RED.

Run `sudo ln -s /opt/nodejs/lib/node_modules/node-red/bin/node-red-pi /usr/bin/node-red-pi` to fix it. Otherwise ignore this.