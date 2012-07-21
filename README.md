RobotoMOD development branch
=========

VERSION:        X
CODENAME:       XXXXXX
ANDROID VER:    4.0.4 (ICE CREAM SANDWICH)
AUTHOR:         WFSDEV
BRANCH:         dev

Porting RobotoMOD?
=========

If you are porting RobotoMOD please note the following:

- Don't port from the *dev* branch. This branch is unstable and it is unlikely it will even flash correctly.
- When porting Xena (1.0.0 or 1.0.1) please modify both *build.prop* files, these are found in *system* and *packages/beatsaudio/cm9aokp*
- Change the following lines in build.prop
-> ro.goo.developerid (you can also delete this)
-> ro.build.fingerprint
-> ro.rommanager.developerid (you can also delete this)

**We recommend you use dsixda's kitchen to cook RobotoMOD**

Download RobotoMOD?
=========

If you wish to download RobotoMOD then please use the following link:

--> http://forum.xda-developers.com/showthread.php?t=1781391 <--

