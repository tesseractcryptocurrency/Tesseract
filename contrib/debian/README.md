
Debian
====================
This directory contains files used to package tesseractd/tesseract-qt
for Debian-based Linux systems. If you compile tesseractd/tesseract-qt yourself, there are some useful files here.

## tesseract: URI support ##


tesseract-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install tesseract-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your tesseract-qt binary to `/usr/bin`
and the `../../share/pixmaps/bitcoin128.png` to `/usr/share/pixmaps`

tesseract-qt.protocol (KDE)

