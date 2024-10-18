This repository contains the mods I have created for [GZDoom](https://zdoom.org). As these are personal works, no pull requests or other forms of communication are accepted on this repository.

# Structure

Each mod is stored in a single toplevel folder, containing at least:
- A `LICENSE.md` file detailing the licensing of the resources included in the mod. Typically, anything I create myself will be placed into the public domain as per usual. However, third-party resources (such as textures, sprites and music) may have their own licensing rules which the file will outline.
- A `gameinfo.txt` file that outlines which of the ZDoom family of games (IWADs) the mod is built for. You could purchase the original id Software titles, or substitute them for their free equivalents. For mods that ask for `DOOM.WAD` or `DOOM2.WAD`, you can substitute that for `freedoom1.wad` and `freedoom2.wad` respectively. For mods that ask for `HERETIC.WAD`, you can substitute that for `blasphem.wad`. No other IWADs are required by anything here.

# Downloading

To get the complete mod set, click [here](https://github.com/andOlga/wads/archive/refs/heads/master.zip).

To download individual mods, click the folder for the mod you want, then copy the URL from your address bar and paste it [here](https://download-directory.github.io/).

# Playing

To play any of the mods, you can do any of the following:
- Drag-and-drop the mod's folder itself onto `gzdoom.exe` (Windows only).
- Pass the path to the mod's folder into a `-file` parameter when starting GZDoom.
- Zip the folder up and rename the archive to `.pk3`, then double-click it to play (picking GZDoom for the file association if prompted).
  - If you downloaded an indivudal mod per instructions above, the ZIP you get from that can be renamed into `.pk3` directly.  
