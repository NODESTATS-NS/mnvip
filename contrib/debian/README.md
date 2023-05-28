
Debian
====================
This directory contains files used to package mnvipd/mnvip-qt
for Debian-based Linux systems. If you compile mnvipd/mnvip-qt yourself, there are some useful files here.

## pivx: URI support ##


mnvip-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install mnvip-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your mnvip-qt binary to `/usr/bin`
and the `../../share/pixmaps/pivx128.png` to `/usr/share/pixmaps`

mnvip-qt.protocol (KDE)

