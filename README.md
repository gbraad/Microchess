# Microchess
Peter Jennings' Microchess for the 6502


### Kim-1 simulation

To try Microchess, download the program by right clicking the link below and choosing Save Target As:

[Microchess for Soft6502](microchess.h65)

  * Unzip and run the [Soft6502 simulator](http://www.crbond.com/download/soft65.zip).
  * Load the code file ( File | Load | microchess_1_soft6502.h65)
  * Select `0x0000` as the starting address or key in **AD** `0000`
  * Press **GO** to run the program
  * Press **C** to reset the board
  * Press **PC** to make the program play the first move (`1333` P-K4)
  * Press `6343` to respond with your move (P-K4)
  * Press **PC** to tell the computer to play

Read the [complete manual](microchess.html) to understand the board layout and program commands. Because the simulation works slightly differently from the Kim-1, it is necessary to watch the OUT LEDs on the left. When the program is expecting user input, the LEDs will be lit.

With the speed slider at full speed, the simulation will be faster than the original Kim on a new PC.

To make the program play itself, alternate between **E** to exchange sides and **PC** to play.

Many thanks to Charles Bond for adapting the simulator to handle the ROM routines for I/O and debugging the OCR code and making Microchess work.

From: https://www.benlo.com/microchess/
