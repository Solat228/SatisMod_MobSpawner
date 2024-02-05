# Mob Spawners

Highly configurable mob spawners that can spawn the fauna of MASSAGE-2(A-B)b.

![MobSpawner Screenshot](https://i.imgur.com/NeFSKWj.jpg)

<video controls="" width="720" height="405">
  <source src="https://i.imgur.com/wjWG2bv.mp4" autoplay="false" controls="true" type="video/mp4">
</video>

## Features

This screenshot is out of date, the Cliff and Radioactive hog are also available.

![Available Mobs edited screenshot](https://i.imgur.com/0CS7hDG.png)

- Progress in a MAM Tree to construct new types of mob spawners
- Lots of configuration options, most of which can be edited in-game:
  - **Multiple Use Spawners**
    - Enabled by default
    - Enabled - spawners can spawn infinite creatures.
    - Disabled - the building will destroy itself as soon as it spawns one creature.
  - **Spawn a Creature On Load**
    - Disabled by default
    - Enabled - Spawn a creature as soon as the building is placed, and every time the game loads.
    - Disabled - Only spawns a creature when the building is interacted with.
  - **Spawn Delay**
    - Gives you some time to tactically retreat before the creature spawns
    - When "Spawn a Creature On Load" is ENABLED: How long after building, in seconds, it takes for the creature to spawn.
    - When "Spawn a Creature On Load" is DISABLED: How long it takes after interacting, in seconds, for the creature to spawn.
    - Default 0.0 seconds
  - **Small Manta**
    - Spawn small, quarter-size mantas instead of the full-size one.
  - **Spawn Angle**
    - Yaw angle to spawn creatures at. 180 is upside down, which looks pretty silly.
  - The volume of sounds produced by the spawners can be adjusted with the base game options' Sound Effects category
- Creatures spawned by the mod persist even after their spawner is destroyed or the mod is removed.
- Stinger spawner icons are the Arachnophobia icons (cats). Eventually™ this will be configurable.

## Getting Started

You should check out the mod's configuration options to change the balance to your liking.
You can access them from the [Mod Savegame Settings menu](https://docs.ficsit.app/satisfactory-modding/latest/ForUsers/ConfiguringMods.html#_mod_savegame_settings).

You can unlock spawners for different creatures in the "Mob Spawners" MAM tree.
Once you've unlocked it, you can build it from the Spawners category of the Build Gun.

By default, when you build a spawner, you must interact with it to spawn its respective creature.

## Known Bugs

- Spawned mantas don't move, and don't seem to persist on save/load.
  - They might teleport to the path the main flying manta follows? This hasn't been tested.
- Flying crabs spawned directly with spawners (not from a hatcher) don't persist on save/load

## Extra Info for Modders

The mod has been rewritten to make creating new spawners in the future very straightforward.
This is accomplished via Editor Utility Blueprints.
Check out the source code for an example of how to use them yourself.
You'll have to enable the engine "Editor Scripting" plugin to use them.

## Credits

Original Mod Author's Discord: Solat#5057

Current mainainter since Update 6 and Editor Utility generated content overhaul: Robb#6731 _(If you enjoy my work, please consider my [completely optional tip jar](https://ko-fi.com/robb4).)_

For some help in creating the mod, thanks to: MayorAquila#7740

Mod avatar made by: Deantendo#4265.
