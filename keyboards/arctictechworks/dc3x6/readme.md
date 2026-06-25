# Dactyl Cygnus 3x6

Make example for this keyboard (after setting up your build environment):

`make arctictechworks/dc3x6:default`

or for vial 

`make arctictechworks/dc3x6:vial`

Flashing example for this keyboard:

`make arctictechworks/dc3x6:default:flash`

See the [build environment setup](https://docs.qmk.fm/#/getting_started_build_tools) and the [make instructions](https://docs.qmk.fm/#/getting_started_make_guide) for more information. Brand new to QMK? Start with our [Complete Newbs Guide](https://docs.qmk.fm/#/newbs).

## Bootloader

Enter the bootloader in 2 ways:

* **Physical boot button**: Hold BOOT button down and connect MCU to the PC
* **Keycode in layout**: Press the key mapped to `QK_BOOT` if it is available
