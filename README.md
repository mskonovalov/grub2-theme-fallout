# grub2-theme-fallout


[![Version][version img]][version]
[![Download][download img]][download]
[![][license img]][license]

Grub2 theme aka Fallout terminal interface

![Screenshot](preview.png)

## Installation

You can download [grub2-theme-fallout.tar.gz][download] and apply it with [grub-customizer](https://launchpad.net/grub-customizer)

## Tuning

### Font size

You can change font size on your taste just call the following command with desired size instead of placeholder:
```
  grub-mkfont -o ./theme/fixedsys-regular-${your_size}.pf2 -s ${your_size} ./raw_font.ttf
```

Then edit `theme/theme.txt` substituting `*-font: "Fixedsys Regular 32"` with `*-font: "Fixedsys Regular ${your_size}"`

### Icons color

If you want white colored icons just copy with replacement all files from `theme/icons_white` into `theme/icons`.
Or you can change the color of icons with any graphic editor you like.


[version]:../../releases/tag/1.0
[version img]:https://img.shields.io/badge/version-1.0-blue.svg
[download]:../../releases/download/1.0/grub2-fallout-theme.tar.gz
[download img]:https://img.shields.io/badge/download-.tar.gz-brightgreen.svg
[license]:LICENSE
[license img]:https://img.shields.io/badge/License-MIT-blue.svg
