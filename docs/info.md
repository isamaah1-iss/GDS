<!---

This file is used to generate your project datasheet. Please fill in the information below and delete any unused
sections.

You can also include images in this folder and reference them in the markdown. Each image must be less than
512 kb in size, and the combined size of all images must be less than 1 MB.
-->

## How it works

And and Nand gate connected to input a and input b
Or gate connected to input a and input c
16 flipflops are used to divide the clock speed with 2 outputs, one at 12th flip flop and another at 16th flipflop

## How to test

input a, b, c | output and  | output nand  | output or
000           |   0         |     1        |     0    
001           |   0         |     1        |     1
010           |   0         |     1        |     0 
011           |   0         |     1        |     1
100           |   0         |     1        |     1 
101           |   0         |     1        |     1 
110           |   1         |     0        |     1 
111           |   1         |     0        |     1

set clock to 10khz output 4 flshing quickly output 5 flashing slowly 
## External hardware

List external hardware used in your project (e.g. PMOD, LED display, etc), if any
output 4 and 5 connected to separate LED
