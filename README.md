# Command for Minecraft Bedrock edition

![Design_sans_titre-removebg-preview](https://github.com/user-attachments/assets/170a7614-3b34-4972-ab20-c262ce8d4252)

## Base

- /gamemode (survival or creative or adventure or spectator) [Player] : Changes a player's play mode. | Exemple : /gamemode creative Naiko

- /give [Player] : Gives the targeted player an item in the inventory. | Exemple : /give Naiko minecraft:command_block

- /setworldspawn [X Y Z] : Changes the default spawn position for the current world. | Exemple : /setworldspawn -133 65 -400

- /tp [Player] [Player] or [X Y Z] : Teleports a player to another position. | Exemple : /tp Naiko Notch or /tp Naiko -133 65 -400

- /time (add or query or set) : Changes world time (and the position of the sun and moon). | Exemple : /time set day

- /weather (clear or rain or thunder) : Change the weather to the one you choose. | Exemple : /weather clear

## Advanced

-  /fill [X Y Z] [X Y Z] <Block> : Fills an area with a block. Zone size limited to 32768 blocks maximum. | Exemple : /fill 300 65 350 ~ ~ ~ dirt

-  /gamerule : Modifies game options. true : on / false : off | Exemple : /gamerule keepInventory True

-  /locatebiome <biome> : Enter the coordinates of the designated biome closest to your position. Coordinates are displayed in chat. | Exemple : /locatebiome Plains

-  /locate (structure or biome or poi) : Searches for a naturally-generated element in the game and displays the coordinates of the nearest element | Exemple : /locate structure village

-  /summon <Entity> [X Y Z] [TagNBT] : Creates a creature (or entity). | Exemple : /summon minecraft:creeper ~ ~1 ~ {CustomName:"\"Naiko\"",CustomNameVisible:1}


### Author

🔸 𝘔𝘢𝘥𝘦 𝘣𝘺 𝘕𝘢𝘪𝘬𝘰 🔸

![Naiko](https://github.com/user-attachments/assets/02a8fbca-6bdd-43c1-98a5-1eebcd0936e4)
