
Debian
====================
This directory contains files used to package aimnd/aimn-qt
for Debian-based Linux systems. If you compile aimnd/aimn-qt yourself, there are some useful files here.

## aimn: URI support ##


aimn-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install aimn-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your aimnqt binary to `/usr/bin`
and the `../../share/pixmaps/aimn128.png` to `/usr/share/pixmaps`

aimn-qt.protocol (KDE)

