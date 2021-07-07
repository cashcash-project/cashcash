
Debian
====================
This directory contains files used to package cashcashd/cashcash-qt
for Debian-based Linux systems. If you compile cashcashd/cashcash-qt yourself, there are some useful files here.

## cashcash: URI support ##


cashcash-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install cashcash-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your cashcash-qt binary to `/usr/bin`
and the `../../share/pixmaps/cashcash128.png` to `/usr/share/pixmaps`

cashcash-qt.protocol (KDE)

