
Debian
====================
This directory contains files used to package nodezerod/nodezero-qt
for Debian-based Linux systems. If you compile nodezerod/nodezero-qt yourself, there are some useful files here.

## nodezero: URI support ##


nodezero-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install nodezero-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your nodezero-qt binary to `/usr/bin`
and the `../../share/pixmaps/bitcoin128.png` to `/usr/share/pixmaps`

nodezero-qt.protocol (KDE)

