
Debian
====================
This directory contains files used to package rshcoind/rshcoin-qt
for Debian-based Linux systems. If you compile rshcoind/rshcoin-qt yourself, there are some useful files here.

## rshcoin: URI support ##


rshcoin-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install rshcoin-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your rshcoinqt binary to `/usr/bin`
and the `../../share/pixmaps/rshcoin128.png` to `/usr/share/pixmaps`

rshcoin-qt.protocol (KDE)

