Arch Linux Packages
===================

This repository contains all packages which I maintain for my Arch Linux box.
The resulting packages are then kept in a custom repository. See the 
[pacman wiki](https://wiki.archlinux.org/index.php/Pacman_tips#Custom_local_repository
"Pacman - custom local repository") for details how to set up such a repository.

Included Packages
=================

runningx
--------
This package contains a small program checking whether an X server is currently running.
This program can be used in conjunction with mutt's mailcap functionality. The original
program is developed [here](http://www.fiction.net/blong/programs/mutt/autoview/RunningX.c).


brightd
-------
This package contains the back light management tool
[brightd](http://www.pberndt.com/Programme/Linux/brightd/index.html# "brightd") for
Thinkpad Laptops. This tool automatically dims your screen if there is no activity
going on.


systemd-screenlock
------------------
This package provides a systemd service file which will trigger a 'loginctl lock-session'
command every time the laptop goes to sleep.


systemd-propagate
-----------------
This package provides systemd service files which allow propagation of some targets of the
system session to a user session.


python-pynoter
--------------
This package contains the [pynoter](https://github.com/l3nkz/pynoter "pynoter") python package
which provides a python library for advanced notifications.


passwrapper
-----------
This package provides the [passwrapper](https://github.com/l3nkz/passwrapper "passwrapper") 
script which allows smooth management of multiple password stores on one machine.
