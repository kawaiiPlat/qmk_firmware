# Chalice

A Cheap Alice, powered by a Pro-Micro

* Keyboard Maintainer: [kawaiiPlat](https://github.com/kawaiiPlat/)
* Hardware Supported: Pro-Micro
* Hardware Availability: [None](https://github.com/kawaiiPlat/qmk_firmware/keyboards/kawaii6x3)

Make example for this keyboard (after setting up your build environment):

    make kawaii6x3:default

Flashing example for this keyboard:

    make kawaii6x3:default:flash
    
## Bootloader

Enter the bootloader in 3 ways:

* **Bootmagic reset**: Hold down Escape and plug in the keyboard.
* **Physical reset button**: Briefly press the reset button below the pro-micro.
* **Keycode in layout**: The `RESET` key can be found by holding `FUNC` in between the space bars and pressing `ESC`.

See the [build environment setup](https://docs.qmk.fm/#/getting_started_build_tools) and the [make instructions](https://docs.qmk.fm/#/getting_started_make_guide) for more information. Brand new to QMK? Start with our [Complete Newbs Guide](https://docs.qmk.fm/#/newbs).
