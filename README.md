**Description**

*This ServerSide mod adding Triggers to certain areas to allow spawn infected or whatever somewhere.*

Together with mod is shipped config for Namalsk map.
Now when someone enter the underground facility it will be not empty.

**When mod first start, it will create under server profile folder new folder called SpawnerBubaku and almost empty json file there. 
Put into this folder config file shipped with mod, which you can find in @SpawnerBubaku folder (where are pbo located).**

*AI will not work on mapped areas or over sea/water, mostly because missing navmesh or ai behaviour. Not a bug of this mod. Its normal vanilla behaviour of ai.*

**How It works**

**In config you can define some trigger areas. When player enter there, its triggered action which spawn infected on defined areas. 
Config is very descriptive dont worry. Just one word - Bubak is in czech language something like ghost or scary creature :-)**

**Config**

loglevel 0-100 - higher number produce more verbose logging

BubakLocations - list of locations

name - name of locations

wortkinghours - when should this trigger work (game time)

triggerdependency - list of trigger names on which that trigger depends or can be empty

triggerpos - position of trigger

triggermins, triggermaxs - those two points define box shaped trigger, its relative to position of trigger

triggerradius - when non zero is selected sphere shape of trigger - center is triggerpos

triggercylradius, triggercylheight - when non zero and other are zero is selected cylinder shape for trigger - cylinder is defined by radius and height

notificication - when not empty its show notification when trigger triggered - useful for debug

notificationtime - time in seconds how long should be visible notification text above

triggerdelay - time in seconds (cooldown) when can be trigger again triggered

spawnerpos - list of positions for spawning

spawnradius - you can define radius around spawn points to randomize little

bubaknum - number of ai/items to be spawned

onlyfilltobubaknum - only for ai - when reached this limit no more others ai will be spawned

itemrandomdmg - only for items - when spawn items, they are random damaged not pristine

bubaci - list of ai/items t be spawned

bubakinventory - list of random loot of creatures spawned
