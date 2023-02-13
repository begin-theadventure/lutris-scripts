## Tutorial
Hey!

This is a tutorial on how to play the Northstar client on Linux with Lutris+Wine.

I made a [script](https://github.com/begin-theadventure/lutris-scripts/releases/tag/Northstar) for Lutris that will set the prefix.

It's based on [Titanfall 2](https://lutris.net/games/titanfall-2), the [EA App](https://lutris.net/games/ea-desktop) scripts and this [Reddit post](https://www.reddit.com/r/linux_gaming/comments/qhq3pn/ea_desktop_finally_working).

If you already have the game files install the client first, if not then skip it and do it after installing the game.

You can do it manually (extract the [zip file](https://github.com/R2Northstar/Northstar/releases) and drop everything in the game folder), using my auto shell [script](https://github.com/begin-theadventure/northstar-upllers/releases) or [Viper](https://github.com/0neGal/viper/releases).

Steps:

1. Click + near "Search games".
2. Choose "Install from a local install [script](https://github.com/begin-theadventure/lutris-scripts/releases/download/Northstar/northstar-client-ea-app.json)" and open it. After succesful installation, launch.
3. Changing one setting (you can skip this).

    Settings:

    _Application_: **Enable In-game overlay**.

4. If you don't have the game files, install them, but if you do, the EA App has no option to add them (it's possible with [Origin](https://github.com/begin-theadventure/lutris-scripts/tree/main/lutris-scripts/Northstar/Origin)).

    Alternatively, you can Run EXE inside prefix (NorthstarLauncher.exe) without adding the files, but it won't count the hours played.

5. In the Titanfall2 folder, create a file `run_northstar.txt` and type `1` in it ([source](https://github.com/R2Northstar/NorthstarLauncher/pull/19)).

    After that the game should be ready to play!

Images for Lutris (banner, covert art and icon), [link](https://github.com/begin-theadventure/lutris-scripts/tree/main/lutris-scripts/Northstar/images/NorthstarImagesLutris#readme). [Source/preview](https://github.com/R2NorthstarTools/NorthstarLogo).

Have fun! :)
