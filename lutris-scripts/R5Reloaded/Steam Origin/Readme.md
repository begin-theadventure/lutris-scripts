## [Tutorial](https://www.reddit.com/r/r5reloaded/comments/wv19jf/r5reloaded_works_on_linux_v2)
Hello.

This tutorial's on how to play R5Reloaded on Linux.

From v2.0.2_rc, the workaround to run Lutris with "echo 1 |" is no longer required.

Before, follow the tutorial on how to properly install R5Reloaded on YT https://youtu.be/FOkehL03CFc or R5Reloaded [Discord](https://discord.com/invite/r5reloaded) in [#instructions](https://discord.com/channels/873158454850756638/873170878475669514/995977751502803014).

You can also use my automatic [shell scripts](https://github.com/begin-theadventure/r5reloaded-upllers/releases) to download the client.

Steps:

1. Download the [Origin installer](https://taskinoz.com/downloads/OriginSetup-10.5.119.52718.exe) and [GE-Proton7-37](https://github.com/GloriousEggroll/proton-ge-custom/releases/tag/GE-Proton7-37) (thanks lu7e for the info; you can try a different version, but it may not work), put it in ~/.local/share/Steam/compatibilitytools.d or use [ProtonUp-Qt](https://github.com/DavidoTek/ProtonUp-Qt/releases).

2. ADD A GAME -> Add a Non-Steam Game... -> OriginSetup.exe.

3. Right click -> Properties... -> COMPATIBILITY:.

4. PLAY -> install Origin and after close.

5. Find the prefix in ~/.local/share/Steam/steamapps/compatdata/x

6. Right click -> Properties... -> TARGET: "/path/to/x/pfx/drive_c/Program Files (x86)/Origin/Origin.exe" and START IN: "/path/to/x/pfx/"

7. Log in to Origin and see this [Twitter post](https://twitter.com/p0358/status/1635796691902160896).

    The proper exe was linked by me earlier.

    Empty value "" for UpdateURL should also work.

    In our case, the directory is /path/to/x/pfx/drive_c/ProgramData/Origin/local.xml

8. Changing settings to save resources and other things (not necessary).

    To disable **hardware acceleration**, which in my case uses 500+ MiB of GPU (!), see this [Reddit post](https://www.reddit.com/r/origin/comments/q8o9gv/disable_origin_client_hardware_acceleration). In our case, the directory is /path/to/x/pfx/drive_c/Program Files (x86)/Origin/platforms

    Origin->Applications Settings:

    _Application_: Client update - all off, Start-up options_ - all off.

    _Help improve Origin_: Diagnostics - all off.

    _Origin in-game_: Enable Origin In-Game.

9. Origin: ADD A GAME -> Non-Origin Game... r5apex.exe starts the game automatically and launcher.exe allows you to choose various options.

10. Play.

[Images for Steam](https://github.com/begin-theadventure/lutris-scripts/tree/main/lutris-scripts/R5Reloaded/images/R5ReloadedImagesSteam#readme). [Source/preview](https://twitter.com/r5reloaded).

Have fun! :)
