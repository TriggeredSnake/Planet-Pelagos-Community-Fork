This is a fork of Pelagos v0.55.1, the last version released under the GPLv3 license rather than CC BY-NC-ND 4.0. This fork exists primarily to bypass lua scripts inserted by Talandar to prevent the game from loading if [any](https://mods.factorio.com/mod/TS_Pelagos_CSRR) of [these](https://mods.factorio.com/mod/space-age-many-planets-server-mod-compat) [mods](https://mods.factorio.com/mod/pelagos-autobarreling) are loaded. It also exists to provide an archive of Pelagos in it's final open-source state, given the author's penchant for deleting old versions of their mods when they realize people are using them to bypass their arbitrary restrictions.

My goal is to make this fork into a community-focused alternative, implementing feautures requested by the community that Talandar has no interest in implementing, as a result community contributions on [the GitHub repository](https://github.com/TriggeredSnake/Planet-Pelagos-Community-Fork) are welcomed. Plus, feel free to report bugs, and make suggestions in the discussion tab.

As of the date of upload, compatible versions of all the mod's dependencies are still available on the mod portal. However, going by Talandar's track record, I expect this mod to be blacklisted by their mods in the next update. As they frequently delete old versions of their mods, especially when they allow people to bypass arbitrary restrictions, [I've uploaded an archive of dependencies and recommended side mods that are known to be compatible with this fork.](https://www.mediafire.com/file/dpyhcnzidthiluj/Pelagos_Fork_0.55.1_Working_Dependencies.rar/file)

# Planet Pelagos
![welcome_on_pelagos](https://raw.githubusercontent.com/TriggeredSnake/Planet-Pelagos-Community-Fork/refs/heads/main/Mod%20Page%20Images/welcome_on_pelagos.png)
Welcome to Pelagos! An insular planet rich in tropical coconut palms, methane deposits, and mysterious lifeforms. 
Harvest coconuts, process them into oil, sealant, and biofuels, experiment with fermentation, and use high-temperature calciners 
to improve smelting processes in your factory. 

## Built around the Cargo Ships mod
[Cargo Ships mod](https://mods.factorio.com/mod/cargo-ships)
- Essential dependency
- Pelagos is designed to give this mod more of a place, as it rarely fits in with vanilla Nauvis terrain generation.
- By default, Cargo Ships are unlocked on Pelagos, and sealant is required to craft them. Use my [Cargo Ship Recipe Restorer](https://mods.factorio.com/mod/TS_Pelagos_CSRR) mod to set them back to default.

## Canal Excavator mod
[Canal Excavator mod](https://mods.factorio.com/mod/canal-excavator)
- Essential dependency
- You can't find stone patches on Pelagos. But you can mine the ground with a Canal Excavator.
1. Mine a big rock on Pelagos to unlock it.
2. Craft an Excavateable surface.
3. Mine it with the excavator to get some stone.

## Calciner
![calciner](https://raw.githubusercontent.com/TriggeredSnake/Planet-Pelagos-Community-Fork/refs/heads/main/Mod%20Page%20Images/calciner.png)
- A big fluid-powered furnace. 
- Can and should be used like regular furnace.
- Provides an extra 50% productivity.
- Allows the high-temperature purification and transformation of raw materials into refined minerals.
- Should accept any fluid with "Fuel Value" (vanilla game property). Check fluids like light oil in game wiki.

## Diesel Machines
![diesel-machines](https://raw.githubusercontent.com/TriggeredSnake/Planet-Pelagos-Community-Fork/refs/heads/main/Mod%20Page%20Images/diesel-machines.png)
- Fuel-powered machines that run on liquid fuels instead of electricity. 
- Allows off-grid automation but requires constant fuel supply.
- Doesn't produce electromagnetic waves, unlike electric machines.

![pelagos-deep-sea](https://raw.githubusercontent.com/TriggeredSnake/Planet-Pelagos-Community-Fork/refs/heads/main/Mod%20Page%20Images/pelagos-deep-sea.png)

## Barrelling Machines
- Specify the liquid you intend to barrel, and provide the resources.
- Barrels of liquid are used to fuel diesel cargo ships, and most other burners.
- Use [this mod](https://mods.factorio.com/mod/pelagos-autobarreling) to make barrelling machines process whatever fluid is inputted like a furnace, rather than setting recipes manually.
- (You must use Barrelling Machines v0.1.2 from the [dependencies archive](https://www.mediafire.com/file/dpyhcnzidthiluj/Pelagos_Fork_0.55.1_Working_Dependencies.rar/file) rather than the latest v0.1.5 and v0.1.6 if you want to use this mod.)

## Giving new life to vanilla mechanics
![fishing_inserter](https://raw.githubusercontent.com/TriggeredSnake/Planet-Pelagos-Community-Fork/refs/heads/main/Mod%20Page%20Images/fishing_inserter.png)
Fish are a good starting source of nutrients on Pelagos. They are also essential for progression.
- (vanilla mechanic) Fishing inserters. You can place an inserter near the water to catch fish.Remember to use a negative filter (for fish) on your cargo ship unloading stations.
- (vanilla mechanic) Fish breeding recipe. You can use the fish breeding recipe on Pelagos.

## Integrations with other planets/mods:
###Any Planet Start (Currently Broken)
- You can start your game on Pelagos.
- You unlock technologies in a different order to better flesh out the Pelagos tech path. For example instead of getting the regular thruster first, you get an Ethanol Thruster. The regular techs are still available, but they unlock a bit later so that you genuinely start the game from the Pelagos point of view.
###Apia
- Pelagos Coconut biolubricant is affected by Apia lubricant productivity
- Pelagos Copper spitter eggs production is affected by Apia biter eggs productivity
- Pelagos Coconut processing is affected by Apia agriculture productivity
- Apia larvae cultivation is affected by Pelagos cultivation productivity
- Apia wax platform is affected by Pelagos landfill productivity
###Vesta
- Lighthouse can be placed on the surface of Vesta.
- Vesta has two gases that can be used as liquid fuel for diesel engines: Methane and Hydrogen.
- Gas giant platform is affected by landfill productivity.
- Diesel Excavator unlocked on Pelagos can be used on the surface of Vesta to mine stone, and remove asteroids.
- There is a new optional setting (turned off by default) to enable methane stain instead of Vesta methane tiles. It can be mined with an oil rig because it's a Sea of clouds.
- To make sure you can choose any icon you want, there is an additional setting to prioritize either the Pelagos or Vesta methane icon and colors.
### Arig
- Landfill productivity also affects Sandstone foundation
- Dedicated recipe to make biodiesel from cactus
- Coconut drop technology allows you to drop coconuts on surface bypassing cargo drop lock
### Maraxis
- Coconut Sealant can be turned into Super Sealant Substance if Maraxis is installed. 
- Recipe enables itself when you research "Project Seadragon" just like regular Super Sealant Substance recipe
- Fluids used in pelagos diesel machines can also be used in diesel submarine
### Cerys
- Pelagos Methane overrides Cerys Methane if Cerys is installed. 
- Methane is essential resource on Pelagos and it is almost unused on Cerys (vented into atmosphere). 
- With Pelagos you can now barrel up Methane and ship to other planets.
- Coconut drop technology allows you to drop coconuts on surface bypassing cargo drop lock
###Castra
- Engine unit casting is affected by engine unit productivity research
### Boompuff Agriculture
- Puff Gas can be used as Calciner fuel
### AAI Vechicles:Ironclad
- Ironclad is part of pelagos tech tree if both mods are present
- Adjusted Recipe to make it balanced around other ships
### Wood themed mods
- In addition to coconuts, the coconut palm gives a small amount of wood.
- Calciner allows wood carbonization (turning wood into coal).
- Pelagos research allows wood spoiling in a biochamber (turning wood into spoilage).
###Colorful Biochamber
- https://mods.factorio.com/mod/colorful_biochamber
- All pelagos recipes now have 4 tint colors, so they will work with colorfull biochamber
###Gleba Cultured Soil
- Cultured soils are affected by landfill productivity bonus

##Great mods to install with Pelagos:
###Inserter Fuel leech (highly recomended if you plan any planet start run)
- https://mods.factorio.com/mod/InserterFuelLeech
- Early game has a longer burner stage, this mod makes life a bit easier.
###Barrelling group
- https://mods.factorio.com/mod/barreling-group2
- Titanium barrels add a lot of items and recipes. Barreling group mod helps to organize them
###Spoiled Trenches Of Fulgora
- https://mods.factorio.com/mod/spoiled_trenches_of_fulgora
- Tweaks the way you get holmium ore on Fulgora. You need oil rig and tanker ship to get it.
###Depths Of Nauvis
- https://mods.factorio.com/mod/depths_of_nauvis
- Changes Nauvis terrain and resource generation to be more ship friendly
###AquiloTrenches
- https://mods.factorio.com/mod/AquiloTrenches
- One more place to use ships
###Fishing Dock
- https://mods.factorio.com/mod/fishing-dock
- Gorgeous mod for turning eggs into bait for automatic fishing
###Fishing Boat
- https://mods.factorio.com/mod/fishing-boat
- Small boat for collecting fish
### Storage Tank (it's best to pick one):
- https://mods.factorio.com/mod/zithorian-extra-storage-tanks-port
- https://mods.factorio.com/mod/large-storage-tank
- More options for fluid tanks

## Issues?
- Post a discussion thread on the mod page, or make a pull request on the GitHub page.

## Credits and thanks
- Thanks to the existence of [Cargo Ships mod](https://mods.factorio.com/mod/cargo-ships) and [Canal Excavator mod](https://mods.factorio.com/mod/canal-excavator) creating this mod was made possible
- Thank you to [uniquename9000](https://mods.factorio.com/user/uniquename9000) for creating the music and sounds!
- Thank you to [Talandar99](https://mods.factorio.com/user/Talandar99) for making the original Pelagos mod, even if their anti-consumer practices caused the creation of this fork.
Plus, thank you to:
- Powerscooter for extensive testing and tons of feedback
- AnthonyDPS for Spanish translation
- Пружинка for Russian translation
- snouz for improved pirate ship graphic
- cackling.fiend for skillfull repainting rocket silo into current diesel dragon sprite
- InanimateLog for insanely well made copper spitter graphics 