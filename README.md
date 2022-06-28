# Usage
```sh
$ git clone https://github.com/void-linux/void-packages
$ cd void-packages
$ git clone https://github.com/monke0192/eww-template
$ ./xbps-src binary-bootstrap
$ cp -r eww-template/eww srcpkgs/eww # for Xorg & X11
$ cp -r eww-template/eww-wayland srcpkgs/eww # for wayland users
$ ./xbps-src pkg eww
```
# Installation
If you have `xtools` installed, run
```
$ xi eww
```
else, run
```
# xbps-install -R hostdir/binpkgs eww
```
