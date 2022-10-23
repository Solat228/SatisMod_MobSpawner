Fix bug with spawned creature scale. New single-use spawner VFX. This update brought to you by Robb#6731




## Changed Stuff

- Single-use spawners now use the building deconstruct animation instead of just poofing out of existence.

## Bugfixes

- Fixed that some creatures (hog, small spitters) were spawned at incorrect sizes. This size override was required to make them spawn correctly back in EXP, but they fixed the base-game bug related to that, so it needed to be turned off now.

## Extra Info for Modders

The mod has been rewritten to make creating new spawners in the future very straightforward.
This is accomplished via Editor Utility Blueprints.
Check out the source code for an example of how to use them yourself.
You'll have to enable the engine "Editor Scripting" plugin to use them.
