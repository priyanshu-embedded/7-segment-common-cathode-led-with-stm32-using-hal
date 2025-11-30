This project shows how to display decimal values on a multiplexed 7-segment display using STM32 HAL. A digit's segments are encoded into a byte (or uint8_t) where each bit corresponds to one segment (A..G + DP). We use bit extraction (mask & shift) to set GPIO pins for each segment quickly and clearly.

Advantages:

Clear mapping digit → segments.

Compact, maintainable code.

Easy to extend (alpha, custom patterns).

Works with any HAL-supported STM32 microcontroller.

##hardware Requirement
stm32
7 segment commom cathode display
7 220 resistor



