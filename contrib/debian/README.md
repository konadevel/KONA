
Debian
====================
This directory contains files used to package KONAd/KONA-qt
for Debian-based Linux systems. If you compile KONAd/KONA-qt yourself, there are some useful files here.

## KONA: URI support ##


KONA-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install KONA-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your KONAqt binary to `/usr/bin`
and the `../../share/pixmaps/KONA128.png` to `/usr/share/pixmaps`

KONA-qt.protocol (KDE)

