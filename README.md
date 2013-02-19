List installed packages
=======================

* List manually installed packages on Debian based systems.
* This python script has been cloned from [here](http://www.aifdr.org/projects/system_administration/browser/statistics/list_manually_installed_packages.py)
(found via [this Superuser thread](http://superuser.com/questions/48374/find-all-user-installed-packages)).
* Tested on Mint 14 and works great so far. 
* Cloning it here since I have been looking for such a script (to cut the fat and to help when migrating/reinstalling the system) and because I think I can make some improvements to it.
* Sample output:

```
2013-01-24 13:36:42 yakuake:amd64:  a Quake-style terminal emulator based on KDE Konsole technology
2013-01-24 13:40:08 python2.6:amd64:  An interactive high-level object-oriented language (version 2.6)
2013-01-24 14:06:49 libreadline5:amd64:  GNU readline and history libraries - run-time libraries
2013-01-24 14:18:13 python-pip:all:  alternative Python package installer
2013-01-24 14:18:13 python-virtualenv:all:  Python virtual environment creator
2013-01-24 14:21:18 ipython:all:  enhanced interactive Python shell
2013-01-24 14:21:19 python-ipdb:all:  IPython-based pdb replacement
2013-01-24 14:24:21 chromium-codecs-ffmpeg:amd64:  Free ffmpeg codecs for the Chromium Browser
2013-01-24 14:24:22 chromium-browser:amd64:  Chromium browser
2013-01-24 14:24:27 chromium-browser-l10n:all:  chromium-browser language packages
2013-01-24 14:30:24 python2.6-dev:amd64:  Header files and a static library for Python (version 2.6)
2013-01-24 14:30:24 python2.7-dev:amd64:  Header files and a static library for Python (v2.7)
...
```

* Many thanks to the original author for this script. 

