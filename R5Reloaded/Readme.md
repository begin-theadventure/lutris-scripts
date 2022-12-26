Sha512sum (r5reloaded.json):
`````
8ee0ca96bdfb49f5bcf28dd279a1c2f2f175668062b2c8780adda2ad8f47a10339dbafd57a4d54616b88d8040fe2e41de8a5f92f7cfe35c27a392f0559234528
`````

## [Tutorial](https://www.reddit.com/r/r5reloaded/comments/wv19jf/r5reloaded_works_on_linux_v2/)

26 Dec 2022 EDIT: Updated tutorial and script for Lutris.

Hey!

So this is a v2 tutorial on how to play R5Reloaded on Linux

From v2.0.2_rc the workaround that was launching lutris with "echo 1 |" is no longer required.

I made an automatic [script](https://github.com/begin-theadventure/lutris-scripts/blob/main/R5Reloaded/r5reloaded.json) for Lutris which will set the prefix.

It's based on [Origin](https://lutris.net/games/origin), [Apex Legends](https://lutris.net/games/apex-legends) and [EA App](https://lutris.net/games/ea-desktop) scripts.

Before follow the tutorial on how to properly install R5Reloaded on YT https://youtu.be/FOkehL03CFc or on R5Reloaded [Discord](https://discord.com/invite/r5reloaded) in [#instructions](https://discord.com/channels/873158454850756638/873170878475669514/995977751502803014).

You can also additionally use my shell [scripts](https://github.com/begin-theadventure/r5reloaded-upllers/releases) to download the needed files.

Steps for Lutris:

1. Click + near "Search games".
2. Choose "Install from a local install [script](https://github.com/begin-theadventure/lutris-scripts/releases/download/R5Reloaded/r5reloaded.json)".
3. After a successful installation, I recommended to change the Wine version to [wine-ge-custom](https://github.com/GloriousEggroll/wine-ge-custom/releases).

    Close Lutris, add it with [ProtonUp-Qt](https://github.com/DavidoTek/ProtonUp-Qt/releases), re-open and then right click on the banner->Configure->Runner options->Wine version. After that, launch the EA App, log in and exit the app.

4. Unfortunately there's no "Non-EA App Game" option like in Origin, instead we can change the executable file from EADesktop.exe to r5apex.exe. Right-click on the banner->Configuration->Game Options->Executable->Path/to/r5apex.exee.

    Right click on the banner->Configuration->Game Options->Executable->path/to/r5apex.exe

    Now it'll launch the EA App and after it has launched we need to run the exe again, so just double-click on the R5Reloaded banner and after that the game should launch!

Images for Lutris (banner, covert art and icon), [link](https://github.com/begin-theadventure/lutris-scripts/tree/main/R5Reloaded/images/R5ReloadedImagesLutris#readme). [Source/preview]( https://nitter.net/R5Reloaded).

Another way is to use Bottles. Since I don't use it this video may be helpful: [https://youtu.be/VqDgrHCPWG8?t=368](https://youtu.be/VqDgrHCPWG8?t=368)

You can play with Steam too however I don't recommend it.

//Steam tutorial wasn't updated for EA App.

Before download [Origin installer](https://download.dm.origin.com/origin/live/OriginSetup.exe) and [GE-Proton7-37](https://github.com/GloriousEggroll/proton-ge-custom/releases/tag/GE-Proton7-37) (thanks lu7e for the info; you can try a different version, but it may not work), put it in ~/.local/share/Steam/compatibilitytools.d.

Steps for Steam:

1. ADD A GAME -> Add a Non-Steam Game... -> OriginSetup.exe.
2. Right click -> Properties... -> COMPATIBILITY:.
3. PLAY -> install Origin and after close.
4. Find the prefix under: ~/.local/share/Steam/steamapps/compatdata/x
5. Right click -> Properties... ->  TARGET: "/path/to/x/pfx/drive_c/Program Files (x86)/Origin/Origin.exe" and START IN: "/path/to/x/pfx/".
6. PLAY -> Origin: ADD A GAME -> Non-Origin Game... r5apex.exe starts the game automatically, launcher.exe allows to choose various options.

   (I recommend to symlink or move the R5Reloaded folder to x/drive_c/Program Files (x86)/Origin Games).
7. Play.

Images for Steam, [link](https://github.com/begin-theadventure/lutris-scripts/tree/main/R5Reloaded/images/R5ReloadedImagesSteam). [Source/preview]( https://nitter.net/R5Reloaded).

Have fun! :)

[v1 tutorial](https://www.reddit.com/r/ApexLegendsOnLinux/comments/pd56t5/r5reloaded_is_working_on_gnulinux/)
