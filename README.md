## black-min: rEFInd theme

This repository represents my current bootloader theme.

## Usage

1. Copy the entire folder into your rEFInd directory within your EFI partition. (/boot/EFI/refind)
2. Copy the black-min-theme.conf to your rEFInd directory within your EFI partition.
3. Edit your refind.conf file to include the black-min-theme.conf file and comment out any other include <theme.config> lines.

Since rEFInd has no mechanism for a primary title, the title has been baked into the banner (background) file. The .xcf file can be modified and used as
background with a nametag.

## Attribution

This theme was inspired by [rEFInd-minimal](https://github.com/EvanPurkhiser/rEFInd-minimal/), [dream-machine](https://github.com/Lindstream/dm-refind-theme/) and [my-rEFInd-theme](https://github.com/initramfs/rEFInd-Theme). I tweaked and combined elements of all three in the black-min theme.


**Icons:** [Lightness for burg][icons] by [SWOriginal][icon-author] and [icons8.com](https://icons8.com/)

[icons]: http://sworiginal.deviantart.com/art/Lightness-for-burg-181461810
[icon-author]: http://sworiginal.deviantart.com/
