# Welcome! #

Welcome to npp-installer! The automated notepad++ installer for linux.

This application is easy to use, and should require little effort to use properly.

Your linux system needs to have apt-get and wget to work. It has currently been tested on Ubuntu 7.04 and Debian 4.0 (but not the latest fix). You will also need wine in your distro's repos.

This software is open source/Free and licensed under the MIT license. See LICENSE for more details.

How To:

Unpack this directory

then run;

_chmod 755 ./npp-installer.py_

_python npp-installer.py_

Follow the prompts

KNOWN ISSUES

There is an issue with debain: the program installed npp in /home/root/.wine instead of /home/USERNAME/.wine. I have added a fix, but I have not tested it.