# OpenBSD Init script

This is a script that automatically installs basic software and configures a barebones but functional installation of OpenBSD for a minimal GUI usage. 

**IMPORTANT**: My build of dwm is extremely limited (on purpose). If you want to use the vanilla version of dwm, skip the GUI software installation in this script and compile dwm manually.

## GUI Programs used: 
- Window manager: dwm
- Terminal: st
- Status bar: dwmblocks (disabled by default)
- Compositor: picom

## Installation
Run the following command as root:
`ftp https://raw.githubusercontent.com/Fiscoon/obsdinit/main/init.sh && sh ./init.sh`
