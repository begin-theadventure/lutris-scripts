## [Tutorial](https://www.reddit.com/r/titanfall/comments/zxvhbu/i_made_lutris_install_scripts_linux_for_titanfall)
Hello.

This tutorial's on how to play Titanfall on Linux with Lutris+Wine.

I made a [script](https://github.com/begin-theadventure/lutris-scripts/releases/tag/Titanfall) for Lutris that will set the prefix.

It's based on the [Northstar](https://github.com/begin-theadventure/lutris-scripts/tree/main/lutris-scripts/Titanfall) script.

Steps:

1. Click + near "Search games".

2. Choose "Install from a local install [script](https://github.com/begin-theadventure/lutris-scripts/releases/download/Titanfall/titanfall-steam-ea-app.json)" and open it. After successful installation, click Launch.

3. Changing settings to save resources and other stuff (not necessary).

    Log in to Steam. I couldn't log in with the QR code, so I used my login and password. A restart may be needed.

    I like to change these settings in Steam->Settings:

    _Friends_: Sign in to friends when Steam Client starts

    _In-Game_: **Enable the Steam Overlay while in-game**.

    _Interface_: Notify me about.., Start Up Location.. - Library, Start Steam in Big Picture Mode, **Enable GPU accelerated**.. & **Enable hardware video**..

    _Library_: Low Bandwith Mode, Low Performance Mode & Disable Community Content.

    I recommend using Steam in Big Picture mode.

    Launch options:

    Lutris->right click on the banner->Configure->Game options->`+open steam://open/minigameslist` opens the mini-games list and `steam://rungameid/1454890` launches the game automatically.

    In the EA App:

    Lutris->▲->Run EXE..->drive_c/Program Files/Electronics Arts/EA Desktop/EA Desktop EADesktop.exe and log in.

    Settings:

    _Application_: **Enable In-game overlay**.

    Now exit Steam & the EA App.

4. If you don't have the game files, install them via Steam, but if you do, you can add them:

    To add the game, move `appmanifest_1454890.acf` + `appmanifest_228980.acf` (by default in ~/.local/share/Steam) to /path/to/titanfall-2/drive_c/Program Files (x86)/Steam/steamapps and symlink `Titanfall` + `Steamworks Shared` to `common` in the same folder.

    Open Steam, and now Titanfall will be in your library!

Add the game to favorites to make it easier to choose, play, agree to EULA, Steam will install the necessary stuff, and the game should be ready to play!

[Icon for Lutris](https://github.com/begin-theadventure/lutris-scripts/tree/main/lutris-scripts/Titanfall/TitanfallIcon#readme).

Have fun! :)
