# Quantum Mechanical Keyboard Firmware

## About
this fork hosts my keyboard layouts for qmk, right now targeting only 
the [lily58](https://github.com/kata0510/Lily58)

## Usage
### Pre-requisites:
1. must be at project root
2. must have installed 'qmk' module from pip3
3. must have a working docker install

```
# compile the firmware
./util/docker_build.sh lily58:deloachcd
# flash the firmware, (re)compiling if needed
./util/docker_build.sh lily58:deloachcd:avrdude
```

## If shit breaks with docker or something
Just git rebase from [upstream](https://github.com/qmk/qmk_firmware), pull from
docker hub and cross your fingers.

## links
[flashing](https://docs.qmk.fm/#/newbs_flashing)
