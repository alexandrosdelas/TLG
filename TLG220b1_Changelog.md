# Update 6 [2.2.0] (2019-11-25)
456 changes

## Campaign
### New map
- New interlude "Adamant"
- The heroes return to Stormwind

### Multiple maps
#### Gameplay
- User control is now disabled less often
- Khadgar will no longer move closer to a nearby unit when right-clicking it
- Increased collision size of Moroes from 16 to 32
* Medivh
  - Increased armor of Medivh from 0 to 1
  - Increased base damage of Medivh from 9 to 27
  - Decreased damage sides per die of Medivh from 16 to 5
* Karazhan maps
  - Added more pathing blockers to some areas
  - Added Line of Sight Blockers to the Secret Room
  - Moved Magical Pen Wall to Observatory
  - Changed position of some Circles of Power
  - Moved all gameplay elements in the Museum

#### User Interface
- Retconned The Great Dark Beyond into The Twisting Nether where appropriate
- Inventory/Lockpick error transmissions are no longer played if already playing
- Updated campaign preview image
- Fixed spelling and grammar
- Removed many transmissions and hints
- Changed text in some transmissions
- Updated duration of some transmissions
- Updated loading screens
- Changed loading screen text
- Replaced transmissions for Barrel countdown with floating texts
- Will no longer clear player selection outside of cinematics
- Decreased hit points of Cook from 2000 to 200
- Decreased hit point renegeration rate of Cook from 1000 to 0.5
- Elevated Circles of Power can no longer be selected or show a health bar
- Replaced some hints with transmissions
- Set starting hit points of Cook and Moroes to 1
- Revised all quest descriptions
- Circles of Power are no longer visible on the minimap
- Some floating texts will now fade out
- New icon for Favourite Book/Book of Medivh
- Changed color of leaderboards

#### Audio/Visuals
* Khadgar (Grunt)
  - Khadgar (Grunt): Added Hero Glow
  - Khadgar (Grunt): Decreased selection scale from 1.5 to 1.4
* Karazhan
  - Changed rotation of a Karazhan Archway to 215
  - Moved runes at Medivh's bed
  - Decreased scale of Church Font in Medivh's quarters
  - Redesigned Museum, Banquet Hall and Medivh's Secret Quarters
- Removed unused custom data and imports
- Fixed custom music not playing
- Improved fade in/out for all cinematics
- Replaced all GateEpicBash sounds with LargeCityGateOpen sounds
- New model for Sargeras by PROXY and ~Nightmare
- New model for Aegwynn by Stefan.K
- Added new music themes
- Custom music themes will now play more often in battles and cinematics
- Fixed sound playing at the wrong time when Transfer Items is used
- Added talk animations to Medivh
- New model for Hammer by Blaxor
- Removed blight in some areas
- Fixed position of Scout Tower outside Karazhan
- Lothar no longer buffs other units with Devotion Aura
- Reset animation speed of dying units to 100%
- Improved Far Clipping for some cameras
- All cinematics and transmissions are now inside a trigger queue
- Camera movement is no longer inside a trigger queue
- Changed model of Priest to Reign of Chaos version
- Changed model of Sorceress to Reign of Chaos version

### Abilities
* Pillar of Flame
  - Renamed Flame Strike to Pillar of Flame
  - New icon by The_Avenger's_Return
  - Decreased area of effect from 200 to 100
  - Decreased cooldown from 10 to 5 seconds
  - Decreased mana cost from 135 to 65
  - Decreased duration from 9 to 5 seconds
  - Decreased cast range from 800 to 600
  - Can no longer damage Khadgar
* Realm of Time
  - Can now be cast on all enemy or neutral units
  - Can be recast to cancel it on a target unit
  - Now lasts forever
  - Cooldown increased from 2 to 8 seconds
  - Sound effects changed
  - Mana cost increased from 75 to 120
  - Changed description
* Magic Stash
  - Added Transfer Items to Magic Stash unit
  - Mana cost increased from 25 to 50
  - Cooldown increased from 10 to 20 seconds
  - Decreased sight radius from 900/600 to 400
* Wind Walk
  - Improved description
  - Removed bonus damage
* Portal
  - The Portal units can no longer be selected
  - Changed spell information on Normal difficulty
  - Runes are no longer hidden on Normal and Hard difficulty
  - Added white glowing runes on Hard difficulty
- Changed Haste buff to Haste
- Steal now works on invulnerable units

### Items
- The Song of Aegwynn now functions like a Spell Book
- Removed Conan's Claws and Spartan Shield from Volbir and Bolvir Merchandise
- Acquiring a Tome of (Greater) Experience with Garona now gives the item to Khadgar
- Will no longer remove power ups at map end
- Renamed Spell Book to Book of Medivh
- New icon for Haste by Wildfire
- New icon for Focus by KelThuzad


## Prologue
- Renamed from "The Violet City" to "The Kirin Tor"
- New loading screen by gemkimart
- Replaced Loading sound with a Teleport effect
- Fixed small library
- Changed position and appearance of some Statues
- Added a Spell Breaker moving around

## Chapter 1
### Gameplay
- Failing the first chest no longer activates the second chest
- Added more pathing blockers around Karazhan
- Decreased hit points of Gargoyles to 200
- Gargoyles will no longer deactivate stone form prematurely
- Increased Repair cast range of Clockwerk Goblin from 50 to 75
- The items Laws of Arcane Magic and Letter for Medivh are no longer removed at map end
- Pages One and Three can now be obtained a few seconds earlier
- Decreased acquisition range of Gargoyles
- Increased partial damage of Magic Land Mine from 100 to 200
- Removed mana of ZombieWraith
- The Gargoyle Spell is now created when combining the pages
- Can no longer destroy The Gargoyle Spell
- All items created at map start are now invulnerable
- Moved some Magic Land Mines
- Magic Land Mines are now invulnerable

### User Interface
- Khadgar will now comment when selecting the Specter
- Removed Backyard/Graveyard hint on Easy and Normal difficulty
- Removed Shipyard hint on Normal and Hard difficulty
- Khadgar is now paused instead of changing his owner when repairing the Observatory
- Removed Way Gate Hint on Hard difficulty
- Changed initial ownership of Gargoyles to Neutral Passive
- Changed description of Khadgar's Pouch
- Removed hint about entering the boat
- Removed player 12 (The Guardian) from score screen
- Increased hero level of Professor Marvel from 1 to 3
- The Return transmission will be activated 6 seconds later
- Changed quest requirement to "Find Page One, Page Two and Page Three"
- Changed quest requirement to "Create the Gargoyle Spell"

### Audio/Visuals
- Intro: Changed camera
- Removed Glowing Runes at Gargoyles
- Removed Dead Woman
- Fixed water sound regions
- Removed all superfluous waterfall sounds
- Added ItemReceived sound when obtaining the Gargoyle Spell
- The Renegade Wizard exclamation mark is now removed and recreated
- Improved teleport effect
- The Grain Warehouse can no longer be selected or destroyed

## Chapter 2
### Gameplay
- Items from Chapter 1 are now removed after answering the appropriate questions
- Added a crate with the Laws of Arcane Magic
- Khadgar can now be controlled during the interviews
- Items dropped in the Observatory or the Kitchen are now moved to Khadgar's Quarters
- Khadgar's mana is set to 100% after the first interview
- Decreased base damage of Skeletal Marksman from 20 to 16
- Decreased base damage of Unbroken Rager from 20 to 16
- Decreased base damage of Voidwalker from 22 to 20
- Decreased base damage of Greater Voidwalker from 35 to 30
- Decreased base damage of Fire Revenant from 13 to 12
- Decreased base damage of Sludge Flinger from 22 to 20
- Decreased base damage of Giant Skeleton Warrior from 11 to 10

### User Interface
- New loading screen by Mr--Jack
- Added a 5 second wait timer before the NoExit transmission can be replayed
- Replaced Botanic Garden Hint with transmission by Wraith

### Audio/Visuals
* Intro cinematic
  - Items and a Circle of Power are now hidden
  - Fixed pathing problems of Khadgar
* Medivh
  - Medivh no longer walks away after the first interview
  - Medivh is no longer visible in the Kitchen until the second interview
- The Specter is now hidden until after the first interview
- The Library Circles of Power and floating texts are now removed earlier
- The camera will no longer move after the Outland cinematic

## Chapter 3
### Gameplay
* Start
  - Khadgar's mana is now set to 60 until he is healed
  - The Bullfrog can no longer be dropped
  - Decreased hit points of Spitting Spider from 300 to 200
* Finding
  - The Alchemist's chest will now also drop a Sharp Knife
  - A Champion's Curl is now created when using the Sharp Knife on Lothar
  - Added Khadgar's Diary
  - The Vulture is no longer ethereal
* Spying
  - Added Lothar's Notes
  - Removed a Grunt from one of the fights
- Moved Lothar further back
- Moved crate with Chest Key to the human camp
- Decreased acquisition range of Swordsman
- Removed many pathing blockers for the fights
- Player 1 and Player 2 now treat each other as Neutral
- Can no longer initiate a conversation with Lothar by selecting him

### User Interface
- Removed Barrel transmission on Normal and Hard difficulty
- The KhadgarHurt transmission will no longer play twice
- Increased hero level of Mam and Sax from 1 to 5
- Can no longer cancel a conversation with Lothar
- Renamed players Orcish Scouts to Orc Scouts
- Renamed Log to Bundle of Lumber
- The lumber hint is no longer displayed on Hard difficulty
- Will no longer mention something explosive while placing the Barrel
- The missing dusguise transmissions can no longer be repeated

### Audio/Visuals
* Intro cinematic
  - Increased terrain height behind gryphons
  - Khadgar's death animation is now played at the end
- Outland cinematic: All units are removed at the end
- Added animation to Resurrection Stone
- Improved water sound regions
- Improved terrain around the Keeper Statue
- Replaced some pathing blockers with a force field
- The corpses are now removed when going to the Alchemist

## Interlude
- Decreased scale of Hammer from 1.8 to 1.5
- Fixed non-existent walls
- Fixed sounds not playing while repairing the Telescope
- Removed Resistant Skin of Infernals
- Increased attack range of Aegwynn from 100 to 600
- Replaced custom spells with standard spells and effects
- Improved effects
- Units are no longer constantly being healed
- Decreased time of battle
- Sargeras and Aegwynn are now removed when the vision ends
- Changed cameras

## Chapter 4
### Gameplay
- Can no longer complete a task by Cutty before talking to him
- Changed pathing in the Observatory
- Changed location of items in the Observatory
- The Empty Bottle can now be filled at the well
- The destructible crates are now created when the Radar is bought
- Moved a Footman at the Palace to the west
- Removed pathing blockers at the Palace chest
- Decreased acquisition range of all Honor Guards and Footmen
- Removed Footmen and citizens from the Harbor
- Added citizens to the King's garden
- The bandits now attack at the chest in the Harbor
- The Ismail dialogue is now triggered by bringing him a Golden Tooth
- Replaced dialogs for Ismail's transmission with a reaction game
- Decreased size of region to trigger Ismail
- Added Horn of Stormwind to the Harbor Shop
- Changed position of Specter
- Added more pathing blockers
- The Radar is now removed when acquiring the Gold Bag
- Removed an Assassin
- The Staff of Teleportation is now created 4 seconds earlier
- Albert will now attack the Mutated Sheep earlier
- Decreased starting hit points of Fountain to 50
- Moved Book in Observatory slightly to the left
- Removed vision on Specter
- The Signed Papers will now be given directly to Khadgar
* Acetone
  - No longer adds 200 damage to Khadgar
  - Is now a usable item
  - Can now be dropped
  - Is now removed after beating the Gambler

### User Interface
- Entering a building will no longer change the camera bounds
- The first LotharGuardian dialogue can now be skipped
- No longer creates additional buttons for the PalaceGuardsID dialog
- Renamed quest "Where is Lothar?" to "Champion of Azeroth"
- Khadgar will no longer say where the Gamble is on Normal and Hard difficulty
- Removed hint about speaking to Lothar on Normal and Hard difficulty
- No longer repeatedly triggers the Lothar conversation without new information
- The Return to Medivh hints are no longer displayed if Khagar is in the Observatory
- Renamed Malloy to Christoph
- The Fountain floating text will now appear on all diffculty levels
- The EnterHousingBuilding hint will no longer appear before Khadgar talked to Duck Maylor
- Replaced FightFlee transmission with a floating text by Ismail
- Changes transmissions by Ismail
- The Sheep transmissions will now only appear on Normal and Hard difficulty
- Renamed Wake Up Juice to Ingredients List
- User control is no longer disabled when saying no to the Gambler
- The ships, Tavern and Siege Engine can no longer be selected
- Housing Firefighters Dialogue will now play earlier
- Changed description of Cutty's List
- Removed hint on where to find Lothar on Normal dificulty
- Replaced hint about east-Stormwind with transmission by Khadgar
- Added some time before Garona talks about her mana
- Renamed Ismail to Ismail the Collector
- Changed unit name of Ismail to Captain
- Improved description of Golden Tooth
- Added floating text by Peasant when placing the Barrel
- Replaced hint aboud School Area with transmission from Khadgar
- Renamed Honor Guard One and Honor Guard Two to honor Guard
- Replaced hint "Talk to Lothar" with a quest requirement

### Audio/Visuals
- LotharArrives cinematic: Improved cameras
- Peasants will no longer be attacking the pillars in most cinematics
- Added new cinematics for the Guardian dialogues
- Improved terrain in some areas
- Changed position of many doodads in the Observatory
- Replaced all Swordsmen with Footmen
- Changed Honor Guard model to Swordsman
- Added an Honor Guard in the King's Quarters
- Fixed height of chains in workshop
- Decreased hit points of Jesse McGambler to 500
- Hit points of Jesse McGambler will no longer reset during the fight
- Moved Harbor camera slightly to the right
- Added a Circle of Power to Ismail
- Replaced Stone Tables with Wooden Tables
- Removed Clock Tower
- Changed model of Book
- Changed position of Harbor2 camera
- The Sleep effect will no longer appear on Khadgar
- The exclamation mark on Horace no longer disappears until the conversation has finished
- Added exlamation mark on Albert
- Removed shared vision on Neutral Passive when entering Albert's Wares
- Added GoodJob sound when bringing the Building Plans
- The Barrel of Explosives is now moved to the Circle of Power when dropped

## Chapter 5
### Gameplay
* BanquetVision
  - Added ghosts which must be defeated when acquiring the Ghost Mushroom
  - Can no longer reach the Barrel of Explosives outside the storeroom
- Garona: Haste and Inventory are no longer disabled when chasing/fighting Garona
* Interview
  - Garona no longer loses her abilities after losing
  - Garona is now invulnerable
  - Remade to be more interactive
  - Khadgar can now be controlled
  - Interview will no longer completely reset if lost
- Demon: Switched positions of Mana Plant and Hardened Demon Blood
* Leaving
  - Moved pathing blockers
  - Medivh is now invulnerable until Khadgar can use Realm of Time
  - Garona can now also create the Spell Book
  - The storage room can now be accessed after the Guldan cinematic
- Replaced visibility on Chapel and Garden Gate with Fog of War
- Garona's mana is now 100% after cinematics
- Replaced a Tome of Greater Experience with multiple Tomes of Experience
- Cook now remains invulnerable

### User Interface
* Order
  - The proper quest requirement is now completed when reading an Order message
  - Replaced hint about the correspondence with a transmission by Khadgar
  - Improved description for Message from Lothar
* BanquetVision
  - Added explanation as to why Khadgar needs to get into the Banquet Hall
  - Removed dialog button Nothing
  - Changed transmission about Medivh when using the Telescope
  - The Items transmission is no longer played on Hard difficulty
  - Improved description for Ghost Mushroom
* Interview
  - No longer creates the answers multiple times when losing
  - Added more choices
  - The DemonFlee transmission can no longer be played multiple times
  - Garona's inventory is now disabled until her mana is replenished
- Leaving
  - Garona will now say something when she tries to combine an item
  - Can now skip the Medivh Dialogue
  - Removed camera pan when creating the vision
- Will no longer clear selection when talking to Moroes

### Audio/Visuals
- Intro cinematic: Added pathing blockers at Medivh's quarters
* Sargeras cinematic
  - Changed some text by Khadgar
  - Changed a camera
  - Changed blink effect
* Nielas cinematic
  - Made table smaller
  - Changed cameras
  - New model for Nielas Aran by Stefan.K
  - Changed color of Nielas Aran to pink
* ReportDemon cinematic
  - Removed the demon
  - The reveal effect is now properly destroyed
- Guldan cinematic: Can no longer see the Outland sky before the Outland scene
- Garona: The FelHound sound can now be heard
* Leaving
  - Added effects to visualize the path blocking
  - Granted shared vision of Garona
- Replaced Vision floating texts with new cinematic
- Added more object hints

## Chapter 6
### Gameplay
* Entrance
  - Removed two of the Tree peons
  - Will regain control more quickly when approaching the Burrow
  - Only Khadgar will now be paused when approaching the village
  - Replaced Watch Tower with a Burrow/Peon
- Water: Fixed bug turning preventing Garona from walking on water
* Portal
  - Decreased range of Portal at Hungry Footman
  - The island no longer deactivated with the second group of warlocks
  - Will now check more frequently if a hero stands on a Portal
  - Moved second group of ChickenGrunts to the south
* ScoutTower
  - Added more enemy units
  - Increased acquisition range of enemy units
* Renegade Wizard
  - Replaced pathing blockers with a force field
  - Removed 4 Gold Coins
  - Decreased gold cost of Barrel of Explosives from 2000 to 1000
  - Added more destructible rocks
  - Khadgar and Garona will no longer become vulnerable
  - The Renegade Wizard now drops a Potion of Mana when killed
* HeavyBag
  - Improved enemy AI when the Heavy Bag is picked up
  - Can no longer activate all switches with a single hero
  - Can no longer pick up the Heavy Bag without Wind Walk
* Escape
  - Destroying a Prison tree now destroys the other too
  - Moved Prison trees to the west
- Added a delay before a hero becomes invulnerable
- Garona may now also use the Chest Key
- Khadgar and Garona can no longer attack units
- All enemy and neutral units are now vulnerable
- All enemy and neutral units are now periodically healed
- Added more orcs
- Will no longer create additional items if Khadgar is not restored from game cache

### User Interface
* Entrance
  - Thorough transmission is now triggered after the first Elevator
  - The Disguise quest is now always discovered before completion
- Water: Removed debug messages when Garona drinks an Elixir of Water Walking
* Portal
  - Added a transmission about luring Grunts on Easy and Normal difficulty
  - First group of warlocks will now say something when teleported
  - Fixed disappearing exclamation mark on first ChickenGrunt
  - Changed transmission about luring a Grunt
* Renegade Wizard
  - Added transmission by Renegade Wizard
  - New transmission about orcs at the Goblin Shop
  - The camera now pans when placing the Barrel of Explosives
  - Added an additional floating text by the shop
- HeavyBag: Changed transmission when killed
- Renamed player Azeroth Scouts to Azeroth Company
- Increased hero level of Lothar from 7 to 8

### Audio/Visuals
- Moved some Glowing Runes
- Intro cinematic: Added fade
- Nielas cinematic: Khadgar is now stopped when the cinematic starts
- Can no longer hear combat sounds during cinematics
* Renegade Wizard
  - Removed the Advanced Boulder Tower
  - Replaced Sasquatches with orcs
  - Replaced Forest Troll Warlord with a Renegade Wizard
  - Added more rocks around the shop
  - The runes are no longer visible until Khadgar arrives
* HeavyBag
  - Changed human camp to orc camp
  - Added more rocks at the bridge
  - Removed a tree at the bridge
  - Removed a Raccoon

## Chapter 7
### Gameplay
- Main Hall: Can now speak to the Statue without carrying the Song of Aegwynn
* Banquet Hall
  - Can no longer get the Cheese by going to Cook on Hard difficulty
  - Moved a Tome of Experience
* Chapel
  - Removed a Tome of Experience
  - Moved a Life Egg
* Garden
  - Can no longer get the Spirit Drink by going to Moroes on Hard difficulty
  - Garona is now invulnerable
- Library: Changed maximum number of Slime Demons to 4/6/8
- Secret: Difficulty now affects number of dialog buttons for the Door Code
- Observatory: Increased range of where Telescope items can be used
* Statue Combat
  - Khadgar will no longer be forced to die on his first attempt
  - Replaced turn-based combat with real-time combat and puzzles
  - Removed Statue Combat Rules
  - The MeetMedivh/OldKhadgar cinematics are now automatically replayed when losing
- Fixed Spirit Drink and Cheese appearing twice
- Improved path blocking

### User Interface
* Main Hall
  - Added a titel to the Statue dialog
  - Improved description of Reverse Speech
  - The Statue now gives the Statue Combat Rules to Khadgar immediately
  - Changed quest requirement to "Activate and defeat the Corrupted Minions"
* Garden
  - Changed quest requirement to "Heal the plants" on Hard difficulty
  - Added dialog button for asking Garona for a blade
- Library: Changed quest requirement to "Kill the Library Demons"
* Observatory
  - Items descriptions for the Telescope are now more ambiguous
  - Changed name of List to Telescope List and improved description
* Lothar
  - Changed a dialog button text
  - Changed transmission about the Song of Aegwynn being the key
* Statue Combat
  - Changed ownership of all Statues minions to player 5 (Corrupted)
  - Added "Main Quest Completed" message
- Random Swordsman transmissions will now only play once
- Renamed Cook to Cook's Corpse and Moroes to Moroes's Corpse

### Audio/Visuals
* Intro cinematic
  - Can no longer see the Chapel Swordsman
  - Changed cameras
* Stormwind cinematic
  - Increased death time of Llane
  - Increased death time of Llane from 1.5 to 10 seconds
  - Honor Guards will now walk towards Llane
* OldKhadgar cinematic
  - Changed cameras
  - Added death animation to Khadgar
  - Garona is now being teleported away
* Outro cinematic
  - Changed cameras
  - Lothar's shackles are now destroyed when Medivh is attacked
  - All items are now removed
* Banquet Hall
  - The portals are now removed after teleporting the rats
  - Replaced PlaceCheese transmission with GoodJob sound
* Library
  - Changed model of Sludge Demon to Sludge Minion
  - Removed Slime Demon
- Observatory: Changed models of Gearwheel, Hammer and Radar to the standard model
* Statue Combat
  - Added a Force Wall at the endfight
  - The final battle themes will no longer repeat
- The resurrection region is now ativated after the Intro cinematic
- Replaced Shackles with Realm of Time effect
- Added camera border effect to Medivh's Secret Quarters
- The Circles of Power of a Statue is now removed when the Statue is beaten
- Added flies in the Kitchen
- Changed camera in Museum
- The Glowing Runes in Medivh's Quarters are now visible on all difficulty levels
- Changed tint color of Fountain
- Will no play ItemReceived sound when finding all Spectres
- Changed special effect when finding all Spectres

## Epilogue
- Restructured types of credits
- Updated all credits
- Increased duration of credits
- Changed final message
- Delayed final fade out
- Removed waterfall sounds
- Added sound effect when Medivh morphs into a raven
- The cinematic music will no longer play over the credits music
