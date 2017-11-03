# Component Crafting Stations 
<sub>(Created by Soraphis: 16.9.2016)</sub>

*note: all numbers used below may need a bit fine-tuning. they may be inbalanced and should just represent the idea behind the suggestion*

## General

This mod aims to replace all the Crafting stations, with a more dynamic and customizable system. Where you can fine-tune the crafting stations for your needs.

*I should note, that i've not modded rimworld myself. So some of it might be not possible, but i doubt it. :D*

The crafting stations will be replaced with an 1x1 block like this: [img](http://imgur.com/wg1iLcw).
the surrounding 7 tiles can be filled with Addons.


> The general thought behind this System is to have the option of either highly optimized crafting stations on the cost of space and electricity 
> or all-in-one crafting stations to save space at the cost of efficiency   


## Crafting Stations

### Cooking Station

Processes meals at 40% Speed. Can't process Meat. 

#### Addons

*(Multiple usage of the same Addons does Stack)*

Name | Structure | _ | Effect
-----| --------- | --- | ------
Kitchen Sink | 1x1 |   | Chance of Food Poisoning reduced by 15%
Large Kitchen Counter | 1x2 | (Both Tiles adjacent to the Cooking Station) | Increase Workspeed by 80%
Stove (wood) | 1x1 |  | Allows to process Meat
Hob (elec) | 1x1 |  | Allows to process Meat. Increases Workspeed by 50%.
Microwave (elec) | 1x1 | (Research *Microwaves*) | Allows to process Meat.Workspeed +175%.Nutrition -20%. Meals can't be tastier than Simple.
Workspace Addition | [2x2](http://imgur.com/85U8jk1) | (Workspace Tile adjacent to Cooking Station) | Allows an additional Cook at the same time (with full access to the main-cookingstation's addons).
Kitchen Knifes | 1x1 |   | Increase Workspeed by 35%
Mixer (elec) | 1x1 |   | Increase Workspeed by 65%

#### Misc
Possible Addon that allows a single cook, to craft two meals at the same time.

___

### Workbench
This will replace the [Crafting Spot](http://rimworldwiki.com/wiki/Crafting_spot). And his addons will replace the other crafting stations 

Name | Structure | _ | Effect
-----| --------- | --- | ------
Stone Cutting Tools | 1x1 |   | +Working with Stone, +Creation of Stoneblocks, +30% workspeed to stone sculpturing *(yep sculpturing)*
Stone Sculpturing Tools | 1x1 || +Working with Stone, +Creation of Statues/Sculptures, +30% workspeed to stone cutting  *(synergy to cutting)*
Wood Sculpturing Tools | 1x1 | | +Working with Wood, +Creation of Statues/Sculptures
Wood Mill (elec.) | 1x1 | | +Working with Wood, +Creation of Statues/Sculptures, +60% workspeed to wood sculpturing 
Sculpturing Jackhammer (elec.) | 1x1 |  | +Working with Stone, +Creation of Statues/Sculptures, +75% workspeed to stone sculpturing 
Stone Saw | 1x2 | | +Working with Stone, +75% workspeed to stone cutting, +50% workspeed to sculpturing
Stone Laser | 1x2 |  | +50% workspeed to stone sculpturing, +15% better quality to sculptures
Forge | 1x1 |  | +Working with Metals
Electric Smelter (elec.)| 1x1 |  | +Working with Metals, +Allow Smelting Mechanoids and Stuff back to Steel
Anvil | 1x1 | | +Allows Meele Weapons (needs Forge for Metal)
Power hammer / Air hammer (elec.) | 1x1 | | +Allows Meele Weapons (needs Forge for Metal), +20% Workspeed for Meele Weapons, +10% better quality for Meele Weapons
Drilltable (elec) | 1x1 |  | +Speed for Metalcraft
Mannequin (elec) | 1x1 |  | +Allows Armor Creation (need forge or tailoring workbench or equivalent)
Tailoring Workbench | 1x1 |  | +Work with fabric
Sewing machine (elec) | 1x1 |  | +Work with fabric, +60% Workspeed on Cloth
Workspace Addition | [2x2](http://imgur.com/85U8jk1) |  | +Allows an additional Pawn to craft at the same time, -Things craftet at this can't exceed 'Masterwork'-Quality

#### Misc
- Some fine mechanic tools or soldering workbench to create Energy Armor / Energy Weapons.
- Something like [this 2x2 structure](http://imgur.com/85U8jk1) without workspace position as addon for creating components.

___

### Assembly Line (elec.) 

> this is the core of this suggestion, the part above this came to my mind while formulating this one :)

- Adds the Research-Topics `Assembly Line` and `Robot Automation`<sup>Requires `Assembly Line`</sup>

Instead of using a 1x1 structure with 7 addon tiles, the assembly line uses a 2x2 structure with 4 addon tiles, and 2 continue tiles. [Image here](http://imgur.com/WBBqajg)

The energy cost of such a basic-structure should be about a quarter of the sun lamp (~400), (1 vanilla-solar pannel per 4 assembly line parts). plus all the addons have a power consumption. The robot parts more, the workstations less.

> this idea needs to be elaborated further, the aim is to have robotic-addons for the endgame to have a fully autonomous production-chain at the cost of **electricity** and **space**


#### Assembly Line

<div style="width: 100%; padding: 1em 0;">
<div style="width: 100%; padding: 1em 0; display: flex; justify-content: center; background: #3d3d3d;">
<img style="margin: 0 1em;" src="content/assembly_line/assembly_line.png"></img>
</div>
</div>

- *this is the base structure*
- 2x2 Building as described above
- +60% Workspeed (*the more the faster*)

___
- All Workstations: 2x1 structure (a workplace with a 1x1 block), both need to be adjacent to the Assembly Line
- All Robot-Arms: 2x1 structure, both need to be adjacent to the Assembly Line. (No Pawn needed, fully automatical)
___

<div style="width: 100%; padding: 1em 0;">
<div style="width: 100%; padding: 1em 0; display: flex; justify-content: center; background: #3d3d3d;">
<video style="margin: 0 1em;" src="content/assembly_line/robotarm.webm" loop="loop" autoplay="true"></video>
</div>
</div>

#### Workstations: Controll Console
- Needs an AI core to be crafted
- +Allows usage of Robot-Arm addons.

#### Workstation
- +60% Workspeed
- +Non-Metal Meele Weapons
- +Non-Metal Ranged Weapons

#### Workstation: Drill
- +Metal Meele Weapons
- +Metal Ranged Weapons
- +5% Better Quality

#### Robot-Arm: Drill

- 2x1 structure, both need to be adjacent to the Assembly Line
- +Metal Meele Weapons
- +Metal Ranged Weapons
- +40% Workspeed
- +Quality can't exceed Excellent

#### Workstation: Saw
- +Woodcrafts
- +5% Better Quality

#### Robot-Arm: Saw
- +Woodcrafts
- +40% Workspeed
- +Quality can't exceed Excellent

#### Workstation: Fine-Mechanic-Tools
- +Energy Weapons
- +Energy Armor
- +5% Better Quality

#### ...

plus many more.