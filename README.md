# my dwm config
patches used: alpha, alwayscenter, fullgaps, gridmode

### make dwm appear on display manager
> vim /usr/share/xsessions/dwm.desktop
```
[Desktop Entry]
Encoding=UTF-8
Name=dwm
Comment=Dynamic window manager
Exec=dwm
Icon=dwm
Type=XSession
```
### dependencies
void 
```
# xbps-install -S make base-devel libX11-devel libXft-devel libXinerama-devel
```

arch
```
# pacman -S make base-devel libx11 libxft libxinerama freetype2 fontconfig
```

debian
```
# apt install make gcc libx11-dev libxft-dev libxinerama-dev xorg
```

alpine
```
# apk add git make gcc g++ libx11-dev libxft-dev libxinerama-dev ncurses dbus-x11
```
