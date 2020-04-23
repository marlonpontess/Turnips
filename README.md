# Turnips
Turnip prices previewer for Animal Crossing: New Horizons.

DISLAIMER: This reads data from your save. I am not responsible for any data loss, consider backing up before use.

<p align="center"><img src="https://i.imgur.com/zhyOTG8.jpg" </p>

# Compiling
Building needs a working devkitA64 environment, with packages `libnx`, `switch-mesa` and `switch-libdrm_nouveau` installed (`sudo (dkp-)pacman -S switch-dev switch-mesa switch-libdrm_nouveau`).
```
$ git clone --recursive https://github.com/averne/Turnips.git
$ cd Turnips
$ make -j$(nproc)
```
Output will be located in out/.

# Credits
- The [NHSE](https://github.com/kwsch/NHSE) project for save decrypting/parsing.
- [Cianuro](https://twitter.com/CianuroArts) for the [background](https://twitter.com/CianuroArts/status/1245790634352480260).
