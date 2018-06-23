
Debian
====================
This directory contains files used to package bizonetd/bizonet-qt
for Debian-based Linux systems. If you compile bizonetd/bizonet-qt yourself, there are some useful files here.

## bizonet: URI support ##


bizonet-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install bizonet-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your bizonet-qt binary to `/usr/bin`
and the `../../share/pixmaps/bizonet128.png` to `/usr/share/pixmaps`

bizonet-qt.protocol (KDE)

