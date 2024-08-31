# XBox Series S/X Wireless Controller

###  Operating System
* Kubuntu 22.04

## Issue
* Bluetooth connection drops after pairing
* Bluetooth connection unstable after successful pairing


## Solution
* Xbox controllers required privacy setting to be set to `device`
* Bluetooth LE requires specific configuration to work properly, the default values in bluez `main.conf` may not be sufficient

[main.conf.patch](./etc/bluetooth/main.conf.diff.patch)