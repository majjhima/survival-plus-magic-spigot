# survival-plus-magic-spigot
Run a Spigot 1.18.1 Minecraft server with Survival Plus, Magic, Aurelium Skills, and several other plugins using Docker Compose.

## Plugins
### [AureliumMobs](https://www.spigotmc.org/resources/1-16-5-1-18-aureliummobs-add-rpg-experience-to-your-survival.94168/)
Add RPG-leveled mobs based on near players levels of AureliumSkills.


### [AureliumSkills](https://www.spigotmc.org/resources/aurelium-skills-advanced-skills-stats-abilities-and-more.81069/)
Aurelium Skills is a feature-packed skills plugin that enhances the vanilla survival experience. Players level up skills to earn stat buffs, unlock and level up abilities, and more.
#### Commands
* `/mana (player)` - shows how much mana you or another player has
* `/stats` - show stats menu
* `/sk` or `/skills` or `/skill` - show skill menu
* `/sk help` - shows help page
* `/sk toggle` or `/abtoggle` - toggles your own action bar
* `/sk top (page)` or `/sk top [skill] (page)` or `/sk top average (page)` - shows the top players in a skill (Alias: `/skilltop`)
* `/sk rank` - shows your skill rankings (Alias: `/skillrank`)
* `/sk claimitems` - opens the unclaimed items menu to claim unclaimed items


### [BestTools](https://www.spigotmc.org/resources/besttools.81490/)
Automatically switch to the best tool for the job.
#### Commands
* `/bt` or `/besttools` - toggle functionality to use best available tool when mining blocks
* `/rf` or `/refill` - toggle auto refill of item stacks in hotbar from inventory


### [ChestSort](https://www.spigotmc.org/resources/chestsort-api.59773/)
Use double-click, shift-click or shift+right-click within player inventories, chests etc. to have them sorted.  Optionally enable suto sort.
#### Commands
* `/sort` or `/chestsort` or `/sort hotkeys` or `/chestsort hotkeys` - toggle your sorting settings using GUI
* `/sort help` or `/chestsort help` - display help
* `/invsort` or `/isort` - sort inventory
* `/invsort hotbar` or `/isort hotbar` - sort the hotbar
* `/invsort all` or `/isort all` - sort inventory and hotbar
* `/invsort toggle|on|off` or `/isort toggle|on|off` - toggle auto inventory sorting
* `/invsort help` or `/isort help` - display help


### [Dynmap](https://www.spigotmc.org/resources/dynmap%C2%AE.274/)
Load the map in your web browser with `http://${HOSTNAME}:8123/`


### [HoloMobHealth](https://www.spigotmc.org/resources/holomobhealth-display-mob-health-damage-indicator-client-side-javascript-formatting.75975/)
Show hearts for mobs.
#### Commands
* `/holomobhealth toggle` - toggle mob health display for yourself (or `/hmh toggle`)


### [Magic](https://www.spigotmc.org/resources/magic.1056/)
Magic is a plugin that adds powerful magic wands and items to your server! Magic also offers a progression system, custom mobs, NPCs, crafting, image maps, and a host of other features.  See the [Magic wiki](https://github.com/elBukkit/MagicPlugin/wiki) for detail usage.
#### Using Magic
Most spellcasting in Magic is done using a magic wand item. While holding a wand, left-click to cast the active spell. Wands that have more than one spell will have a "wand inventory" that you can use to quick-change spells and manage any number of spells in a single wand.


### [Minepacks](https://www.spigotmc.org/resources/minepacks-backpack-plugin-mc-1-7-1-18.19286/)
Always available 6x9 backpack as an item in your inventory.  Note that you will keep your backpack on death, but all items inside will be dropped next to your death chest.  Collected items will go into your backpack when inventory is full.
#### Commands
* `/backpack` - opens backpack


### [RocketBoots](https://www.spigotmc.org/resources/rocketboots.13529/)
* **Gold boots:** hold shift (sneak), point up and fly
* **Diamond boots:** repeatedly tap shift (sneak) to hover in the air
* **Leather boots:** right click an animal or mob and kick them into the air
* **Iron boots:** tap shift (sneak) to make all animals and mobs go flying away from you
* **Chainmail boots:** like gold boots but with lightning

#### Commands
* `/rocketboots on|off` - toggle boot special abilities


### [SavageDeathChest](https://www.spigotmc.org/resources/savagedeathchest.6633/)
Store inventory in a chest on death with sign.  You have 1 hour to retrieve your items.  Shift (sneak) click a chest to retrieve all items.  You can't put items in your death chest and it will disappear once emptied.
#### Commands
* `/deathchest list [player]` - lists deathchests and their locations


### [SavageDeathCompass](https://www.spigotmc.org/resources/savagedeathcompass.81306/)
You are given a compass after death to find your way back to your death chest.  It will be destroyed automatically if dropped or once you find your death location.


### [ServerMinimap](https://dev.bukkit.org/projects/serverminimap)
Show surrounding area on regular map item with ability to set marker waypoints.
#### Commands
* `/minimap` - give yourself the map
* `/waypoint help [command]` - gives you information about this command
* `/waypoint add [x] [z]` - adds a waypoint either on your current location, or to the specified x and z coordinates
* `/waypoint list` - lists all your waypoints together with their index
* `/waypoint remove <index>` - removes the waypoint with the index <index> (indicies change when removing waypoints)
* `/waypoint hide <index> [true|false]` - either toggles visibility of a waypoint, or sets it to the given boolean


### [Spawnx](https://www.spigotmc.org/resources/spawnx-implemented-random-spawn.2429/)
Random spawn, set spawn, spawn to another player.
#### Commands
* `/setspawn` - set a spawn point (OP only)
* `/spawnx` - get help about the plugin
* `/spawn [player]` or `/hub [player]` - teleports you to your or another player's spawn point
* `/randomspawn` - teleports you to a random spawn point (Up to 1000 blocks far)
* `/nearrandomspawn` - teleports you to a near random spawn point (Up to 500 blocks far)
* `/farrandomspawn` - teleports you to a far random spawn point (Up to 4000 blocks far)
* `/massiverandomspawn` - teleports you to a massive random spawn point (Up to 8000 blocks far)


### [SurvivalPlus](https://www.spigotmc.org/resources/survival-plus-recoded-making-survival-fun-again.67351/)
SurvivalPlus adds new mechanics, items, and tools to enhance vanilla gameplay mechanics.
#### Getting Started
See https://github.com/Pixelated-Studios/SurvivalPlus/wiki/Intro
#### Commands
* `/status [all|none|hunger|thirst|nutrients|fatigue]` or `/stat` or `/s` - toggle display for each type
* `/nutrition` - opens the nutrition GUI


### [TreeAssist](https://www.spigotmc.org/resources/treeassist.67436/)
Enabled by default.  You can only cut trees with the proper tool (no tree punching) and you can't cut down a tree if your tool durability is too low. Only blocks above the targeted block will be affected.
#### Commands
* `/treeassist toggle` - turn TreeAssist auto destruction on or off
* `/treeassist noreplant` - stop replanting for a set period of time (30 seconds)


### [ViveCraft](https://github.com/jrbudda/Vivecraft_Spigot_Extensions/releases)
VR support with [ViveCraft](http://www.vivecraft.org/).


## VR Commands
### AureliumSkills
* `/mana (player)` - shows how much mana you or another player has
* `/stats` - show stats menu
* `/skills` - show skill menu
* `/skilltop` - shows the top players in a skill
* `/skillrank` - shows your skill rankings
* `/skills claimitems` - opens the unclaimed items menu to claim unclaimed items

### BestTools
* `/besttools` - toggle functionality to use best available tool when mining blocks
* `/refill` - toggle auto refill of item stacks in hotbar from inventory

### ChestSort
* `/sort` - toggle your sorting settings using GUI

### RocketBoots
* `/rocketboots on` - turn on boot special abilities
* `/rocketboots off` - turn off boot special abilities

### SavageDeathChest
* `/deathchest list` - lists deathchests and their locations

### ServerMinimap
* `/minimap` - give yourself the map
* `/waypoint add` - adds a waypoint either on your current location
* `/waypoint list` - lists all your waypoints together with their index

### Spawnx
* `/spawnx` - get help about the plugin
* `/spawn` - teleports you to your or another player's spawn point
* `/nearrandomspawn` - teleports you to a near random spawn point (Up to 500 blocks far)
* `/randomspawn` - teleports you to a random spawn point (Up to 1000 blocks far)
* `/farrandomspawn` - teleports you to a far random spawn point (Up to 4000 blocks far)
* `/massiverandomspawn` - teleports you to a massive random spawn point (Up to 8000 blocks far)

### SurvivalPlus
* `/nutrition` - opens the nutrition GUI

### TreeAssist
* `/treeassist toggle` - turn TreeAssist auto destruction on or off
* `/treeassist noreplant` - stop replanting for a set period of time (30 seconds)

## Client Setup
1. Install [OpenJDK 17](https://jdk.java.net/17/)
2. Install [MultiMC](https://github.com/MultiMC/Launcher) with a new instance of vanilla 1.18.1
3. Run the instance once
4. Install [ViveCraft 1.18.1](https://github.com/jrbudda/Vivecraft_118/releases) VR or NONVR
5. Check the MMC Instance settings and update the min memory to `4096 MiB` and max memory to `8192 MiB`

## Server
```
docker-compose up -d && docker attach survival-plus-magic-spigot_mc_1; docker-compose stop
```
