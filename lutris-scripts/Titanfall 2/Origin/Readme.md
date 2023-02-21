## Tutorial
_Before see [this Twitter post](https://twitter.com/p0358/status/1626811868412010497)._

Hello.

This is a tutorial on how to play Titanfall 2 on Linux with Lutris+Wine.

I made a [script](https://github.com/begin-theadventure/lutris-scripts/releases/tag/Titanfall-2) for Lutris that will set the prefix.

It's based on [Titanfall 2](https://lutris.net/games/titanfall-2) and [Origin](https://lutris.net/games/origin) scripts.

Steps:

1. Click + near "Search games".
2. Choose "Install from a local install [script](https://github.com/begin-theadventure/lutris-scripts/releases/download/Titanfall-2/titanfall-2-origin.json)" and open it. After succesful installation, click Launch.
3. Changing settings to save resources (you can skip this).

    To disable **hardware acceleration**, which in my case uses 500+ MiB of GPU (!) see this Reddit post, [link](https://www.reddit.com/r/origin/comments/q8o9gv/disable_origin_client_hardware_acceleration). In our case, the directory is /path/to/titanfall-2/drive_c/Program Files (x86)/Origin/platforms

    Origin->Applications Settings:

    _Origin in-game_: **Enable Origin In-Game**.

    (optional:)

    _Application_: Client update - all off, Start-up options_ - all off.

    _Help improve Origin_: Diagnostics - all off.

4. If you don't have the game files, install them, but if you do, you can add them:

    Symlink the Titanfall2 folder to /path/to/titanfall-2/drive_c/Program Files (x86)/Origin Games

    Origin->right click on Titanfall 2->Locate Game and it will verify the game files.

    After that the game should be ready to play!

Have fun! :)
