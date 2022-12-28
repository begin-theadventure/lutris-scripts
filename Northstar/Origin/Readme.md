## Tutorial
Hey!

This is a tutorial on how to play the Northstar client on Linux.

I made a [script](https://github.com/begin-theadventure/lutris-scripts/blob/main/Northstar/northstar-client.json) for Lutris that will set the prefix.

It's based on [Titanfall 2](https://lutris.net/games/titanfall-2/) and [R5Reloaded](https://github.com/begin-theadventure/lutris-scripts/blob/main/R5Reloaded/r5reloaded.json) scripts.

If you already already have the game files install the client first, if not do it for later but if you do then just skip it.

You can do it manually (extract the zip file and drop everything in the game folder), using my auto shell [script](https://github.com/begin-theadventure/northstar-upllers/releases) or [Viper](https://github.com/0neGal/viper/releases).

Steps:

1. Click + near "Search games".
2. Choose "Install from a local install [script](https://github.com/begin-theadventure/lutris-scripts/releases/download/Northstar/northstar-client.json)" and open it. After succesful installation, launch.
3. Changing settings to save resources (you can skip this).

    To disable **hardware acceleration**, which in my case uses 500+ MiB of GPU (!) see this Reddit post, [link](https://www.reddit.com/r/origin/comments/q8o9gv/disable_origin_client_hardware_acceleration). In our case, the directory is /path/to/northstar-client/drive_c/Program Files (x86)/Origin/platforms

    Origin->Applications Settings:

    _Origin in-game_: **Enable Origin In-Game**.

    (optional:)

    _Application_: Client update - all off, Start-up options_ - all off.

    _Help improve Origin_: Diagnostics - all off.

4. If you don't have the game files, install them, but if you do, you can add them:

    Symlink the Titanfall2 folder to /path/to/northstar-client/drive_c/Program Files (x86)/Origin Games

    Open Origin->Download->Origin, Exit. Re-open and it will verify the game files.

    After that the game should be ready to play!

Images for Lutris (banner, covert art and icon), [link](https://github.com/begin-theadventure/lutris-scripts/tree/main/Northstar/images/NorthstarImagesLutris#readme). [Source/preview](https://github.com/R2NorthstarTools/NorthstarLogo).

Another way is to use Bottles. Since I don't use it, this video may be helpful: [https://youtu.be/VqDgrHCPWG8?t=368](https://youtu.be/VqDgrHCPWG8?t=368)

Have fun! :)