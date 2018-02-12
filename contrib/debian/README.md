
Debian
====================
This directory contains files used to package vizeed/Vizeh-qt
for Debian-based Linux systems. If you compile vizeed/Vizeh-qt yourself, there are some useful files here.

## Vizeh: URI support ##


Vizeh-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install Vizeh-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your vizeeqt binary to `/usr/bin`
and the `../../share/pixmaps/vizee128.png` to `/usr/share/pixmaps`

Vizeh-qt.protocol (KDE)

