# Cleaner

This is a simple PC cleanign app designed to make clearing cache and temp files, flushing ram, cleaning apt, and
performing trim on mounted drives.

Cleaner started as a compilation of scripts I had either figured out or found laying around across the web. There
is a particular Windows program that inspired me to write these scripts, and I have decided to share them with the
world.

The script has been written to use zenity to make everything easy to use. Note, most actions will have a root/sudo password prompt. For these actions, root password is required.

Installation and Usage
    Download latest release (see below) and install via normal .deb install process
    If your linux distro does not support .deb, you can always clone the repo and manually install the binary and 
    icon. Place binary in /usr/local/bin and the icon in /usr/share/applications.
        App can be executed straight from menu->administration->cleaner or in terminal with `cleaner`. Since there is
        a password prompt, there is no need to execute with sudo.

**Releases are in .deb format.**
Download the latest release here https://github.com/TeamFahQ/Cleaner/tree/master/releases

Please don't hesitate to post any issues. For features and suggestions, you can use the issues but please add 
**[FEATURE REQUST]** to your title.

NOTE:
Due to random errors like this:
cleaner: ��3~�R�/4!
Switch from binary to script version.
