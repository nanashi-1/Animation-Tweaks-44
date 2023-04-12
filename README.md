the same extension, but a few changes have been made for partial compatibility with gnome since version 42. the effects of opening the top panel menu, dash, desktop menu and window menu do not work.

to install, just run the script INSTALL.sh after enabling the script execution permission:

```bash
chmod +x INSTALL.sh
./INSTALL.sh
```

if you are too lazy to customize the animations yourself, then you can try my config for the extension. to install the config, enter the following command by opening the terminal in the folder with the ``.dconf`` file:

```bash
dconf load /org/gnome/shell/extensions/animation-tweaks/ < animations-set.dconf
```
