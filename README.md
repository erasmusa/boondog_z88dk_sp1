# Boondog Z88DK & SP1

This is a ZX Spectrum remake of the free Windows game [Boondog](https://boondog.en.uptodown.com/windows) done with z88dk + sp1 for the zx spectrum.

# To build this for Windows

Just run make.bat and the result should be in the build directory.

# To build this using Docker

1. First of all you must have GNU make installed. 
2. Secondly you must have docker and docker-compose installed.

Simply run `make` or `make z88dk-breakout` to build the game. The resulting `.tap` file will be in the `build` directory and a .map in the `maps` directory. This build uses the SDCC compiler as opposed to the SCCZ80.

[Z88DK Docker Usage Reference Material](https://github.com/z88dk/z88dk/wiki/Docker-Usage)

# References
[z88dk_sp1_breakout](https://github.com/antoniocmateus/z88dk_sp1_breakout)
z88dk forums
World of Spectrum forums

# Kudos
Antonio Mateus for his well documented [z88dk_sp1_breakout](https://github.com/antoniocmateus/z88dk_sp1_breakout) game source code.
