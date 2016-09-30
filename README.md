# stm32f10x_HAL
Hardware Abstraction Library for stm32f10x devices using CMSIS Core.

This project is supposed to be an educational project for myself, 
to become a better person working with low level coding and datasheets.

Tips and advices are welcome :)

## Using it

At this point is as easy as:

1. Clone this repository
2. Do some macig with `main.c`
3. Edit `Makefile` to fit it to your needs. 
  * modify your project name!
  * modify your toolchain directory and/or prefix (`arm-none-eabi` by default)
  * modify flags `C_DEFS` and `CXX_DEFS` to select your device (stm32f100rb by default)
4. Run `make all` to build all it up.

There are also `make flash` and `make debug` scripts in `Makefile`, which are the ones 
I use for my STM32VLDISCOVERY board. Change them to suit your needs as well.

## Credits

[@n0p](https://twitter.com/@n0p) for the Discovery board :)

[Freddie Chopin](http://www.freddiechopin.info/), whose example codes are the ones
that made me figure out how to bare-metal without an IDE.

