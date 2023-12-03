# Minecraft Death Items No Despawn Timer

Items and XP dropped upon death will not despawn anymore.

Tested on Minecraft 1.20, in Overworld, Nether and End, on Multiplayer game.
If you find any bugs, make sure to offer instructions on how to reproduce them (steps, Minecraft version).

# **Behaviour of script:**
1. Upon death, an Armor Stand is summoned at player's location.
2. All items and experience orbs within 20 blocks range are set to erase in 15 minutes *(-12,000 ticks)* and are reset every 11,000 ticks.
3. Once any player gets within 5 blocks of the Armor Stand, it will disappear *(i.e. supposedly someone is picking up the items)* and the items will not be refreshed anymore *(i.e. will be erased as soon as the item Age reaches 6000 ticks).*

# **Installation instructions:**
- Inside your Minecraft folder *(check your profile settings to find it),* you should find a subdirectory called `saves`.
- Inside that directory, select the world you want to insert this datapack into and place the .ZIP inside the `datapacks` subdirectory (i.e. %appdata%\.minecraft\saves\World\datapacks\despawnextend.zip).

# **Credits:**
- @TheRobified: https://www.planetminecraft.com/data-pack/item-despawn-time-increase/
