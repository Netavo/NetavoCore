
Debian
====================
This directory contains files used to package netavod/netavo-qt
for Debian-based Linux systems. If you compile netavod/netavo-qt yourself, there are some useful files here.

## netavo: URI support ##


netavo-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install netavo-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your netavo-qt binary to `/usr/bin`
and the `../../share/pixmaps/netavo128.png` to `/usr/share/pixmaps`

netavo-qt.protocol (KDE)

