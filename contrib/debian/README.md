
Debian
====================
This directory contains files used to package baalcoind/baalcoin-qt
for Debian-based Linux systems. If you compile baalcoind/baalcoin-qt yourself, there are some useful files here.

## baalcoin: URI support ##


baalcoin-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install baalcoin-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your baalcoinqt binary to `/usr/bin`
and the `../../share/pixmaps/baalcoin128.png` to `/usr/share/pixmaps`

baalcoin-qt.protocol (KDE)

