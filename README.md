# AUR
Collection of my personal PKGBUILD scripts for Arch Linux
____
## How to use
Run `makepkg` inside any subdirectory of this repo. After the build process finishes, install the resulting .pkg.tar.zst using `pacman -U package_name.pkg.tar.zst`
## Repo structure
### [/globalquake](https://github.com/mrdexterssj/aur/tree/main/globalquake)
An experimental java application used to monitor earthquakes using publicly available databases (entertainment only!)
* PKGBUILD - Used to download and setup the binaries into a package
* globalquake.desktop - Desktop entry
* globalquake.sh - Launcher script. Sets up the user directory
* globalquake.install - Script ran after the package installs with pacman

