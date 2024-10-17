This repository contains the mods I have created for [GZDoom](https://zdoom.org).

Each mod is stored in a single toplevel folder, containing at least:
- A `LICENSE.md` file detailing the licensing of the resources included in the mod. Typically, anything I create myself will be placed into the public domain as per usual. However, third-party resources (such as textures, sprites and music) may have their own licensing rules which the file will outline.
- A `gameinfo.txt` file that outlines which of the ZDoom family of games (IWADs) the mod is built for. You could purchase the original id Software titles, or substitute them for their free equivalents. For mods that ask for `DOOM.WAD` or `DOOM2.WAD`, you can substitute that for `freedoom1.wad` and `freedoom2.wad` respectively. For mods that ask for `HERETIC.WAD`, you can substitute that for `blasphem.wad`.

To play any of the mods, you can do any of the following:
- Drag-and-drop the folder itself onto `gzdoom.exe` (Windows only).
- Pass the path to the mods folder into a `-file` parameter when starting GZDoom.
- Zip the folder up and rename the archive to `.pk3`, then double-click it to play (picking GZDoom for the file association if prompted).

No pull requests or other forms of communication are accepted on this repository.
