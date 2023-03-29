## [Tutorial](https://www.reddit.com/r/titanfall/comments/zxvhbu/i_made_lutris_install_scripts_linux_for_titanfall)
Hello.

This tutorial's on how to play Titanfall 2 on Linux with Lutris+Wine.

I made a [script](https://github.com/begin-theadventure/lutris-scripts/releases/tag/Titanfall-2) for Lutris that will set the prefix.

It's based on [Titanfall 2](https://lutris.net/games/titanfall-2), the [EA App](https://lutris.net/games/ea-desktop) scripts and this [Reddit post](https://www.reddit.com/r/linux_gaming/comments/qhq3pn/ea_desktop_finally_working).

Steps:

1. Click + near "Search games".

2. Choose "Install from a local install [script](https://github.com/begin-theadventure/lutris-scripts/releases/download/Titanfall-2/titanfall-2-steam-ea-app.json)" and open it. After successful installation, click Launch.

3. Changing settings to save resources and other things (not necessary).

    Log in to Steam. I couldn't log in with the QR code, so I used my login and password. A restart may be needed.

    I like to change these settings in Steam->Settings:

    _Friends_: Automatically sign into..

    _In-Game_: **Enable the Steam Overlay while in-game**.

    _Interface_: Notify me about.., Select which window.. - Library, **Enable GPU accelerated**.. & **Enable hardware video**..

    _Library_: Low Bandwith Mode & Low Performance Mode.

    Launch options:

    Lutris->right click on the banner->Configure->Game options->`-no-browser` saves resouces (albeit resulting in fewer features, including Properties), `+open steam://open/minigameslist` opens the mini-games list (which is less buggy) and `steam://rungameid/1237970` launches the game automatically->Save.

    In the EA App:

    Lutris->▲->Run EXE..->drive_c/Program Files/Electronics Arts/EA Desktop/EA Desktop EADesktop.exe and log in.

    Settings:

    _Application_: **Enable In-game overlay**.

4. If you don't have the game files, install via Steam, but if you do, you can add them:

    To add the game, move `appmanifest_1237970.acf` + `appmanifest_228980.acf` (by default in ~/.local/share/Steam) to /path/to/titanfall-2/drive_c/Program Files (x86)/Steam and symlink `Titanfall2` + `Steamworks Shared` to `common` in the same folder.

    Open Steam and, now Titanfall 2 will be in your library!

    Add the game to favorites to make it easier to choose, play, agree to EULA, Steam will install the necessary stuff, and the game should be ready to play!

Have fun! :)