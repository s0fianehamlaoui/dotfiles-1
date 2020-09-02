## Installation
1. Put all fonts in the **fonts** folder to */usr/share/fonts/*
2. Put **slim.conf** into */etc/*
3. put the **custom** folder to */usr/share/slim/themes/*
4. Create symbolic link for slim background to *~/.wallpaper/slim.png* \
   `sudo ln -s ~/.wallpaper/slim.png /usr/share/slim/themes/custom/background.png`

## Additional configuration
> Edit the **slim.conf** file
- Screenshots
  `screenshot_cmd      scrot -e 'mv $f /home/*username*/Pictures/'`
  
Slim requires *~/ .xinitrc* to execute WM/DE sessions
More information is available on the [Arch Wiki](https://wiki.archlinux.org/index.php/SLiM).
