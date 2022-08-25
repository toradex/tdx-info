# tdx-info #

## Objective ##
Script to get useful information about Toradex Hardware.
The goal of this script is to run it once and get useful information about hardware and software.

## Usage ##

Usage: ./tdx-info [OPTION]

* If no parameter was passed, this script will display hardware and software information by default.
* --bootloader, -b   : Display bootloader related information (U-Boot and GRUB only).
* --devices, -d      : List all devices in /dev/.
* --device-tree, -dt : Display device tree and overlays related information.
* --dmesg, -dm       : Export the dmesg output in a txt file at ~.
* --hardware, -w     : Display only hardware information.
* --help, -h         : Display this message.
* --no-devices, -nd  : Display hardware and software information without listing devices.
* --software, -s     : Display only software information.
* --all, -a          : Display all information shown above without the dmesg log.
