
Debian
====================
This directory contains files used to package cmkd/cmk-qt
for Debian-based Linux systems. If you compile cmkd/cmk-qt yourself, there are some useful files here.

## cmk: URI support ##


cmk-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install cmk-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your cmk-qt binary to `/usr/bin`
and the `../../share/pixmaps/dash128.png` to `/usr/share/pixmaps`

cmk-qt.protocol (KDE)

