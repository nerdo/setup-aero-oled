# setup-aero-led
A shell script for setting up the Gigabyte Aero OLED laptop in Pop!_OS.

## Pre-requesites:
* Gigabyte Aero OLED laptop
* Pop!_OS 19.04
* An Internet connection through the ethernet port, since the Killer AX1650x WiFi module does not work out of the box at the time of this writing. I actually used my iPhone hotspot connected over USB to do the initial setup.

It is untested on other Ubuntu distributions, but it _should_ work for Ubuntu 19.04.

This script addresses:
* Killer AX1650x WiFi
* OLED brightness adjustment
* Laptop bluetooth sleep fix
* Synaptics drivers for trackpad and a fix for the overly sensitive edges while typing

## Usage
```
./setup-aero-oled
```

The script will ask for your root password to perform some operations.

I highly recommend taking a look at the script to understand exactly what it is doing. There's no magic here, just a list of things that have been addressed in using the Aero OLED in Linux.
