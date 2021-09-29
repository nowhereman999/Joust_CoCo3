# Joust for the CoCo 3 - Requires 512k

This is a conversion of William's arcade classic video game Joust for the Tandy Color Computer 3.

If you are going to use it please read the following, to get he most out of the game:

**Important**

Once you're done playing Joust don't turn off your CoCo.  To save your settings and scores while still in the game press `BREAK` and
the game will exit back to BASIC but the scores and other data are still in RAM.  To save it to disk for future use type:
`RUN"SAVE" [ENTER]`

To start playing a game simply type:
`RUN"JOUST" [ENTER]`

Controls for the game are the same as MAME:

* Insert a coin - 5
* Start a one player game - 1
* Start a two player game - 2
* Default player controls are:
* Player 1 Flap  - C
* Player 1 Right - S
* Player 1 Left  - A
* Player 2 Flap  - /
* Player 2 Right - L
* Player 2 Left  - K

Use the config program as described below to either select which keys are used for the players controls or to select Joystick mode.

To configure or reset all the settings of the game type:
`RUN"CONFIG" [ENTER]`

I’d like to thank Einar Saukas for his cool ZX0 compressor and Doug Masten for porting the decompressor code to 6809 assembly and sharing it for us all to use.

Enjoy Joust on the CoCo 3,
Glen Hewlett

History:

V1.0 - Initial realease

V1.1 - Added a CLR $FF40 as per Doug Masten, to shut off the drive motor just before game starts
