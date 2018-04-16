
Debian
====================
This directory contains files used to package zumbad/zumba-qt
for Debian-based Linux systems. If you compile zumbad/zumba-qt yourself, there are some useful files here.

## zumba: URI support ##


zumba-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install zumba-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your zumba-qt binary to `/usr/bin`
and the `../../share/pixmaps/zumba128.png` to `/usr/share/pixmaps`

zumba-qt.protocol (KDE)

