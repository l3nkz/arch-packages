Arch Linux Packages
===================

This repository contains all packages which I maintain for my Arch Linux box.
The resulting packages are then kept in a custom repository. See the 
[pacman wiki](https://wiki.archlinux.org/index.php/Pacman_tips#Custom_local_repository
"Pacman - custom local repository") for details how to set up such a repository.

Included Packages
=================

mutt-sidebar
------------
This package contains the console mail client [mutt](http://www.mutt.org/ "mutt") with
a partly self developed sidebar patch. This patch adds a sidebar to mutt showing your
mailboxes. This patch additionally adds proper support for folder indention and short
folder names in the sidebar.


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
