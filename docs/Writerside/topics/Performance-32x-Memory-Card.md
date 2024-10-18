# Performance 32x Memory Card

This is a much more engineered version of the memory card, utilzing a lot more electronics, and two 7 segment displays
to show what card you're on.

Switching between cards if done by the "largest" dot which is the only button on it, it can be clicked to go to
the next, or held to scroll through and release when it reaches which number is desired. After a new number
is selected it will display "--" as it loads the saved memory into the SRAM chip.


### Board
The main storage of this is unknown at this point, it utilizes two custom Datel
silicon chips, one is an ASIC. It has an SRAM, shift registers, and a microcontroller

#### Hardware Specs

    Ram chip:  Hynix GM76C256C 
    32K x8 bit 5.0V Low Power CMOS slow SRAM

    Microchip PIC16C57
    EPROM/ROM-Based 8-bit CMOS Microcontroller Series

    2x Fairchild MM74HC164
    8-Bit Serial-in/Parallel-out Shift Register

    Fairchild MM74HC00
    Quad 2-Input NAND Gate

    Datel D080 SL744

    Datel ASIC4

| ![p32x_case_front.jpg](..%2Fimages%2Foriginal%2Fpreformance-32x%2Fp32x_case_front.jpg) | ![p32x_case_back.jpg](..%2Fimages%2Foriginal%2Fpreformance-32x%2Fp32x_case_back.jpg)     |
|----------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------|
| ![p32x_board_back.jpg](..%2Fimages%2Foriginal%2Fpreformance-32x%2Fp32x_board_back.jpg) | ![p32x_board_front.jpg](..%2Fimages%2Foriginal%2Fpreformance-32x%2Fp32x_board_front.jpg) |

![p32x_screen.jpg](..%2Fimages%2Foriginal%2Fpreformance-32x%2Fp32x_screen.jpg)


