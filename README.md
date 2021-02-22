# RandomScene

## Credits

Tat @ Ares Central

## Overview
This plugin generates random locations for RP and provides prompts for scene ideas.

It uses four configurable lists to suggest 1) a random adjective for each person involved 2) a random scenario or 3) a random npc/action pair.  

Some examples:

> Nessie's prompt is thankful. Your location is Grand Lake/Shadowcliff Mountain Lodge..

> Random scenario: A belligerent student hosts a dance contest. Your location is Grand Lake/Manna Thrift Store.

> Adelaide's prompt is itchy. Nessie's prompt is creepy. Your location is Grand Lake/Cabin Shop & Pharmacy.

> Random scenario: Locked in a room. Your location is Grand Lake/Ransom Investigations.

> Random scenario: A snobbish realtor gets into a fist fight. Your location is The Foundry Cinema & Bowl/Foundry Bowling Alley.

> Adelaide's prompt is fierce. Nessie's prompt is join. Your location is Feixuzhicheng/The Golden Gate.

## Web Portal

This plugin has no web portal code.  

## Installation

In the game, run `plugin/install <github url>`.

Additional configuration options are described below.

##configuration
Configuration options can be set in `randomscene.yml`. A fun way to get thematic options for your game is to create a shareable Google sheet with columns for the various configurations and ask your players to help populate it. 

`excluded_areas` - A list of areas to exclude in the basic random scenes prompts. Will also exclude all 'child' areas. For example, you may with to exclude 'Grand Lake Homes', which in turn excludes 'Cabin Shop Apartment,' an area parented to 'Grand Lake Homes.' Using the 'area' switch in the command will still return these areas if they are specified.

`scenarios` - Complete scenarios in sentence form.

`npcs` - NPC descriptions as would be found at the start of a sentence. Paired with 'actions' in the randomzier.

`actions` - Actions for NPCs to take, as would be found at the end of a sentence. Paired with 'npcs' in the randomizer.

`words` - One-word prompts for individual characters - mostly adjectives, but you can put whatever you like.

## Uninstalling

Removing the plugin requires some code fiddling.  See [Uninstalling Plugins](https://www.aresmush.com/tutorials/code/extras.html#uninstalling-plugins).

## License

Same as [AresMUSH](https://aresmush.com/license).
