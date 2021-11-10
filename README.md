## OpenFFBoard Motor Encoder Interface

See <https://github.com/Ultrawipf>

This board connects to the encoder interface pins on the TMC board.
There is a provision on the PCB to run from either 5v or 3.3V.

Probably the pull-up resistors, filter caps & inline resistors are
no longer required on the TMC board.

If running from 3.3V then the level shifters on the TMC board are not
required either. These will need to have solder bridges across the
relevant pins.

Produced with [Kicad 5.1](https://www.kicad.org)

![PCB image](https://github.com/jonlidgard/OpenFFboard_Encoder_Interface/blob/master/RS422.png)


### Version History
V1.0  - 14/04/20  - Initial release.
