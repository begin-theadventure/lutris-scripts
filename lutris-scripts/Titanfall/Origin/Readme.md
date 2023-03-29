## Tutorial
Hello.

This tutorial's on how to play Titanfall on Linux with Lutris+Wine.

I made a [script](https://github.com/begin-theadventure/lutris-scripts/releases/tag/Titanfall) for Lutris that will set the prefix.

It's based on the [Northstar](https://github.com/begin-theadventure/lutris-scripts/tree/main/lutris-scripts/Northstar) script.

Steps:

1. Click + near "Search games".

2. Choose "Install from a local install [script](https://github.com/begin-theadventure/lutris-scripts/releases/download/Titanfall/titanfall-origin.json)" and open it. After a successful installation, click Launch.

3. Log in to Origin and see this [Twitter post](https://twitter.com/p0358/status/1635796691902160896).

    The proper exe is already installed by the script.

    Empty value "" for UpdateURL also works.

    In our case, the directory is /path/to/titanfall/drive_c/ProgramData/Origin/local.xml

4. Changing settings to save resources (not necessary).

    To disable **hardware acceleration**, which in my case uses 500+ MiB of GPU (!), see this [Reddit post](https://www.reddit.com/r/origin/comments/q8o9gv/disable_origin_client_hardware_acceleration). In our case, the directory is /path/to/titanfall/drive_c/Program Files (x86)/Origin/platforms

    Origin->Applications Settings:

    _Origin in-game_: **Enable Origin In-Game**.

    _Application_: Client update - all off, Start-up options_ - all off.

    _Help improve Origin_: Diagnostics - all off.

5. If you don't have the game files, install them, but if you do, you can add them:

    Symlink the Titanfall folder to /path/to/titanfall/drive_c/Program Files (x86)/Origin Games

    Origin->right click on Titanfall->Locate Game, and it will verify the game files.

After that, the game should be ready to play!

[Icon for Lutris](https://github.com/begin-theadventure/lutris-scripts/tree/main/lutris-scripts/Titanfall/TitanfallIcon#readme).

Have fun! :)
