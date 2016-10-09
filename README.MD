## LFS PKGBUILD SCRIPTS
This is a collection of PKGBUILD scripts that I have created so far for LFS. This covers all the packages from chapter 6 (bar GRUB, which I don't use) plus additional packages from BLFS and elsewhere as I create them.

## NOTES
Before being able to use these PKGBUILD scripts, you'll of course need to download, build and install pacman. Most of the dependencies for pacman have build instructions on the BLFS except for fakeroot, but that is a straightforward package.

I suggest initially installing pacman and its dependencies into the /tools directory and then follow the book onwards from there. Once you finished configuring your system, package and install pacman and its dependencies so that it will be available from your LFS build once you reboot into it.

## WARNING

Not all of the packages here follow the instructions directly from the book, while most do you will need to modify some accordingly. Essentially any of the packages in the book that reference the /tools directory will need to be modified to be used. Some other packages also have optimizations specifically for my system which you may not want.

## LICENSE
The bulk of the code used in the PKGBUILDs is taken from the LFS book in which the code therein is under a MIT license. The license and copyright notice is found in the LICENSE file in the top-level directory.
