## [Tutorial](https://www.reddit.com/r/r5reloaded/comments/wv19jf/r5reloaded_works_on_linux_v2)
Hello.

This tutorial's on how to play R5Reloaded on Linux.

From v2.0.2_rc, the workaround to run Lutris with "echo 1 |" is no longer required.

I made a [script](https://github.com/begin-theadventure/lutris-scripts/releases/tag/R5Reloaded) for Lutris, which will set the prefix.

It's based on [Apex Legends](https://lutris.net/games/apex-legends) and [Origin](https://lutris.net/games/origin) scripts.

Before, follow the tutorial on how to properly install R5Reloaded on [YouTube](https://youtu.be/FOkehL03CFc) or R5Reloaded [Discord](https://discord.com/invite/r5reloaded) in [#instructions](https://discord.com/channels/873158454850756638/873170878475669514/995977751502803014).

You can also use my automatic [shell scripts](https://github.com/begin-theadventure/r5reloaded-upllers/releases) to install and update the client (after following the tutorial).

Steps for Lutris:

1. Click + near "Search games".

2. Choose "Install from a local install [script](https://github.com/begin-theadventure/lutris-scripts/releases/download/R5Reloaded/r5reloaded-origin.json)" and open it. After successful installation, click Launch.

3. Changing settings to save resources and other things (not necessary).

    To disable **hardware acceleration**, which in my case uses 500+ MiB of GPU (!), see this [Reddit post](https://www.reddit.com/r/origin/comments/q8o9gv/disable_origin_client_hardware_acceleration). In our case, the directory is /path/to/r5reloaded/drive_c/Program Files (x86)/Origin/platforms

    Origin->Applications Settings:

    _Application_: Client update - all off, Start-up options_ - all off.

    _Help improve Origin_: Diagnostics - all off.

    _Origin in-game_: Enable Origin In-Game.

4. Add the game to Origin.

    ADD A GAME -> Non-Origin Game... r5apex.exe starts the game automatically and launcher.exe allows you to choose various options.

[Images for Lutris](https://github.com/begin-theadventure/lutris-scripts/tree/main/lutris-scripts/R5Reloaded/images/R5ReloadedImagesLutris#readme). [Source/preview](https://twitter.com/R5Reloaded) (banner, covert art and icon).

Have fun! :)
