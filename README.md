Gotcha-Antihack
===============
Changelog:

1.1:

08.02.2012
[FIXED] Freezing during filtering log items

[FIXED] Freezing during filtering for players

[FIXED] Various spelling mistakes

[FIXED] Various grammar errors

[FIXED] Flickering of log tabs

[FIXED] Flickering of player tab

[FIXED] Increased overall consistency of naming

[FIXED] Bottom buttons disappearing when resizing to a very small size

[FIXED] Fixed resizing / minimize / maximize boxes on all windows


[NEW] You are now able to ban specific IP's or entire IP ranges!

[NEW] When putting a new GUID in the whitelist, you can add a comment to it, so that you can for example remember who this GUID belongs to.

[NEW] A new plugin system for Gotcha! If you are able to code in C#, you can create your own plugins in Gotcha and share them with others! Credits for this awesome feature goes entirely to Wotuu!


09.02.2012

[FIXED] Fixed freezing when banning someone

[FIXED] Banning a user sometimes wouldn't actually kick the player

[FIXED] Copy message to clipboard was not working properly

[FIXED] Vehicle and Squad chat wasn't showing up in chat tab

[FIXED] Correct action according to settings when users get kicked/banned for having hacked weapons (will no longer always say user was banned)

[NEW] Added loading messages for loading screen


10.02.2012

[NEW] Chat coloring now also is applied to the chat tab

[FIXED] Users that are already in-game are now updated (correct local ID, ping)


11.02.2012

[FIXED] If a user logged out and in within the time it took for Gotcha to update the players, he'd have a wrong local ID, which would lead to kicking the wrong person if you decide to kick that player

[REMOVED] "Admin said: <message>" message removed from chat tab (it would show up anyways through RCon)


12.02.2012

[FIXED] Further improved the performance of the log filter (should now also show loading messages)

[NEW] Added an Export To File option for currently filtered logs




1.0

[NEW] Connect gotcha to the database of the server (only working for private hive people). Also works with Bliss!

[NEW] View peoples inventory within Gotcha! (Right click player -> Show Inventory)

[NEW] Chat Filter. (The point of this is to have some bad words you don't want to see on your server.)

[NEW] New Notification Center! Which will combine things like the hacker detected box into just one list with a detail view!

[NEW] Some small fixes in the usebillity

            - Commands -> Show filter
            
            - Commands -> Load inventories from database (this will happen every 30 seconds automatically if you applied a database to the server in gotcha)
            
            - ITS NOT WORKING button ;)
            
[NEW] Extended the error log file.

[NEW] If a hack contains any kind of position, its now possible to view this on map.

[FIXED] countless things you guys didn't and will never notice :D

