# i3gaps
my own i3-gaps config files, for Arch.

Use compton for transparency, urxvt or xfce4-terminal or terminator for the terminal, and make sure the config file has the keybind set to launch the right terminator when you press your mod key+enter.

use nitrogen to set and change desktop backgrounds, and use rofi as the program launcher. use wicd-curses as a terminal based wifi manager, and use fontawesome (downgraded version if necessary) for the taskbar segments which you define in the i3blocks conf. make sure the i3 config is set up to use i3blocks rather than i3status.

the actual blocklets for i3blocks themselves are defined in /usr/lib/i3blocks, so if the i3bar looks wrong when importing the i3blocks configs, check those. However i haven't changed them myself I don't think. The custom blocklets simply use available commands and font icons which don't have to be in separate bash scripts (I believe).
