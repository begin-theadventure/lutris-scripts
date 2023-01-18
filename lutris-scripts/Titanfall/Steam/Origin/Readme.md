## Tutorial
Hey!

This is a tutorial on how to play Titanfall on Linux with Lutris+Wine.

I made a [script](https://github.com/begin-theadventure/lutris-scripts/releases/tag/Titanfall) for Lutris that will set the prefix.

It's based on [Northstar](https://github.com/begin-theadventure/lutris-scripts/tree/main/lutris-scripts/Titanfall) script.

Steps:

1. Click + near "Search games".
2. Choose "Install from a local install [script](https://github.com/begin-theadventure/lutris-scripts/releases/download/Titanfall/titanfall-steam-origin.json)" and open it. After succesful installation, click Launch.
3. Changing settings to save resources and some bugs (you can skip this).

    Log in to Steam. I couldn't log in with the QR code, so I used my login and password. A restart may be needed.

    Running Steam with these arguments will have a less buggy GUI, and may save more resources (albeit -no-browser means fewer features):

    Lutris->right click on the banner->Configure->Game options->`-no-browser +open steam://open/minigameslist`->Re-open.

    Personally, I like to change these settings in Steam->Settings:

    _Friends_: Automatically sign into..

    _In-Game_: **Enable the Steam Overlay while in-game**.

    _Interface_: Notify me about.., Select which window.. - Library, **Enable GPU accelerated**.. & **Enable hardware video**..

    _Library_: Low Bandwith Mode & Low Performance Mode.

    And also in Origin:

    To disable **hardware acceleration**, which in my case uses 500+ MiB of GPU (!) see this Reddit post, [link](https://www.reddit.com/r/origin/comments/q8o9gv/disable_origin_client_hardware_acceleration). In our case, the directory is /path/to/titanfall-2/drive_c/Program Files (x86)/Origin/platforms

    Lutris->▲->Run EXE..->drive_c/Program Files (x86)/Origin Origin.exe and log in.

    Origin->Applications Settings:

    _Application_: Client update - all off, Start-up options_ - all off.

    _Help improve Origin_: Diagnostics - all off.

    _Origin in-game_: **Enable Origin In-Game**.

    Now exit Steam & Origin.

4. If you don't have the game files, install via Steam, but if you do, you can add them:

    To add the game move `appmanifest_1454890.acf` + `appmanifest_228980.acf` (by default in ~/.local/share/Steam) to /path/to/titanfall-2/drive_c/Program Files (x86)/Steam and symlink `Titanfall` + `Steamworks Shared` to `common` in the same folder.

    Open Steam and now Titanfall will be in your library!

    Add the game to favorites to make it easier to choose, play, agree to EULA, Steam will install the necessary stuff and after that the game should be ready to play!

Have fun! :)
