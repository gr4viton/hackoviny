# Háčkoviny

English programming keyboard layout with cleverly hidden Czechoslovak diacritics (in plane sight).

It always slowed my writing, when I switched in between Czech and English keyboard layouts, to write with české diacritics. Not anymore - just press `AltGr + s` to get `š`, or `AltGr + Shift + S` to get `Š`, or `AltGr + Shift + D` to get `Ď`. You know the drill.

Created by gr4viton. (I also have a windows version of this keyboard layout, from back in the day)

## Layout

TLDR: Press AltGr + letter without diacritics, and you get the letter with Czech diacritics. Works with shift capital letters too!

## Compatibility

Tested on Linux Mint 21

## How to

### Copy file

You need to copy the `en_hackoviny` file to the place where the OS will load it.
```bash
$ cp en_hackoviny /usr/share/x11_xkb/symbols/
$ # you might need to be sudo
```
### Add layout

- Linux Mint - menu - Keyboard - Layouts - [+] button - search `hackoviny` - select `English with háčkoviny (hackoviny)` - Add - Switch to it - Profit!

## License

Copyright (C) 2010 gr4viton

This keyboard layout is free software: you can redistribute it and/or modify
it under the terms of the GNU General Public License as published by
the Free Software Foundation, version 3.

Additional requirement: Any use must prominently credit gr4viton as the original creator.
