## Tutorial
Hey!

So this is a tutorial on how to play the Northstar Client on Linux.

I made an automatic [script](https://github.com/begin-theadventure/lutris-scripts/blob/main/Northstar/northstar-client.json) for Lutris which will set the prefix.

It's based on [R5Reloaded](https://github.com/begin-theadventure/lutris-scripts/blob/main/R5Reloaded/r5reloaded.json) script, which in turn is based on [Origin](https://lutris.net/games/origin), [Apex Legends](https://lutris.net/games/apex-legends) and [EA App](https://lutris.net/games/ea-desktop) scripts.

Before that, download the client, extract the zip file and drop everything into the game folder. However you can also use my automatic shell [script](https://github.com/begin-theadventure/northstar-upllers/releases) or [Viper](https://github.com/0neGal/viper/releases).

Steps:

1. Click + near "Search games".
2. Choose "Install from a local install [script](https://github.com/begin-theadventure/lutris-scripts/releases/download/Northstar/northstar-client.json)".
3. After a successful installation, I recommend to change the Wine version to [Kron4ek Wine-Builds](https://github.com/Kron4ek/Wine-Builds/releases).

    Close Lutris, open [ProtonUp-Qt](https://github.com/DavidoTek/ProtonUp-Qt/releases) and install Kron4ek Wine-Build Vanilla (in case the latest one doesn't work, try [8.0-rc2](https://github.com/Kron4ek/Wine-Builds/releases/tag/8.0-rc2)), re-open and then right-click on the banner->Configure->Runner options->Wine version. After that, launch the EA App, log in and exit the app.

4. Now it depends on where you got the game.

    If from Steam then you can skip it altogether, although have in mind that it won't count the hours played however you can also use Steam in the Wine prefix and run the game using it (if you need help with this, ask me//I might update this soon).

    Steam: Launch EA->in Lutris: ▲->Run EXE inside Wine prefix->NorthstarLauncher.exe

    I recommend to symlink the game folder to path/to/northstar-client/ next to drive_c folder.

    EA App:

    If you've already downloaded the game then it's probably possible to add the game to EA App this way:

    Start downloading Titanfall 2, close the EA App, after that remove the Titanfall2 folder from the path/to/northstar-client/drive_c/Program Files/EA Games/ directory and symlink the game folder to the same folder, open the EA App and now it should verify the files after it's done rename `NorthstarLauncher.exe` to `Titanfall2.exe`. Keep in mind that I haven't tested this.

Images for Lutris (banner, covert art and icon), [link](https://github.com/begin-theadventure/lutris-scripts/tree/main/R5Reloaded/images/R5ReloadedImagesLutris#readme). [Source/preview](https://github.com/R2NorthstarTools/NorthstarLogo).

Another way is to use Bottles. Since I don't use it this video may be helpful: [https://youtu.be/VqDgrHCPWG8?t=368](https://youtu.be/VqDgrHCPWG8?t=368)

Have fun! :)
