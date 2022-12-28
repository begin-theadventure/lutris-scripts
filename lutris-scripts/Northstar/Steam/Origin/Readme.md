## Tutorial
Hey!

This is a tutorial on how to play the Northstar client on Linux with Lutris+Wine.

I made a [script](https://github.com/begin-theadventure/lutris-scripts/releases/tag/Northstar) for Lutris that will set the prefix.

It's based on [Titanfall 2](https://lutris.net/games/titanfall-2) and [R5Reloaded](https://github.com/begin-theadventure/lutris-scripts/tree/main/lutris-scripts/R5Reloaded) scripts.

If you already already have the game files install the client first, if not do it for later but if you do then just skip it.

You can do it manually (extract the zip file and drop everything in the game folder), using my auto shell [script](https://github.com/begin-theadventure/northstar-upllers/releases) or [Viper](https://github.com/0neGal/viper/releases).

Steps:

1. Click + near "Search games".
2. Choose "Install from a local install [script](https://github.com/begin-theadventure/lutris-scripts/releases/download/Northstar/northstar-client-steam-origin.json)" and open it. After succesful installation, launch.
3. Changing settings to save resources and some bugs (you can skip this).

    Log in to Steam. I couldn't log in with the QR code, so I used my login and password. A restart may be needed.

    Running Steam with these arguments will have a less buggy GUI (albeit with fewer features), and may save more resources:

    Lutris->right click on the banner->Configure->Game options->`-no-browser +open steam://open/minigameslist`->Re-open.

    Personally, I like to change these settings in Steam->Settings:

    _Friends_: Automatically sign into..

    _In-Game_: **Enable the Steam Overlay while in-game**.

    _Interface_: Notify me about.., Select which window.. - Library, **Enable GPU accelerated**.. & **Enable hardware video**..

    _Library_: Low Bandwith Mode & Low Performance Mode.

    And also in Origin:

    To disable **hardware acceleration**, which in my case uses 500+ MiB of GPU (!) see this Reddit post, [link](https://www.reddit.com/r/origin/comments/q8o9gv/disable_origin_client_hardware_acceleration). In our case, the directory is /path/to/northstar-client/drive_c/Program Files (x86)/Origin/platforms

    Lutris->▲->Run EXE..->drive_c/Program Files (x86)/Origin Origin.exe and log in.

    Origin->Applications Settings:

    _Application_: Client update - all off, Start-up options_ - all off.

    _Help improve Origin_: Diagnostics - all off.

    _Origin in-game_: **Enable Origin In-Game**.

    Now exit Steam & Origin.

4. If you don't have the game files, install via Steam, but if you do, you can add them:

    To add the game move `appmanifest_1237970.acf` + `appmanifest_228980.acf` (by default in ~/.local/share/Steam) to /path/to/northstar-client/drive_c/Program Files (x86)/Steam and symlink `Titanfall2` + `Steamworks Shared` to `common` in the same folder.

    Open Steam and now Titanfall 2 will be in you library!

    Rename `NorthstarLauncher.exe` to `Titanfall2.exe`, add the game to favorites to make it easier to choose, play, agree to EULA, Steam will install the necessary stuff and after that the game should be ready to play!

Images for Lutris (banner, covert art and icon), [link](https://github.com/begin-theadventure/lutris-scripts/tree/main/lutris-scripts/Northstar/images/NorthstarImagesLutris#readme). [Source/preview](https://github.com/R2NorthstarTools/NorthstarLogo).

Another way is to use Bottles. Since I don't use it, this video may be helpful: [https://youtu.be/VqDgrHCPWG8?t=368](https://youtu.be/VqDgrHCPWG8?t=368)

Have fun! :)
