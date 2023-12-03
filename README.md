# ![logo](https://raw.githubusercontent.com/azerothcore/azerothcore.github.io/master/images/logo-github.png) AzerothCore
# sql-npc-teleporter

### This is for [AzerothCore](http://www.azerothcore.org)
- This is based upon the excellent work from [Rochet2](https://rochet2.github.io/Portal-Master.html)
- Entirely based on SQL!

#### Features:
This enables a teleporting NPC that will be able to send players to level and faction appropriate destinations such as:
- Zones
- Dungeons
- Raids

It also includes a teleporting NPC that will be able to send players to starting zones (let's say you start as one race but prefer a different starting zone).

### Requirements:
- Tested on AzerothCore release [9a9308](https://github.com/azerothcore/azerothcore-wotlk/commit/9a9308afd16a291e4c88b53c1bc2852223682c19)

### How to install
1. To get the teleporter for the capitals:
   Rename the file `data/sql/db-world/teleporter_capital_npc.dist` to `data/sql/db-world/teleporter_capital_npc.sql`.
2. To get the teleporter for the starting zones:
   Rename the file `data/sql/db-world/teleporter_starting_zone_npc.dist` to `data/sql/db-world/teleporter_starting_zone_npc.sql`.
2. Modify is you see fit.
3. Import to world database.
3. Done :)

## Credits

- [Rochet2]( http://rochet2.github.io) 

AzerothCore: [repository](https://github.com/azerothcore) - [website](http://azerothcore.org/) - [discord chat community](https://discord.gg/PaqQRkd)
