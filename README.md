spi2neo
=======

spi to neopixel (ws2812) converter.  Designed for the Raspberry Pi.

Convert SPI to neopixel (ws2812) using 74x00 logic.

This kinda-sorta doesn't work.  In theory it does.  In practice it doesn't.
The circuit expects the SPI data stream to be continuous. On the Raspberry Pi there are gaps due to other processes.
