# Session Logs

Every Session gets its own Log. In this Log it is recorded which NPC gave/got which Information from Whom.

# Threads

Every Quest Like Thingy gets its own Log where the Progress is recorded.

# Everything can be a Note

Everything that needs an Identity should have its own Note. This goes for Notable NPCs, Items, Places and Monsters. So most stuff does not need it.

If a Chest in a Room contains a bunch of Consumables neither the Chest nor the Items need their own Note. Because the Chest is only relevant in that room and its Content will be looted.

If an Item is important for a Quest, it should have its own Note so it can be Located quickly. (Where in the world is it atm.)

# Every Note has a Session Log

The state of an Entity is tracked on a per Session basis. When the Entity is altered for the first time during that Session the Inventory/State is Copied and then subsequently altered.
Keeping Track of everything is kind of time consuming. Inventories and Locations of NPCs/Items are Important and Quick to manage. An Item should only be a Note if it is a unique Item.

Items that belong to the Player are Tracked by the Player.
If they leave them in a special Place then a reference is recorded there so things can get stolen if need be.

Log for [[Example Place]]
# Maps

When the spatial relationship of Entities are Important it is recorded in a Canvas.
If the Entity has a Note the note is attached to the Canvas.

# Searching for Stuff

* What was the name of that darn Dwarf we met Ages ago
	* Look into the Session logs, if you talked about something relevant he is there
	* If you just want the Name of that Shopkeeper for Roleplaying, checkout the Log of the Place where you first met him (her Shop), there you can find the name and see also if he is dead or something
* Where did I leave that darn item
	* Do you remember any of the Places where you saw it
		* Look into that places Note. If it was there then one of the Session Entries references it and then you can figure out where it is now by clicking into that note and checking its log
* What room connects to which again?
	* Every Location that is relevant has a Canvas of the same Name
* Where was that Dungeon again?
	* Dugeons are Referenced on the Canvas for the Location they are in
		* from there you can use the canvas backlinks to navigate upwards



