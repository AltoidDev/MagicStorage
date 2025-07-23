# Magic Storage

Forked to work on issues instead of waiting for aquarian.

Are you tired of having a mess of chests in your base? Never remember where you put your items, and have to run across your entire house to get from chest to chest? This mod will solve all of your problems!

This mod offers a solution to storage problems once and for all. It allows you to construct a central network to store all your items, that you can access from one single block. If desired, you can even set up multiple access points to use your storage from anywhere in the world. You can search your storage for items with a certain name, filter by item types, etc. The magic storage can even craft items for you!

The magic storage scales as you progress in your playthrough. It is accessible very early in the game, but with limited power. As you defeat bosses and earn more materials, you will be able to upgrade your storage to perform more functions and more easily expand the storage capacity.

Are you unable to keep track of the dozens of crafting stations in your base? This mod will help you to keep track of all of them with its Combined Crafting Stations! The Combined Crafting Stations combine the functionality of several crafting stations into each tier, with the next tier having all of the previous tiers' crafting stations.

## Credits
* [@AdipemDragon](https://forums.terraria.org/index.php?members/adipemdragon.2930/) - Spriting

## Contributing

### Dependencies
* This tutorial is made for linux systems, if you want windows instructions check the original repo.
* tModLoader can't be running using any custom compatibility layer, ex. Force the use of a specific Steam Play compatibility tool can't be turned on in steam settings.
* Join the [Discord Server](https://discord.gg/FemPG7eev4) to discuss
* .NET 8 (this mod originally said to use .NET 6, but tModLoader itself requires .NET 8)
* [Microsoft XNA Framework Redistributable 4.0](https://www.microsoft.com/en-us/download/details.aspx?id=20914)
* tModLoader 1.4.4
* SerousCommonLib (absoluteAquarian Utilities)
  	- Needs to be installed in game as well downloaded from github

### Aquiring SerousCommonLib Assembly Files From Github
1. Go to https://github.com/absoluteAquarian/SerousCommonLib
2. Find the latest release
3. Download the `.dll`, `.pdb` and/or `.xml` assembly files

### Getting your Project Setup
1. Clone the project to `/home/<your name>/.local/share/Terraria/tModLoader/ModSources/` (Not required, as this fork uses absolute paths to avoid certian issues with linux)
2. Create a folder in `/home/<your name>/.local/share/Terraria/tModLoader/ModSources/` called `references`, and a `1.4.4` folder in that folder
3. Copy SerousCommonLib assembly files into the `references/1.4.4/` folder created above.
4. Open terminal in `/home/<your name>/.local/share/Terraria/tModLoader/ModSources/MagicStorage/` (Or wherever you cloned it)
5. Run `dotnet build`
6. Start tModLoader 
