# Allay Client downloads

Allay Client is an all-in-one Fabric client for Minecraft 26.2 and 26.3.

## Get it

On Linux, download the [Allay Launcher AppImage](https://github.com/JoddabodScripts/allay-releases/raw/main/launcher/allay-launcher-0.1.0-x86_64.AppImage), make it executable (`chmod +x allay-launcher-*.AppImage`), and run it.

The launcher downloads Java, Minecraft, Fabric and the newest Allay Client by itself. It keeps everything in `~/.allay` and never touches `.minecraft`. Sign in with the account you use in Modrinth App, or play offline in singleplayer.

To use Allay with another launcher, take the newest jar from [allay/](allay) and put it in a Fabric 26.2 or 26.3 mods folder.

## For the launcher

`latest.json` names the newest Allay jar and launcher. The launcher reads it on startup and before each launch, and downloads a newer jar when there is one.
