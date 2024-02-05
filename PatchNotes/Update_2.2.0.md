SML3.7/server support. Migrate config options to Mod Savegame Settings. Johnny bugfix.




This update brought to you by Robb.
If you enjoy my work, please consider my [completely optional tip jar](https://ko-fi.com/robb4).

## New Stuff

- Added support for SML 3.7.0/servers

## Changed Stuff

- You now must unlock any of the 4 base-game Alien Protein recipe nodes before the mod's Research Tree is open
  - Avoids potential issue where the tree was locked despite having no unlock requirements
- Moved all mod configuration options to Mod Savegame Settings
  - These are stored per save file instead of global to your game install.
  - [Learn how to edit these on the docs](https://docs.ficsit.app/satisfactory-modding/latest/ForUsers/ConfiguringMods.html#_mod_savegame_settings).
  - Enables easy configuration on servers.
  - Unfortunately, this means your old (mod config option) settings will be lost.
    You can view their old values in your
    [mod config files](https://docs.ficsit.app/satisfactory-modding/latest/faq.html#Files_ModConfig)
    (which will still be around from previous updates)
    if you forgot what you had them set to.
- Updated all spawner and MAM node descriptions accordingly
- Updated the tree's icon to be the spawner category icon instead of the mod logo

## Fixed Stuff

- Fix Alpha Hog spawner mam node also unlocking Johnny spawners
- Fixed spawners that were operated when the mod is in "Single Use Spawners" mode being unusable when the mod is in "Multi Use Spawners" mode.

## Extra Info for Modders

The mod has tools to make creating new spawners very straightforward.
This is accomplished via Editor Utility Blueprints.
Check out the source code for an example of how to use them yourself.
You'll have to enable the engine "Editor Scripting" plugin to use them.
