# Update 4 [2.0.0]  (2016-12-13)
487 changes

## Campaign
### Multiple maps
#### Gameplay
- Merged numerous areas and their gameplay
- Removed several areas that contained no gameplay besides walking
- Changed terrain for almost all areas
- Undiscovered areas will now be covered by a black mask
- Enabled Fog of War
- The camera will now always focus on Khadgar if he and Garona are selected at the same time
- Added cheat "camera" to switch between "adventure" and "strategy" camera modes
- Hero abilities level skip set to 2
- Rebalanced all non-quest alchemy items
- Added Chest Keys which are hard to find but can open any chest instantly
- Selecting the Specter will now add a skill point to Khadgar
- Items sold by a Marketplace or vendor are now removed from stock
* Karazhan
  - Decreased number of areas from 65 to 26
  - Changed various connections between areas
  - Decreased map size from 160x224 to 96x192

#### User Interface
- Karazhan: Renamed all gates to Karazhan Gate
- Changed hotkey layout to QWER
- Fixed duration of some transmissions
- Capitalized all golden letters in the Song of Aegwynn
- Selection will no longer be cleared when talking to people
- Renamed all non-quest alchemy items
- Improved descriptions of all non-quest alchemy items
- Changed icons and models of some non-quest alchemy items
- Dialog titles will no longer disappear
- New loading screens
- User control is now disabled less often

#### Audio/Visuals
- Improved terrain outside gameplay areas
- Added smooth movement to all cameras when changing angles/areas
- Changed almost all camera angles
- Improved camera movement in cinematics
- Karazhan: Decreased number of game cameras from 65 to 26
- Karazhan: Changes to various doodads (e.g. color, scale, pathing)
- Khadgar: Changed attack type and visuals of Grunt-Khadgar to melee
- New model for Aegwynn by Chizume
- Decreased sight radius of cinematic gryphons to 0
- Replaced all non-Blizzard music with Blizzard music
- The music will now continue playing after winning a fight
- Decreased number of flickering textures
- Added floating texts to the Chests which show previous lockpicking attempts
- Fixed a bug preventing music from playing after cinematics
- Will no longer play the EnchantedCellLoop sound for vision cinematics
- Fixed sound regions
- Fixed positioning of Circles of Power

### Heroes
#### Khadgar
- Decreased collision size from 32 to 24
- Attribute points are now retained when turning into a Grunt
- Added a special effect when turning into a Grunt
- Decreased maximum levels by 1 per map
- Set experience gain to 100% until he has the minimum level for each chapter
- New passive hero ability Lockpicking that will automatically unlock pins on chests
- Flame Strike: Added info that it can damage trees
* Realm of Time
  - Is now part of the Spell Book acquired in Chapter 5
  - Fixed sound effect
* Haste
  - Increased Attack Speed bonus from 20/25/30% to 35/45/55%
  - Decreased cooldown from 20 to 15 seconds
  - Improved description
* Alchemy
  - Can now be levelled manually
  - Decreased cooldown from 5 to 2 seconds
  - Quest items no longer cost additional mana
  - Quest items no longer require a minimum ability level
  - Removed info about penalty
  - Will now always play a sound effect when creating an item
* Portal
  - Decreased casting range from 3000 to 1200
  - Decreased cooldown from 5 to 3 seconds
  - Units are now teleported by entering the associated regions
  - Fixed a bug that moved units to the center of the map when using a portal
  - Decreased time of teleport effect
  - Is now part of the Spell Book acquired in Chapter 5
  - Improved description
* Focus
  - Renamed Concentrate to Focus
  - Increased mana cost from 0 to 25
  - Added level 3 which will highlight information and disable Fog of War
  - Decreased cooldown/effect time from 10 to 6/8/10 seconds
* Lockpicking
  - Decreased number of picked locks required to open mosts chests by 2
  - Fixed a bug that prevented resetting the counter of bad lockpicking attempts

#### Garona
- Decreased collision size from 32 to 16
- Added ability Focus (formerly known as Concentrate)
- New ability Transfer Items transfers all of Garona's items to Khadgar
* Steal
  - Decreased cooldown from 15 to 10 seconds
  - Added stun info
  - Changed buff from Dizziness to Stunned
  - Removed some effects


## Prologue
- Decreased map size from 160x128 to 96x128
- Decreased movement speed of Khadgar from 300 to 230
- Fixed Khadgar's movement behavior
- Fixed some doodad and terrain issues
- Increased Far Clipping of some cameras
- Decreased time of Aegwynn battle by 6 seconds

## Chapter 1
### Gameplay
- Decreased number of areas from 39 to 15
- The Axe can now be used when close to the Tree Bridge
- Removed a Brigand
- Removed four Bandits
- Removed two Kobolds
- Removed two mine fields
- The Bandit Lord will no longer be ordered to attack Khadgar
- Khadgar will no longer stop at the Chest hint
- Removed a Barrel of Explosives
- The weed will now burn faster
- Khadgar will now start at level 2 with no enabled ability
- Increased starting Mana of Khadgar from 0 to 100
- Khadgar's Mana will no longer be stuck at 100 until drinking a Potion of Mana
- Removed the Letter for Medivh from Khadgar
- The first Rogue will now drop Khadgar's Pouch instead of an Axe
- Khadgar's Pouch will give Khadgar various items and the ability to cast Flame Strike
- The top tower of Karazhan is now invulnerable
- Added a Wand of Chain Lightning to each of the Resurrection Stones
- Removed a Potion of Mana
- Added book "Laws of Arcane Magic" to the item shop, which explains "Sympathy"
- Increased range of region for the hint about picklocking chests
- No longer required to step away from the first Chest to retry it
- Can no longer destroy Page Two
- Removed pathing blockers in front of Professor 

### User Interface
- The Weeds transmission will play when the rocks have been destroyed
- The GotYou transmission will play when Khadgar fights the Bandits
- Added a transmission which says not to go back at the starting area
- Added a hint about Chest Keys
- Added hint about switching between camera modes
- Can now skip the first conversation with the Renegade Wizard

### Audio/Visuals
- Decreased number of game cameras from 39 to 15
- Will no longer hear a scream at start
- Added special effect when Zombie turns into a Wraith
- The observatory camera pan is now played in cinematic mode and more quickly
- Removed fade out/in from the ship sequences
- Khadgar's movement speed will no longer be decreased to 80 at the start of the Outro cinematic

## Chapter 2
### Gameplay
- The Guide to Beginner's Alchemy is no longer actively used
- Some items required for the Alchemy quest are now scattered around Karazhan
- Decreased size of regions where books need to be placed
- Removed Library category Funny Books
- Removed a Rune of Mana
- Some killed enemies will now drop Runes of Greater Healing
- Enemies in Library will now spawn in groups of 3
- The Races book is now placed just outside the Library
- The Specter's item will now be created outside Medivh's quarters
- Removed spells from Voidwalkers
- If Khadgar dies during the fight with Medivh he will now be instantly moved to the Library after his resurrection
- During the fight Medivh will now teleport to Khadgar every 10 seconds
- Vision of Khadgar is now shared with Medivh in the fight

### User Interface
- Removed some dialogue from the Intro cinematic
- Added more information to extended tooltip of The Guide to Beginner's Alchemy
- Removed transmissions about the secret ingredient and leaving the garden
- Return to Moroes is now a quest requirement
- The Survive hint is now a required quest named Gone Mad
- Renamed book Animals and Plants to Races. This book now describes trolls and goblins
- Added a transmission that says the gate to the Botanic Garden is locked
- Fixed an error message when Khadgar carries only 1 Stick and tries to use it
- Removed hint about being honest to Medivh
- Renamed item Alchemy to Glyph of Alchemy
- Removed hint about using the minimap to orientate and navigate
- Added transmission about green and blue making purple

### Audio/Visuals
- Added Circles of Power to show where books need to be placed
- Added special effects for spawned Library enemies
- Replaced ItemDrop sound with GoodJob sound when placing a book in the Library
- Most Circles of Power are now removed when no longer required
- Floating texts in the Library will now appear much faster
- Will now play the Warcraft 2 War theme when fighting Medivh
- Moroes reappears now as soon as Khadgar enters the Botanic Garden
- Will no longer change ownership of Old Khadgar in the Outland cinematic

## Chapter 3
### Gameplay
- Decreased map size from 128x128 to 96x96
- Decreased number of areas from 46 to 15
- Increased mana cap at map start from 100 to 125
- Increased experience gain from 50% to 90% at level 4
- Decreased life of Spitting Spider from 400 to 300
- The Dangerous Fish can now be killed but will respawn
- Increased mana regain by Potion of Recovery from 200 to 400
- Removed Rune of Speed from first fight
- Removed alternate route to Orc camp and a force field
- The Guide to Intermediate Alchemy is no longer actively used
- Created Logs will be given to Khadgar if he has enough inventory space
- Decreased level of Blademaster from 3 to 2
- Removed Critical Strike from Blademaster
- Decreased level of Mirror Image for Blademaster from 2 to 1
- Added a Tome of Experience

### User Interface
- The Hurt transmission will now play two seconds after gameplay starts, unless triggered earlier
- Added a transmission which says to burn the trees
- Removed Khadgar's transmissions about fighting groups of orcs and humans
- Removed a transmission by Khadgar when talking to Lothar for the first time
- The Axe can now be used when close to a Tree
- The Axe will now be removed when the player cuts down the second Tree
- Removed one of each unit type in the Corpses area
- Added more information to extended tooltip of The Guide to Intermediate Alchemy
- The Keeper Statue is now a doodad instead of a unit
- Renamed A Hero's Lock to A Hero's Curl
- Decreased time until the hints for Lothar's men appears from 4 to 2 seconds
- Added a new transmission to a Raider
- Can now skip all orc conversations
- Can now skipp all of Lothar's and Khadgar's conversations about Medivh
- Added Object Hints to the Trees
- Khadgar will be selected when turning into a Grunt/Mage
- The inventory will no longer be disabled as a Grunt
- Removed hint about Keg of Thunderwater (now called Extra Spice)

### Audio/Visuals
- Decreased number of game cameras from 46 to 15
- Increased fog Z start from 500 to 1500
- Will no longer hear death sounds at map start
- Removed Blighted Mist from Bullfrog
- Decreased time for Bullfrog Eating Fish sequence
- The Bullfrog Circle of Power is removed during the Bullfrog Eating Fish sequence
- Replaced Felwood Canopy Trees with Felwood Tree Walls in starting area
- Removed a Lava Cracks doodad
- Removed fighting groups of orcs and humans
- Removed Glowing Runes from force fields
- Decreased scale of Scout Towers from 5.0 to 2.0
- Playing a sound when Khadgar gets a Log
- Increased Scaling Value of Logs from 0.6 to 1.0
- The ItemReceived sound when a Vulture or Skink dies is no longer a 3D sound
- The War theme will now play before an enemy starts his transmission
- Added special effects when items and enemies appear for a fight
- Increased region for Color of Rainbows placement
- Units are now properly removed after the MeetLothar cinematic
- Will no longer create an Exclamation Mark above Lothar after helping his men

## Interlude
- Fixed some sound effects
- Fixed missing dialogue
- Decreased scale of Hammer from 2.0 to 1.8
- Changed owner of Medivh from Player 10 (Khadgar) to Player 11 (The Guardian)
- Increased life of all Fel Stalkers from 75 to 750
- Removed all Dragon Whelps
- Units will no longer die until triggered to do so

## Chapter 4
### Gameplay
- Decreased overall map size from 160x160 to 128x128
- Decreased number of areas cameras from 85 to 32
- Removed four fountains
- Increased use region of remaining fountains
- Triggers for the Gambler Peasant are now used on The Bum
- Items are no longer sold via dialogs, instead vendors function like normal Marketplaces
- Renamed Fountain Ruined to Ruined Fountain
- Decreased life of Fountain from 150 to 75
- The position of the Mutated Sheep will be reset whenever Khadgar enters Albert's place
- Added pathing blockers to the School area
- Fixed a bug casting Disease Cloud on Khadgar for 2 minutes
- The Bandits gold coins will now spawn directly at the Chest
- Increased restart region for fight
- Decreased size of region used to talk to Lothar in the Tavern
- The Specter item will now be created at a spot in front of the Fruit Stand
- Increased mana cost of Staff of Teleportation from 0 to 50
- Increased cooldown of Staff of Teleportation from 0 to 10 seconds

### User Interface
- Removed hint about going upstairs in the tavern
- Changed quest requirement "Get him to the mage quarters" to "Get Lothar to the Mage Quarters"
- Removed all triggers for street signs
- Added a reference to another adventure game
- Renamed The Bum to Jesse McGambler
- Renamed City Entrance to Gate
- Changed Race of Citizens from Commoner to Human
- The Tavern Entry hint will no longer run if the Mob has already been chased off
- Improved descriptions of various items
- Added trigger to deactivate the hint to the entrance of the unfinished house
- Added hint to select the shopkeeper to buy something
- Changed unit race of Mutated Sheep from Critter to Other

### Audio/Visuals
- Decreased number of game cameras from 85 to 32
- Increased Far Clipping of all game cameras from 5000 to 6000
- Increased Far Clipping of some cinematic cameras from 5000 to 10000
- Removed Barracks and nearby units
- Removed all Lava Cracks
- Removed Fountain of Power
- Random Mob in front of Tavern will no longer be removed from the game
- The Exit Gate is now removed after the Intro cinematic
- Replaced Circle of Power (Teleport) with a Way Gate
- Decreased fight time with McGambler from 13 to 7 seconds
- Fixed water sound regions
- The Exclamation Mark on Ismail will now be properly removed
- Neutral units will no longer wander around (except Creeps)
- All vendors now belong to Player 3 (Merchants)
- Removed display items from shops in the Housing area
- Replaced Elf Land Mine with Barrel of Explosives
- The Swordsmen will no longer move once the Firefighters have been called
- Replaced Exclamation Marks from all vendors with Object Hints
- Added Wander ability to all children
- Removed supports columns from unfinished house in housing area
- Removed a Water Elemental Missile sound effect
- Changed owner of Workshop Peasant from Player 2 (Stormwind Guards) to Neutral Passive
- Some citizens are now removed when Khadgar enters the Tavern

## Chapter 5
### Gameplay
- The Specter item will now be created at the Specter's position
- Player 12 (The Guardian) will now treat Player 1 (The Emissary) as a neutral
- Order Messages will no longer have any charges left after being used correctly
- Can no longer enter the Observatory before getting the quest "I Spy"
- The Storage Room will no longer be closed after demolishing it
- Will now close the gate when fighting Garona (and reopen it if Khadgar dies)
- Garona can now flee towards any of two directions when being chased by Khadgar
- Removed some wait time until Garona begins to attack Khadgar
- Increased collision size of Garona from 0.0 to 32.0
- Haste and the Inventory are now enabeld before Garonas is finished talking
- The Garona fight can now start while Khadgar is already inside the Banquet Hall
- Added two Runes of Healing when fighting Garona
- Will now play a special effect on Garona when she is moved during the fight
- Fixed a bug that set Garona's level to 7 when redoing the Interview quest
- Garona will no longer use Mirror Image
- The Demon Belt is now invulnerable
- New items and ingredients needed to restore Garona's mana
- The Demon Damage Amplifier will now add +200 to attack damage
- Changed ingredients for the Demon Damage Amplifier
- The Inventory is now disabled for Player 12 after creating Realm of Time
- Combining the items in the Leaving quest will now create the Spell Book which is used to cast Realm of Time
- Removed Mana Bulbs from the Demon fight

### User Interface
- Renamed Red Key to Banquet Hall Key
- Renamed quest "The Messages" to "Order of Tirisfal"
- Renamed quest requirements "Deciper the first/second order message" to "Deciper the first/second message"
- Added hints to the dialog options of the "Order of Tirisfal" quest
- Added minimap pings for the entrance Chest and Medivh
- Removed hint "Check on Medivh"
- Added quest requirement "Return to Medivh" to quest "Order of Tirisfal"
- The hint to the second Chest will no longer appear if it has already been opened
- Removed transmission about picklocking the chest
- Renamed Player 1 from "Vision Horde" to "The Emissary"
- Player 1 (The Emissary) will now be hidden in the post-game score screen
- Added an additional transmission that can play after demolising the Storage Room
- Renamed quest "Another Spy" to "You Spy"
- The Nielas cinematic can now be skipped 4 seconds earlier
- Changed hints about support column
- Removed some dialogue when interviewing Garona
- Garona's hint will no longer be played if her mana pool has already been restored
- Can now skip the Moroes Whistle dialogue
- Removed some dialogue between Medivh and Aegwynn
- Repositioned dialogue (floating text) between Medivh and Aegwynn
- Changed colors of Aegwynn's/Medivh's floating texts from green/red to red/dark yellow
- Can now speak to Moroes before wreaking havoc in the Storage Room
- Removed hint about Moroes not being in his room
- Removed some dialogue in the ReportGarona cinematic
- Removed Resurrection Stone minimap ping when starting the map
- Fixed a bug that prevented the update message for the quest "Revealing the Rift"
- Added transmission about the Spell Book when Khadgar gets the Realm of Time ability
- Added a new transmission about combining Medivh's Grail with other items
- Added quest requirement Defeat the Demon to the Interview with an Orc quest

### Audio/Visuals
- Will no longer hear Medivh dying when gameplay starts
- The Gryphons will be removed before the intro cinematics fade back in
- Increased scale of Sargeras from 1.0 to 2.0
- Moroes is no longer removed after going to the Storage Room
- Will now play a sound when opening the gate to the Banquet Hall
- Cook and Moroes are now removed after the Nielas cinematic
- Garona is now "rescued" when converting to Player 10 (Khadgar)
- Removed Trap Frost doodads
- Garona will now move towards a Gryphon when winning the map
- Will no longer create a Circle of Power in the Observatory to call the Gryphons
- Removed fog from Gul'dan cinematic
- Cook is now removed after the Gul'dan cinematic
- Decreased shadow image height/width of Emissary (Hooded) from 160 to 100
- Added special effect to the appearance of the demon

## Chapter 6
Gameplay
- Decreased overall map size from 192x128 to 160x64
- Decreased number of game cameras from 51 to 20
- Garona is no longer restored from game cache
- Khadgar and Garona will no longer be moved when encountering the Burrow
- Khadgar and Garona can now cross water areas independent from one another
- Removed failsafe which moved a Water Walking item (e.g. Imbued Vial) to one of the heroes
- Water Walking will no longer be removed unless both heroes have had Water Walking
- Removed some Imbued Vials and Ethereal Oils
- Added Elevators that need to be activated by the first hero crossing water
- Removed a Stone of Ressurection
- Resurrection Stones are now activated and used independently by each hero
- The Roasted Chicken item will now be dropped only after the two Grunts die
- The two fighting Grunts will now kill each other 16 seconds earlier
- Removed the peon standing at the Chest
- Decreased movement speed of Warlocks from 270 to 1
- Warlocks will no longer flee from enemy attacks
- Decreased some wait time when teleporting enemy units
- Moved the first Chest to the Troll area
- The first Chest will now drop Gold Coins instead of Imbued Vials
- The Warlocks at the Rider now carry an Imbued Vial and an Ethereal Oil
- Decreased attack range of Burrow from 700 to 500
- Octavia and Khadgar no longer share the same Resurrection Stone
- A hero can no longer teleport to the Shop if he carries the Goblin Land Mine
- Removed all Tomes of Experience
- Added a Tome of Intelligence
- Decreased time between checks for the last bridge switches from 2.0 to 0.2 seconds
- The guard carrying the cell key will now become invulnerable after his key is stolen
- Wind Walk is now disabled while Garona is under the effects of Water Walking
- Removed wait time between using the Prison Key and opening the door
- Units will no longer move to a Portal before being teleported
- Added failsafe if Khadgar gets Garona's Prison Key

### User Interface
- "Thorough" comment will no longer trigger if a hero has reached the Burrow
- The Burrow dialogue can now be skipped
- Will now select Khadgar after turning into a Grunt
- The defeat condition "Don't attack any orcs" will now appear with the Disguise quest message
- Improved description for Give Item hint
- Added transmission "I shouldn't..." if Garona tries to use the last Elixir of Water Walking
- Removed hints for Mind Egg and Life Egg
- Removed repeating Orc Rider floating texts
- Fixed an Orc Rider floating text
- Can now skip the Disguise hint
- Removed transmission about waiting for the other hero
- The Troll Portal hint will no longer be displayed if the troll is dead
- Removed wait time for the Troll Portal hint to appear
- Added transmission for when the hungry Footman gets close enough
- The Disguise Again quest will no longer be marked as discovered when already completed
- Renamed item Portal to Glyph of Portal
- Added transmission about the Spell Book when Khadgar gets the Portal ability

### Audio/Visuals
- Decreased number of areas from 51 to 20
- Removed some Glowing Runes
- Fixed Garona's revive sound
- Increased hero level of Lothar from 5 to 6
- Fixed animation of Resurrection Stones
- Circles of Power will now become hidden when not required
- Added teleport effects when teleporting the Chicken or the Goblin Land Mine
- Removed fade out when being attacked while carrying the Heavy Bag
- The Captured video now starts immediately after pressing all switches
- Glowing Runes will now play a death animation when their respective Teleporter is used
- Replaced Northrend Trees with Fall Trees
- Goblin Land Mine explosion is now visible
- The Barrel of Explosives and th Goblin Land Mines will now be removed after being bought

## Chapter 7
### Gameplay
- Improved AI of rats
- Books borrowed from the Library will now be placed in Khadgar's inventory
- Decreased time until Rats are being teleported
- Rats will now be teleported to random points in the Storage Room
- Rats will no longer move randomly if the Cheese item is in the correct area
- Will create Khadgar's Gem of Health for Khadgar if all Specters were found
- Khadgar will no longer be ordered to stop when using the Chapel Guide
- Can now drop useless books
- Khadgar will no longer stop when speaking to one of the Statues outside the Museum
- Will no longer place the Cheese automatically if the Rats have already been teleported
- Replaced all Tomes of Greater Experience with Tomes of Experience
- Will now remove the Reverse Speech book once spoken to the Main Hall Statue
- Changed movement type of Rats to Foot
- Can no longer get the Reverse Speech Guide once the Examine All Statues quest is discovered
- The Chapel Guide will no longer be removed if another Book is chosen
* Statue Combat
  - Decreased duration of first fake fight from 10 to 8 seconds
  - Changed melee weapons to missile weapons
  - Removed "Down" from the move options
  - Decreased number of combos from 16 to 9
  - Enemies now deal a fixed amount of damage
  - Khadgar now deals his own attack damage +50
  - Decreased hit points of all enemies
  - Changed counter-moves (e.g. LL now beats LU instead of RR)
  - Removed Statue Combat Rules, Parts 2-5
  - Decreased number of moves each Statue can make
  - Decreased some wait time between attacks
  - The enemy will now repeat the last move if it won
  - The enemy will no longer repeat the last move if it lost or it was a draw
  - Fixed a bug that prevented the creation of pages of the Song of Aegwynn
  - The combatants will no longer heal
  - Khadgar's attribute points are now retained when he turns old
  - Will now create a Tome of Experience after each won fight
* Final Fight
  - Khadgar's items will no longer be removed
  - Increased damage of Medivh from 56 to 59
  - Decreased life of Medivh from 1000 to 800
  - Medivh's life is now set to 100% after the OldKhadgar cinematic
  - Khadgar's life is now set to 100% after the OldKhadgar cinematic
  - Khadgar will now forget counter-moves in the second phase
  - It is no longer required to play the first phase if Khadgar dies in the second phase
  - The Statue Combat Rules item is now removed at the start of the second phase
  - Decreased hero level of Lothar from 10 to 9

User Interface
- Player 1 (Vision Horde) and Player 2 (Vision Alliance) are now hidden in the post-game score screen
- New icon for Secret File by kola
- Can now skip all conversations with Lothar
- Renamed Statue Combat Rules, Part 1 to Statue Combat Rules
- Can now skip the OldKhadgar cinematic properly
- Changed description of Radar item
- Fixed a lexical error in the Outro cinematic
- Statue Combat
  - Renamed Paladin to Library Statue
  - Renamed Earthen to Observatory Statue
  - Renamed Garden Statue to Botanic Garden Statue
  - Changed item description and hints for Statue Combat Rules
  - Added multiboard which displays the health of combatants and learned counter-moves
  - Changed color of draw from pink to yellow
  - Moved the hint "Each Statue has new combos..." to the Combat Rules item
  - Added hint "Try to guess unknown counter-moves."
  - Fixed a bug not removing the Floating Text correctly when Khadgar died
  - Changed hint "...with all pages." to "...with six pages"

### Audio/Visuals
- Music or sound volume will no longer be changed
- Removed fire effect at the Library gate
- Replaced EarthquakeLoop1 sound with EarthquakeRock sound
- Decreased scaling of Spanner from 2.0 to 1.0
- The runes at the Secret Door will now play their death animation when the Door is unlocked
- Will now play a sound effect when repairing the Telescope
- Will now play a sound effect when cutting the vines in the Botanic Garden
- Will now play a sound effect when the Orb of Nature is used in the Botanic Garden
- Fixed a bug that continued shaking the camera after skipping the intro cinematic
- Will now stop the Earhquake sound when skipping the intro cinematic
- Removed Runes from the Library fight
- The Circle of Power in the Banquet Hall is now removed when Rats have been teleported
- The Statues will now speak with a proper portrait model
- Added special effect when a Library Demon is created
- Decreased volume of Vision sound
- Added spell animation to Medivh in the OldKhadgar cinematic
- Added more special effects to Lothar and Garona when imprisoned by Medivh
- Removed fog effect from Stormwind cinematic
- Statue Combat
  - Added special effect when Khadgar and the enemy are moved/removed
  - Will now play a DropItem sound when creating a page of the Song of Aegwynn
  - Added special effects to attacks
* Final Fight
  - Swapped positions of Garona and Lothar
  - Increased height of the prison effect on Garona and Lothar
  - Removed reverse effect

## Epilogue
- Time of day now starts at 12PM
- Decreased time of day speed from 20% to 0%
- Removed dead Moroes, Cook and Medivh
- Added spell animation to Medivh
- Changed ownership of last Medivh from Player 10 to Player 12
- Renamed category "Idea and Execution" to "Design"
- Renamed category "Loading Screens, Icons and Miscellaneous Art" to "Icons and Additional Art"
- Removed category "Terrain and Triggers"
- Added Chizume and Oinkerwinkle to Models and Skins credits
- Added kola and Marcos DAB to "Icons and Additional Art" credits
- Removed EvilYardGnome from Models and Skins credits
- Removed Gary Jules and Michael Andrews from Music credits
