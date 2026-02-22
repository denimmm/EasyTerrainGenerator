# EasyTerrainGenerator
Easy Terrain is a Roblox plugin which allows the user to create performant, massive terrain using heightmaps.

This plugin is still a work in progress. It has been posted to github because Roblox will not publish it due to the use of loadstring() being used to dynamically load the config file. This will hopefully be fixed by replacing loadstring() with luaception in the future.

To view the source code you can open it in Roblox studio or view the XML with a text editor

**Features:**
* Large-scale triangel terrain generation
* Terrain shape determined by heightmaps
* Easy scaling both vertically and along XZ axis
* Prebaking spawnpoints for mobs, resources, etc.
* Biomes configurable with config file and biomemap
* Realistic distribution of foliage and other terrain features using Poisson-Disk sampling

**How to Install**
* Download the RBXMX file and place it in your roblox plugins folder (C:\Users\<your_username>\AppData\Local\Roblox\Plugins)
* Open a Studio instance and click on the icon in your plugins tab

**Editing The Config**
* Easy Terrain will automatically create a config for you in ServerStorage.EasyTerrainConfig
* It will also automatically create an Assets/Features folder in your ReplicatedStorage
* A demo config is included which can be used as a template for your game. Simply create tables for each biome, tree, etc in order to add more features.
* In order to use the config, a BiomeMap must be used. The plugin comes with a default biomemap for the demo config.

**Video Demonstration:**
https://youtu.be/gj1J22GmFkM?si=QdTLLNJYrqUG1nwk


