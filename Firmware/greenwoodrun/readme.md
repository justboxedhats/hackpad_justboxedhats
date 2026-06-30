# greenwoodrun

![greenwoodrun](https://stardance.hackclub.com/rails/active_storage/representations/proxy/eyJfcmFpbHMiOnsiZGF0YSI6ODgwMjYsInB1ciI6ImJsb2JfaWQifX0=--e0548889f35583d35e75255e97b77b4e81a7b806/eyJfcmFpbHMiOnsiZGF0YSI6eyJmb3JtYXQiOiJ3ZWJwIiwicmVzaXplX3RvX2xpbWl0IjpbMTYwMCw5MDBdLCJzYXZlciI6eyJzdHJpcCI6dHJ1ZSwicXVhbGl0eSI6NzV9fSwicHVyIjoidmFyaWF0aW9uIn19--3bc8a2c9d65e3b087c0c0b37dcfb642bb247bc73/Screenshot%202026-06-27%20154357.png)

A 4x2 microboard powered by a MOUDLE-SEEEDUINO-XIAO   


* Keyboard Maintainer: [Justin Fernandez](https://github.com/justboxedhats)
* Hardware Supported: *The PCBs, controllers supported*
* Hardware Availability: *Links to where you can find this hardware*

Make example for this keyboard (after setting up your build environment):

    make greenwoodrun:default

Flashing example for this keyboard:

    make greenwoodrun:default:flash

See the [build environment setup](https://docs.qmk.fm/#/getting_started_build_tools) and the [make instructions](https://docs.qmk.fm/#/getting_started_make_guide) for more information. Brand new to QMK? Start with our [Complete Newbs Guide](https://docs.qmk.fm/#/newbs).

## Bootloader

Enter the bootloader in 3 ways:

* **Bootmagic reset**: Hold down the key at (0,0) in the matrix (usually the top left key or Escape) and plug in the keyboard
* **Physical reset button**: Briefly press the button on the back of the PCB - some may have pads you must short instead
* **Keycode in layout**: Press the key mapped to `QK_BOOT` if it is available
