
Debian
====================
This directory contains files used to package ParadiseCoind/ParadiseCoin-qt
for Debian-based Linux systems. If you compile ParadiseCoind/ParadiseCoin-qt yourself, there are some useful files here.

## ParadiseCoin: URI support ##


ParadiseCoin-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install ParadiseCoin-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your ParadiseCoinqt binary to `/usr/bin`
and the `../../share/pixmaps/ParadiseCoin128.png` to `/usr/share/pixmaps`

ParadiseCoin-qt.protocol (KDE)

