# grub2-theme-fallout

Grub2 theme aka Fallout terminal interface

![Screenshot](_img/Screenshot.png)

## Installation

You can download source-code, pack it with .tar.gz and apply it with [grub-customizer](https://launchpad.net/grub-customizer)

## Tuning

### Font size

You can change font size on your taste just call
```
  grub-mkfont -o ./fixedsys-regular-${your_size}.pf2 -s ${your_size} ./raw_font.ttf
```
with desired size instead of placeholder.
Then edit `theme.txt` substituting `*-font: "Fixedsys Regular 32"` with `*-font: "Fixedsys Regular ${your_size}"`

### Icons color

If you want white colored icons just copy with replacement all files from `./icons_white` into `./icons`
Or you can change the color of icons with any graphic editor you have.
