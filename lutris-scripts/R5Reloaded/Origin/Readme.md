## [Tutorial](https://www.reddit.com/r/r5reloaded/comments/wv19jf/r5reloaded_works_on_linux_v2/)

Hey!

This is a tutorial on how to play R5Reloaded on Linux.

From v2.0.2_rc, the workaround that was to run lutris with "echo 1 |" is no longer required.

I made a [script](https://github.com/begin-theadventure/lutris-scripts/releases/tag/R5Reloaded) for Lutris which will set the prefix.

It's based on [Apex Legends](https://lutris.net/games/apex-legends) and [Origin](https://lutris.net/games/origin) scripts.

Before, follow the tutorial on how to properly install R5Reloaded on YT https://youtu.be/FOkehL03CFc or on R5Reloaded [Discord](https://discord.com/invite/r5reloaded) in [#instructions](https://discord.com/channels/873158454850756638/873170878475669514/995977751502803014).

You can also use my auto shell [scripts](https://github.com/begin-theadventure/r5reloaded-upllers/releases) to download the client.

Steps for Lutris:

1. Click + near "Search games".
2. Choose "Install from a local install [script](https://github.com/begin-theadventure/lutris-scripts/releases/download/R5Reloaded/r5reloaded-origin.json)". and open it. After succesful installation, click Launch.
3. Disabling **hardware acceleration** (you can skip this).
    To disable **hardware acceleration**, which in my case uses 500+ MiB of GPU (!) see this Reddit post, [link](https://www.reddit.com/r/origin/comments/q8o9gv/disable_origin_client_hardware_acceleration). In our case, the directory is /path/to/r5reloaded/drive_c/Program Files (x86)/Origin/platfo
4. Add the game to Origin.

    ADD A GAME -> Non-Origin Game... r5apex.exe starts the game automatically, launcher.exe allows to choose various options.

Images for Lutris (banner, covert art and icon), [link](https://github.com/begin-theadventure/lutris-scripts/tree/main/R5Reloaded/images/R5ReloadedImagesLutris#readme). [Source/preview](https://twitter.com/R5Reloaded).

Another way is to use Bottles. Since I don't use it this video may be helpful: https://youtu.be/VqDgrHCPWG8?t=368

You can play with Steam+Proton too.

Before download [Origin installer](https://download.dm.origin.com/origin/live/OriginSetup.exe) and [GE-Proton7-37](https://github.com/GloriousEggroll/proton-ge-custom/releases/tag/GE-Proton7-37) (thanks lu7e for the info; you can try a different version, but it may not work), put it in ~/.local/share/Steam/compatibilitytools.d or use [ProtonUp-Qt](https://github.com/DavidoTek/ProtonUp-Qt/releases).

Steps for Steam:

1. ADD A GAME -> Add a Non-Steam Game... -> OriginSetup.exe.
2. Right click -> Properties... -> COMPATIBILITY:.
3. Disabling **hardware acceleration** (you can skip this).
    To disable **hardware acceleration**, which in my case uses 500+ MiB of GPU (!) see this Reddit post, [link](https://www.reddit.com/r/origin/comments/q8o9gv/disable_origin_client_hardware_acceleration). In our case, the directory is /path/to/x/prefix/drive_c/Program Files (x86)/Origin/platfo
4. PLAY -> install Origin and after close.
5. Find the prefix under: ~/.local/share/Steam/steamapps/compatdata/x
6. Right click -> Properties... -> TARGET: "/path/to/x/pfx/drive_c/Program Files (x86)/Origin/Origin.exe" and START IN: "/path/to/x/pfx/".
7. PLAY -> Origin: ADD A GAME -> Non-Origin Game... r5apex.exe
8. Play.

Images for Steam, [link](https://github.com/begin-theadventure/lutris-scripts/tree/main/utris-scripts/R5Reloaded/images/R5ReloadedImagesSteam). [Source/preview](https://twitter.com/r5reloaded).

Have fun! :)

[v1 tutorial](https://www.reddit.com/r/ApexLegendsOnLinux/comments/pd56t5/r5reloaded_is_working_on_gnulinux/)
