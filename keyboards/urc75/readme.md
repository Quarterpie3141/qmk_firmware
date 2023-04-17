# urc75

![urc75](https://imgur.com/a/z8LUGDC)

A modular keyboard made by and for URC members, more submodules arriving soon:)

* Keyboard Maintainer: [Prashan Wijesinghe](https://github.com/Quarterpie3141)
* Hardware Supported: URC75 pcb v1.10 onwards, rp2040
* Hardware Availability: Hardware is given on a case by case basis, head on down to URC and talk to one of out committe members to get started

Make example for this keyboard (after setting up your build environment):

    make urc75:default

Flashing example for this keyboard:

    make urc75:default:flash

See the [build environment setup](https://docs.qmk.fm/#/getting_started_build_tools) and the [make instructions](https://docs.qmk.fm/#/getting_started_make_guide) for more information. Brand new to QMK? Start with our [Complete Newbs Guide](https://docs.qmk.fm/#/newbs).

## Bootloader

Enter the bootloader in 3 ways:

* **Bootmagic reset**: Hold down the key at (0,0) in the matrix (usually the top left key or Escape) and plug in the keyboard
* **Physical reset button**: Briefly press the button on the back of the PCB - some may have pads you must short instead
* **Keycode in layout**: Press the key mapped to `QK_BOOT` if it is available
