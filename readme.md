
# Jericho 941

A custom weapon for fivem!

# Installation

- Put the `Jericho-941` into your `resources` folder.
- ensure Jericho-941 - add this line in your `server.cfg`

# If using ox_inventory

- Place in `ox_inventory/data/weapons.lua`
```lua
    ['WEAPON_JERICHO941'] 			  = { label = 'Jericho 941',         weight = 1000,	durability = 0.0,	ammoname = 'ammo-45',},
```

# If using QBCore & qb-inventory

- Place in `qb-core/shared/items.lua`
```lua
['weapon_jericho941'] 			     = {['name'] = 'weapon_jericho941', 			 	['label'] = 'Jericho 941', 				['weight'] = 7000, 		['type'] = 'weapon', 	['ammotype'] = 'AMMO_PISTOL',			['image'] = 'weapon_jericho941.png', 						['unique'] = true, 		['useable'] = false,["created"] = nil,	['description'] = 'pistol'},
```
- Drop the next code in `qb-core/shared/weapons.lua`
```lua
[`weapon_jericho941`] 		 = {['name'] = 'weapon_jericho941', 		['label'] = 'Jericho 941', 			['ammotype'] = 'AMMO_PISTOL',	['damagereason'] = 'Pistoled / Blasted / Plugged / Bust a cap in'},
```
- Drop the next code in `qb-weapons/config.lua`
```lua
    ['weapon_jericho941'] 	             = 0.15,
```
- Add the weapon name in `qb-smallresources/client/weapdraw.lua`
```lua
    `weapon_jericho941`
```
# Credits
- [Hoodlum](https://www.gta5-mods.com/users/Hoodlum)
