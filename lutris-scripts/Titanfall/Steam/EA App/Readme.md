## Tutorial
Hello.

This is a tutorial on how to play Titanfall on Linux with Lutris+Wine.

I made a [script](https://github.com/begin-theadventure/lutris-scripts/releases/tag/Titanfall) for Lutris that will set the prefix.

It's based on [Northstar](https://github.com/begin-theadventure/lutris-scripts/tree/main/lutris-scripts/Titanfall) script.

Steps:

1. Click + near "Search games".
2. Choose "Install from a local install [script](https://github.com/begin-theadventure/lutris-scripts/releases/download/Titanfall/titanfall-steam-ea-app.json)" and open it. After succesful installation, click Launch.
3. Changing settings to save resources and some bugs (you can skip this).

    Log in to Steam. I couldn't log in with the QR code, so I used my login and password. A restart may be needed.

    Running Steam with these arguments will have a less buggy GUI, and may save more resources (albeit -no-browser means fewer features):

    Lutris->right click on the banner->Configure->Game options->`-no-browser +open steam://open/minigameslist`->Re-open.

    Personally, I like to change these settings in Steam->Settings:

    _Friends_: Automatically sign into..

    _In-Game_: **Enable the Steam Overlay while in-game**.

    _Interface_: Notify me about.., Select which window.. - Library, **Enable GPU accelerated**.. & **Enable hardware video**..

    _Library_: Low Bandwith Mode & Low Performance Mode.

    In the EA App:

    Lutris->▲->Run EXE..->drive_c/Program Files/Electronics Arts/EA Desktop/EA Desktop EADesktop.exe and log in.

    Settings:

    _Application_: **Enable In-game overlay**.

    Now exit Steam & the EA App.

4. If you don't have the game files, install via Steam, but if you do, you can add them:

    To add the game move `appmanifest_1454890.acf` + `appmanifest_228980.acf` (by default in ~/.local/share/Steam) to /path/to/titanfall-2/drive_c/Program Files (x86)/Steam and symlink `Titanfall` + `Steamworks Shared` to `common` in the same folder.

    Open Steam and now Titanfall will be in your library!

    Add the game to favorites to make it easier to choose, play, agree to EULA, Steam will install the necessary stuff and after that the game should be ready to play!

Icon for Lutris, [link](https://github.com/begin-theadventure/lutris-scripts/tree/main/lutris-scripts/Titanfall/TitanfallIcon#readme).

Have fun! :)
