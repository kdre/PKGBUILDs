# PKGBUILDs

This repository contains some PKGBUILD files for Arch Linux.

To use them follow the following steps:

1. Clone repository

	git clone https://github.com/kdre/PKGBUILDs.git

2. Change to the desired package inside PKGBUILDs, e.g.

	cd PKGBUILDs

	cd libmpsse-kdre-git

3. Create package

	makepkg

4. Install package

	sudo pacman -U libmpsse-kdre-git*xz
