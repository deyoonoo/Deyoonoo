
Debian
====================
This directory contains files used to package dond/don-qt
for Debian-based Linux systems. If you compile dond/don-qt yourself, there are some useful files here.

## don: URI support ##


don-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install don-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your don-qt binary to `/usr/bin`
and the `../../share/pixmaps/don128.png` to `/usr/share/pixmaps`

don-qt.protocol (KDE)

