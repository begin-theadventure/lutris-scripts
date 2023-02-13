## Tutorial
Hey!

This is a tutorial on how to play the Northstar client on Linux with Lutris+Wine.

I made a [script](https://github.com/begin-theadventure/lutris-scripts/releases/tag/Northstar) for Lutris that will set the prefix.

It's based on [Titanfall 2](https://lutris.net/games/titanfall-2) and [Origin](https://lutris.net/games/origin) scripts.

If you already have the game files install the client first, if not then skip it and do it after installing the game.

You can do it manually (extract the [zip file](https://github.com/R2Northstar/Northstar/releases) and drop everything in the game folder), using my auto shell [script](https://github.com/begin-theadventure/northstar-upllers/releases) or [Viper](https://github.com/0neGal/viper/releases).

Steps:

1. Click + near "Search games".
2. Choose "Install from a local install [script](https://github.com/begin-theadventure/lutris-scripts/releases/download/Northstar/northstar-client-origin.json)" and open it. After succesful installation, launch.
3. Changing settings to save resources (you can skip this).

    To disable **hardware acceleration**, which in my case uses 500+ MiB of GPU (!) see this Reddit post, [link](https://www.reddit.com/r/origin/comments/q8o9gv/disable_origin_client_hardware_acceleration). In our case, the directory is /path/to/northstar-client/drive_c/Program Files (x86)/Origin/platforms

    Origin->Applications Settings:

    _Origin in-game_: **Enable Origin In-Game**.

    (optional:)

    _Application_: Client update - all off, Start-up options_ - all off.

    _Help improve Origin_: Diagnostics - all off.

4. If you don't have the game files, install them, but if you do, you can Run EXE inside prefix (NorthstarLauncher.exe), but it won't count the hours played or add them:

    Symlink the Titanfall2 folder to /path/to/northstar-client/drive_c/Program Files (x86)/Origin Games

    Open Origin->Download->Origin, Exit. Re-open and it will verify the game files. 

[5.](https://github.com/R2Northstar/NorthstarLauncher/pull/19) In the Titanfall2 folder, create a file `run_northstar.txt` and type `1` in it.

    After that the game should be ready to play!

Images for Lutris (banner, covert art and icon), [link](https://github.com/begin-theadventure/lutris-scripts/tree/main/lutris-scripts/Northstar/images/NorthstarImagesLutris#readme). [Source/preview](https://github.com/R2NorthstarTools/NorthstarLogo).

Have fun! :)
