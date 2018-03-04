# Inkscape EggDuino Extension

This Inkscape extension helps you to use the EggDuino based EggBot
from inside Inkscape.

## Installation Linux and OSX
You have to put these two directories inside your ```~/.config/inkscape``` folder.

```bash
curl -L https://github.com/section77/eggbot_extension/archive/1.1.tar.gz | tar -xz
mkdir -p ~/.config/inkscape
cp -r eggbot_extension-1.1/templates ~/.config/inkscape
cp -r eggbot_extension-1.1/extensions ~/.config/inkscape
```

## Installation Windows
You have to unpack the zip file from https://github.com/section77/eggbot_extension/archive/1.1.zip
and copy the templates and extensions folders to the inkscape/share folder which
is typically located at C:\programme\inkscape\share

# Access Rights

Your user need to have access to the serial port. On Linux you have to add
your user to the dialup group. Take a look at the /dev/tty Ports that looks like
the correct arduino port.


## Other Projects Parts

 * [Eggduino Firmware](https://github.com/section77/EggDuino)
 * [Eggbot77 Wiki](https://wiki.section77.de/projekte/eggbot77) (in german)