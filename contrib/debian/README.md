
Debian
====================
This directory contains files used to package flexworkd/flexwork-qt
for Debian-based Linux systems. If you compile flexworkd/flexwork-qt yourself, there are some useful files here.

## flexwork: URI support ##


flexwork-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install flexwork-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your flexworkqt binary to `/usr/bin`
and the `../../share/pixmaps/flexwork128.png` to `/usr/share/pixmaps`

flexwork-qt.protocol (KDE)

