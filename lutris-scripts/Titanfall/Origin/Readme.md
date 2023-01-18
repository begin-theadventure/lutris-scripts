## Tutorial
Hey!

This is a tutorial on how to play Titanfall on Linux with Lutris+Wine.

I made a [script](https://github.com/begin-theadventure/lutris-scripts/releases/tag/Titanfall) for Lutris that will set the prefix.

It's based on [Northstar](https://github.com/begin-theadventure/lutris-scripts/tree/main/lutris-scripts/Northstar) script.

Steps:

1. Click + near "Search games".
2. Choose "Install from a local install [script](https://github.com/begin-theadventure/lutris-scripts/releases/download/Titanfall/titanfall-origin.json)" and open it. After a successful installation, click Launch.
3. Changing settings to save resources (you can skip this).

    To disable **hardware acceleration**, which in my case uses 500+ MiB of GPU (!) see this Reddit post, [link](https://www.reddit.com/r/origin/comments/q8o9gv/disable_origin_client_hardware_acceleration). In our case, the directory is /path/to/titanfall/drive_c/Program Files (x86)/Origin/platforms

    Origin->Applications Settings:

    _Origin in-game_: **Enable Origin In-Game**.

    (optional:)

    _Application_: Client update - all off, Start-up options_ - all off.

    _Help improve Origin_: Diagnostics - all off.

    Exit Origin.

4. If you don't have the game files, install them, but if you do, you can add them:

    Symlink the Titanfall folder to /path/to/titanfall/drive_c/Program Files (x86)/Origin Games

    Origin->right click on Titanfall->Locate Game and it will verify the game files.

    After that the game should be ready to play!

Icon for Lutris, [link](https://github.com/begin-theadventure/lutris-scripts/tree/main/lutris-scripts/Titanfall/TitanfallIcon#readme).

Have fun! :)
