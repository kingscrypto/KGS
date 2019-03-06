
Debian
====================
This directory contains files used to package kgsd/kgs-qt
for Debian-based Linux systems. If you compile kgsd/kgs-qt yourself, there are some useful files here.

## kgs: URI support ##


kgs-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install kgs-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your kgsqt binary to `/usr/bin`
and the `../../share/pixmaps/kgs128.png` to `/usr/share/pixmaps`

kgs-qt.protocol (KDE)

