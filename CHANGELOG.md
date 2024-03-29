# Changelog

v0.4 - 03/18/2024

- Restored more vanilla behavior for medical items and food. Changes:
  - Using medical items no longer penalizes stamina.
  - Food no longer restores stamina.
- Made red hit marks invisible on HUD from mutants and NPCs (optional feature).
- Fixed the low poly hand mesh and weapon model for TOZ-34.

v0.3 - 03/11/2024

- Disabled including stash's level abbreviation.
  - It was enabled again by mistake during the implementation of the InGameCC mod mini-update.
- Improved inventory icon for medical supplies to look more like COP (from PRP).
- Fixed medkit revive functionality for downed NPCs.
  - Resolved an issue where medkits occasionally failed to revive downed NPCs.
  - This bug primarily affected non-critical gameplay but is now fixed.

v0.2 - 03/09/2024

- Restored crouch/walk/run/sprint indicator on HUD.
- Added an optional, alternative HUD that:
  - Removes the crouch/walk/run/sprint indicator.
  - Moves the sound/endurance/visibility indicators further to the right side to look more like CS/COP.
- Disabled outfit information with personal tweaks by default.
- Added outfit information as an optional feature.
- Updated InGameCC mod mini-update for ZRP v1.07 R5RC to v0.3.

v0.1 - 03/02/2024

- Enabled automatic ammo boxing.
- Disabled per-level autosaves and using rename instead of copy.
- Enabled ZRP flashlight beam.
- Enabled reduced head bobbing.
- Enabled skipping the starting tutorial tips.
- Enabled including night music.
- Enabled quieting the starting nightvision sound and the ending nightvision sound.
- Disabled time limit for quests.
- Disabled repeatable quests.
- Enabled allowing Screw and Ivantsov to repair weapons and armor.
- Disabled including stash's level abbreviation.
- Disabled displaying clock on HUD.
- Enabled real gun names and fixed some text files related to it.
- Enabled treating zombified like normal enemies.
- Increased camera_height_factor to 0.92 (match CS/COP).
- Reduced max_item_mass (weight limit before fatigue) from 50kg to 30kg.
- Reduced max_walk_weight (maximum weight for movement) from 60kg to 50kg.
- Enabled installing xStream's grenadier.
- Enabled installing live stalker ranking support.
- Enabled the NPC ability to turn off flashlights.
- Enabled rain sound fix when changing levels.
- Enabled stopping disk I/O icon from flashing at the lower right corner of the HUD.
- Disabled Esc T TZIO chapter selection.
- Disabled Esc J level jump.
- Disabled free play at end.
- Enabled no enemy minimap spots.
- Muted NPC detection sounds on PDA.
- Hidden NPC counter number on HUD.
- Removed the empty hand cursor.
- Hidden artefact belt on HUD
- Hidden ammo counter on HUD.
- Hidden distance task counter on HUD.
- Made crosshair smaller.
- Removed some elements on minimap and HUD:
  - Minimap:
    - Direction of current objective.
    - Red hit shoot mark.
  - HUD:
    - NPC counter indicator.
    - Crouch/walk/run/sprint indicator.
- Disabled tagging NPCs through the binoculars.
- Disabled sound notification of detected NPCs through the binoculars.
- Removed nightvision from suits with closed-cycle breathing system as in COP.
- Enabled Strelok will keep his helmet on.
- Updated inventory icon to exoskeleton (icon from COP).
- Fixed the scope (and binocular) views when running the game in 16:9 resolutions.
- Fixed global map and some detailed maps on PDA.
- Enabled helicopters at CNPP no longer use rockets.
- Implemented adapted-updated InGameCC mod for ZRP 1.07 R5 RC.
- Disabled CC of sound effects in-game by default.
- Implemented Medicine Mod for ZRP compatibility and addressed audio issues:
  - Adapted Medicine Mod for seamless integration with ZRP.
  - Fixed minor audio inconsistencies related to consumable items.
  - Added long usage and sound effects for all consumable items.
- Enabled no intro movies.
- Added NatVac's sound fixes:
  - Addressed the clicks and pops in the following sounds:
    - sounds\device\metal_small_open.ogg
    - sounds\monsters\boar\boar_death_2.ogg
    - sounds\monsters\dog\hit_0.ogg
  - Removed the repeating portion of Ghost's PDA recording (only English):
    - sounds\characters_voice\scenario\yantar\ghost_pda.ogg
- Added new anomaly Post-processing-effectors (from CS).
- Revised Weapon Placement:
  - Overhauled weapon HUD placement for all vanilla weapons.
  - Adjusted iron sights, shell ejections, and fire points for improved visual consistency.
- Partially implemented "Vanilla Weapons Adjusted" mod:
  - Fixed low-poly mesh issue with SPAS-12 hand model.
  - Corrected shotgun shell ejection animation to prevent unrealistic visual effect.
  - Adjusted Groza mesh to improve visual consistency with grenade placement.
  - Addressed missing or bugged sound effects for various weapons.
  - Implemented animation changes for specific weapons.
  - Enabled sprinting with SVD, SVU, Gauss Rifle, and RG-6.
- Tweaked stalker_neytral_hood_9.ogf model:
  - Replaced gas mask with a variant featuring disjointed lenses.
  - Updated oxygen tank visuals for use without mask, converting it to a backpack.
- Enabled outfit information with personal tweaks.
- Added nightvision visual effects from CS to SOC.
- Stretched static_weapon tag in maingame_16.xml for visual consistency with vanilla.
- Set new time for NPCs and monsters to disappear (vanilla default - 36 hours).
- Added vanilla weapon textures from COP to SOC (optional feature).
- Improved inventory icon for RPG-7 (from SRP).
- Increased fire_distance (knife reach) to 1.6 as in CS.
