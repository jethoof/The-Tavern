---
attribution: jethoof
creation: 2023-05-06
modified: 2023-05-13
type: other
---

# Quest Table

> [!summary] 
> This is a simple way of generating a seed for creating quests and this is one way of generating your own library of resource on types of quest you can generate.
^tldr

> [!error] The Quest
> Here are 3 sets of quest description and 4th one if you are daring to make it more complex. Feel free to mix these words to make sense as these are randomly generated.
> - `dice:[[Quest-Table#^table1]]` `dice:[[Quest-Table#^table2]]`
> -  `dice:[[Quest-Table#^table1]]` `dice:[[Quest-Table#^table2]]`
> - `dice:[[Quest-Table#^table1]]` `dice:[[Quest-Table#^table2]]`
> 
> Optional
> 
> - `dice:[[Quest-Table#^table1]]` `dice:[[Quest-Table#^table2]]`
^dice1


> [!error] Quest Version 2
> Here is the quest description and three optional, you could either swap in or add to enrich your quest.
> 
> - `dice:[[Quest-Table#^table1]]\|nodice` `dice:[[Quest-Table#^table2]]\|nodice`
>
> Optional
> - `dice:[[Quest-Table#^table1]]\|nodice` `dice:[[Quest-Table#^table2]]\|nodice`
> -  `dice:[[Quest-Table#^table1]]\|nodice` `dice:[[Quest-Table#^table2]]\|nodice`
> - `dice:[[Quest-Table#^table1]]\|nodice` `dice:[[Quest-Table#^table2]]\|nodice`
> 
^dice2

## Creating a Complex Quest
You can create a complex quest structure by creating milestones for the quest,

![[QotW-2023W18]]
=======
![[QotW-2023W19]]
>>>>>>> c0931197f3b4a2cc57311908bed0c5ba243c09da

# Tables

###### Table 1 - Objective

| Objective   |
| ----------- |
| Aid         |
| Attack      |
| Build       |
| Burgle      |
| Capture     |
| Deceive     |
| Deliver     |
| Destroy     |
| Find        |
| Hide        |
| Investigate |
| Persuade    |
| Protect     |
| Retrieve    |
| Spy         |
| Undermine   |
^table1

###### Table 2 - Subject

| Subject      |
| ------------ |
| `dice:[[Quest-Table#^locationdescriptor]]\|nodice` `dice:[[Quest-Table#^location]]\|nodice`    |
|  `dice:[[Quest-Table#^creature-description]]\|nodice` `dice: [[Quest-Table#^creature-type]]\|nodice`    |
| `dice:[[Quest-Table#^event]]\|nodice`         |
| `dice:[[Quest-Table#^item-descriptor]]\|nodice` `dice:[[Quest-Table#^item-type]]\|nodice`            |
| `dice:[[Quest-Table#^organization]]\|nodice` `dice:[[Quest-Table#^orgtype]]\|nodice`    |
| `dice:[[Quest-Table#^settlementdescriptor]]\|nodice` `dice:[[Quest-Table#^settlement]]\|nodice`     |
^table2

###### Table 2-1 Building 

| Description |
| ----------- |
| Fortified   |
| Ruined      |
| Abandoned   |
| Ancient     |
| Haunted     |
| Corrupted   |
| Blessed     |
| Dangerous   |
| Isolated    |
| Unstable    |
^building

###### Table 2-2-1 Creature 
| Description |
| ----------- |
| Corrupted   |
| Holy        |
| Dangerous   |
| Sick        |
| Wounded     |
| Hostile     |
| Friendly    |
| Wayward     |
| Wary        |
| Young       |
| Old         |
^creature-description

###### Table 2-2-2 Creature Type

| Description            |
| ---------------------- |
| Humanoid               |
| Beast                  |
| Monstrosity            |
| Undead (Zombie, Ghost) |
| Construct (Robot)      |
| Aberrant (Horror)      |
| Fey                    |
| Fiend (Devil, Demon)   |
| Ooze (Slime)           |
| Celestial (Angel)      |
| Dragon                 |
^creature-type

###### Table 2-3 Event 
| Description         |
| ------------------- |
| Ritual              |
| Celebration / Feast |
| Funeral             |
| Wedding             |
| Meeting             |
| Parade              |
| Trial               |
| Execution           |
| Ball / Banquet      |
| Coronation          |
| Musical / Play      |
| Concert             |
| Skirmish            |
| Invasion            |
| Blizzard            |
| Flood               |
| Fire                |
| Thunderstorm        |
^event

###### Table 2-4-1 Item Descriptor
| Description         |
| ------------------- |
| Corrupted           |
| Blessed             |
| Relic               |
| Magical (High Tech) |
| Memento             |
| Unstable            |
| Sentient            |
^item-descriptor

###### Table 2-4-2 Item Type
| Description  |
| ------------ |
| Weapon       |
| Armor        |
| Tool         |
| Ring         |
| Amulet       |
| Medal        |
| Gem          |
| Book         |
| Potion       |
| Food / Drink |
^item-type

###### Table 2-5 Location  Descriptor
| Description |
| ----------- |
| Isolated    |
| Abandoned   |
| Magical     |
| Spiritual   |
| Corrupted   |
| Blessed     |
| Fortified   |
| Dense       |
| Flat        |
| Crowded     |
| Unstable    |
| Burning     |
| Frigid            |
^locationdescriptor

###### Table 2-5 Location  
| Description  |
| ------------ |
| Theatre      |
| Barrack      |
| Cemetery     |
| Palace       |
| Fortress     |
| House        |
| Inn / Tavern |
| Marketplace  |
| Mansion      |
| Forest       |
| Lake         |
| Hill         |
| Mountain     |
| Mine         |
| Cavern       |
| Valley       |
| Plain        |
| Desert       |
| Tundra       |
| Bog          |
| River        |
| Waterfall    |
| Beach        |
| Lagoon       |
| Oasis        |
^location

###### Table 2-6 Organization 
| Description |
| ----------- |
| Friendly    |
| Hostile     |
| Secretive   |
| Public      |
| Notorious   |
| Famous            |
^organization

###### Table 2-6-1 Organization Type

| Description        |
| ------------------ |
| `dice:[[Quest-Table#^guildtype]]\|nodice` Guild              |
| Kingdom            |
| Company            |
| Cult               |
| Mercenaries        |
| Circus             |
| Raiders            |
| Order            |
| Arcane Institution |
|                    |
^orgtype

###### Table 2-6-2 Organization type, Guild 

| Description    |
| -------------- |
| Thieves        |
| Artisan        |
| Assassin's     |
| Bounty Hunting |
| Trading        |
| Crafting               |
^guildtype

###### Table 2-7 Settlement 
| Description |
| ----------- |
| Hamlet      |
| Village     |
| Town        |
| City        |
| Capital     |
| Fort        |
| Port        |
^settlement

###### Table 2-7-1 Settlement descriptor 
| Description |
| ----------- |
| Gloomy      |
| Bustling    |
| Dangerous   |
| Vibrant     |
| Hostile     |
| Friendly    |
| Militant    |
| Religious   |
| New         |
| Old         |
| Abandoned   |
| Sleepy            |
^settlementdescriptor

You can pick and choose or if not sure which one, roll d12 and d6 to find out what the contract is 

## Subject - Expanded

### Creature
I have described more on detail on what kind of creature you can create in [[Tips-on-Creating-Creatures-for-Encounters]]. 


`dice:[[Quest-Table^se]]`