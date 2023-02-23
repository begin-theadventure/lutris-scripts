## NosByte script
The launcher doesn't work properly in a 64-bit prefix and the game crashes with Windows version 7 upwards, so the script sets Vista instead.

## Tutorial

Hello.

I made a [script](https://github.com/begin-theadventure/lutris-scripts/releases/tag/NosByte) for Lutris which will set the prefix.

This Wine version compiled by me is required as it has a fix for mouse control: https://github.com/begin-theadventure/wine-tkg-nostale/releases

Download it and extract the zip file to:

`~/.local/share/lutris/runners/wine` or for Flatpak: `~/.var/app/net.lutris.Lutris/data/lutris/runners/wine`.

Steps:

1. Click + near "Search games".

2. Choose "Install from a local install [script](https://github.com/begin-theadventure/lutris-scripts/releases/download/NosByte/nosbyte.json)" and open it. After a successful installation, click Close.

4. Click Play and then UPDATE in the launcher to update, after that close and change the executable to NosByte.exe:

    Lutris->right click on the banner->Configure->Game options->Executable->Browse...->NosByte.exe

    Run the launcher only when there's an update or you need to check the game files, to do this change the executable as before. In my case, using 'Run EXE inside Wine prefix' caused the launcher to download the game files to nosbyte (next to drive_c).

5. Play.

Keys don't work by default, and it's necessary to re-bind them, sharing the bindings.nb file doesn't work across different prefixes and Wine versions as well.

In-game click the sprocket wheel->Game configuration->Change keybinds->set General and Quicklist first then restart the game to set the rest (Mates and Emotes). Enter and F keys work by default.

The only thing that can't be re-binded are two emoticons: Long Face and Rainbow, they don't display with any keybinding.

A workaround is to put them on a bar so you can use them with some combinations such as alt+1.

Images for Lutris (banner, covert art and icon), [link](https://github.com/begin-theadventure/lutris-scripts/tree/main/lutris-scripts/NosByte/images#readme). [Source/preview](https://nosbyte.eu/assets/images/global/logo.png).

Have fun! :)
