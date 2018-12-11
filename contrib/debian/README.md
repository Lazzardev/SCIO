
Debian
====================
This directory contains files used to package sciod/scio-qt
for Debian-based Linux systems. If you compile sciod/scio-qt yourself, there are some useful files here.

## scio: URI support ##


scio-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install scio-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your scioqt binary to `/usr/bin`
and the `../../share/pixmaps/scio128.png` to `/usr/share/pixmaps`

scio-qt.protocol (KDE)

