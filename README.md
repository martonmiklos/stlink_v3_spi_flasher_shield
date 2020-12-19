## STLinkV3 SPI flasher shield - Untested

![Board top view](https://raw.githubusercontent.com/martonmiklos/stlink_v3_spi_flasher_shield/master/docs/top.png)
![Board bottom view](https://raw.githubusercontent.com/martonmiklos/stlink_v3_spi_flasher_shield/master/docs/bottom.png)

Drawn in EAGLE 9.x

Due to the fact that a socket and a wide SOIC8 footprint is added the signal integrity is something what we should not talk about.
If something fails use lower SPI speeds.

Socket used: cheapest SOIC socket found ebay equipped with (an obviously counterfeit) OTS-16-03 SOIC8 socket.

https://www.waveshare.com/datasheet/Test_Socket_PDF/SOP/SOP_Enplas.pdf

## Recommended flashing software

[flashrom](https://www.flashrom.org/Flashrom) supports this programmer since the 1.2 release
