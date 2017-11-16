
Debian
====================
This directory contains files used to package filbitd/filbit-qt
for Debian-based Linux systems. If you compile filbitd/filbit-qt yourself, there are some useful files here.

## filbit: URI support ##


filbit-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install filbit-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your filbit-qt binary to `/usr/bin`
and the `../../share/pixmaps/filbit128.png` to `/usr/share/pixmaps`

filbit-qt.protocol (KDE)

