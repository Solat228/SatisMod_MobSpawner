Update 6 support, spawner overhaul. Can now be configured to be reusable. New visuals. This update brought to you by Robb#6731




## New Stuff

![MobSpawner Screenshot](https://i.imgur.com/NeFSKWj.jpg)

![Available Mobs edited screenshot](https://i.imgur.com/0CS7hDG.png)

- New spawners for the creatures in Update 6, including Johnny
- New visuals and sounds for constructing a spawner and spawning a creature
  - "Spawning pad" with a hologram of the creature to be spawned
- Lots of additional configuration options
  - **Multiple Use Spawners**
    - Enabled - spawners can spawn infinite creatures.
    - Disabled - the building will destroy itself as soon as it spawns one creature.
  - **Spawn a Creature On Load**
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

## Changed Stuff

- Spawners are now **unlocked in the MAM instead of the HUB.**
- By default, spawners are now reusable at no additional cost per spawn.
  - **To get old v1.0.0 behavior:** disable 'Multiple Use Spawners' and enable 'Spawn a Creature On Load'
- Creatures spawned by the mod _should_ persist even after the mod is removed.
- Altered the cost of spawners to use Update 6 ingredients.
- Stinger spawner icon is the Arachnophobia icon. Eventually™ this will be configurable.

## Bugfixes

- The entire mod was rewritten, so any past bugs have probably been replaced with new bugs.

## Extra Info for Modders

The mod has been rewritten to make creating new spawners in the future very straightforward.
This is accomplished via Editor Utility Blueprints.
Check out the source code for an example of how to use them yourself.
You'll have to enable the engine "Editor Scripting" plugin to use them.
