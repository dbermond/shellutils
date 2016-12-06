# shellutils
A small collection of shell scripts. Currently only image utils are available.

- [IMAGE UTILS](#image-utils)
- [LICENSE](#license)


## IMAGE UTILS
POSIX-compliant shell scripts to help running TruePNG and pingo through Wine in Unix-like systems.

TruePNG and pingo are very efficient image optimizers for Windows, being closed source and free of charge. Both of them have visually lossless and lossy modes. TruePNG supports only PNG images while pingo supports PNG and JPG.


### Installation
- Install Wine
- For TruePNG support:
    - Copy truepng helper script to any folder in your PATH and make it executable
    - Copy the file ```TruePNG.exe``` (link provided bellow) to ```/usr/share/truepng```
- For pingo support:
    - Copy pingo helper script to any folder in your PATH and make it executable
    - Copy the file ```pingo.exe``` (link provided bellow) to ```/usr/share/pingo```
- **Note:** The default WINEPREFIX ```$HOME/.wine``` is used to run the programs


### Usage
- ```$ truepng [options] <PNG file(s)>```
- ```$ pingo [options] <PNG/JPG file(s)>```

For a list of options just run without arguments.


### Remarks
TruePNG can be combined with other tools.

A nice combination is to use it with advdef utility that is part of [AdvanceCOMP](http://www.advancemame.it/comp-readme). Run TruePNG before advdef.


### Links
- TruePNG: [http://x128.ho.ua/pngutils.html](http://x128.ho.ua/pngutils.html)

- pingo: [http://css-ig.net/pingo/](http://css-ig.net/pingo/)

- Arch Linux AUR package for TruePNG: [https://aur.archlinux.org/packages/truepng/](https://aur.archlinux.org/packages/truepng/)

- Arch Linux AUR package for pingo: [https://aur.archlinux.org/packages/pingo/](https://aur.archlinux.org/packages/pingo/)

- Wine: [https://www.winehq.org/](https://www.winehq.org/)

- A nice tutorial about TruePNG: [http://css-ig.net/articles/truepng/](http://css-ig.net/articles/truepng/)

## LICENSE
These shell scripts are licensed under the Creative Commons Zero (CC0) 1.0 License.

For details see the file COPYING.