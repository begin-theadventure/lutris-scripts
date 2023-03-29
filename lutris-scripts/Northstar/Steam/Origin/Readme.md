## [Tutorial](https://www.reddit.com/r/titanfall/comments/zxvhbu/i_made_lutris_install_scripts_linux_for_titanfall)
Hello.

This tutorial's on how to play the Northstar client on Linux with Lutris+Wine.

I made a [script](https://github.com/begin-theadventure/lutris-scripts/releases/tag/Northstar) for Lutris that will set the prefix.

It's based on [Titanfall 2](https://lutris.net/games/titanfall-2) and [Origin](https://lutris.net/games/origin) scripts.

If you already have the game files, install the client first; if not, skip it and do it after installing the game.

You can do it manually (extract the [zip file](https://github.com/R2Northstar/Northstar/releases) and drop everything in the game folder), using my [shell scripts](https://github.com/begin-theadventure/northstar-upllers) or other tools such as [ViperSH](https://github.com/0neGal/viper-sh), [Papa](https://github.com/AnActualEmerald/papa), [FlightCore](https://github.com/R2NorthstarTools/FlightCore), [Viper](https://github.com/0neGal/viper) and [r2modman](https://github.com/ebkr/r2modmanPlus).

Steps:

1. Click + near "Search games".

2. Choose "Install from a local install [script](https://github.com/begin-theadventure/lutris-scripts/releases/download/Northstar/northstar-client-steam-origin.json)" and open it. After successful installation, click Launch.

3. Log in to Origin and see this [Twitter post](https://twitter.com/p0358/status/1635796691902160896).

    The proper exe is already installed by the script.

    Empty value "" for UpdateURL should also work.

    In our case, the directory is /path/to/northstar-client/drive_c/ProgramData/Origin/local.xml

4. Changing settings to save resources and other stuff (not necessary).

    In Origin:

    To disable **hardware acceleration**, which in my case uses 500+ MiB of GPU (!), see this [Reddit post](https://www.reddit.com/r/origin/comments/q8o9gv/disable_origin_client_hardware_acceleration). In our case, the directory is /path/to/northstar-client/drive_c/Program Files (x86)/Origin/platforms

    Origin->Applications Settings:

    _Application_: Client update - all off, Start-up options_ - all off.

    _Help improve Origin_: Diagnostics - all off.

    _Origin in-game_: **Enable Origin In-Game**.

    Lutris->▲->Run EXE..->drive_c/Program Files (x86)/Steam/steam.exe.

    Log in to Steam. I couldn't log in with the QR code, so I used my login and password. A restart may be needed.

    I like to change these settings in Steam->Settings:

    _Friends_: Automatically sign into..

    _In-Game_: **Enable the Steam Overlay while in-game**.

    _Interface_: Notify me about.., Select which window.. - Library, **Enable GPU accelerated**.. & **Enable hardware video**..

    _Library_: Low Bandwith Mode & Low Performance Mode.

    Launch options:

    Lutris->right click on the banner->Configure->Game options->`-no-browser` saves resources (albeit resulting in fewer features, including Properties) and`+open steam://open/minigameslist` opens the mini-games list.

5. If you don't have the game files, install them via Steam, but if you do, you can add them:

    To add the game, move `appmanifest_1237970.acf` + `appmanifest_228980.acf` (by default in ~/.local/share/Steam) to /path/to/northstar-client/drive_c/Program Files (x86)/Steam and symlink `Titanfall2` + `Steamworks Shared` to `common` in the same folder.

    Open Steam, and now Titanfall 2 will be in your library! Exit Steam.

6. In the Titanfall2 folder, create a file `run_northstar.txt` and type `1` in it, ([source](https://github.com/R2Northstar/NorthstarLauncher/pull/19)).

7. If you launch the game with Steam, it nags that the EA App isn't installed, so instead, we have to launch the game with Origin.

    If Steam isn't running, Origin will launch it when you click "Play", and then you must click it again to launch the game.

After that, the game should be ready to play!

[Images for Lutris](https://github.com/begin-theadventure/lutris-scripts/tree/main/lutris-scripts/Northstar/images/NorthstarImagesLutris#readme) (banner, covert art and icon). [Source/preview](https://github.com/R2NorthstarTools/NorthstarLogo).

Have fun! :)
