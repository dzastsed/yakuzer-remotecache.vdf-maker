# yakuzer-remotecache.vdf-maker
Scripts for making remotecache.vdf files for yakuza games


Based on https://github.com/zarroboogs/p4g-saveconv

Collection of python script files for generating remotecache.vdf files for various yakuza games.

Useful if you are importing converted saves/clear data from PS3/PS4 consoles, or from cracked installations of the game, no judging here.

So far Yakuza 0, Kiwami and 3-5 are supported.




USAGE

1. Find your save files directory (C:\Program Files (x86)\Steam\userdata\userid\638970 for Yakuza 0, C:\Program Files (x86)\Steam\userdata\userid\834530 for Yakuza Kiwami).
2. Delete existing remotecache.vdf, if it exists.
3. Run the script while pointing to ``remote`` as save dir - Yakuza Kiwami as an example here - (``python remotecache-kiwami.py "C:\Program Files (x86)\Steam\userdata\userid\834530\remote"``, and new remotecache.vdf file should be generated.
4. Launch steam in offline mode (MAKE SURE TO DO A FULL RESTART!) and run your game, check if it detects your save data.
5. If everything is correct, you can launch steam in online mode, and start the game again. If asked about save conflict, choose local saves.
6. That's it, have fun playing!

KNOWN ISSUES:

Clear data does not get detected properly on 0/Kiwami, no idea why.
