# Allay Client downloads

Allay Client is an all-in-one Fabric client for Minecraft 26.2 and 26.3.

## Get it

Download the launcher from the [launcher release](https://github.com/JoddabodScripts/allay-releases/releases/tag/launcher-0.1.0).

- Linux: `allay-launcher-0.1.0-x86_64.AppImage`. Make it executable (`chmod +x`), then run it.

The launcher downloads Java, Minecraft, Fabric and the newest Allay Client by itself. It keeps everything in `~/.allay` and never touches `.minecraft`.

To use Allay with another launcher, grab `allay-client-<version>.jar` from the [releases](https://github.com/JoddabodScripts/allay-releases/releases) and put it in your Fabric 26.2 or 26.3 mods folder.

## For the launcher

`latest.json` tells the launcher which Allay version is newest. The launcher reads it on startup and before each launch.
