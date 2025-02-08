 ## More Synths 

Adjustable chance that Human NPCs will have Synth Components on their corpse. In effect, NPCs have a chance of being Gen 3 synths (either infiltrators or escaped).

Nexus Mod entry can be found here: https://www.nexusmods.com/fallout4/mods/33697

---

I thought there'd be more escaped Gen-3 Synths / Synth Infiltrators running around the Commonwealth. So where are they? Well, this mod adds a 1% (default) chance that when a human NPC is killed there will be a Synth Component on their corpse. Simple and immersive.

### Features

The Mod's default settings give a 1% chance that non-unique Human NPCs will have a Synth Component on them when they die.
Settings can by adjusted by the Mod Configuration Menu﻿ or through an optional Holotape.

Adjustable settings include:

- Option to turn the functionality of the Mod's scripts on or off
- Option to limit the effect to only non-unique Human NPCs or to affect all Human NPCs
- Ability to change the effect chance on a scale from 0.1% (1 in 1,000 NPCs) to 100% (everyone is a Synth <:O)

### Installing

Note: It's good practice to create a clean, backed-up save before installing any Mods or Mod Updates - especially ones that use scripts. While this Mod's premise is simple and straightforward it may still cause unforeseen results during play.

1) Copy all files/folders (except "More Synths Settings Holotape.rar") to your "Fallout 4\Data\" folder.

2) Add "MoreSynthsRaceModifier.esl" to your mod load order.

3) (Optional Settings Holotape) Open "More Synths Settings Holotape.rar". Extract all files/folders to your "Fallout 4\Data\" folder. Add "MoreSynthsSettingsHolotape.esl" to your mod load order.

### Known Issues & Compatibility

For your safety ensure that you create a clean backed-up save before installing any Mod or any Mod Updates.

The Mod's script relies on the "Synth Component" item so any changes to that item/form will be reflected with this mod. The Mod modifies (adds an Ability) to the vanilla "Human Race" Form, so there are potential conflicts with mods which also affect the Human Race Form.

If you're unsure if this Mod is conflicting with another Mod, try changing the Chance setting to "100" in the MCM menu (or "Always" with the Settings Holotape) and kill a generic NPC (Raider, Gunner, etc.). If their body doesn't have a Synth Component on it, then it's likely there's a conflict with another mod.

If this mod conflicts with any other mod you are using, please let me know and I will whip-up a patch for you!

Patches are currently available for:

- The PimpCrew's Pip-Boy 2000 v0.3﻿

### How it Works

Adds 5 Forms: 3 Global Variables, a Magic Effect, and a Spell. Modifies a single vanilla Form (the "Human Race" form) by attaching the aforementioned Spell which runs a short script attached to its Magic Effect. The script runs first when a Human NPC is spawned to declare variables, and again when the NPC dies. A randomizer determines if a synth component will appear on their corpse. After the NPC has died the Magic Effect dispels from the NPC, clearing it of all used variables and scripts.

The optional Holotape ESL adds 4 additional Forms: the Holotape object, the Terminal file for the Holotape menus, the Recipe to craft the Holotape at a Chemistry station, and a Quest that adds the Holotape to the Player's inventory. With both the main file and the Holotape installed the Mod adds a total of 9 Forms.
