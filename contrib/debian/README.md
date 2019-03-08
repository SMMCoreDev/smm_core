
Debian
====================
This directory contains files used to package smmd/smm-qt
for Debian-based Linux systems. If you compile smmd/smm-qt yourself, there are some useful files here.

## smm: URI support ##


smm-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install smm-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your smmqt binary to `/usr/bin`
and the `../../share/pixmaps/smm128.png` to `/usr/share/pixmaps`

smm-qt.protocol (KDE)

