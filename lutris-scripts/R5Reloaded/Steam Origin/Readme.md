## [Tutorial](https://www.reddit.com/r/r5reloaded/comments/wv19jf/r5reloaded_works_on_linux_v2)
Hello.

This tutorial is on how to play R5Reloaded on Linux with Steam+Proton.

Steps:

0. Use an _alt account_ just in case of a ban (better be careful).

1. Download the [Origin installer](https://download.dm.origin.com/origin/live/OriginSetup.exe) and [GE-Proton7-37](https://github.com/GloriousEggroll/proton-ge-custom/releases/tag/GE-Proton7-37) (thanks to lu7e for the info; you can try a different version, but it may not work), put it in `~/.local/share/Steam/compatibilitytools.d` or use [ProtonUp-Qt](https://github.com/DavidoTek/ProtonUp-Qt/releases).

2. Add to Steam.

    Add a Game -> Add a Non-Steam Game -> Browse... -> OriginSetup.exe.

    Right click -> Properties... -> Compatibility -> Force Proton -> GE-Proton7-37.

    PLAY -> install Origin and close.

3. Find the prefix in `~/.local/share/Steam/steamapps/compatdata/`x

    Right click -> Properties... -> TARGET: /path/to/x/`pfx/drive_c/Program Files (x86)/Origin/Origin.exe` and START IN: /path/to/x/`pfx`

4. Download the [Origin patch](https://github.com/p0358/Fuck_off_EA_App/releases/latest) and install it (TARGET)

5. Download the [R5Reloaded Launcher](https://r5reloaded.com/download), install it (TARGET), and "Install Apex".

    After installing, click "Launch Apex" and log in to Origin.

    And then: Search games and more -> Apex Legends -> Add to Library

Launch Apex (with the R5Reloaded launcher)

6. Change settings to save resources, etc. (optional).

    To disable **hardware acceleration**, which in my case can use 500+ MiB of GPU, see this [Reddit post](https://www.reddit.com/r/origin/comments/q8o9gv/disable_origin_client_hardware_acceleration). In our case, the directory is /path/to/x/pfx/drive_c/Program Files (x86)/Origin/platforms

    Origin -> Applications Settings:

    _Application_: Client update, and Start-up options } off

    _Diagnostics_: Help improve Origin } off

    _Origin in-game_: Enable Origin In-Game - off

[Images for Steam](https://github.com/begin-theadventure/lutris-scripts/tree/main/lutris-scripts/R5Reloaded/images/R5ReloadedImagesSteam#readme). [Source/preview](https://x.com/r5reloaded).

If you need assistance, open [an issue here](https://github.com/begin-theadventure/lutris-scripts/issues/new) or come to the [R5Reloaded Discord](https://discord.gg/r5reloaded) ([Linux thread](https://discord.com/channels/873158454850756638/880164364898951178)).
