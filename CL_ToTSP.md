## 2.2.2 - Indev
### Worldspace Changes
- Updated TOTSP to Tamriel Data 8.
- Added deer and female moose to Solstheim level-lists via the TD Content Integration esps. Spiders have been removed.
- In the Hirstaang Forest, dozens of trees have been resized to add greater growth-variety to the forest. 
- More vertex painting and floating/clipping static fixes, as usually.
- Bees and wild beehives have been added to the Hirstaang Forest and Isinfier Plains regions.





## 2.2.1
### Worldspace Changes
- Fixed Voiced INFO entries pointing to the wrong cells.

## 2.2.0
### Worldspace Changes
- Changed internal ID convention.
- Sados Relothan, who was set up as an Imperial, changed to a Dunmer. Level changed from 40 to 4.
- Doors renamed: Wooded Gate -> Wooden Gate.
- Removed an unused, broken static.
- Fixed various typos in dialogue entries for topic "booze".
- Added Leradr Barrow, which replaces Heirdun Barrow, due to permissions issues.
- Removed a duplicate snow prince cuirass from Jolgier Barrow in the Snow Prince Armor Redux.esp.
- Removed a duplicate Sigvatr the Strong.
- Fixed floating Torches in Raven Rock.
- Resolved rogue Doormarker in -22,17.
- Fix caspering t_mw_terrrockvm_cliffsnow_02: -12, 28: -93178.7 233436 2315.99.
- Fix capering colony door: -18, 25: -141910 207956 1643.33. 
- Udyfrykte Lair had a non-unique static blocking it, preventing its later removement; replaced it with a new unique static (just to make sure) and adjust the scripts.
- Fixed the quest Race Against the Clock: Carnius Magius had been misplaced in the water, and needed repositioning.
- Fixed the quest The Skaal Test of Wisdom: Halfhand sometimes did not enter the wolf-enclosure.
- Hid unintentionally-visible script-component-ring on the Skaal wolf enclosure gatepost.
- Fixed the quest The Ristaag: NPC movement has been corrected and the quest progresses normally.
- Fixed incorrect location pointers in The Skaal Test of Strength and The Ritual of Trees.

### Package Changes:
- Removed "VSW" from file names. 
- Removed PfP v3.2 compatbility patch.
- Added PfP v4 compatbility patch.
- Added a Forceful Travel NPC Override patch, load this after any other mod that affects them.

## 2.1.X
### Worldspace Changes:
- Fixed even more mildy-misplaced objects.
- Added red and grey squirrels to BM's level list, via the VSW_Solstheim_Creature_Expansion.esp.
- Fixed a floating pillar at Gandrung Caverns, exterior.
- Added names to the Skaal wooden gates, so they no longer display their ID.
- Increased the amount bm_horker_h20 creatre spawns for add more waterlife.
- Fixed the terrestrial bird level list, which should have contained crows and eagles, but mistakenly contained only seagulls
- Increased the amount of inland bird level lists (crows and eagles).
- Added a goat pens to Skaal Village.
- Removed the rocksrocks and snow along the path to Bloodskaal Barrow which were making it inaccessible. 
- Fixed a floating food hut in Skaal Village
- Added some extra Tamriel Data items to the worldspace, like Nordic Silver and Huntsmans bows, and Harpoons. 

### Graphical Changes:
- Scaled down a few previously-missed HD textures (mostly creatures) in the core repository, in order to match vanilla resolution (HD versions are provided by the graphical replacer package).
- Fixed flickering on 'wl_ex_statue_hircine', the Hircine statue.
- Resolved an archaic alpha-flag on the Flora_BM_shrub_0X models.

### Package Changes:
- Moved Remiros' grass sub-package to the graphical TOTSP download.
- Add squirrels to the creature expansion package, expanded that package beyond just creatures; adding new items, weapons and ingredients to Solstheim level lists and containers, for a more cohesive integration with Tamriel Data and the Province mods. Ie: Solstheim boars and horker now drop meat, like those of SHOTN.
- A complete list of changes in the item expanion plugin can be found [here](https://docs.google.com/spreadsheets/d/1GRg0S60BoNaGF-rznfpnUNXUKE1rUCDE-LA5nOxXx-A/edit?usp=sharing).
Removed the creature expansion sub-package. Move the new item expansion .esp into the main mod sub-folder.
- Add several more compatibility patches.
 
## 2.0.X - Anthology Release and Package Split
### Worldspace Changes:
- Moved Solstheim 7 cells north and 6 cells east.
- Added dependency to Tamriel_Data v7.
- Replaced all VSW meshes with internal T_D data versions.
- Removed superflours rocks from around Fort Frostmoth.
- Fixed dozens of floaters and bleeders - particularly those that became present if the user was using vanilla trees and rocks.
- Removed an interior-less barrow entrance from -16,29.
- Lowered terrain beneath Raven Rock ship to stop clipping, simultaneously raised it for the peer.
- Added lighthouse and storage tower to Fort Frostmoth.
- Replaced the teleporting Skaal fortification gate with gates that rotate open when activated.
- Replaced some creature level list spawns with more regionally appropriate level lists (-15,30),(-15,31),(-14,31).
- Restored a missing BM_bear_snow_unique to -17,22 and -19,25.
- Added Draugr spawns outside some barrows.
- Replaced random creature spawns in front of the Water Stone with Draugr.
- Removed Riekling patrol from the cave beneath the Altar of Thrond.
- Fixed massive Riekling patrol sunk beneath Castle Karstaag.
- Removed Riekling patrol from -11,28 (too close to a wolf pack).
- Fixed Riekling patrol sunk in -17,29 (across the bridge from Hvitkald Peak).
- Relocated a nearby wolf pack to be in front of the Connorflenge Barrow.
- Placed Seagull level list spawns and seagull nests along the coast.
- Added crow and eagle level lists, and robin, tomtits, goldfinch level lists throughout Solstheim.
- Added bats to some exterior caves.
- Added raw iron and silver containers throughout the north.
- Added Elf Cup, Greenstain, Stinkhorn, Fly Amanita, Milkthistle, Foxglove and Blackberry to the south of Solstheim.
- Added a spider-zone south of Raven Rock.
- Painted vertex shading under statics.
- Raised some terrain under the dock platform to hide a blue pixel on the map -15,23
- Fixed numerous seams.
- Added T_Glb_Sound_Water_01 to the ponds -16,23, -13,26.
- Added rocks so you can't go under the waterfall -16,23.
- Added an entirely new barrow by Corsair, called Heidrun barrow. It contains a unique sword by Remiros.
- Fixed Valbrandr Barrow's broken exit marker's placement.

### Graphical Changes:
- Fixed missing wl_wtx_metal_trim_01 on wl_in_skaal_firep; missing stump texture on wl_ex_skaal_f_l_01.
- The MWScript Raven Rock Windows Glow package has been disbanded: MWScript functionality was replaced with MWSE-Lua, and the RR windows have been moved from VSW add integrated directly into the Glow in the Dahrk mod.
- Removed MET derived textures, and various others: Remiro's HD textures are the new recommended base.
- Added and resized (to 1024x) lots of ground textures to remove Vanilla Land as a prerequisite.
- Resized dozens of textures to appropriate sizes for improved performance.
- Made BM-MOP-trees the default ToTSP trees, the skyrim-like trees are now optional.
- Improved tree leaf geometry for ingame lighting.
- Decreased the brightness and contrast on some dirt textures, as requested.
- Provided vanilla resolution textures for all new VSW assets, to be more cohesive with the vanilla game. Included HD replacers of these custom assets within the graphical replacers.

### Package Changes:
- Split the Solstheim sub-packages from the main VSW package, which will be the archive method for all future releases. Split the landmass overhaul and graphical replacer into separate packages.
- Added the Missing Snow Prince Armor mod.
- Added the Fierce Wolf Helms replacer.
- Added an optional hide-like animal pelts replacer.
- Added the Armor of the Snow Prince Redux (BB) mod to the VSW package, to replace the Steel Snow Prince Armor.
- Added a new sub-package containing an esp that adds more, mostly passive creatures to Solsthiem
- Split the graphical sub-packages and content sub-packages into separate downloads. 
- Added a patch for Pfp.

## 1.0.3
### Worldspace Changes:
- Lowered a floating tree in Raven Rock.
- Fixed pathgrids for Fort Frostmoth, Raven Rock, Skaal Village and Thirsk.

### Graphical Changes:
- Fixed numerous UV and texture issues present on the Raven Rock and Skaal tilesets; applied MOP improvements to the models.

## 1.0.2
### Worldspace Changes:
- Resolved several instances of rocks caspering.
- Resolved missing lighting/fog settings for Skaal Village, The Blodskaal's House interior.
- Resolved issue where-in Rolf Long-Tooth had been slightly repositioned into the neighbouring cell, causing a missing NPC error after cleaning a save with Wrye Mash.
- Cleaned dirty references pertaining to the Ministry of Truth, Prison Keep.
- Deleted Numerous unused NPCs/Interiors created for the previous STOTSP mod.
### Package Changes:
- Packaged missing Raven Rock colony fireplaces.

## 1.0.1
### Graphical Changes:
- Added missing MIP maps to dozens of textures, and removed unnecessary alpha channels from others.
- Fixed missing texture path for ingred_comberry_01.nif (again...?)
- Fixed numerous clipping/caspering issues that occurred on Solstheim when the Solstheim components of the graphical package were not installed.
- Resolved a couple of BM cliff models using tx_bm_rock_01.dds instead of 02.

## 1.0.0 Release
- released!

