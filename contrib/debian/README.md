
Debian
====================
This directory contains files used to package Dueliumd/Duelium-qt
for Debian-based Linux systems. If you compile Dueliumd/Duelium-qt yourself, there are some useful files here.

## Duelium: URI support ##


Duelium-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install Duelium-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your Dueliumqt binary to `/usr/bin`
and the `../../share/pixmaps/Duelium128.png` to `/usr/share/pixmaps`

Duelium-qt.protocol (KDE)

