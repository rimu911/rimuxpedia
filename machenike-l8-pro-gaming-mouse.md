# Machenike L8 Pro Gaming Mouse

### Operating System
* Kubuntu 22.04

## Issue:
* Keyboard behaves erratically when Machenike L8 Pro Gaming mouse is connected wired or wirelessly


## Solution
* Disable detected keyboard via udev rules

[99-disable-machenike-l8-pro-virtual-keyboard.rules](./etc/udev/rules.d/99-disable-machenike-l8-pro-virtual-keyboard.rules)