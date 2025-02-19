## 4.2.1
- Update MinimapAPI to 2.45
- Readd stinger music to Hub 2
- No longer handle tinted rocks as StageAPI does it
- Fix Haugr errors
- Remove redundant music files
- Fix/improve avalanche AI
- Hub 2 handles pre-womb floors

Internal
- Added build.py to assemble some mod files
- Remove callback return check
- Add StageAPI entity data

## 4.2.0

- Add enemy: Sandstorm
- Add enemy: Juniaugr
- New rooms, including community ones

Tweaks
- Update Rev MinimapAPI to 2.42 (workshop 05.03.2023)
- Vanity shop items can be duplicate with Diplopia
- Willo buffed: aura grants homing tears, taking damage shoots a burst of tears instead of one
- Addict changes: skitterpills have less HP, but more stage HP, dropped pills disappear after a while, more skitterpills possible, using a pill in a room with skitterpills will kill all of them, gold and good pills are less common
- Improve save data behavior and performance
- Added POST_REVELATIONS_LOAD callback for mod compatibility
- More Encyclopedia compatibility
- Clear cache now disabled by default as not needed since latest Repentance patch
- Improve Fecal Freak + Anti-Gravity

Fixes
- Fix Pact of Paranoia replacing existing traps
- Fix Addict skitterpills dropping the wrong pill
- Fix Perseverance crash
- Fix all spiders HP being changed due to Raging Long Legs code
- Fix Birthday candle lowering range
- Fix Cardboard robot visibility
- Fix Ragtime and Prong being broken/softlocked by killing too fast
- Fix some Birth Control synergyes applying to all familiars
- Fix Prong breaking the wrong ice tiles sometimes
- Fix Narc locking controls sometimes

## 4.1.2

- Community rooms!
- Tomb Prank now has sand attack
- Nerf igloo firerate
- Lovers libido works with curse of the blind
- Vanity shops + curse of the blind fix
- Narc spikes can't be mitosed
- Minor epiphany compat tweak for vanity shop

## 4.1.1

- Perseverance: quality 3
- Punishment: cannot attempt steal Legemeton wisps
- Various room tweaks
- Fix room-related crash

## 4.1.0

- Add trinket: Memory Cap
- Add trinket: Christmas Stocking
- Add object: Bell Shard
- Add shrine: Pact of Mitosis
- Rev pocket items have announcer voice lines
- Tutorial rooms for some rev floor mechanics that are much more likely to appear until first encountered
- New rooms
- New Fiend Folio-compat rooms, including skins for many FF enemies

- Update internal MinimapAPI

Tweaks
- Tweaked HP of a lot of Rev monsters
- D+C: no bonus heart
- D+C: extra boss items only on second stages
- Sandshaper: AI rework, active instead of reactive
- Dungo: shockwaves target player, can die before phase 2
- Rag fatty: buffed
- Anima: faster
- Bloatbip: faster
- Antlion egg: spawns less babies with more HP
- Tomb revive traps close doors
- Some item quality
- Pact of grounding: 2->3 vanity
- Vaniy shop items spawn the collectible, should be more compatible with various game features
- More SFX
- More EID support

Fixes
- D+C item dupes and knife/rep sequences issues
- Rev item tracking counting fake items as real
- Death certificate in rev stages, half of this on the StageAPI side
- Mirror room shard dupe or vanishing
- Elites being guaranteed, weren't supposed to
- Champion Prong not needing achievement
- Dynamo

## 4.0.3

- Vanity has functions for other mods to spawn their own vanity shop items
- Hice and Iced Hive have new effects when killed
- Rebalanced HP of several Glacier enemies
- Nerf Sarah demon speed
- Faster snowst attack
- Various reskins for FF enemies
- Increase sandbip hitbox
- Change ragtag behavior
- Room updates
- Fix Dante+Charon unlocks
- Fix Dante Satan room appearing for sarah in her angel room
- Fixed a certain fun easter egg
- Fix birth control + legemeton
- Fix FF rooms not appearing
- Fix EID mod name
- Fix maxwell softlock with charmed enemies
- Remove old glacier bosses from champion achievement
- Fix stalagmight + dark arts
- Fix fragile ice pit respawning
## 4.0.2

- Fix data not resetting between runs, leading to
persisting shrine pacts, charon items and mirror
door not spawning again
- Fix Chuck softlock
- Ice Wraith doesn't block Dead Sea Scrolls menu
update (might need an update in other mods that
use DSS)
- Williwaw loses the dmg reduction if he stays in 
his intro for too long
- Increased the aura radius of coal shards
- Increase vanity price of q4 items by 1, reduced
the vanity price of the more expensive items
- Fix haugrs not working
- Cracked key can be used in a certain room too
other than the red key
- Glass shards can no longer be abused to respawn by rerolling etc.
- `revunlock` command is no longer tied to DEBUG mode

## 4.0.1

- Temporarily disable XL Rev floors until we find
a way to fix those properly
- Minor room tweaks

## Vanity Update - 4.0.0

Major Features

- Replace the Hub room with Hub 2, inside of the Repentance transition room, and usable by other mods. Old Hub can be enabled via setting, and is still found in the starting room
- Shrine System overhaul: Shrines give Vanity, can be exchanged for rewards at chapter end in a new shop. The shop has many fun things...
- New shrines, detailed below
- New enemies and an elite, detailed below
- Many boss balance tweaks and reworks, detailed below
- MinimapAPI included with the mod, installing the standalone version is still supported and also recommended to have it always up to date

New enemies

+ Jackal
+ Gilded Jackal
+ Stabstack
+ Ragma
+ Harfang
+ Pine
+ Pinecone
+ Snot Rocket
+ Dune
+ Blockblockblockhead Gapers
+ New Elite: Ragtime, with his troupe

New shrines

+ Pact of Champions
+ Pact of Grounding
+ Pact of Scarcity
+ Pact of Masochism
+ Pact of Punishment
+ Pact of Hemorrhage
+ Pact of the Ice Wraith
+ Pact of Paranoia

Major general tweaks

- Dante and Charon: Phylactery is a pocket active item
- Dante and Charon: no longer force Curse of the Labyrinth, instead each character has a separate map memory
- Glacier general graphics overhaul
- Tomb grids graphics overhaul
- Glacier is smaller (experimental)
- Revending machine can have different item pools, and support for shop affecting items
- Old hub has Repentance functionality if option is used, making Rev stages cost keys/bombs too
- Birthright for Sarah and Dante and Charon
- Custom tracks for boss calm, shop, secret rooms, and more in rev floors, from the Afterlife OST (with permission)
- Rev items support transformations
- Restore rev item weights to normal, currently dynamic weight system + base weights made rev items way rarer
- Add setting to disable dynamic item weights, setting rev items to always baseline weight
- Sinami now has a reward, as Bertran is out and about, increases with retries
- Something with Narcissus?


Major boss tweaks

- Chuck rework, doesn't use invincibility anymore and completely overhauled fight pattern
- Sarcophaguts: buttons don't get all lowered when one is pressed, hard cap on gut amount, lower bullet speed and easier patterns, less hp, slightly more boulder damage, vulnerable during laser attack, guts spawn more spaced out to reduce shielding, buttons move slowly instead of completely stopping, can be shot from any angle instead of just the front when open, head only shoots when player is close, no long rooms, rework phase 2 guts attack
- Narc 2: shard explosion has tracer tells, pillars can be damaged without bombs but less
- Sandy: final attack lasts less (even less for Jeffrey), Jeffrey starts at 50% HP, has slightly reduced damage
- Maxwell lasers have a telegraph
- Willywaw: more damage reduction during phase transitions, can only do Beast Winds attack once in phase 1, increased snowflake speed for it, and lasts much less for clone, clones no longer block shots, more time to shoot snowflakes during wind attack, Gateway Sniping slows down player
- Catastrophe: yarn leaves a trail when it is damaging, remove shield for guppy's urn
- Raging Long Legs: decreased health from spawns, reduced spider spawns
- Punker: no longer shoots puckers during dash, more brimstone laser telegraph, removed from catacombs
- Dungo: has high damage reduction instead of invincibility, hp bar streamlined during fight so boss progress is more visible, reduce shockwave fart frequency, reduced fart range, projectiles are more predictable, red poop projectiles no longer bounce, reduced red poop cap, small delay between phase 2 plunger attacks, shockwaves are targeted, coffins have a cooldown, golden boulders take damage when dropping coins
- Auroric Glacier Pride
- Snotty Glacier Sloth
- Tomb Gluttony has damage reduction instead of invincibility
- Elite HP nerfed
- Added GigaChuck


Other changes

* Heavy internal refactor and rework
- Pact of Gratuity renamed to Pact of Mischief
- Pact of Radiance renamed to Pact of Frost
- Improve how custom rooms (mirror, etc) work thanks to StageAPI changes
- Slightly improve reflections depending on character
- Better glacier shaders are default, since Repentance they should be compatible with all graphics cards (that support Repentance)
- Rev floors' name streak can now show up when holding tab
- More sounds
- Setting for global mod sound volume
- Hud Offset setting automatically matched without manual config
- "Never won with" no longer increases rev item chance with dynamic item weight
- Starting room doodles for the rev characters
- Dynamo has a charge bar
- Elites have a 33% chance to drop boss pool items
- Narcissus 1 and 2 have outro jingles
- Fragile ice easier to see
- `rperf` command to test out performance of the mod via the log
- Shrine pacts have HUD icons
- Add `addv` command to add Vanity, `vshop` command to teleport to the vanity shop, `revpact` command to add a shrine pact
- Tinted rock spiders drop runes with Geode
- Can push hockey puck with swords/bones
- Settings include a reset save button
- Punker and RLL no longer required for the champions achievements
- Freezing snowballs leave snow particles
- Sand castle affected by archaeology, custom drops
- Urny: clearer tell, no longer recoils off enemies
- Wendy: damage reduction on phase transition
- Freezerburn and Tomb Gluttony have a different color damage flash to show damage is being reduced
- Remove Window Cleaner from boss item pool
- Buff moxie's paw damage
- More birth control effects for Rep familiars
- Mirror bombs updated for rep floors
- Ghost pepper, bird's eye, red candle can now break ice rocks
- Rag family has glow eyes when buffed
- More glow effects in general
- Glacier Lust's body leaves creep for easier seeing
- Fragile ice has a warning before snowsts break it
- Narcissus 1 and 2 have a VS screen after the first encounter

- A lot of new sfx!
- Various minor sprite updates
- Various minor polish
- Various numerical boss and enemy tweaks 
- More optimization, hopefully
- Lots of bug fixes, too many to write and/or remember
- More rooms

Internals

* Split most things into their own file
* Made naming and spacing more consistent
* StageAPI metaent update: Use StageAPI directions for traps too in rooms, etc.
* Rev library is separated into various files, and has a `library.md` file to list all its functions. `library.md` can be generated/updated with a Python script, `generate_library_list.py`.
* XML script to merge shaders 
* Rev now contains an `enums` folder that contains various custom enum files for rev and missing vanilla stuff, including rev/stageAPI callbacks
* add `idcheck.py` to check for used ids in entities2.xml


