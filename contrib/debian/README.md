
Debian
====================
This directory contains files used to package ichibacoind/ichibacoin-qt
for Debian-based Linux systems. If you compile ichibacoind/ichibacoin-qt yourself, there are some useful files here.

## ichibacoin: URI support ##


ichibacoin-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install ichibacoin-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your ichibacoinqt binary to `/usr/bin`
and the `../../share/pixmaps/ichibacoin128.png` to `/usr/share/pixmaps`

ichibacoin-qt.protocol (KDE)

