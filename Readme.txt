Erik's True Tracks

***

This is a simple mod that replaces the wolf tracks in Caves and Tyrannosaur tracks in Lost Valley to make them more accurate.

The levels are otherwise untouched. New textures are in the original resolution, not HD, so they should fit the aesthetic, with or without bilinear filtering.

***

Installation:

1. Download the two LEVEL files in the DATA folder. (Or download the full repo as a .zip, unzip it, and find the two LEVEL files in DATA.)

2. Find your Tomb Raider installation. I have a Steam copy, so I'll open a new File Explorer window and navigate to C:\Program Files (x86)\Steam\steamapps\common\Tomb Raider (I).
Tip: You can also open your Steam library, right-click on Tomb Raider (I), and click Open Folder Location.

3. (Optional) Make backups of your original level files, in case you want to revert. Rename LEVEL1.PHD and LEVEL3A.PHD to something like "LEVEL1_orig.PHD" and "LEVEL3A_orig.PHD".

4. Copy the two LEVEL files from the mod's DATA folder to your installation's DATA folder, and overwrite.

***

You can use TRMOD 0.3 to apply these textures files yourself, if you'd like to merge them with another texture mod.

1. Find the following textures in the Texture samples folder, and copy them alongside TRMOD.exe and the level files LEVEL1.PHD and LEVEL3A.PHD.
    level1_textile0_mod.bmp
    level1_textile3_mod.bmp
    level3a_textile3_mod.bmp

2. Run the following commands on the command line (or PowerShell).
    .\TRMOD LEVEL1.PHD replace texture 0 level1_textile0_mod.bmp
    .\TRMOD LEVEL1.PHD replace texture 3 level1_textile3_mod.bmp
    .\TRMOD LEVEL3A.PHD replace texture 3 level3a_textile3_mod.bmp

***

This mod is compatible with TombATI.
It should be compatible with the Tomb Raider releases from Steam, GOG, or the original CDs.
It is probably not compatible with other level mods or HD mods.
Save files from the original versions of these levels should be compatible.
The gameplay of these levels is identical to the original game; however, mods like this are not approved by the moderators on Speedrun.com, so I'd advise against using it for any runs you're planning on submitting.

The idea for this mod came to me while watching Beckski93 attempt various Board Raiders challenges on Twitch. Shout out to Becks and her chat -- hey y'all! (https://www.twitch.tv/beckski93)

This mod was made with TRMOD 0.3 (https://github.com/Aerik72/TRMOD)
