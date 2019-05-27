
Debian
====================
This directory contains files used to package pipod/pipo-qt
for Debian-based Linux systems. If you compile pipod/pipo-qt yourself, there are some useful files here.

## pipo: URI support ##


pipo-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install pipo-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your pipo-qt binary to `/usr/bin`
and the `../../share/pixmaps/pipo128.png` to `/usr/share/pixmaps`

pipo-qt.protocol (KDE)

