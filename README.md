# Linux Scripts: Xenial (Classic)
"Classic" means that it sets up the old i3wm setup I used to use. Man I've missed it (September 2016).
// TODO update this

**These scripts assume the main user is "jake", and the operating system is Ubuntu 16.04 LTS (Xenial)**

## install-core.sh
**Run this first**

Installs git, vim, screen, and software-properties-common for adding repositories more easily. 

## add-apt.sh
**Run this second**

This adds any required repositories using add-apt-repository. It will include repositories that you have to install manually as comments. 

## install-common.sh
Install commonly used command line programs.

## install-defiance.sh
Install laptop dependencies, like the NVIDIA Optimus support packages.

## install-media.sh
Install software that's used to play media. This is in a separate script because there may be installations such as headless servers that don't need media playback capabilities.

## install-gui-common.sh
Install commonly used gui programs.

## install-personal.sh
Install programs used at home only.

## install-work.sh
Install programs used for work.

## install-fun.sh
Install a load of useless shit.

## purge.sh
Removes personal information from the home directory.

## Headless server 
No script, just a package list.
- `bind9` for setting up a DNS