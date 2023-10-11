# Custom SplatFest Tutorial
Simple tutorial for custom splatfests on Splatoon 1. For some reason people keep trying to hide on how to make them so y'all's secrets are gone now ^-^
# Anyways, how do you even do it?
Well, It's not that hard. I personally recommend **dumping online files from your Wii U to use with Cemu**, because this requires editing files that are downloaded from Nintendo's servers to your Wii U's NAND, and therefore modifying these files (which we're going to do) can cause permanent bricks. **Also note your game's region NEEDS to be USA for this to work!**
# Setup
**UPDATE: An app called "Toolbox" can make the editing process easier than ever because it supports the majority of Nintendo's game files from Wii U, 3DS and Switch, and also has an interactive interface. Download it at https://github.com/KillzXGaming/Switch-Toolbox/releases/tag/EXPERIMENTAL_LATEST. To edit the 00000544 file, just drag the file into the program once it's open. Thanks for whoever created this app :)**
<br />
**WARNING: Deleting the files will make the game crash every time the game is started. Make sure to make backups of the original files before modifying them so you can play normally!**
<br />
After dumping the files and starting the game from the first time (it will download the BOSS files), go to [YOUR CEMU FOLDER]\mlc01\usr\boss\00050000\10176900\user\common\data\optdat2. If everything goes right, there should be three files, 00000543, 00000544 and 00000545.
00000544 is the file you will need to edit to make the Splatfest work. The others are from the panel images and the tee images, which needs to be all from the same size to that's why we're not editing them, but you're free to edit them and figure how they work though.<br />
Assuming that you're using Toolbox, to edit the file properly (toolbox apparently doesn't handle the "\n" newline character the speak lines have, so, editing the speak lines will break the file), right click on the first entry on the byaml tree, then click "Export". Open the file with Notepad++, then Once you're done changing stuff, do the same thing as before, then click "Import", if it says the file isn't supported, change the file extension to ".xml".<br />
This tutorial is missing a lot of stuff, this is only the basic stuff you can do on the file(s), but with this you can figure stuff yourself and then make your own custom splatfest. <br />
# About 00000543 and 0000545
These are the Splatfest Tee and Panel files. They have the panel image and shirt textures on them. You're free to modify them using the same application as before, but the game is really picky about these files and they should be modified correctly, otherwise the files will stop working.
# Troubleshooting
- If the game says that you don't have an Internet connection, you broke the files. This may happen if you modify the character's speaking lines without exporting the file first, or modify the tee/panel images incorrectly. To make them work again, restore from the backup you made and try again.
- All files should have the same fest ID. If you modify the fest ID on one file, you will need to modify it on the other remaining two files. Not doing so will break the files.
# Can I join public matches with the Splatfest on?
Yep! You will end up on an empty lobby but if other people that also did the same thing or has the same files joins your lobby you should be able to play.
# Warnings
Do NOT use the Splatfest Tee in friend matches and only use it on the Splatfest Lobbies. Otherwise people may report you and get your console and your NNID banned!
