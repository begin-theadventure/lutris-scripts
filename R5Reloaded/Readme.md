## [Tutorial](https://www.reddit.com/r/r5reloaded/comments/wv19jf/r5reloaded_works_on_linux_v2/)

Before follow the tutorial on how to properly install R5Reloaded on YT https://youtu.be/FOkehL03CFc or on R5Reloaded [Discord](https://discord.com/invite/r5reloaded) in [\#instructions](https://discord.com/channels/873158454850756638/873170878475669514/995977751502803014).

You can also use my shell [scripts](https://github.com/begin-theadventure/r5reloaded-updaters/releases/tag/r5reloaded-updaters).

Steps for Lutris:

1. Click + near "Search games".
2. Choose "Install from a local install [script](https://github.com/begin-theadventure/lutris-scripts/releases/download/R5Reloaded/r5reloaded.json)"
3. After a successful installation open R5Reloaded.
4. Origin: ADD A GAME -> Non-Origin Game... r5apex.exe starts the game automatically, launcher.exe allows to choose various options.
5. Play.

Another way is to use Bottles. Since I don't use it this video may be helpful: [https://youtu.be/VqDgrHCPWG8?t=368](https://youtu.be/VqDgrHCPWG8?t=368)

You can play with Proton & Steam too.

Before download [Origin installer](https://download.dm.origin.com/origin/live/OriginSetup.exe) and [NorthstarProton](https://github.com/cyrv6737/NorthstarProton/releases), put it in ~/.local/share/Steam/compatibilitytools.d.

Warning: Unlike Proton-GE, NorthstarProton doesn't have FSR so if you need it contact the maintainer or use Gamescope.

Steps for Steam:

1. ADD A GAME -> Add a Non-Steam Game... -> OriginSetup.exe.
2. Right click -> Properties... -> COMPATIBILITY: NorthstarProton.
3. PLAY -> install Origin and after close.
4. Find the prefix under: ~/.local/share/Steam/steamapps/compatdata/x -> and symlink or move R5Reloaded folder to x/drive_c/Program Files (x86)/Origin Games
5. Right click -> Properties... ->  TARGET: "/path/to/x/pfx/drive_c/Program Files (x86)/Origin/Origin.exe" and START IN: "/path/to/x/pfx/".
6. PLAY -> Origin: ADD A GAME -> Non-Origin Game... -> Origin Games/game/r5apex.exe or launcher.exe.
7. Play.

Have fun! :)
