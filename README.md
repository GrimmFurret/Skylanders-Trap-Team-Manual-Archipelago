# Manual Skylanders Trap Team Randomizer
A Manual Archieplago randomizer for _Skylanders Trap Team_.

It allows for the "Randomization" of aspects in the game, such as Skylanders, Traps, Villains, and Hats using [Archipelago](https://archipelago.gg).  
These can be distributed across a Multiworld to enable items and progression to be shared across multiple different games.

## What can be Randomized?
- Skylanders
  - Including: Trap Masters, Cores, and Minis
  - _(Only Figures originating from Trap Team are currently in the item pool)_
- Villains
- Villain Quests
- Traps
- Treasure Chests
  - Including Villain Stashes
- Winged Sapphires
- Story Scrolls
- Legendary Treasures
- Soul Gems
- Hats
- Skystones
- Level Unlocks
  - Expansion Packs are included, but this may be changed in future
- Level Completion
  - This determines some shop item availability to prevent Auric's shop from being immediately available

## How do I play this Manual?
For this Manual AP, you start in Skylander's Academy with 1 Unlocked Skylander (can be any kind).  
You are locked to Skylander's Academy until you receive a "Level Unlock" item, which then grants you access to the relevant levels.  
- _There are however 5 (6 with a Mini) Item Checks around the Academy to do whilst you wait._

Currently there is only one goal ***Defeat Kaos***.  
Within the Multiworld is 20 (By Default) _Traptanium Kaos Shards_, only 10 are required for the Kaos Boss Fight to become available.

> The website [Dark Spyro](https://www.darkspyro.net/trapteam/walkthrough/) is incredibly useful if you are unfamiliar with the game, as it details where every Item Check is

## Requirements to Play
- [Cemu Emulator](https://cemu.info)
- A Copy of Skylanders Trap Team, with a Completed Save File
  - The Save File provided is on Nightmare Difficulty, a Second File on the Lower Difficulties may be uploaded at a later date
- Every Trap Master, Core, Mini, Expansion Pack, and at least one Trap of each element.
- Archipelago (Website)
- Archipelago (Launcher)
- Archipelago (Manual Client)
  - Recommended: [Universal Tracker](https://archipelago.miraheze.org/wiki/Universal_Tracker)

## Skylanders Setup
1.) Open Cemu and provide it with a Skylanders Trap Team .wua file.

2.) On the Cemu home menu, right click Skylanders Trap Team and select "save directory".

3.) This should open a file path that ends with "1017c600", being the designation for the game.

4.) Select "user" and then "80000001", this is the save data folder.

5.) Download the "Save_Slot_4" file and drop it into this folder.
  - If prompted to replace the file, select yes

6.) Now when re-opening the game, there should be a Nightmare Difficulty save file on slot 4.

- When playing the Randomizer, it is intended to start with wiped Skylanders. _(use the in-game menu to delete their data)_

## Archipelago Setup
1.) Download the [Archipelago Launcher](https://github.com/ArchipelagoMW/Archipelago/releases).

2.) Download the Trap Team Randomizer's most recently released .apworld file.

3.) Launch the Archipelago Launcher and drag the .apworld file into the client. Restart the Archipelago Launcher after installing the apworld.

4.) Download the Trap Team Randomizer's latest release .yaml file  
  - Currently, the .apworld does not work with Archipelago's in-built "options creator", so this is the fix for now

5.) Place the .yaml into the Archipelago 'Players' folder alongside any other .yaml that you will be using for your Multiworld.

6.) Go back to the Archipelago Launcher and select "Generate". This will generate your Multiworld seed and place a .zip file into your Archipelago 'output' folder.

7.) You can then upload the zip to host the game as you wish. Archipelago's upload hosting page can be found [here](https://archipelago.gg/uploads).

8.) Connect using the [Manual Client](https://github.com/ManualForArchipelago/Manual/blob/main/docs/play/connect-client.md) on the Archipelago Launcher
