FiveM Ban/Warning/Help-Assist System for QBCore

---------------
Original Author
---------------
Original resource Author: Elipse458 Discord server Webpage Original resource

------------
Installation
------------
1) Download the resource
2) Rename it to el_bwh and put it in your resources folder
3) Import sql.sql into your database
4) Edit the config to your liking
5) Add start el_bwh to your server.cfg
6) Start it and you're good to go

-------------
Documentation
-------------
There's a few commands this adds:
```
/bwh <- root admin command, this will display all sub-commands
/bwh ban <- opens the ban menu
/bwh warn <- opens the warn menu
/bwh banlist <- opens the ban list
/bwh warnlist <- opens the warning list
/bwh assists <- shows pending/active assists in the chat
/bwh refresh <- pulls all bans from the database and refreshes the ban cache
/accassist <player id> <- admin command, admins can accept help requests from players
/finassist <- admin command, this closes the current help request and teleports you back to your original position
/decassist <- admin command, this just hides the current assist popup on the screen
/assist <reason> <- player command, players can request help with this
/cassist <- player command, this cancels the players ongoing assist request
To unban someone, go to the ban list and scroll far right to the "Actions" section, you'll find a green unban button there
```

---------------
Important Notes
---------------
This bans all players identifiers, that means their ip,license,steam,discord,xbl ids will get banned
Offline bans ban everything that's stored in the identifier db

If find any bugs, please join my discord server and report it in the #bug-reports channel
If you like my work, please check out my page, i'll probably release a few more things if i have the time and feel like it

------------
Dependencies
------------
```
qb-core
oxmysql
```
