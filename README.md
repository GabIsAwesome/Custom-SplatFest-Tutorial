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
00000544 is the file you will need to edit to make the Splatfest work. The others are from the panel images and the tee images, which needs to be all from the same size to that's why we're not editing them, but you're free to edit them though.<br />
Open the file with NOTEPAD++ or with a byaml editor, and start editing! While using Notepad++, you will notice strange symbols and that's normal. **Editing the character's speaking lines will break the files (for some reason?)**. Anyways, search for "2017" in the file and then start editing the dates.
And that's it. <br />
I don't really know why people keep trying to hide these types of things but anyways that's it lol
# Troubleshooting
If the game says that you don't have an Internet connection, you broke the files. This may happen if you modify the character's speaking lines, or modify the tee/panel images incorrectly. To make them work, restore from the backup you made.
# Can I join public matches with the Splatfest on?
Yep! You will end up on an empty lobby but if other people that also did the same thing joins your lobby you should be able to play.
# Warnings
Do NOT use the Splatfest Tee in friend matches and only use it on the Splatfest Lobbies. Otherwise people may report you and get your console and your NNID banned!
