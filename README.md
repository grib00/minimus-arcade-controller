# USB game controller 

Based on: 

[Minimus AVR USB 32](https://github.com/grib00/minimus-toys/blob/master/doc/README.md)

[LUFA](http://www.fourwalledcubicle.com/LUFA.php)

## Button / input mapping

| Button  | Port   | Code   | Color  |
|---------|--------|--------|--------|
| 1 up    | B0     | up     | purple |
| 1 down  | B1     | down   | orange |
| 1 left  | B2     | left   | yellow |
| 1 right | B3     | right  | brown  |
| 1 but1  | B4     | ctrl   | grey   |
| 1 but2  | B7     | alt    | white  |
| 2 up    | D0     | R      | purple |
| 2 down  | D1     | F      | orange |
| 2 left  | D2     | D      | yellow |
| 2 right | D3     | G      | brown  |
| 2 but1  | D4     | Q      | grey   |
| 2 but2  | D7     | S      | white  |
| COIN    | B6     | 5      | copper |

## Build and flash

    git clone https://github.com/abcminiuser/lufa.git
    git clone https://github.com/grib00/minimus-arcade-controller.git
    cd minimus-arcade-controller
    make

Plug minimus and prepare to flashing

    sudo make flash

## See also

Similar project: https://www.youtube.com/watch?v=UwCsVCvL0es https://sites.google.com/site/degenatrons/controller-interfaces/usb-keyboard-encoder

