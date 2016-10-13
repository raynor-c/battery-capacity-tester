# battery-capacity-tester
Tests the mAh capacity of NiMH, NiCAD, and Li Ion cells

Original project used a Nokia 5110 screen.

I modified the code slightly to use an I2C 20x4 LCD screen.

Working on more code modifications:

    Remove the button polling and replace with rising or falling edge interrupt.
    Reduce the amount of delay calls, while retaining the functionality and LCD readability.
