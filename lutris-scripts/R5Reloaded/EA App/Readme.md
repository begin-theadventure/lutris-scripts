## [Tutorial](https://www.reddit.com/r/r5reloaded/comments/wv19jf/r5reloaded_works_on_linux_v2/)

Hey!

From v2.0.2_rc the workaround that was launching lutris with "echo 1 |" is no longer required.

I made an automatic [script](https://github.com/begin-theadventure/lutris-scripts/releases/tag/R5Reloaded) for Lutris which will set the prefix.

It's based on [Origin](https://lutris.net/games/origin), [Apex Legends](https://lutris.net/games/apex-legends) and [EA App](https://lutris.net/games/ea-desktop) scripts.

Before follow the tutorial on how to properly install R5Reloaded on YT https://youtu.be/FOkehL03CFc or on R5Reloaded [Discord](https://discord.com/invite/r5reloaded) in [#instructions](https://discord.com/channels/873158454850756638/873170878475669514/995977751502803014).

You can also additionally use my shell [scripts](https://github.com/begin-theadventure/r5reloaded-upllers/releases) to download the needed files.

Steps for Lutris:

1. Click + near "Search games".
2. Choose "Install from a local install [script](https://github.com/begin-theadventure/lutris-scripts/releases/download/R5Reloaded/r5reloaded-ea-app.json)".
3. After a successful installation, I recommended to change the Wine version to [wine-ge-custom](https://github.com/GloriousEggroll/wine-ge-custom/releases).

    Close Lutris, open [ProtonUp-Qt](https://github.com/DavidoTek/ProtonUp-Qt/releases) and install Wine-GE (in case the latest one doesn't work, try [7-35](https://github.com/GloriousEggroll/wine-ge-custom/releases/tag/GE-Proton7-35)), re-open and then right click on the banner->Configure->Runner options->Wine version. After that, launch the EA App, log in and exit the app.

4. Unfortunately there's no "Non-EA App Game" option like in Origin, instead we can change the executable file from EADesktop.exe to r5apex.exe.

    Right click on the banner->Configuration->Game Options->Executable->path/to/r5apex.exe

    Now it'll launch the EA App and after it has launched we need to run the exe again, so just double-click on the R5Reloaded banner and after that the game should launch!

Images for Lutris (banner, covert art and icon), [link](https://github.com/begin-theadventure/lutris-scripts/tree/main/R5Reloaded/images/R5ReloadedImagesLutris#readme). [Source/preview](https://twitter.com/R5Reloaded).

Another way is to use Bottles. Since I don't use it this video may be helpful: [https://youtu.be/VqDgrHCPWG8?t=368](https://youtu.be/VqDgrHCPWG8?t=368)

Have fun! :)

[v1 tutorial](https://www.reddit.com/r/ApexLegendsOnLinux/comments/pd56t5/r5reloaded_is_working_on_gnulinux/)
