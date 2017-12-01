# MIDI-Patchbay
This project contains hardware and firmware for a 4x4 MIDI
merger/splitter patchbay based on an Arduino MEGA 2560.
It has 4 MIDI inputs and 4 MIDI outputs.  In the
simplest case, it will merge all 4 inputs and then split the combined
MIDI stream across the 4 outputs.  However the routing is controlled by
the firmware so you can configure it to patch any combination of inputs
into any of the outputs.

# Table of contents
* [Hardware](#hardware)
* [Firmware](#firmware)
* [Warning](#warning)

## Hardware:

The [hardware](https://github.com/abw/MIDI-Patchbay/blob/master/hardware)
directory contains Eagle schematics, board designs and Gerber files for
the following modules.

* [MIDI-Patchbay-Shield](https://github.com/abw/MIDI-Patchbay/blob/master/hardware/MIDI-Patchbay-Shield)
is a shield for an Arduino MEGA 2560 that provides 4 MIDI inputs, 4 MIDI
outputs and connectors for interfacing to the
[MIDI-Patchbay-Display](https://github.com/abw/MIDI-Patchbay/blob/master/hardware/MIDI-Patchbay-Display)
board.  It also contains connectors for accessing 8 analog pins and 8
digital pins for further expansion.
* [MIDI-Patchbay-Display](https://github.com/abw/MIDI-Patchbay/blob/master/hardware/MIDI-Patchbay-Display)
is a board for mounting a 16x2 LCD display and two RGB rotary encoders.
This is an optional extra.  You can build a fully functioning MIDI
merger/splitter without it.
* [MIDI-Patchbay-Simple](https://github.com/abw/MIDI-Patchbay/blob/master/hardware/MIDI-Patchbay-Simple)
is the predecessor of the [MIDI-Patchbay-Shield](https://github.com/abw/MIDI-Patchbay/blob/master/hardware/MIDI-Patchbay-Shield).
This is a reduced size shield for the Arduino MEGA 2560 that only has 4
MIDI inputs and 4 MIDI outputs, along with the relevant circuitry to
support it.  If you just want a simple MIDI merge/splitter without any
extra frills then this is the simplest option.

## Firmware:

Coming soon

## Warning:

These are new designs that haven't been fully tested yet.  Use them at
your own risk.
