## NosVoid script
The game crashes with Windows version 7 upwards, so the script sets Vista instead.

Windows 7/8 version wasn't tested, but 10/11 works anyway.

## Tutorial

Hello.

I made a [script](https://github.com/begin-theadventure/lutris-scripts/releases/tag/NosVoid) for Lutris which will set the prefix.

This Wine version compiled by me is required as it has a fix for mouse control: https://github.com/begin-theadventure/wine-tkg-nostale/releases

Download it and extract the zip file to:

`~/.local/share/lutris/runners/wine` or for Flatpak: `~/.var/app/net.lutris.Lutris/data/lutris/runners/wine`.

And of course download [NosVoid](https://nosvoid.com/download) Windows 10/11.

Steps:

1. Click + near "Search games".

2. Choose "Install from a local install [script](https://github.com/begin-theadventure/lutris-scripts/releases/download/NosVoid/nosvoid.json)" and open it. After a successful installation, click Close.

3. Symlink the NosVoid folder with the game to /path/to/nosvoid/drive_c

4. Click Play and then PLAY in the launcher to update, after that close and change the executable to NosVoid.exe:

    Lutris->right click on the banner->Configure->Game options->Executable->Browse...->NosVoid.exe

    Run the launcher only when there's an update or you need to check the game files, to do this change the executable as before. In my case, using 'Run EXE inside Wine prefix' caused the launcher to download the game files to nosvoid (next to drive_c).

5. Play.

Images for Lutris (banner, covert art and icon), [link](https://github.com/begin-theadventure/lutris-scripts/tree/main/lutris-scripts/NosVoid/images#readme). [Source/preview](https://nosvoid.com/static/img/baner_video.webm).

Have fun! :)
