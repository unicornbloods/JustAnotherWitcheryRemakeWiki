# Changelog

## 0.5.38

### Additions

### Changes
- Sacrificial circle for vampire path requires 8 candles too.

### Fixes
- Crash when using candles on sacrificial circle (26.1.2)

## 0.5.37

### Additions

### Changes
- Blacklist resource mobs from Productive Bees encasing

### Fixes
- Spirit villagers could be picked up and sometimes duplicated with Easy Villagers (Forbidden magic)
- Not consuming [Mutandis](Items/Resources/Mutandis.md) in off-hand
- Being able to close the tarot screen to avoid unwanted tarots mid-draw
- Death's healthbar doesn't go away after he is killed
- Rituals not completing and leaving the golden chalk stuck
- More sycning for lich, vamp, werewolf attributes

## 0.5.36

### Additions

### Changes
- Ent spawning, Vampire children hunting, Freeze and Petrify logic optimized
- Owl wont drop off of a player riding a broom

### Fixes
- Chalk crafting recipe error

## 0.5.35

### Additions

### Changes

### Fixes
- SummonItemWithOwnerRitualEvent checks for fake player
- Nightmare movementspeed typo

## 0.5.34

### Additions

### Changes
- Wild Bramble accepts the witchery gold_ttols tag insetad of just gold axe.
- Vanilla Wooden Spear added to Witchery Wooden weapons tag

### Fixes

## 0.5.33

### Additions

### Changes

### Fixes
- Dont void items if hanged man event fails

## 0.5.32

### Additions
- Reversed Lovers now also affect Fish

### Changes

### Fixes

## 0.5.31

### Additions

### Changes
- Player shells get better load/unloading when teleporting between spiritworld and overworld

### Fixes
- Brew of sleeing consuming the first spiritworld transferable item in inventory
- Fixed Owl model transform

## 0.5.30

### Additions
- Owls can be on shoulder
- FTB essentials /enderchesat compat for spiritworld
- Capability for Oven to accept items input output

### Changes

### Fixes
- Owl taming
- Chalk enchantability
- Potion crash with Sortilege


## 0.5.29

### Additions

### Changes
- Reverse The Devil accelerate curses so they last shorter

### Fixes
- Book lang entries name
- Brew of Oblivion entry in Tarot section
- Stack overflow issue in hunter chance

## 0.5.28

### Additions
- Effigy mechanics

### Changes

### Fixes
- Formatting error in tarot pages for guide book

## 0.5.27

### Additions
- Added hunter ambush chance to more rituals, abilities and voodoo

### Changes
- Bosses can now kill vampires

### Fixes
- Fix Tablet block entity ticking too frequently (Forbidden magic)
- Missing langs for quest book
- Fixed statues item display
- Fixed hobgoblin patron statue unbound on break
- Fixed spinning wheel sometimes not consuming input item

## 0.5.26

### Additions
- Easy Villagers support for taglocking

### Changes

### Fixes
- Vampiric poppet crash damage redirect loop.
- Hunger and armor poppet missfire

## 0.5.26

### Additions

### Changes

### Fixes
- Curios transfer into proper slots

## 0.5.25

### Additions

### Changes

### Fixes
- Curios get deleted on death in spirit world

## 0.5.24

### Additions

### Changes

### Fixes
- Ticking arthana block

## 0.5.23

### Additions

### Changes

### Fixes
- Broom not flying

## 0.5.22

### Additions
- Made werevolves spawn naturally around an altar with a bear trap
- Made 3% chance of a villager to be a werewolf on spawn

### Changes
- Made werewolf-players stronger

### Fixes
- Vampire death message being "Turned to ash but the sun"
- Curio transfer in soulform
- Werewolves not animate thair arm when attacking

## 0.5.21

### Additions
- Draggable Hud for Soul Pool (Forbidden magic)
-
### Changes

### Fixes
- Vampire child hunt UnsupportedOperationException crash


## 0.5.20

### Additions

### Changes
- Leaving the spiritworld drops non transferable items in the spiritworld

### Fixes

## 0.5.19

### Additions


### Changes

### Fixes
- Mixin config typo

## 0.5.18

### Additions
- Spirit world support for FTB essential commands (non admin players will create a sleeping player and cant cheat the system by bringing items)
- Spirit world support for Kindered Spirits (disallow them there)

### Changes
- Regular players generate blood if drained (vampire stuff).

### Fixes
- Missing Lich level 8 quest description (Forbidden magic)
- Soul form ability from potion now gets prioritised on ability hotbar.(Forbidden magic)
- Phylactery deaths recored on Lich level 9 (Forbidden magic)

## 0.5.17

### Additions

### Changes
- Vamp armor grants extra sun resiost instead of fire protection
- Curse removal becomes easier after each attempt
- Simple handler for players who are both Lich and Vampires (Forbidden magic)
- Phylacteries dont need skylight in dimesnions without a sky (level 9+) (Forbidden magic)

### Fixes
- Cage drop extra when area mining tool is used
- Curse removal didnt care about witch level

## 0.5.16

### Additions
- Easy villagers compat for Cages
- Added drawing of a sacrificial circle for observations of an immortal
- Added ability to give cages villagers vamp blood through the cage

### Changes
- Well to spawn better

### Fixes
- Fixed Creation of Blood stained Wool from needing taglock to bone needle
- Fixed Vampire child hunt crash
- Fixed Death armor on mobs crash
- Fixed Vampire blood aquireable for only bottles, not wineglass.

## 0.5.15

### Additions
- Added missing blood values for vanilla mobs
- Added ice and fire blood values
- Brew of love adds loyalty in cauldron infusion

### Changes
- Players can use the Deatn Sickle throw attack

### Fixes
- Fixed huntsman spear and death sickle damage
- Fixed crash on ore vision from High Priestess Tarot
- Fixed vampires hurt from "sun" in The End, and other similar cases
- Fixed Ethereal Servants attacking owner (forbidden magic)
- Fixed Wispy cotton and distrubed drops nothing in overworld
- Vampires kill from blood drasin counts as player kill
- Sunlight collector recipe page in book error
- Seeds in the proper loottable injection i think

## 0.5.14

### Additions
- Added Torn page trade to fortune teller max level
### Changes
- Revert village structures only spawning in walled villages due to compat issues.
- Lithostitched support for structure injects

### Fixes
- Assembled altar drop blocks

## 0.5.13

### Additions
- Added Dispenser behaviour for witchery brews and potions
- Added missing Garlic loot table
- Added config for vampire immortality
- Added config for vampire sun damage protection in dimensions
- Added Sacrifice ritual support entity tags and either or entities.
- Added support for clear vampirism and lycantropy for remove curse ritual.

### Changes
- Tweak village structure spawn
- Made level 2 -> 3 vamp quest text more clear

### Fixes
- Tweaked poppets to hopefully fix poppet disconnect
- Fixed Arthana dissapearing on world reload
- Fixed Owl
- Fixed missing lang for advancements
- Fixed baby animals not having a blood pool
- Fixed vampire food to support tag
- Fixed kick when going to spirit world sometimes

## 0.5.12

### Additions
- NeoVitae compat: Added empowered bloodstone pendant allowing replenishing one's blood from Anima
- Icy slippers
- More book entries
- Blacklist config for [Mutandis](Items/Resources/Mutandis.md)

### Changes

### Fixes
- empowered sunstone pendant is now visible in JEI
- Fixed server crash with forbidden magic related to creative tab banners
- Some book entries are advancement gated (26.1.2)
- Werewolf book entry trigger

## 0.5.11

### Additions
- Some villages will have Walls and Watchtowers
- Garlic now damages vampires

### Changes
- NeoVitae integration reworked: vampires drink blood from orb and altar now, not from Anima directly

### Fixes
- Fixed quest system only showing up in singleplayer
- Fixed Vampire bat flying thorugh village quest to be more generous with area
- Sacrifical circle can now be assembled with the skull last
- Sacrifical circle needs solid ground under it
- Wine glass acting weird in off-hand
- Skull renders correctly in sacrifical circle (1.21.1)
- abilities should now all be visible on smaller screens

-----
## 0.5.10

### Additions
- Appleskin support for Vampire, hides overlay
- Compatibiltiy with NeoVitae, vampires can feed off Anima network when holding a blood orb and using drink ability

### Changes
- Set default config for enable empowered charms to false.
- Made Vamp not able to gain fire resistance
- Increased Bone Needle self stab damage from 2 to 4
- Running out of blood causes Vampires to become weak
- Sun damage doesn't affect vampires during rain or thunder
- Regular food causes Vampires to get nausea and hunger

### Fixes
- Fixed vampire immortality to not block everything.
- Fixed Vampires blood drink ability not killing entities with 0 blood.
- Fixed render box for Cage.
- Fixed Blood particle height for sleeping villagers.
- Fixed Voodoo poppet unable to get stabbed by bone needle
- Fixed Bone needle use durability
- Fixed Bone needle crafting durability
- Fixed vampire drink blood ability hurting transfixed villagers
- Fixed cage not dropping its item when top block was broken
