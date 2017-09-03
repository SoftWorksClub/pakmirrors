# Name of the project:
**pakmirrors**

### Website:
[SourceForge](http://pakmirrors.sourceforge.io "pakmirrors at SourceForge")

### Short description:
Archlinux's pacman mirrors sorter

### Long description:
A simple script to sort the fastest mirror list for pacman on a standard archlinux install.
It is based upon rankmirrors.
The purpose was to have a just works command line tool without the need to remember the syntax, and without user iteration.

### Based upon:
* [ArchWiki](https://wiki.archlinux.org/index.php/mirrors#List_by_speed/ "mirrors at ArchWiki")
* Archlinux's pacman rankmirrors utility

### Copyright 2017:
* speedytux@posteo.net
* gnuman@posteo.eu

### License:
GNU General Public License version 3.0 (GPLv3)

### ToDo:
* Add a pacman hook to execute pakmirrors on pacman-mirrorlist upgrade
* Divide in functions
* Add the version for the actual revision
* Add the help ( -h or --help ) command line option
* Ask for help on bbs.archlinux.org
* Make it independent from rankmirrors
* Convert this shell script into a language like python or C
* Create a pacman package for archlinux
* Propose the package to an archlinux's Trusted User to include in AUR

### Tested on:
Archlinux updated on April 24, 2017
