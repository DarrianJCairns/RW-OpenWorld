# Open World - Server Files
## A Free Multiplayer Mod For Rimworld.

Attention! This is a work in progress mod! Things are prone to breaking! If you find something broken please post it!

Attention! Needs .Net 6.0 or newer to work!
x32: https://dotnet.microsoft.com/en-us/download/dotnet/thank-you/runtime-desktop-6.0.2-windows-x86-installer
x64: https://dotnet.microsoft.com/en-us/download/dotnet/thank-you/runtime-desktop-6.0.2-windows-x64-installer

**Things to know before using?**
- To host a private server you will need to forward a dedicated port for your server to comunicate using TCP protocol! I can't guide everyone on how to do this as it varies per internet provider / router. So you might need to follow a tutorial to achieve it.
- Check the releases tab to download the server files! At the right of the Github page!

## Server Setup
The server distributes the files in 4 different parts.
- Mods.
- Players.
- Server Settings.
- World Settings.

**Mods:**

If you want to play with mods, copy your essential mods, the ones you will be forcing your players to use, in the "Mods" folder. Restart your server if your mods folder is missing.

You can also place whitelisted mods in the "Whitelisted Mods" folder. This are mods that are allowed, but not essential to play in the server. This mods may include graphic or sound mods.

**Players:**

All the player files are stored in the "Players" folder, this files contain all the data of each player, and they can't be modified by normal means, trying to do so will probably result in permanent file corruption for said player. If you want to erase a player from the server, simply delete this file and upon restarting, the player will no longer be listed.

Please DO NOT manually create player files. Doing so will cause the server to crash on load.

**Server Settings:**

This file contains all the server configuration parameters that you can adjust as a server owner. The list of options will grow as time comes. In this file, you MUST NOT forget to change the configuration of the IP and Port used to your liking or the server might not start at all. You must write the LOCAL IP of the system hosting the server in the IP setting.

**World Settings:**

This file contains all the world configurables. It comes with default parameters, so you might adjust them to your liking, changing this file requires all players, new and old, to create a new game to prevent map mismatching, although you should not need to change this file again after doing it at first world creation.

**Found a bug?**
- First check you are using the latest version, then, please, submit it! By doing so you are helping not only me but also every other user of this program. It helps out a ton!

**Thanks a bunch for downloading the mod! - Lollipop.**
