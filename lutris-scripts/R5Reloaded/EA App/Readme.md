## [Tutorial](https://www.reddit.com/r/r5reloaded/comments/wv19jf/r5reloaded_works_on_linux_v2)
Hello.

This tutorial's on how to play R5Reloaded on Linux with Lutris+Wine.

From v2.0.2_rc, the workaround to run Lutris with "echo 1 |" is no longer required.

I made a [script](https://github.com/begin-theadventure/lutris-scripts/releases/tag/R5Reloaded) for Lutris, which will set the prefix.

It's based on [Apex Legends](https://lutris.net/games/apex-legends), the [EA App](https://lutris.net/games/ea-desktop) scripts and this [Reddit post](https://www.reddit.com/r/linux_gaming/comments/qhq3pn/ea_desktop_finally_working).

Before, follow the tutorial on how to properly install R5Reloaded on [YouTube](https://youtu.be/FOkehL03CFc) or R5Reloaded [Discord](https://discord.com/invite/r5reloaded) in [#instructions](https://discord.com/channels/873158454850756638/873170878475669514/995977751502803014).

After following the tutorial, you can use my [shell scripts](https://github.com/begin-theadventure/r5reloaded-upllers/releases) to install and update the client.

Steps:

1. Click + near "Search games".

2. Choose "Install from a local install [script](https://github.com/begin-theadventure/lutris-scripts/releases/download/R5Reloaded/r5reloaded-ea-app.json)". After a successful installation, click Close.

3. Unfortunately, there's no "Non-EA App Game"; instead, we can change the executable file from EADesktop.exe to r5apex.exe.

    Right-click on the banner->Configuration->Game Options->Executable->path/to/ r5apex.exe starts the game automatically and launcher.exe allows you to choose various options.

    Now it'll launch the EA App, log in and after it has launched, we need to rerun the exe, so double-click on the R5Reloaded banner, and the game should launch!

[Images for Lutris](https://github.com/begin-theadventure/lutris-scripts/tree/main/lutris-scripts/R5Reloaded/images/R5ReloadedImagesLutris#readme) (banner, covert art and icon). [Source/preview](https://twitter.com/R5Reloaded).

Have fun! :)
