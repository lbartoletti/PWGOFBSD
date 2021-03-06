# PWGOFBSD - Play Windows Games On FreeBSD
[![CodeFactor](https://www.codefactor.io/repository/github/alexander88207/pwgofbsd/badge)](https://www.codefactor.io/repository/github/alexander88207/pwgofbsd) ![GitHub release](https://img.shields.io/github/release/Alexander88207/PWGOBSD)

# Introduction

Inspired by lutris, we would like to provide a game launcher to play windows games on FreeBSD.

# Description &#x1F4D8;

Install your favorite windows games & launcher easily!

![](https://github.com/Alexander88207/PWGOFBSD/raw/master/Screenshot.png "Screenshot")

# Dependencies :syringe:

- curl
- p7zip
- dialog
- webfonts
- winetricks
- i386-wine-devel on amd64 or wine-devel on i386

# States :fire:

This list will be refreshed on every update of [i386-wine-devel](https://www.freshports.org/emulators/i386-wine-devel)

Application | Works?
------------ | -------------
 Steam | Uses winxp with an older steam client to get some online features. (Doesn't affect performance)
 Blizzard | Runs out of the box.
 Origin | Uses winxp with an older origin client. (Doesn't affect performance)
 Uplay | Runs out of the box, but crashes to often.
 Teamspeak | Runs out of the box.
 Clone Hero | Runs out of the box. WARNING: The game can also cause a very, very loud sound error! To fix it restart the system.
 Drakensang Online |  Crashes at start.
 Anarchy Online | Runs out of the box. Please let the installer create a shortcut or you are unable to start the launcher!

If you want a special game then create an issue :)

# Tweaks :wrench:

Tweaks are [here](Tweaks.md)

# Limitations :x:

- Only 32-Bit Games and Applications working currently.
- No vulkan support on amd64 systems.

# Installation/Uninstallation :cd:

Download the latest stable release from [here](https://github.com/Alexander88207/PWGOBSD/releases)

To start this script use the follwing command in the folder:
```
bash PWGOFBSD.sh
```
To get a better design copy the file `.dialogrc` to `/home/$USER`

To uninstall that script just delete that and the Games & Programs folder in the home directory.

## Contribute :pencil2:
if you want to contribute to this repo then just send a pull request or issues :)
