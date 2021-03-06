---
title: "Changelog"
weight: 3
type: docs
description: >
  For all versions since the Github release (3.2 and later).
---

## Release 4.1

> 10/02/2021

As it turns out, the Timing Is Everything preset feature is broken. I hadn't previously noticed it as I didn't check *all* the pages and on the "Extras" page everything seemed to work well. Umgak fixed that in scripts packaged with the CRP. The preset itself was updated for even better synergy with other mods in TPF, ensuring quests will not be available before you are capable of beating them. Details can be found on the new [Quests](/skyrim-se/gameplay-guide/quests) page in the Gameplay Guide.

While working on the Quests segment of the Gameplay Guide, I noticed that it was rather inconsistent to use Andrealphus' Dawnguard DLC integration option for the Stones of Barenziah (No Stones Unturned) but not the Dragonborn DLC one. So I fixed that.

#### Mod Installation

- **Landscape:** Changed Blended Roads instructions to simply use the Medieval Bridges optional file.
- **Food & Ingredients:** Removed Unique Stros M'Kai Rum (encountered a CTD in connection with it that needs further investigating).
- **Apparel & Weapons:** Added instructions to install the new hotfix for LeanWolf's Better-Shaped Weapons.
- **Improved Vanilla Quests:** Added Buyable Golden Claw.
- **Improved Vanilla Quests:** Added instructions to download Andrealphus' Gameplay Tweaks - Stones of Barenziah - Solstheim.
- **College of Winterhold:** Added instructions to select the Viewable Faction ranks patch in the Obscure's COW FOMOD.
- **Miscellaneous:** Added Viewable Faction Ranks.

#### Mod Configuration

- Rephrased instructions for Timing Is Everything so applying the preset no longer feels optional.

#### Gameplay Guide

- **Quests:** Added a new page to cover changes to quests, level requirements, etc.

#### Conflict Resolution Patch

- **4.0.1:** Updated for Adamant 4.2.7
- **4.0.1:** Fixed the preset functionality in tie_mcmscript.pex
- **4.1:** Reverted amount of pamphlets to be distributed in the Spread the Love quest to vanilla (30 > 20)
- **4.1:** Increased buy price for the Golden Claw from 500 to 5000 Septims

#### Wabbajack Installer

- Updated Adamant - A Perk Overhaul to 4.2.7
- Updated Aetherius - A Race Overhaul to 2.4.0
- Updated Mundus - A Standing Stone Overhaul to 1.4.0
- Updated Timing Is Everything - TPF Preset to 1.1
- Updated Conflict Resolution Patch

## Release 4.0 Final

> 09/02/2021

After a rather long Beta phase and rather more substantial updates than I had planned to do, we have finally arrived at a point where I consider 4.0 polished enough for a full release.

#### Initial Setup

- **INI Files:** Added note to ignore Skyrim not recognising newer AMD cards.
- **INI Files:** Increased values in View Distance tab (attempt to fix fade-in of lanterns).

#### Mod Installation

- **Essential Mods:** Replaced the buggy Autorun Console Commands with Umgak's remade Autorun.
- **Landscape:** Added Blended Roads (version packaged with Cath Landscapes is outdated).
- **Landscape:** Added instructions to remove a file from Northside to fix moss tiling.
- **Landscape:** Removed Ashbound (redundant with the latest versions of Better Dynamic Ash).
- **Interiors:** Added Ennead Banners - RUGNAROK Patch.
- **Dungeons:** Re-added ENB Particle Lights - Dwemer Lanterns - Ancient Dwemer Metal Patch.
- **Dungeons:** Re-added Rudy HQ - Bthardamz - Dwemer Ichor Barrel Patch.
- **Food & Ingredients:** Added Unique Stros M'Kai Rum.
- **Non-Player Character:** Removed Simple Offence Suppression MCM - Block Friendly Fire.
- **Improved Vanilla Quests:** Added Radiant Requirements MCM.
- **Improved Vanilla Quests:** Added Radiant Requirements MCM - TPF Preset.
- **College of Winterhold:** Added note to Misc College of Winterhold to activate previous mods before the FOMOD.
- **Balancing:** Added missing download instructions for Faster Mining Plus.
- **Balancing:** Updated instructions for amidianBorn Armor Variants Lite.
- **Miscellaneous:** Added Horses for Followers.
- **Sounds & Music:** Fixed link for Phoenix - Merged Music Patch.

#### Finalisation

- **First Launch:** Slightly rewrote the last bit to not make it seem as if you were done with the guide at this point.

#### Wabbajack

- Added instructions to re-enable VSYNC for those who need it.

#### Mod Configuration

- Added note about the carriage ride and a potential glitch.

#### Gameplay Guide

- Added section about Radiant Requirements.

#### Appendix

- **Troubleshooting:** Rewrote section on grass shadows or lack thereof.
- **Troubleshooting:** Added fix for black waterfalls.

#### Conflict Resolution Patch 

- Removed Ashbound as a master.
- Cleaned unnecessary edits from cell and worldspace records.
- Resolved conflicts for Radiant Requirements MCM.
- Removed fix for conflicts between Finding Velehk Sain and aMidianBorn Armor Variants Lite (included in AVL's FOMOD).
- Added Dargor's Rock to cover up a hole near the Tomb of Ysgramor.
- Added a replacement mesh for the Skyforge HD LOD to fix it clipping outside of the city walls.

#### Wabbajack Installer

- Updated ENBSeries (no file version change)
- Updated Skyrim Landscape and Water Fixes to 5.9
- Updated moreHUD to 4.0.0.5Beta
- Updated DynDOLOD to 2.91
- Updated Cathedral - 3D Mountain Flowers to 1.8
- Updated Cathedral Player and NPC Overhaul to 4.3
- Updated Mysticism - A Magic Overhaul to 1.1.5
- Updated Adamant - A Perk Overhaul to 4.2.5
- Updated Adamant - Shrines and Amulets to 4.2.5
- Updated Blade & Blunt - A Combat Overhaul to 1.2.0
- Updated Arena - An Encounter Zone Overhaul to 1.1.0
- Updated Misc Tweaks - Shrines Don't Cure Diseases to 1.6
- Updated AllGUD Conditions Fix to 1.1
- Updated xLODGen to Beta 71
- Regenerated AllGUD for aMidianBorn Armor Variants Lite 1.0.1
- Regenerated TexGen, DynDOLOD, and Occlusion

## Release 4.0 Beta 7

> 29/01/2021

With the removal of Fuz Ro D'oh and new instructions for Keyboard Shortcuts Fix, the Clean-up page has essentially become redundant and was removed.

**Beta Testers:** To update to Beta 7, delete Fuz Ro D'oh in Mod Organizer 2 (Utilities separator). Then download the new Alchemy Adjustments - TPF tweaks mod, install it, update the CRP, download the new loadorder.txt and apply it. Done!

#### Mod Installation

- **Fixes:** Added instructions for Keyboard Shortcuts Fix to create its LOG file manually.
- **Trees & Plants:** Fixed missing picture for EL Solstheim 3D Trees.
- **Balancing:** Properly added Alchemy Adjustments - TPF Tweaks.
- **Utilities:** Removed Fuz Ro D'oh (no longer necessary now that AS LAL was removed).

#### Finalisation

- **Wrapping Up:** Expanded the Check for MO2 Warnings section.
- **Final Steps:** Slightly restructured the page and added the A New Playthrough section.
- **Clean-up:** Removed this page which has become redundant.

#### Appendix

- **Troubleshooting:** Marked one listed issue as resolved due to the removal of Fuz Ro D'oh.

## Release 4.0 Beta 6

> 29/01/2021

With this update, **Alternate Start - Live Another Life** (aka AS LAL), got the boot. Gonna be honest here, I've been meaning to remove that mod for a long, long time. Unfortunately, there never was a simple alternative to it that just puts you in a quiet place to go through MCM settings and character creation before the vanilla start. And, spoiler alert, there still isn't.

However, I discovered that the vanilla start - once a buggy mess in modded games - works perfectly fine in TPF. This is due to the fact that most mods no longer instantly fire all their scripts as soon as you start the game and we have very mods that run many scripts anyway. The overall stability of SSE and the decoupling of framerate and physics are helping here as well.

Without AS LAL, everyone is forced to go through the vanilla intro which makes balancing far easier for us. There is simply no way we can balance every single one of AS LAL's starting points so that it's a fair start for a new playthrough. I always recommended the vanilla start anyway. Additionally, AS LAL touches so many parts of Skyrim that it's essentially patching hell. Now we are rid of that, too.

The downside is that there is no quiet mod configuration spot before you are thrown into the game anymore. You will probably have to take a breather after escaping Helgen or later in Riverwood for the MCM stuff. I miss the convenience of the AS LAL cell but it's a small part of the mod and doesn't justify keeping the rest.

**Website structure:** As you may have noticed, I moved around some pages and added a new (WIP) Wabbajack page. The purpose of this is to have a clear distinction of guide sections for manual and for WJ users.

#### Introduction

- Temporarily removed link to mod spreadsheet (very outdated, will get to it).
- Added link to the new [playlist](https://www.youtube.com/playlist?list=PLj_QypS-aCNNyUBLpYsFAeCJk1Zq0xnmV) with music tracks added by mods in TPF.
- Expanded the Wabbajack section and added a FLOWCHART to make it obvious which sections WJ users need to follow.

#### Initial Setup

- **Mod Organizer 2:** Rewrote the Separator section to have DIY instructions (users make their own separators).
- **ESM Cleaning:** Actually fixed Dawnguard manual cleaning instructions (could have sworn I already did this).
- **ESM Cleaning:** Added note to uncheck SSEEdit Backups so that they don't clutter up your Overwrite.

*For Beta Testers: Re-cleaning Dawnguard.esm is not necessary. The problem was that I had custom Filter profiles that I thought were default. Users didn't have them though, so I had to rewrite the instructions without using a filter.*

#### Mod Installation

- **Instructions:** Added paragraph on creating new separators for each new page in the mod installation section.
- **Essential Mods:** Removed Alternate Start - Live Another Life (praise the Nine).
- **Fixes:** Updated FOMOD instructions for Landscape Fixes for Grass Mods (no longer selecting the AS LAL patch).
- **Tweaks:** Removed Multiple Floors Sandboxing (added to ACC).
- **Graphics Baseline:** Fixed file names in additional instructions for aMidianBorn Book of Silence.
- **Graphics Baseline:** Added instructions to delete the scripts folder from aMidianBorn Book of Silence.
- **Landscape:** Updated FOMOD instructions for Rorikstead Basalt Cliffs Patches (no longer installing the AS LAL patch).
- **Dungeons:** Added instructions to Underground to fix the shiny mud in Helgen.
- **Apparel & Weapons:** Fixed download instructions for Sunhallowed and Bloodcursed Arrows (Optional Files > Main Files).
- **Miscellaneous:** Removed Bounty Previews (late note from Beta 1, will be re-added very soon).

#### Finalisation

- **Wrapping Up:** Added instructions to create a new separator before installing the CRP.
- **Wrapping Up:** Removed sandboxcylinderheight.esp from list of plugins to ESL-ify (added to ACC).
- **Nemesis:** Added instructions to add a PATCHER OUTPUT separator.
- **DynDOLOD:** Added instructions to click "Advanced" in the window that comes up when *not* generating 3D tree LOD.
- **Occlusion:** Improved instructions for generating Occlusion (minor rephrasing).
- **First Launch:** Updated for the removal of Alternate Start.
- **Clean-Up:** Moved instructions to check MO2 for errors here.

#### New Game

- This section was completely removed.
- Most of the FINAL STEPS page was redundant except for the MO2 error check which was moved to Clean-up instead.
- The MOD CONFIGURATION page is now a top-level page.
- The GAMEPLAY GUIDE page is now a top-level page.

#### Wabbajack

- Added this new top-level page with instructions for the Wabbajack version of TPF.

#### Mod Configuration

- **Mod Configuration:** This is now a top-level page.
- **Mod Configuration:** Temporarily removed the (fairly pointless) instructions for GIST. Will add proper ones in the future.

#### Gameplay Guide

- **Gameplay Guide:** This is now a top-level page.
- **Gameplay Guide:** Added a far too detailed section about the music mods added in TPF.

## Release 4.0 Beta 5

> 26/01/2021

As you may have noticed, the **ENBSeries** section has vanished from the sidebar. What happened? It was reintegrated. Everything from those pages was moved back into the main body of the guide with ENBMan, binaries, and preset installation being a step in the Finalisation. This was done in order to further streamline the guide and eliminate optional paths and variations.

Also removed was **Nether's Follower Framework** after some internal discussions. Overtime, NFF has grown from a lightweight follower overhaul to an excessively bloated mod doing all kinds of things. While it remains high quality, the vast majority of features are misplaced in a v+ setup. Additionally, combat is easier for us to balance knowing that players are limited to a single follower like in vanilla. Some features of NFF were replaced by other mods.

**New save required** once again because of the removal of NFF. Sorry. =(

#### Introduction

- Updated more outdated parts of the introduction page.

#### Initial Setup

- **INI Files:** Reintegrated ENB-related tweaks (disabling AO, increasing particle count).

#### Mod Installation

- **Tweaks:** Added Followers Don't Draw Weapons.
- **Tweaks:** Added Multiple Floors Sandboxing.
- **Interface:** Fixed file name in download instructions for Fix Note Icon for SkyUI.
- **Graphics Baseline:** Updated AMB instructions (Content Addon version not needed with AVL).
- **Gameplay Overhauls:** Fixed file name in download instructions for Skyrim Uncapper - Adamant Arena.
- **Non-Player Characters:** Added Simple Offence Suppression.
- **Non-Player Characters:** Added Simple Offence Suppression MCM - Block Friendly Fire.
- **Non-Player Characters:** Removed Nether's Follower Framework.
- **Non-Player Characters:** Removed NFF - Disable Craftables.
- **College of Winterhold:** Added note to Obscure's College FOMOD instructions to specifically disable the HMB patch.
- **Combat & Encounters:** Added Better Stealth AI for Followers.
- **Combat & Encounters:** Added Follower Trap Safety.
- **Combat & Encounters:** Added instructions to download the Follower Trap Safety Patch for Improved Traps.
- **Combat & Encounters:** Removed Improved Traps - Nether's Follower Framework Bear Trap Fix.
- **Miscellaneous:** Removed additional instructions from Saddlebags that would remove its Horse Call power.
- **Utilities:** Added Spell Perk Item Distributor.
- **Utilities:** Removed UIExtensions (was only installed for NFF).

#### Finalisation

- **Wrapping Up:** Added Followers Don't Draw Weapons.esp to the list of plugins to ESL-ify.
- **Wrapping Up:** Added sandboxcylinderheight.esp (Multiple Floors Sandboxing) to the list of plugins to ESL-ify.
- **DynDOLOD:** Added skippable instructions on how to remove DynDOLOD's meme loading screens.
- **ENBSeries:** Added this new page which includes many instructions from the now removed ENBSeries section.
- **ENBSeries:** Serio's ENB is now once again the default ENB preset for TPF due to its performance-friendly nature.
- **ENBSeries:** Added instructions on how to customise ENB screenshots in the global enblocal.ini file.

#### New Game

- **Mod Configuration:** Removed instructions for Nether's Follower Framework.
- **Mod Configuration:** Removed instructions for Growl - Werebeasts of Skyrim.
- **ENB Tweaks:** Removed this page as we are now using an already tweaked version of Serio's ENB.
- **Gameplay Guide:** Removed mention of Nether's Follower Framework.

#### Conflict Resolution Patch

- Removed playable flag from Hvergelmir's beards added to Cathedral NPCs (they have transparency issues).
- Removed playable flag from extra hair styles added by Aetherial Crown.

## Release 4.0 Beta 4

> 24/01/2021

Simon's werewolf overhaul is finally out now and replaced Growl which completes our suite of SimonRim mods for gameplay. Because of this and the update Scion received, a new save is required for Beta 4.

I also did some reshuffling. Again. It's better if I do it now before 4.0 is officially out.

#### Initial Setup

- **Skyrim and Steam:** Updated Game Language screenshot for the new Steam UI.
- **Skyrim and Steam:** Updated Disable Auto Updates screenshot for the new Steam UI.

#### Mod Installation

- **Gameplay Overhauls:** Removed Growl - Werebeasts of Skyrim.
- **Gameplay Overhauls:** Added Manbeast - A Werewolf Overhaul.
- **Gameplay Overhauls:** Added Simple Werewolf Favourite Howls Menu.
- **Improved Vanilla Quests:** Added The Companions - Don't Be A Milk Drinker.
- **Balancing:** Renamed "Crafting & New Gear" AGAIN. Yeah. Back to the old name.
- **Tweak Collections:** Added Misc Tweaks - More Expensive Player Homes.
- **Skeleton & Animations:** Fixed file name in download instructions for Immersive Dragons.
- **Skeleton & Animations:** Fixed file name in download instructions for Werewolf Claws Affect Spider Webs.
- **Tweak Collections:** Removed this section because it was dumb.
- **Tweak Collections:** Removed Morrowloot Miscellania - Dremora Bound Weapons.
- **Tweak Collections:** Moved Morrowloot Miscellania - Unleveled Uniques to Balancing.
- **Tweak Collections:** Moved Miscellaneous Tweaks Collection to Gameplay.
- **Tweak Collections:** Moved Andealphus' Gameplay Tweaks to Improved Vanilla Quests (as they all affect quests).
- **Tweak Collection:** Moved Assorted Tiny Tweaks to Tweaks.
- **Sounds & Music:** Added Around the Fire - Skyrim Fan-Made Music.

#### New Game

- **Mod Configuration:** Removed left-over MCM instructions for Diverse Dragons Collection.
- **Gameplay Guide:** Finally started working on this page.

#### Conflict Resolution Patch

- Removed the Draught of Fate Unwound from other leveled lists, now only available in Riften.
- Lowered amount of available Draughts of Fate Unwound in Elgrim's Inventory to 1.
- Tripled value of the Draught of Fate Unwound.
- Removed records and edits related to Growl - Werebeasts of Skyrim.
- Removed two meshes (related to removed mods, EEO and Growl).
- Fixed a conflict between Manbeast and Mortal Enemies.

## Release 4.0 Beta 3

> 24/01/2021

#### Introduction

- Fixed an oversight in the "Included Mods" list.

#### Mod Installation

- **Tweaks:** Removed xEdit tweak for Simply Smaller Wolves (moved to the CRP).
- **Interface:** Added Extended UI for Skyrim Uncapper.
- **Trees & Plants:** Fixed file name in download instructions for Enhanced Landscapes - Solstheim 3D Trees.
- **Creatures:** Added HD Werewolves.
- **Appearance:** Added instructions to Cathedral NPCs to delete one conflicting file.
- **Gameplay Overhauls:** Added note to Reliquary of Myth to explain why certain patches shouldn't be installed.
- **Non-Player Characters:** Added NFF - Disable Craftables.
- **Improved Vanilla Quests:** Added Timing Is Everything - Custom Preset (finally!).
- **Improved Vanilla Quests:** Fixed file name in download instructions for A Lovely Letter - Alternate Routes.
- **Combat & Encounters:** No longer merging optional and main file from No Road Predators Redone.
- **Combat & Encounters:** Removed Diverse Dragons Collection (most of the dragons are out of place in V+).
- **Combat & Encounters:** Removed Diverse Werewolves Collection.
- **Combat & Encounters:** Updated More Werewolves FOMOD instructions.
- **Miscellaneous:** Removed obsolete reference to a mod being optional from Shadowmarks.
- **Assorted Plugins:** Fixed file name in download instructions for Classic Sprinting Redone.
- **Sounds & Music:** Fixed formatting for Phoenix - Merged Music Patch.
- **Skeleton & Animations:** Fixed incomplete file path for downloads folder.

#### Finalisation

- **Cleanup:** Removed note referring to the possibility of having skipped a mod (which no longer exists).
- **Cleanup:** Removed leftover instructions for Simply Knock (which was removed).
- **Cleanup:** Removed one paragraph referring to the long removed Customisation section (the cake is a lie).

#### New Game

- **Mod Configuration:** Added instructions for Timing Is Everything (loading the custom preset).
- **Mod Configuration:** Removed note about potential CTDs from Wonders of Weather rain splashes option (they were fixed).

#### Conflict Resolution Patch

- Fixed the bucket by the Skyforge (a better collision mesh for the wrwalltierdivide01.nif).
- Moved some plants around the Bannered Mare to reduce clipping.
- Fixed conflict between the USSEP and Simply Smaller Wolves.
- Removed records and edits related to Diverse Dragons Collection.
- Removed records and edits related to Diverse Werewolves Collection.
- Disabled one of four werewolves placed by More Werewolves in the Morthal swamp.

## Release 4.0 Beta 2

> 21/01/2021

#### Initial Setup

- **Mod Organizer 2:** Removed instructions to install deorder's MO2 plugins (better suited to a beginner's guide).
- **ESM Cleaning:** Improved instructions for cleaning Dawnguard ESM manually.
- **ESM Cleaning:** Fixed broken link at the bottom to the next page.

#### Mod Installation

- Swapped the **Landscape** (11 > 10) and **Trees & Plants** (10 > 11) steps.
- **Weather:** Fixed link for Wonders of Weather - Less Opaque Rain Splashes for ENB.
- **Trees & Plants:** Fixed download instructions for Enhanced Landscapes - Solstheim 3D Trees.
- **Worldspace Additions:** Removed instructions to install an optional file for Solstheim Lighthouse (would be overwritten anyway).

#### Appendix

- **Troubleshooting:** Added instructions to enable BorderlessUpscale in SSE Display Fixes.
- **Known Issues:** Moved everything from this page to Troubleshooting and removed it.
- **Credits:** Updated for recent changes.

## Release 4.0 Beta 1

> 20/01/2021

Update 4.0 for The Phoenix Flavour is firmly taking the setup back to its "vanilla plus" roots. TPF is committing to low-impact mods that blend in well while doubling down on our performance-friendly visual enhancements. Many mods were removed in this update, some of the beloved favourites, but there are solid reasons behind each removal.

New mods include the custom made **Armor Variants Lite** which is an alternative to kryptopyr's CCOR-dependent aMidianBorn Content Addon, created by Umgak from scratch. I also re-added the much requested artifact overhaul **Reliquary of Myth** and completely rebuilt the appearance section which is now centered around **Cathedral NPCs**. And finally Fore's New Idles was replaced with the more recent and open source **Nemesis**.

**Removal of CBBE:** I only ever included CBBE because many people demanded it. It's not required by anything and half the time I have no idea whether a CBBE patch is required or not. I haven't noticed a difference between CBBE / vanilla body in regular gameplay, ever, and I'm sick of worrying that something might not work correctly. I have no idea how to use BodySlide and frankly, I'm not interested in figuring it out. At this point, CBBE is for me personally just additional headache for zero gain. Well, I guess my character's buttcheeks are low-poly now but I can just about live with that.

**Removal of CCOR and RDO:** Both Complete Crafting Overhaul Remastered and Relationship Dialogue Overhaul were removed in this update because of feature creep. In the case of CCOR, the feature creep is subtle but enough to disturb my V+ vibes. Almost all the features that I personally like were implemented by other means with a faction equipment crafting module being on my to do list. RDO was never properly ported to SSE to begin with, nobody is creating patches for it, and it touches a million different things. The effort of integrating it is almost comparable to CRF. I personally doubt I will even notice if it's missing so I removed it as well.

**Removal of ENB Lights:** While it adds some cool effects, I removed ENB Lights for the time being as it is somewhat annoying to handle. It edits plenty of meshes (which means added compatibility work) and isn't properly updated for some of the newer fire mods. I'll likely come back to this mod and reimplement parts of it in a later 4.x update.

**Removal of the Content Addon:** Since [Elysium](https://github.com/TitansBane/Elysium) is now a thing, I no longer feel any sort of pressure to add new content to TPF. First and foremost, the list is intended to improve the gameplay, balancing, and graphics of the base game (and that's difficult enough!). Some extra content mods are still in the guide (those adding equipment variants) as I cannot imagine playing without them.

#### Introduction

- Rewrote most of the page, updated the feature list, and added testimonials.

#### Initial Setup

- Updated and rephrased many section, added screenshots and replaced some with better ones.
- **Skyrim and Steam**: Renamed this page (used to be called Skyrim SE which is not very specific).
- **Skyrim and Steam**: Added instructions to delete leftover files after uninstalling the game.
- **Skyrim and Steam**: Added more detailed instructions and a screenshot for verifying that Skyrim SE is set to English.
- **Additional Tools**: Added instructions to add an exception to Windows Defender for CAO.

#### Mod Installation

- Updated many download instructions (incremented version numbers mostly).
- Removed all (optional) and (conditional) flags.
- Added instructions to merge additional files with the main file for many mods.
- **Installation Instructions**: Removed all references to optional mods which are no longer a thing.
- **Essential Mods**: Added instructions to UHDAP on how to download with a slow internet connection.
- **Essential Mods:** Added Disable USSEP Book.
- **Essential Mods:** Moved Weapons Armor Clothing and Clutter Fixes here.
- **Fixes:** Removed Skyrim Ultimate Eyemeshes Ruhmastered (included in Cathedral Player and NPC Overhaul).
- **Fixes:** Removed Eye Normal Map Fix (redundant with Cathedral NPCs).
- **Fixes:** Removed Eyes AO Clipping Fix (redundant with Cathedral NPCs / Expressive Facegen Morphs).
- **Fixes:** Removed ENB Brow Fix (redundant with Cathedral Player and NPC Overhaul).
- **Fixes:** Removed Double Sided Vertex Human Mouth Fix (redundant with Cathedral Player and NPC Overhaul).
- **Fixes:** Removed WoodElf - MaleHair - Fix (redundant with Expressive Facegen Morphs).
- **Fixes:** Added Blackreach Tentacle Mesh Fix.
- **Tweaks:** Moved Windhelm Segregation - Stay at New Gnisis Cornerclub here.
- **Tweaks:** Moved Alik'r Warriors Aren't Welcome here.
- **Interface**: Finally re-added Quick Loot Re.
- **Interface**: Removed Undiscovered Means Unknown (wasn't very popular among users).
- **Graphics Baseline:** Removed Caliente's Beautiful Bodies Enhancer (too much unjustified headache).
- **Weather:** Added WoW Dragon Mounds CTD Fix.
- **Weather:** Added Wonders of Weather - Less Opaque Rain Splashes for ENB.
- **Lighting:** Replaced Relighting Skyrim - No Player Homes with the new updated version.
- **Visual FX:** Replaced Subtle Wind FX with Less Distracting Blowing Snow Effects for ENB Particle Patch.
- **Landscape:** Slightly changed the order of mods (update Mod Order in MO2 accordingly).
- **Landscape:** Updated download instructions for Majestic Mountains (now downloading the DynDOLOD LOD Pack).
- **Landscape:** Updated FOMOD instructions for Majestic Mountains.
- **Landscape:** Added Cathedral Landscapes - Recolored Vanilla Swamp Grass Addon.
- **Landscape:** Cathedral Landscape - Windhelm Snow Bridge Fix.
- **Landscape:** Added Cathedral - 3D Pine Grass.
- **Landscape:** Removed The Elder Scrolls - Veydosebrom.
- **Landscape:** Removed Cathedral Landscapes - Veydosebrom Swamp Grass Addon.
- **Landscape:** Removed manual edit from RW2 (no longer necessary after updating mod order).
- **Landscape:** Added Bright Waterfall Fix for ENB.
- **Landscape:** Updated FOMOD instructions for Better Dynamic Snow.
- **Landscape:** Temporarily removed Enhanced Landscapes.
- **Landscape:** Temporarily removed Enhanced Landscapes - Dead Marsh Fixes (mod page hidden).
- **Landscape:** Updated FOMOD instructions for Rorikstead Basalt Cliffs Patches.
- **Landscape:** Removed Better Dynamic Majestic Mountains.
- **Landscape:** Removed Manor Roads (looks ugly).
- **Trees & Plants:** Updated Enhanced Vanilla Trees download instructions.
- **Trees & Plants:** Updated Enhanced Vanilla Trees - Alternative Branches FOMOD instructions.
- **Trees & Plants:** Removed Bent Pines II (it's been in the list forever and I love it but it's not very v+).
- **Trees & Plants:** Moved Immersive Fallen Trees here.
- **Trees & Plants:** Moved Immersive Fallen Trees Patch here.
- **Trees & Plants:** Removed Sacred Trees (regrown Gildergreen can look very ugly).
- **Trees & Plants:** Moved Rudy HQ - More Lights for ENB - Deathbells and Nirnroots here.
- **Trees & Plants:** Added Cathedral - 3D Mountain Flowers.
- **Trees & Plants:** Added Sufficiently Optimised Snowberries 3D.
- **Trees & Plants:** Added High Poly Blackreach Mushrooms.
- **Trees & Plants:** Added Rudy HQ - More Lights for ENB - Glowing Mushrooms.
- **Trees & Plants:** Added High Poly Gleamblossoms.
- **Worldspace Additions:** Added this new page.
- **Worldspace Additions:** Moved Point The Way here.
- **Worldspace Additions:** Moved Lanterns of Skyrim II here.
- **Worldspace Additions:** Updated download instructions for Lanterns of Skyrim II.
- **Worldspace Additions:** Updated FOMOD instructions for Lanterns of Skyrim II.
- **Worldspace Additions:** Moved Immersive Dawnguard Dayspring Patch here.
- **Worldspace Additions:** Moved Unique Border Gates here.
- **Worldspace Additions:** Moved Solstheim Lighthouse here.
- **Worldspace Additions:** Moved Solstheim - Skaal Fishing Camp here.
- **Cities & Towns:** Renamed this step (used to be called "Buildings & Interiors").
- **Architecture:** Removed Pfuscher's Manhole Texture.
- **Architecture:** Replaced STR - High Hrothgar with Halls of the Greybeards.
- **Architecture:** Added HD Reworked Falmer Architecture.
- **Misc Structures:** Added SD Farmhouse Fences Patch for True Nordic Farmhouses.
- **Misc Structures:** Updated FOMOD instructions for SLO - Stone Walls (no longer selecting the new ivy mesh).
- **Misc Structures:** Added Stockades of Skyrim.
- **Misc Structures:** Added WiZkiD Carriages.
- **Misc Structures:** Added Riekling Barrels SMIM.
- **Misc Structures:** Updated FOMOD instructions for Stunning Statues of Skyrim (no longer selecting Mehrunes).
- **Interiors:** Removed Rally's Pillows.
- **Interiors:** Added Vanilla Table Replacers.
- **Interiors:** Added Nordic Beds.
- **Interiors:** Added 4K Retexture for Nordic Beds.
- **Interiors:** Added Thrones of Skyrim.
- **Dungeons:** Removed instructions to delete textures/effects folder from Rudy HQ - Nordic Ruins.
- **Dungeons:** Added Dwemer Ichor Barrel 2K.
- **Dungeons:** Moved ENB Particle Lights - Dwemer Lanterns here.
- **Dungeons:** Moved Rudy HQ - More Lights for ENB - Bthardamz here.
- **Dungeons:** No longer selecting the Hearthfire Patch in the CC's Enhanced Ore Veins FOMOD.
- **Dungeons:** Removed additional instructions from CC's Enhanced Ore Veins (no longer necessary).
- **Dungeons:** Added Dwemer Ichor Barrel 2K.
- **Clutter:** Added Barenziah's Glowing.
- **Clutter:** Removed Rudy HQ - Miscellaneous (was almost completely overwritten anyway).
- **Clutter:** Replaced MAPS with RUSTIC MAPS (which is the new SSE port).
- **Clutter:** Removed Frankly HD Dragonbone (covered by HD Reworked Dragons).
- **Clutter:** Removed JS Purses and Septims (they look gorgeous and unfortunately do not blend in at all).
- **Clutter:** Updated RUSTIC SOULGEMS download instructions (patching now done in CRP).
- **Clutter:** Removed the RUSTIC SOULGEMS FOMOD instructions.
- **Clutter:** Moved Rudy HQ - More Lights for ENB - Soul Gems here.
- **Food & Ingredients:** Added Remiros' Dragonborn Alcohol HD.
- **Food & Ingredients:** Removed additional instructions from True Homecooked Meal (moved to CRP).
- **Food & Ingredients:** Moved Rudy HQ - More Lights for ENB - Torchbugs and Moths here.
- **Food & Ingredients:** Moved Rudy HQ - More Lights for ENB - Chaurus Eggs and Sacs here.
- **Apparel & Weapons:** Updated FOMOD instructions for Practical Female Armors (now once again selecting the AMB CA Patch).
- **Apparel & Weapons:** Added instructions to download the Falkreath Matched Color Fix for Frankly HD Stormcloak and City Guards.
- **Apparel & Weapons:** Added instructions to download the Frankly HD Imperial Armor and Weapons LeanWolf Patch.
- **Apparel & Weapons:** Removed additional instructions to delete meshes from Frankly HD Imperial Armor and Weapons.
- **Apparel & Weapons:** Removed instructions to install the CBBE patch for Frankly HD Dawnguard Armor and Weapons.
- **Apparel & Weapons:** Updated download instructions for Iron Things (the standalone bow file already includes the fixed mesh).
- **Apparel & Weapons:** Removed additional instructions for Iron Things (no longer necessary).
- **Apparel & Weapons:** Updated download instructions for Outlandish Stalhrim (now downloading the blue cubemap).
- **Apparel & Weapons:** Added Rudy HQ - More Lights for ENB - Daedric Weapons.
- **Apparel & Weapons:** Added HD Reworked Shellbug.
- **Apparel & Weapons:** Removed JS Barenziah (prefer Gamwich and Saerileth's retexture packaged with Forgotten Retex Project).
- **Unique Artifacts:** Replaced Unique Uniques - Plugin Replacer with Unique Uniques - Fixes.
- **Unique Artifacts:** Removed instructions to install the CBBE patch for Frankly HD Nightingale Armor and Weapons.
- **Unique Artifacts:** Removed instructions to install the CBBE patch for Frankly HD Miraak.
- **Unique Artifacts:** Added instructions to install the Hotfix for Frankly HD Miraak.
- **Unique Artifacts:** Added Remiros' Ebony Blade HD.
- **Unique Artifacts:** Added instructions to run Ghosu - Auriel's Quiver Replacer through SSE NIF Optimizer.
- **Unique Artifacts:** Added instructions to run Ghosu's Auriel's Quiver Retexture through SSE NIF Optimizer.
- **Unique Artifacts:** Added Remiros' Hrothmund's Axe HD.
- **Creatures:** Updated FOMOD instructions for Bellyache's Animal and Creature Pack (no longer selecting Bears).
- **Creatures:** Replaced HD Rabbit by Pfuscher with Real Rabbits HD.
- **Creatures:** Now selecting 2K textures in the True Wolves of Skyrim FOMOD (instead of 1K).
- **Creatures:** Added HD Reworked Bears.
- **Creatures:** Replaced CC's HD Dwemer Automatons - Remastered with Ancient Automatons.
- **Creatures:** Added Ancient Dwemer Metal - Missing Forgemaster Fix.
- **Creatures:** Replaced RUSTIC DRAGONS with HD Reworked Dragons which covers more dragon and so that the style is consistent.
- **Creatures:** Removed The Decayed Dragon - Durnehviir Retex (Durnehviir is covered by HD Reworked Dragons).
- **Creatures:** Removed HD Serpentine Dragon and Mesh Fix (serpentine dragon is covered by HD Reworked Dragons).
- **Appearance:** This page was completely redone.
- **Appearance:** Added Cathedral Player and NPC Overhaul (this replaces / includes all mods that were removed).
- **Appearance:** Added Expressive Facegen Morphs.
- **Appearance:** Moved DIVERSE SKYRIM here.
- **Appearance:** Added instructions to delete the BSA for DIVERSE SKYRIM.
- **Appearance:** Added DIVERSE SKYRIM - Cathedral NPCs Facegen Patch.
- **Appearance:** Updated FOMOD instructions for Forgotten Argonian Roots (selecting vanilla body instead of CBBE).
- **Appearance:** Removed additional instructions for Eyes AO Clipping Fix (no longer necessary).
- **Appearance:** Removed Just Fangs from BVFE (redundant with Expressive Facegen Morphs).
- **Appearance:** Added Beast Race Fang Removal.
- **Appearance:** Moved TK Children here.
- **Appearance:** Moved Simple Children here.
- **Appearance:** Removed Bijin Skin for CBBE.
- **Appearance:** Removed Skysight Skins.
- **Appearance:** Removed High Poly Male Meshes - Vanilla plus Seamless Head.
- **Appearance:** Removed Coverkhajiit.
- **Appearance:** Removed Painterly - A High Res Vanilla Warpaint Retexture.
- **Appearance:** Removed Northborn Scars.
- **Appearance:** Removed Natural Eyes.
- **Appearance:** Removed Khajiit Wild Eyes.
- **Appearance:** Removed Bed Head - A Vanilla Hair Replacement
- **Appearance:** Removed Argonian Improvements - Horns.
- **Appearance:** Removed Immersive Mouth and Teeth.
- **Appearance:** Removed Immersive Mouth and Teeth for Orcs.
- **NPC Overhauls:** This page was merged with Appearance.
- **NPC Overhauls:** Removed Vanilla NPCs Ruhmastered.
- **NPC Overhauls:** Removed Windsong Immersive Character Overhaul.
- **NPC Overhauls:** Removed Windsong Immersive Character Overhaul - Stripped BSA.
- **NPC Overhauls:** Removed Windsong Immersive Character Overhaul - USSEP and CRF Patches.
- **NPC Overhauls:** Removed Ethereal Elven Overhaul.
- **NPC Overhauls:** Removed Ethereal Elven Overhaul - SSE Patch.
- **NPC Overhauls:** Removed DIVERSE SKYRIM - Ethereal Elven Overhaul Patch.
- **Gameplay Overhauls:** Moved More Expensive Transmute for Mysticism here.
- **Gameplay Overhauls:** Added instructions to download the Shrines and Amulets addon for Adamant.
- **Gameplay Overhauls:** Added Skyrim Uncapper.
- **Gameplay Overhauls:** Added Skyrim Uncapper - Adamant Arena.
- **Gameplay Overhauls:** Removed Complete Crafting Overhaul Remastered.
- **Gameplay Overhauls:** Removed Complete Crafting Overhaul Remastered - JS Circlet Replacer Patch.
- **Gameplay Overhauls:** Replaced Sacrosanct with Scion - A Vampire Overhaul.
- **Gameplay Overhauls:** Removed Trua - Minimalistic Faiths of Skyrim.
- **Gameplay Overhauls:** Moved Trade and Barter here.
- **Gameplay Overhauls:** Added Trade and Barter - Mysticism and Adamant Patches.
- **Gameplay Overhauls:** Re-added Reliquary of Myth - Artifact Overhaul.
- **Gameplay Overhauls:** Moved Genuinely Intelligent Soul Gems here.
- **Gameplay Overhauls:** Updated download instructions for Carriage and Ferry Travel Overhaul (Dawnstar patch no longer needed).
- **Gameplay Overhauls:** Removed CFTO - Winterhold Carriage.
- **Gameplay Overhauls:** Added Carriage and Ferry Travel Overhaul - Fixes and Winterhold.
- **Gameplay Overhauls:** Added Carriage and Ferry Travel Overhaul - Cathedral NPCs Facegen Patch.
- **Gameplay Overhauls:** Removed Night Eye Overhaul.
- **Gameplay Overhauls:** Removed Night Eye Overhaul - Plugin Replacer.
- **Non-Player Characters:** Moved Run For Your Lives here.
- **Non-Player Characters:** Moved Tavern AI Fix here (it doesn't really constitute as a fix).
- **Non-Player Characters:** Removed AI Overhaul - Windsong Immersive Character Overhaul Patch.
- **Non-Player Characters:** Removed AI Overhaul - Ethereal Elven Overhaul Patch.
- **Non-Player Characters:** Removed Relationship Dialogue Overhaul.
- **Non-Player Characters:** Updated download instructions for Hunters Not Bandits (no longer downloading the RDO version).
- **Non-Player Characters:** Updated Nether's Follower Framework FOMOD instructions.
- **Non-Player Characters:** Added Immersive Patrols - Cathedral NPCs Facegen Patch.
- **Improved Vanilla Quests:** Removed Even Better Quest Objectives.
- **Improved Vanilla Quests:** Removed Gildergreen Regrown (looks awful).
- **Improved Vanilla Quests:** Removed The Paarthurnax Dilemma.
- **Improved Vanilla Quests:** Added The Paarthuranx Resolution.
- **Improved Vanilla Quests:** Removed Castle Volkihar Rebuilt.
- **College of Winterhold:** Added this new step because of all the mods related to the college.
- **College of Winterhold:** Moved Obscure's College of Winterhold here.
- **College of Winterhold:** Updated Obscure's College of Winterhold FOMOD instructions.
- **College of Winterhold:** Added Obscure's College of Winterhold - Cathedral NPCs Facegen Patch.
- **College of Winterhold:** Moved Immersive College NPCs here.
- **College of Winterhold:** Added Immersive College NPCs - Cathedral NPCs Facegen Patch.
- **College of Winterhold:** Moved Improved College Entry - Questline Tweaks here.
- **College of Winterhold:** Moved Misc College of Winterhold Tweaks here.
- **College of Winterhold:** Updated Misc College of Winterhold Tweaks FOMOD instructions.
- **College of Winterhold:** Moved Choose Your Own Archmage here.
- **College of Winterhold:** Moved Finding Velehk Sain here.
- **Combat & Encounters:** Re-added Mortal Enemies.
- **Combat & Encounters:** Re-added Realistic Melee Range.
- **Combat & Encounters:** Removed Beast Skeletons.
- **Combat & Encounters:** Removed Beast Skeletons - Plugin Replacer.
- **Combat & Encounters:** Added proper FOMOD instructions for DMC for a vanilla-like player werewolf replacer.
- **Balancing:** This step was removed. Its mods were split up among other categories or removed from the guide.
- **Balancing:** Removed Economy Overhaul and Speechcraft Improvements.
- **Balancing:** Removed Zim's Immersive Artifacts (mostly covered by ROM now).
- **Balancing:** Removed Unique Items Tweaks (might be re-added later).
- **Crafting & New Gear:** This is basically the old Balancing step - but quite different.
- **Crafting & New Gear:** Added Lightweight Smithing Tweaks.
- **Crafting & New Gear:** Added Faster Mining Plus.
- **Crafting & New Gear:** Added Craftable Torches.
- **Crafting & New Gear:** Added Craftable Lockpicks.
- **Crafting & New Gear:** Moved Armor and Clothing Extension here.
- **Crafting & New Gear:** Moved Armor and Clothing Extension (WACCF) - MCM Menu Fix here.
- **Crafting & New Gear:** Added Tweaks for WACCF and ACE.
- **Crafting & New Gear:** Removed aMidianBorn Content Addon.
- **Crafting & New Gear:** Added aMidianBorn Armor Variants Lite.
- **New Gear:** Removed this step and all mods remaining here.
- **New Gear:** Removed Weapon Armor Clothing and Clutter Fixes - CBBE Patch.
- **New Gear:** Removed Common Clothes and Armors (may be re-added in the future).
- **New Gear:** Removed Common Clothes and Armors - CBBE Patch.
- **New Gear:** Removed Armor of Yngol.
- **New Gear:** Removed Kthonia's Unique Weapon Pack.
- **Tweak Collections:** Added this new step.
- **Tweak Collections:** Moved Morrowloot Miscellania here.
- **Tweak Collections:** Updated download instructions for Morrowloot Miscellania.
- **Tweak Collections:** Moved Miscellaneous Tweaks Collection here.
- **Tweak Collections:** Updated FOMOD instructions for Misc Tweaks - Shrines Don't Cure Diseases.
- **Tweak Collections:** Added Misc Tweaks - Night Eye Redux.
- **Tweak Collections:** Moved Andrealphus' Gameplay Tweaks here.
- **Miscellaneous:** Moved Irondusk's Saddlebags here.
- **Miscellaneous:** Removed Simply Knock.
- **Miscellaneous:** Removed Simply Knock SKSE64 DLL.
- **Miscellaneous:** Removed Dragon Remains.
- **Miscellaneous:** Removed Talkative Dragons (can get repetitive).
- **Miscellaneous:** Removed Talkative Dragons - Audio Replacer.
- **Miscellaneous:** Removed Keeper Carcette Survives.
- **Miscellaneous:** Added Simple Player Home Improvements.
- **Assorted Plugins** Added this new page to collect the various SKSE- and NSF-based plugins.
- **Assorted Plugins:** Moved Whose Quest Is It Anyway here.
- **Assorted Plugins:** Moved Yes I'm Sure here.
- **Assorted Plugins:** Added No Attack Messages.
- **Assprted Plugins:** Added Sales Overflow Solved.
- **Assorted Plugins:** Moved Better Stealing here.
- **Assorted Plugins:** Added instructions to lower the MaxPrice value for Better Stealing.
- **Assorted Plugins:** Moved Remember Lockpick Angle - Updated here.
- **Assorted Plugins:** Moved No Lockpick Activate - Updated here.
- **Assorted Plugins:** Moved Classic Sprinting Redone here.
- **Assorted Plugins:** Moved Better Jumping here.
- **Assorted Plugins:** Added I'm Walkin' Here.
- **Assorted Plugins:** Added Free Look.
- **Assorted Plugins:** Moved Uninterrupted Invisibility here.
- **Assorted Plugins:** Moved Uninterrupted Ethereal Form here.
- **New Music:** Merged with the Sound Effects page.
- **Sounds & Music:** Renamed from Sound Effects as this page now also includes the additional music mods.
- **Sounds & Music:** Updated FOMOD instructions for Immersive Sounds Compendium.
- **Sounds & Music:** Removed OMINOUS Dragon Soul Absorb Music.
- **Sounds & Music:** Removed the TPF Merged Music Patch (now part of the main CRP).
- **Skeletons & Animation:** Replaced FNIS with Nemesis Ultimate Behaviour Engine.
- **Skeletons & Animation:** Replaced XPMSSE Automated Patcher with a direct link to the fixed scripts.
- **Skeletons & Animation:** Added AllGUD Conditions Fix.
- **Utilities**: Removed the FISSES ESL-ified Patch.
- **Utilities**: Removed Copy and Paste in Console.

#### ENBSeries

- **Preset Installation:** Updated instructions for Rudy ENB 2.0.
- **Other Presets:** Slightly updated some sections of this page to be consistent with other 4.0 changes.
- **Related Mods:** This section was removed. Most included mods were moved to the main Mod Installation section.
- **Related Mods:** Removed ENB Lights.

#### Finalisation

- **Wrapping Up:** Updated and expanded list of plugins to be ESL-ified.
- **FNIS:** Removed this page as FNIS is no longer part of TPF.
- **Nemesis:** Added this page with instructions for Nemesis which replaced FNIS.
- **AllGUD:** Removed instructions to clean masters for the Alt Textures patch (no longer necessary).
- **AllGUD:** Added instructions to install the fixed Weapon Mesh Generator Script.
- **DynDOLOD:** Slightly updated and improved some of the instructions.
- **Occlusion:** Added this new page with instructions to regenerate occlusion data.

#### Finalisation

- **Mod Configuration:** Removed instruction for mods no longer present in the guide.
- **Mod Configuration:** Added instructions to bind the NFF Horse Whistle hotkey.
- **Mod Configuration:** Added MCM instructions for Storm Lightning.
- **Mod Configuration:** Added MCM instructions for Trade & Barter.
- **Mod Configuration:** Added a picture for the Wonders of Weathers MCM instructions.

## Release 3.5

> 05/09/2020

With this update Aetherius and Mundus were added to complement the existing suite of gameplay mods by SimonMagus. Alchemy got a much needed balancing upgrade with the switch to skepmanmods' Alchemy Potions and Food Adjustments and fighting dragons should be less of a headache now after the removal of Simply Stronger Dragons.

Despite the overall trend to remove customisability, I have once again re-added a page on different ENB presets as I feel that this is an easy way for me to allow personalisation. Switching ENB presets is simple, it can be done anytime. Presets are highly dependent on personal taste and I know that I personally switch all the time (haven't had a personal favourite since Visceral ENB). Rudy ENB remains the default but there are now recommendations/links to Serio's ENB, The Truth, Silent Horizons, and Semirealis.

A handful of mods were removed in anticipation of the elimination of optional mods. **However, TPF 3.5 still has optional mods.** I have decided to push this change to the next update so that from 3.6 (or whatever I'll call it) onwards, you will no longer be able to skip currently optional mods (they will all be mandatory).

#### Mod Installation

- **Essential Mods:** Reverted SSE Engine Fixes config file editing instructions to MO2 since it can now open TOML files.
- **Interface:** Removed Hide These Futile Quests (too confusing for people who don't read).
- **Unique Artifacts:** Added a note to prevent confusion about the AMB FOMOD option that is greyed out.
- **Gameplay Overhauls:** Replaced Morningstar - Minimalistic Races of Skyrim with Aetherius - A Race Overhaul.
- **Gameplay Overhauls:** Added Mundus - A Standing Stone Overhaul.
- **Gameplay Overhauls:** Removed Subtle But Classless (could no longer be optional with the addition of Aetherius).
- **Gameplay Overhauls:** Removed the Subtle But Classless - USSEP and EEO Patch.
- **Combat & Encounters:** Removed Simply Stronger Dragons - TPF Repack (makes dragon fights too difficult).
- **Balancing:** Added instructions to download the new Morrowloot Miscellania - No Fortify Enchanting Alchemy Smithing.
- **Balancing:** Added Alchemy Potions and Food Adjustments.
- **Balancing:** Removed Skyrim Alchemy Fixed.
- **Sound Effects:** Removed mod order instructions from Audio Overhaul Skyrim (they should have been gone several updates ago).

#### ENBSeries

- **Other Presets:** (Re-)Added this page, allowing you once again to choose your own ENB preset.
- **Related Mods:** Removed mod order instructions for the TPF ENB Light Patch.
- **INI Tweaks:** Specified that turning on godrays (Volumetric Lighting) is recommended specifically for Rudy ENB.

#### Finalisation

- **DynDOLOD:** Fixed TexGen instructions (the button actually just says EXIT instead of SAVE AND EXIT).

#### New Game

- **Final Adjustments:** Removed ENB Shader Cache section (doesn't need to be reset for new presets anymore).
- **Mod Configuration:** Renamed "Nether's Follower Framework" section to "Follower Framework" to match the ingame menu.
- **Mod Configuration:** Rephrased instructions to disable Wonders of Weather rainsplashes (must be disabled to prevent CTDs).
- **ENB Tweaks:** Added this page to reintegrate Serio's ENB tweaks.

#### Resources

- **Widescreen Support:** Added proper instructions for widescreen monitor owners.

#### Appendix

- **Frequently Asked Questions:** Restructured the page, updated and expanded it.
- **Known Issues:** Added this page.

#### Conflict Resolution Patch

- Fixed conflicts between Ethereal Elven Overhaul and Aetherius - A Race Overhaul.
- Cleaned out Skyrim Alchemy Fixed as the mod was removed.
- CCOR changes the mesh path for the Necromancer's Amulet but doesn't package the new mesh so the amulet ends up being invisible. I reverted the mesh path back to vanilla. Thanks to caligineux for reporting this!

## Release 3.4.5

> 30/08/2020

This is a quick fix-it for the recently reworked Veydosebrom. The new version no longer works with my plugin replacer / Cathedral addon - fortunately, the original Vey is still available for download.

A bigger update, 3.5, is currently in the works. No ETA.

#### Mod Installation

- **Landscape:** Updated instructions for Veydosebrom, downloading version from Old Files.
- **Landscape:** No longer selecting Snowy Farmhouses in the Better Dynamic Snow FOMOD (they don't look great).

## Release 3.4.4

> 10/08/2020

This is a fix-it for yesterday's update because I messed up a surprising amount of stuff some of which was already fixed yesterday but were included in the changelog for completion's sake.  All I can say in my defence is that 34°C in my flat is doing things to my brain.

**Mysticism and Adamant update:** Simon just released a huge update for Mysticism which is going to require us to update the CRP. Do not install the new versions of Mysticism and Adamant until Umgak had the time to update the CRP. You will be pinged on Discord or see the notification for the update on the Nexus if you are tracking TPF there. **Do not ask for an ETA.**

#### Initial Setup

- **Skyrim Script Extender:** Updated instructions, now supporting SKSE 2.0.19 (latest update).

#### Mod Installation

- **Apparel & Weapons:** Actually removed the (optional) flag from Open Face Guard Helmets.
- **Gameplay Overhauls:** Trua - Minimalistic Faiths of Skyrim is no longer optional (no, seriously this time).

#### Finalisation

- **First Launch:** Removed ENB config section for Serio's ENB that is no longer necessary with Rudy ENB.

#### Appendix

- **Troubleshooting:** Added section for the enblocal.ini VSYNC and SSE Display Fixes conflict.

## Release 3.4.3

> 09/08/2020

With this update, we are switching to the recently released Rudy ENB for Cathedral Weathers which works better out of the box for our setup. It also utilises almost all ENB features without too much of a performance impact which is pretty impressive.

I've also finally gotten around to fixing up some [personal tweaks](https://www.nexusmods.com/skyrimspecialedition/mods/38348/) and putting them on Nexus. Of course they were added to the guide as well.

#### Initial Setup

- **Skyrim Script Extender:** Updated instructions, now supporting SKSE 2.0.18 (latest update).
- **INI Files:** Added instructions to increase particle count to 1500 under BethINI Detail.

#### Mod Installation

- Updated download instructions for a bunch of mods (incremented version numbers).
- **Tweaks:** Added Miscellaneous Tweaks Collection.
- **Tweaks:** Removed Morrowloot Miscellania - Better Ancient Knowledge (included in Miscellaneous Tweaks Collection).
- **Graphics Baseline:** Updated instructions to unpack the aMidianBorn Book of Silence BSA through MO2 instead of CAO.
- **Misc Structures:** Replaced Fences of Skyrim with SD's Farmhouse Fences.
- **Apparel & Weapons:** Open Face Guard Helmets is no longer optional (CRP dependency).
- **Apparel & Weapons:** Removed Open Face Guard Helmets - Plugin Replacer (conflicts addressed in the CRP).
- **Unique Artifacts:** Removed Better Shrouded Armor - Ancient Replacer Only - Plugin Replacer (conflicts addressed in the CRP).
- **Gameplay Overhauls:** Trua - Minimalistic Faiths of Skyrim is no longer optional.
- **Non-Player Character:** Updated the customisation instructions for GDO (new console commands).
- **Non-Player Characters:** Updated FOMOD instructions for Nether's Follower Framework.
- **Combat & Encounters:** Added No Road Predators Redone.
- **Content Addon:** Temporarily removed It Beats For Her (hidden on the Nexus).

#### ENBSeries

- **ENB Preset Installation:** Renamed this step to have a generic name (because I keep changing presets).
- **ENB Preset Installation:** Swapped from Serio's ENB to Rudy ENB for Cathedral Weathers.
- **INI Tweaks:** Added optional instructions to enable volumetric lighting (godrays).

#### Resources

- **How To Update:** Added Skyrim Script Extender updating instructions.

#### Conflict Resolution Patch

- Fixed conflicts between Open Face Guard Helmets and WACCF.
- Fixed conflicts between Better Shrouded Armor - Ancient Replacer Only, WACCF, and Unique Item Tweaks.
- **Updated for Adamant 4.0.4**. Updating instructions [here](/skyrim-se/guide-resources/how-to-update/).

## Release 3.4.2

> 30/07/2020

Maintenance update.

#### Initial Setup

- **Skyrim SE:** Added a note that non-English installations of Skyrim SE are not supported.
- **ESM Cleaning:** Removed manual cleaning instructions for Update ESM (may cause issues and 3DNPC is no longer in the guide).

#### Mod Installation

- **Trees & Plants:** Added Scathecraw HD 2K.
- **Buildings & Interiors:** Updated FOMOD instructions for Obscure's College of Winterhold (no longer using Mannequins Stay Put).
- **Dungeons:** Updated download instructions for CC's Enhanced Ore Veins.
- **Dungeons:** Added instructions to remove Heart Stone meshes/textures from Metallurgy.
- **Clutter:** Added instructions to remove the scathecrow textures from Forgotten Retex Overhaul.
- **Apparel & Weapons:** Added Male Horns for Female Iron Helmet.
- **Unique Artifacts:** Unique Zephyr is no longer optional (needs a conflict fixed in the CRP).
- **Miscellaneous:** Added Ish's Respec Mod.
- **Skeleton & Animations:** Added Relaxed Sneaking Animations.
- **Skeleton & Animations:** Added Slof's Trotting Horse.

#### Resources

- **How To Update:** Added this new page with instructions for updating various tools and certain mods.

#### Conflict Resolution Patch

- Fixed a conflict between Ish's Respec Mod and Night Eye Overhaul.
- Lowered the amount of Draughts of Fate Unwound available at Elgrim's from 99 to 2.
- Fixed a conflict between Unique Zephyr and Unique Item Tweaks.
- The Ring of Pure Mixtures is no longer disenchantable.
- The Forgemaster's Fingers are no longer disenchantable.
- The Dragon ingredients added by Skyrim Alchemy Fixed will no longer drop.
- **Not yet updated for Adamant 4.0 or newer.**

## Release 3.4.1

> 15/07/2020

This is basically just 3.4, but fixed. As usual, the big release had plenty of oversights and little errors that were hunted down by the wonderful people on our Discord server, in particular Lively who went through the entire guide once again with a fine-toothed comb. Thanks!

#### Initial Setup

- **The Creation Kit:** Updated instructions with latest version number for CK Fixes (3.x).
- **INI Files:** Fixed file path to INI folder in "Remove old files" step.
- **INI Files:** Added instructions to check the Tree Shadows box (otherwise trees will look extremely ugly).
- **Additional Tools:** Updated the Cathedral Assets Overhaul profiles screenshot.
- **ESM Cleaning:** Fixed a really dumb typo (move cleaned ESMs BELOW the uncleaned ones in MO2).

#### Mod Installation
- Fixed a lot of version numbers, file names, and links.
- **Fixes:** Updated FOMOD instructions for Landscape Fixes for Grass Mods  (no longer selecting the Provincial Courier Service patch).
- **Fixes:** Removed Mannequins Stay Put.
- **Fixes:** Added Mannequin Management.
- **Graphics Baseline:** Removed the leftover and now redundant Skyrim Realistic Overhaul section.
- **Lighting:** Removed leftover, redundant mod order instructions for the Luminosity - A Quality World Map Patch.
- **Trees & Plants:** Swapped from Lush Large to Lush trees for EVT (good compromise for less powerful systems).
- **Trees & Plants:** Fixed FOMOD instructions for EVT Lush.
- **Trees & Plants:** Fixed FOMOD instructions for EVT - Alternative Branch Textures.
- **Trees & Plants:** No longer installing EVT Alternative Trees (I'm tired of the snowy pines, found myself missing the vanilla ones).
- **Trees & Plants:** Removed EVT Vurts Light Snow Trees (since we're no longer using the big ones).
- **Trees & Plants:** Moved Enhanced Landscapes - Dead Marsh here.
- **Trees & Plants:** Updated the FOMOD instructions for Enhanced Landscapes (they ahd an ancient pre-3.0 format).
- **Trees & Plants:** Moved Enhanced Landscapes - Dead Marsh Fixes here.
- **Trees & Plants:** Removed HQ Tree Bark.
- **Trees & Plants:** Added Flora Mod Collection.
- **Landscape:** Updated FOMOD instructions for LoS II (no longer selecting the Provincial Courier Service patch). 
- **Buildings & Interiors:** Removed Provincial Courier Service.
- **Architecture:** Removed MD's Farmhouses.
- **Architecture:** Added True Nordic Farmhouses (by Spiffyskytrooper who primarily does incredible retextures for Fallout games.)
- **Gameplay Overhauls:** Removed leftover, redundant mod order instructions for the CCOR - JS Circlets Patch.
- **Gameplay Overhauls:** Removed leftover, redundant mod order instructions for the CFTO - Dawnstar Patch.
- **Combat & Encounters:** Removed Mortal Enemies (for real this time).
- **Balancing:** Moved all Morrowloot Miscellania file into one step.
- **New Gear:** Removed leftover, redundant mod order instructions for the WACCF - CBBE Patch.

#### Finalisation

- **Wrapping Up:** Updated instructions for the renamed separator (PATCHES >> FINAL PATCHES).
- **Wrapping Up:** Added instructions to enable all plugins before applying the loadorder.txt.
- **Wrapping Up:** Updated instructions regarding plugins below the CRP.

#### New Game

- **Mod Configuration:** Removed Wildcat - Configuration Power section.
- **Mod Configuration:** Added Cathedral Weathers MCM instructions.
- **Mod Configuration:** Removed Obsidian Weathers MCM instructions.
- **Mod Configuration:** Removed VioLens MCM Instructions.
- **Mod Configuration:** Removed Wildcat MCM instructions

## Release 3.4

> 14/07/2020

Welcome to the Make Phoenix Happy Again update, also known as MAPHA. Fuck Trump by the way (in case there are any doubts about my thoughts on the matter).

This update may well be controversial. A good deal of mods were removed in an effort to get back to my vision of a perfect vanilla-plus game. I fully expect that the changes will put off some users and I'm sorry for that, but it's for the best. Removing pretty much all the customisation options (not including optional mods) helps me a great deal with streamlining my work behind the scenes. I have a lot of polishing and small edits in my backlog that I never get to because I'm busy with a million other things.

The intention is not to make TPF smaller, per se. I will be adding a number of mods over the course of the upcoming updates and I do not plan to keep TPF small for the sake of it. It's the overall complexity and therefore the amount of work required that I need to keep reasonably small. I already struggle with a lack of focus and concentration, no need to make things harder for myself.

**Major changes:**

- Added a new Content Addon section that can be skipped completely. It includes the quest and companion mods that weren't yeeted in this update and will likely be expanded in the future.
- Interesting NPCs was yeeted for good. The quality of the mod is somewhat inconsistent and it doesn't blend in at all (and doesn't try to). It is by no means a "bad" mod, but it doesn't fit TPF.
- Arthmoor's Towns were yeeted for good. Supporting two optional sections is just too much work and I don't like them enough to add them to the new Content Addon.
- Obsidian Weathers was swapped out for Cathedral Weathers (again). In order to be able to control visuals better, I have decided to support only a single weather+ENB combo which will be Cath Weathers and Serio's ENB, ensuring working night eye visuals and decent grass blending.
- Wildcat was swapped out for Blade and Blunt. Not only does B&B complement the existing suite of SimonMagus gameplay mods (Adamant, Mysticism, and Arena), it is also more light-weight while at the same time (partly) replacing other tweaks.

**Structural changes:**

- Removed the numbering completely. The reason behind that is that with all the changes to the order of steps / mods I'm making, they are changing constantly anyway. Plus it's a lot of annoying work to keep them updated. So fuck 'em.
- Changed the order of mod installation steps AGAIN. Yes, I've been reshuffling them with basically every major update. I'd like to think that I'm getting closer and closer to perfection, though.
- Patches are no longer moved to the PATCHES separator. You can just leave them where they are in the installation order and the loadorder.txt will move the plugins to the correct spot.

#### Initial Setup

- This step was renamed to Initial Setup, simply because it looks better when the name is longer. Yeah...
- **Mod Organizer 2:** Added instructions to change the background color for the MO2 separators.
- **Mod Organizer 2:** Added instructions for the new OFFICIAL MASTER FILES separator.
- **INI Tweaks:** Updated BethINI Detail instructions (increasing Exterior Draw Distance to 8000).
- **ESM Cleaning:** Added instructions to move the Cleaned ESMs mod folder below the new OFFICIAL MASTER FILES separator.
- **Skyrim Realistic Overhaul:** This step was removed completely. SRO is no longer part of the guide.
- **Mod Installation:** This step (containing general instructions for the mod installation) was moved to the Mod Installation section.

#### Mod Installation 

- **Essential Mods:** Moved More Informative Console here (from Quality of Life).
- **Fixes:** Updated FOMOD instructions for Skyrim Landscape and Water Fixes (mod update).
- **Fixes:** Updated FOMOD instructions for NARC (no longer selecting the Forgotten City patch).
- **Fixes:** Moved Keyboard Shortcuts Fix here (from Quality of Life).
- **Tweaks:** Moved Remember Lockpick Angle - Updated here (from Quality of Life).
- **Tweaks:** Moved No Lockpick Activate - Updated here (from Quality of Life).
- **Tweaks:** Moved Classic Sprinting Redone here (from Quality of Life).
- **Tweaks:** Moved Better Jumping here (from Quality of Life).
- **Interface:** Moved Roboto Font Replacer here (from Customisation).
- **Interface:** Moved DRELDYN's Original Main Menu Overhaul (from Customisation).
- **Interface:** Moved Yes I'm Sure here (from Quality of Life).
- **Interface:** Moved Whose Quest Is It Anyway here (from Quality of Life)
- **Interface:** Moved Hide Those Futile Quests here (from Quality of Life).
- **Graphics Baseline:** This step was renamed from Main Visual Mods.
- **Graphics Baseline:** Removed aMidianBorn Book of Silence - Dragonborn DLC (redundant with the new, ported AIO).
- **Graphics Baseline:** Added aMidianBorn Book of Silence.
- **Weather:** Removed Obsidian Weathers (replaced by Cathedral Weathers).
- **Weather:** Removed Obsidian Weathers MCM (no longer necessary without OW).
- **Weather:** Removed Smooth Sky Mesh (included in Cathedral Weathers).
- **Weather:** Removed Yee - A New Snowflake Mod (included in Cathedral Weathers).
- **Weather:** Removed Wonders of Weather - Less Transparent Rain Splashes (prefer to just disable the feature entirely).
- **Weather:** Added Cathedral Weathers and Seasons.
- **Weather:** Added Cathedral Weathers MCM.
- **Weather:** Updated instructions for SkyGazer Moons to download the No Glow file because the glow effect looks weird with ENB.
- **Weather:** Added Volumetric Mist.
- **Visual FX:** Removed Glow Be Gone Updated (breaks ghost FX and the fix is rather involved).
- **Trees & Plants:** Renamed the step from Flora to Trees & Plants.
- **Trees & Plants:** Now using the Lush Large Trees option for EVT. FOMOD instructions were updated and simplified.
- **Trees & Plants:** Moved Solstheim 3D Trees here (from Customisation).
- **Trees & Plants:** Added note to keep Solstheim 3D Trees disabled for the time being.
- **Trees & Plants:** Moved Bent Pines II here (from Customisation). Added instructions to install the Navmesh patch.
- **Trees & Plants:** Changed FOMOD instructions, using Kojak’s Trees now.
- **Trees & Plants:** Added Rally's Hanging Moss.
- **Trees & Plants:** Added Rally's Solstheim Plants.
- **Landscape:** Added Rally's Solstheim Landscapes.
- **Landscape:** Moved Immersive Fallen Trees here (from Trees & Plants).
- **Landscape:** Moved Immersive Fallen Trees Patch here (from Trees & Plants).
- **Buildings & Interiors:** This step is a merge of the former Vanilla Locations section and some other mods.
- **Buildings & Interiors:** Updated FOMOD instructions for Obscure's College of Winterhold (no 3DNPC and ToK patches).
- **Buildings & Interiors:** Moved Provincial Courier Service here (from New Quests & Locations).
- **Buildings & Interiors:** Moved Unique Border Gates here (from New Quests & Locations).
- **Buildings & Interiors:** Moved Solstheim Lighthouse here (from New Quests & Locations).
- **Buildings & Interiors:** Solstheim Lighthouse is no longer optional.
- **Buildings & Interiors:** Moved Solstheim - Skaal Fishing Camp here (from New Quests & Locations).
- **NPC Overhauls:** Moved DIVERSE SKYRIM here (from New NPCs & Companions).
- **NPC Overhauls:** Moved DIVERSE SKYRIM - Ethereal Elven Overhaul Patch here (from New NPCs & Companions).
- **NPC Overhauls:** Updated FOMOD instructions for Simple Children (no longer installing the 3DNPC and Forgotten City patches).
- **Architecture:** Added Rally's Raven Rock.
- **Architecture:** Added Rally's Tel Mithryn.
- **Architecture:** Added Rally's Riekling Outposts.
- **Interiors:** Added Rally's Pillows.
- **Apparel & Weapons:** Renamed this step to Apparel & Weapons from Weapons & Armor.
- **Apparel & Weapons:** Moved all mods from the former Clothes & Jewellery step here.
- **Apparel & Weapons:** Removed aMidianBorn Book of Silence - Armors.
- **Apparel & Weapons:** Removed aMidianBorn Book of Silence - Weapons.
- **Apparel & Weapons:** Linked to the new Sunhallowed and Bloodcursed Arrows HD SSE port. Removed porting instructions.
- **Unique Artifacts:** Removed aMidianBorn Book of Silence - Unique Items.
- **Creatures:** Moved all mods from the former Daedra & Dragons step here.
- **Creatures:** Removed Bellyache's HD Dragon Replacer Pack.
- **Creatures:** Removed Odahviing Enhanced.
- **Creatures:** Added RUSTIC DRAGONS.
- **Creatures:** Realistic Skin and Hair Shaders - Falmer and Hagravens is now optional.
- **Gameplay Overhauls:** Moved Trua - Minimalistic Faiths of Skyrim here (from New Mechanics & Features).
- **Gameplay Overhauls:** Moved Irondusk's Saddlebags here (from New Mechanics & Features).
- **Non-Player Characters:** Updated FOMOD instructions for Nether's Follower Framework (no longer selecting the 3DNPC patch).
- **Non-Player Characters:** Moved Prince & the Pauper here (from the former Clothes & Jewellery section).
- **Non-Player Characters:** Finally re-added Hearthfire Multiple Adoptions.
- **Non-Player Characters:** Added Prince and the Pauper - Hearthfire Multiple Adoptions Patch.
- **Non-Player Characters:** Moved Adopt Aventus Aretino here (from New Mechanics & Features).
- **Non-Player Characters:** Moved Immersive Patrols here (from New Encounters & Creatures).
- **Non-Player Characters:** Moved Immersive Patrols Simplified here (from New Encounters & Creatures).
- **Non-Player Characters:** Added FOMOD instructions for the new version of Immersive Patrols Simplified.
- **Non-Player Characters:** Moved Immersive College NPCs here (from New NPCs & Companions).
- **Improved Vanilla Quests:** Moved the Choice Is Yours here (from Quality of Life).
- **Improved Vanilla Quests:** Moved FOMOD instructions for Misc College of Winterhold Tweaks here (from Finalisation).
- **Improved Vanilla Quests:** Updated FOMOD instructions for Misc College of Winterhold (no longer selecting the 3DNPC patch).
- **Improved Vanilla Quests:** Moved Choose Your Own Arch-Mage here (from New Mechanics & Features).
- **Improved Vanilla Quests:** Moved Stackable Stones of Barenziah here (from Quality of Life).
- **Improved Vanilla Quests:** Moved Bounty Preview here (from Quality of Life).
- **Combat & Encounters:** Renamed the step to Combat & Encounters from Combat.
- **Combat & Encounters:** Removed Wildcat - Combat of Skyrim.
- **Combat & Encounters:** Added Blade & Blunt - A Combat Overhaul.
- **Combat & Encounters:** Removed Mortal Enemies (partly included in Blade and Blunt).
- **Combat & Encounters:** Removed Athletik Combat (similar tweaks included in Blade and Blunt).
- **Combat & Encounters:** Removed Realistic Melee Range (similar tweaks included in Blade and Blunt).
- **Combat & Encounters:** Removed No BS AI Projectile Dodge (covered by Blade and Blunt).
- **Combat & Encounters:** Removed VioLens - A Killmove Mod (BB includes player killmove immunity which is all we need).
- **Combat & Encounters:** Moved Beast Skeletons here (from New Encounters & Creatures).
- **Combat & Encounters:** Moved Beast Skeletons - Plugin Replacer here (from New Encounters & Creatures).
- **Combat & Encounters:** Moved Diverse Dragons Collection here (from New Encounters & Creatures).
- **Combat & Encounters:** Moved Splendor - Dragon Variants here (from Daedra & Dragons).
- **Combat & Encounters:** Moved Diverse Werewolves Collection here (from New Encounters & Creatures).
- **Combat & Encounters:** Moved More Werewolves here (from New Encounters & Creatures).
- **Combat & Encounters:** Moved Cannibal Draugr on Solstheim here (from New Encounters & Creatures).
- **Combat & Encounters:** Moved The Blood Horker here (from New Encounters & Creatures).
- **Combat & Encounters:** Removed Cliff Racers of Solstheim (low quality of assets).
- **Balancing:** Removed Reliquary of Myth temporarily (will be re-added as soon as the mod has reached a stable state).
- **Balancing:** Updated FOMOD instructions for Zim's Immersive Artifacts (no longer selecting the Thane pack).
- **Miscellaneous:** Renamed this step from Immersion to Miscellaneous.
- **Miscellaneous:** Moved Simply Knock here (from New Mechanics & Features).
- **Miscellaneous:** Moved Simply Knock SKSE564 DLL here (from New Mechanics & Features).
- **Miscellaneous:** Moved Quick Light here (from New Mechanics & Features).
- **New Gear:** Renamed this step from New Items & Equipment to New Gear.
- **New Gear:** Removed aMidianBorn Book of Silence - Content Addon (the assets are included in the new AIO).
- **New Gear:** Removed Unique Scimitars (low quality of assets).
- **Content Addon:** Added this section.
- **Content Addon:** Moved The Forgotten City here (from New Quests & Locations).
- **Content Addon:** Moved The Forgotten City - No Audio Books here (from New Quests & Locations).
- **Content Addon:** Added Simple Children - The Forgotten City Patch.
- **Content Addon:** Moved The Tools of Kagrenac here (from New Quests & Locations).
- **Content Addon:** Moved It Beats For Her here (from New Quests & Locations).
- **Content Addon:** Updated download instructions for It Beats For Her (the correct file is now once again main file).
- **Content Addon:** Moved Falkreath Hauntings here (from New Encounters & Creatures).
- **Content Addon:** Moved INIGO here (from New NPCs & Companions).
- **Content Addon:** Moved Morrowloot Ultimate - Inigo Patch here (from New NPCs & Companions).
- **Content Addon:** Added cleaning instructions for the MLU Inigo patch.
- **Content Addon:** Moved Inigo Whistle Key here (from New NPCs & Companions).
- **Content Addon:** Moved Lucien - Fully Voiced Follower here (from New NPCs & Companions).
- **Content Addon:** Lucien is now marked as optional since it's not a CRP dependency.
- **Content Addon:** Moved Pandorable's Lucien Replacer here (from New NPCs & Companions).
- **Content Addon:** Pandorable's Lucien Replacer is now marked as conditional since it requires an optional mod (Lucien).
- **Sound Effects:** Removed instructions for the AOS Obsidian Weathers patch.
- **Sound Effects:** Added instructions to download the new AOS Cathedral Weathers patch (thanks, Dylan!).
- **Utilities:** Removed Papyrus Extender (since FEC is no longer in the guide).
- **Utilities:** Moved Copy and Paste in Console here (from Quality of Life).

#### ENBSeries

- **Serio's ENB:** Renamed this step to Serio's ENB from Silent Horizons.
- **Serio's ENB:** Updated instructions for the new preset, Serio's.
- The Additional Presets step was removed.
- **Related Mods:** Added instructions to install the ENB Light Quick Light patch if Quick Light was installed.
- **Related Mods:** Removed the ENB Light - Patch Pack.
- **Related Mods:** Added The Phoenix Flavour - ENB Light Patch (same as the patches from the pack but in one ESP).
- The ENB FAQ step was removed.

#### Finalisation

- **Wrapping Up:** Moved FOMOD instructions for MCWT back to the actual mod (since now all required mods are already installed prior to MCWT itself).
- **Wrapping Up:** Updated the list of plugins to ESL-ify.
- **All Geared Up Derivative:** Added instructions to download and installed a fixed version of one of the scripts.
- **DynDOLOD:** Updated the TexGen screenshot (no longer shows file compression change).
- **DynDOLOD:** The TexGen Output is now to be moved below the PATCHER OUTPUT separator.
- **DynDOLOD:** Added instructions to activate Solstheim 3D Trees before generating 3D tree LOD.
- **First Launch:** Added an ENB Configuration setting for Serio's ENB.
- **Clean-Up:** Split off the final two steps from First Launch and moved them here.

## Release 3.3.3

> 26.06.2020

This is a maintenance update, I fixed some broken links and updated instructions.

#### Setup

- **7.2.2:** Fixed download instructions for the CAO Basic Profiles pack.
- **10.2.5:** Fixed the link to the Basic Instructions page.

#### Mod Installation

- **1.2:** Updated SSE Engine Fixes configuration instructions for the new TOML file.
- **10.4:** Added FOMOD instructions for the updated Enhanced Landscapes - Oaks Standalone.
- **10.6:** Added instructions to download the 512px leave textures for Rudy's Fallen Leaves and Needles.
- **16.12:** Added JS Purses and Septims.

#### Customisation

- **Different Aspen Trees:** Updated the instructions for the Green Aspen Leaves textures.
- **Misc Mods:** Updated download instructions for Frozen Electrocuted Combustion.

## Release 3.3.2

> Uhh...

#### Setup

- **1.5:** Added instructions to install the Visual C++ redists required by Mod Organizer 2.

#### Mod Installation

- **1.4:** Finally added some INI tweak instructions for SSE Display Fixes.
- **23.1:** Added note to Vanilla NPCs Ruhmastered to use a specific file name.
- **28.9:** Replaced Simply Stronger Dragons with a repack of the double health / vanilla damage version that is easier to install.
- **33.3:** Updated Interesting NPCs download instructions (new hotfix).

#### Customisation

- **Large Trees:** Fixed instructions (the Custom Large trees option is contained in a spearate main file now).

## Release 3.3.1

> 13.06.2020

In this update, I primarily focused on restructuring the guide. A *lot* has happened behind the scenes. Step improved much of the theming, especially the dark theme and fixed some remaining issues. We are back on the old domain - thephoenixflavour.com - now with free Cloudflare SSL. It just redirects from foreverphoenix.github.io so it doesn't matter which URL you use. I've been tinkering with more stuff for the guide content but realised fairly soon I was picking up way too many projects at once so most things were put on the backburner until the next update.

Because I've tried and moved and deleted so much stuff, the changelog is probably not complete. Sorry about that. This update kinda ran away from me and became a mess. I hope I didn't horribly break anything.

An new ENBSeries section was added that covers everything related to ENB, including instructions for a new default preset, Silent Horizons ENB. Visceral is still supported and listed under 04 Additional Presets. The mods from the ENB Particle Lights section were moved here to 05 Related Mods. ENB Light is now optional. With these changes, ENBSeries can easily be skipped.

#### Setup

- **6.3:** Updated BethINI instructions to remove ENB-related tweaks. Instructions to disable vanilla AO and increase particle count were moved to the new ENBSeries section.
- **7.2:** Adjusted instructions to link to the new download location for the CAO - Basic Profiles Pack.
- **9.3:** Added instructions to install the new CAO - SRO Profiles Pack.

#### Mod Installation

- Removed Remove Sneak Attack Sounds (feature included in Immersive Sounds - Compendium).
- Moved Frozen Electrocuted Combustion to Customisation.
- Moved ENB Particle Lights page to the new ENB section.
- **2.6:** Updated FOMOD instructions for Skyrim Water and Landscape Fixes (file update).
- **6.2:** Obsidian Weathers and Seasons MCM Patch is no longer optional.
- **21.21:** Realistic Skin Shader for Falmer and Hagravens is no longer optional.

#### ENBSeries

- Added this new section to cover everything related to ENBSeries.

#### Customisation
- **New Music:** This section was moved to the main guide.
- **Misc Mods:** Moved Frozen Electrocuted Combustion here.
- **Plugin Edits:** This section was removed for now. It only included a tweak for Dwemer Spectres which is no longer in the guide.
- **Removing ENB:** This section no longer exists as ENB itself was made completely optional.

## Release 3.3

> 07.06.2020

I re-added the mod installation instructions that I completely missed in the original website setup. Whoops! It's not like they're important or anything. You can find them [here](https://foreverphoenix.github.io/docs/02-setup/step-10/). It's not a straight copy-paste, I re-structured it and re-wrote parts as well. All "generic instructions" (using CAO, resaving plugins, etc) were moved to the [Basic Instructions](https://foreverphoenix.github.io/docs/07-resources/basic-instructions/) page under Resources.

The Mod Installation section itself was split up into four parts to avoid the ugly scrollbar.

The "Unpack Example.bsa" instructions previously contained instructions to delete the BSA afterwards. Some users missed this step and others got confused so I removed it and added instructions to delete the BSA directly to the mod instructions where appropriate. Should be pretty hard to miss now.

Some mods are now flagged as **(conditional)**, meaning they are optional but depend on other mods. You must install a **(conditional)** mod if you installed the mod that it depends on. Otherwise you must skip it.

And finally I added several new mods: **Immersive Sounds Compendium** with DylanJames' new AOS integration patch to the main guide and my favourite new music mods with a merged patch to the Customisation.

#### Setup

- **Step 7:** Removed the zEdit section. zEdit will be re-added to the guide once mator provides ESL support.

#### Mod Installation

- Removed Dwemer Spectres.
- Removed Dwemer Spectres - EBT No Bleeding and Other Fixes.
- Moved Adopt Aventus Aretino from Non-Player Characters (Step 26) to New Mechanics & Features (Step 36).
- **3.9:** Changed download instructions for Realistic Conversation (using a different main file).
- **8.5:** Arctic - Frost Effects Redux is no longer optional (conflict with ISC had to be resolved in the CRP).
- **36.8:** Re-added Irondusk's Saddlebags.
- **37.2:** Added Immersive Sounds - Compendium.
- **37.3:** Added Audio Overhaul - Immersive Sounds Integration.

#### Customisation

- **New Music:** Added this new section with five new music mods and a merged patch.

## Release 3.2.3

> 04.06.2020

Maintenance update.

#### Mod Installation

- **8.1:** Updated download instructions for Frozen Electrocuted Combustion (file update).
- **10.1:** Updated FOMOD instructions for EVT Alternate Branch Textures (file update).
- **37.1:** Updated download instructions for Audio Overhaul for Skyrim, removed instructions to download the EBT Patch (now integrated into the CRP).
- **37.1:** Removed instructions to delete the SKSE folder (no longer preset) and added instructions to delete the modgroups file for Audio Overhaul for Skyrim.

## Release 3.2.2

> 23.05.2020

Just a small maintenance update. Realistic Water Two received a big update today, then got hidden to fix oversights. It's back up now. You can probably expect a CRP update soon, but for now here are the updated instructions.

For those who use Arthmoor's additional towns from Customisation, there are now instructions for the Lanterns of Skyrim II patches. I missed them previously.

**Wabbajack users:** Stop pestering Lively about fixing the installer. When mods are updated, he has to update his own setup and recompile, and that takes time. Consider the fact that he has a life that includes more than updating the installer the second a mod update drops. Plus when a mod is hidden, like RW2 was today, there is nothing anyone can do and we all have to wait for the mod author to unhide the mod page. 

#### Mod Installation

- 1.9 Added instructions to delete a textures from the Particle Patch (fixes a bug where water spray would look much darker than intended).
- 9.7 Updated instructions for Realistic Water Two.
- 9.8 Added Realistic Water Two Patch Hub.

#### Customisation

- Added missing Lanterns of Skyrim II patch instructions for Arthmoor's Towns.

#### Load Order TXT

- Added new RealisticWaterTwo - Resources.esm

## Release 3.2.1

> 21.05.2020

This is a small update, fixing some 3.2 oversights as well as bringing the guide up-to-date with the latest mod updates (of which there were several).

Most notably, BethINI and the guide's instructions for it were updated. The process of re-doing BethINI is quite simple and detailed in a new FAQ section, [How to redo INI files from scratch](https://github.com/foreverphoenix/the-phoenix-flavour/blob/master/The-Phoenix-Flavour-3-2/06-FAQ.md#how-to-redo-ini-files-from-scratch).

**Late note:** I forgot to do this earlier, but the Enhanced Vanilla Trees section is all updated now. You will need to regenerate DynDOLOD.

#### Setup

- 2.9 Added section on what to do with 'creations' reinstalled alongside Skyrim SE.
- 6.3 Updated BethINI settings. Added screenshots.

#### Mod Installation

- Fixed some typos and duplicate instructions.
- Incremented version numbers for some updated files.
- Moved Bent Pines to Customisation.
- 1.9 Added a temporary direct link to the Particle Patch while ENB Forums are down.
- 8.1 Updated instructions for Frozen Electrocuted Combustion (file update).
- 8.2 Removed FEC Extra Crispy Burnt Corpses (now obsolete).
- 5.9 Updated instructions for AMB Dragonborn DLC (file update).
- 10.1 Updated the Enhanced Vanilla Trees instructions for the latest version.
- 10.3 Added instructions to remove snowy pine tree bark textures from Tree Bark in High Definition.
- 20.1 Updated instructions for AMB Unique Items (file update).
- 21.21 Added Realistic Skin and Hair Shaders - Falmer and Hagraven.
- 21.22 Added Realistic Skin and Hair Shaders - Giants.
- 29.1 Updated MM Hybrid Loot link (now available on the Nexus).

#### Customisation

- Split the tree tweaks section up into several smaller ones.
- Rewrote Large Trees and Aspen Trees sections for EVT 2.0.
- Removed support for Whiterun - Forest Borealis.
- Moved Bent Pines here.

#### FAQ

- Added How to regenerate INI files from scratch.
- Added Creation Club section.

#### Load Order TXT

- Removed left-over beta files (AMB Patches).
- Moved KarstaagReborn.esp to match mod order.
- Added HagravenSkinShaders.esp (new in 3.2.1).

## Release 3.2

> 20.05.2020

**Disclaimer:** Release 3.2 is fairly substantial so I am bound to have missed some changes and not everything is fully documented. Installing the guide from scratch is required.

- Added many new screenshots and replaced outdated ones.
- Many instructions were similarly added or updated.
- Links now directly lead to the mod page's file section.
- Vanilla artifacts overhauled with a combination of three different mods.
- Fully integrated the highly requested Interesting NPCs.
- Expanded the Customisation section with multiple new categories.
- Removed Cutting Room Floor. It is not worth the gazillion patches it requires.
- Added an automated patcher to fix bugs in the XPMSSE scripts.
- Replaced Container and Levelled List Fixes with our own, custom loot overhaul.
- Major new additions:
  - Adamant - A Perk Overhaul
  - AI Overhaul SSE
  - Morrowloot Miscellania - Hybrid Loot
  - Reliquary of Myth - Artifact Overhaul
  - Interesting NPCs (3DNPC)
  - All Geared Up Derivative

#### Setup

- **3.6:** Split up instructions into two parts.
- **3.6.1:** Changed instructions, we are now unpacking the Vanilla scripts as we will need them later.
- **4.2.1:** Added Mod Order Fix section (correcting DLC mod order).
- **4.2.2:** Added instructions for three small changes in the MO2 settings.
- **4.5.1:** Added instructions to set the Default profile to use vanilla INIs and save games.
- **4.6.1:** Updated instructions for the latest version of Deorder's MO2 plugins.
- **4.6.1:** Re-added instructions to install Deorder's Sync Mod Order plugin since it appears to have been fixed.
- **4.6.2:** Added instructions to change the hide type for Deorder's Hide Merged Plugins.
- **6.3.4:** Removed Shadow Bias INI tweak.
- **6.3.6:** Contrast can now be tweaked in the Visuals tab, instructions were changed accordingly.
- **7.1.3:** Added instructions for the -DontCache argument to fix a bug.
- **8.4:** Added section with instructions to revert the deletion of a navmesh in Update ESM.
- Moved the Mod Installation Instructions to Setup, Step 10.
- Moved "Step 5 - Skyrim Realistic Overhaul" from the Mod Installation section to the Setup as Step 9.

#### Mod Installation

- Removed Havok Fix (replaced with SSE Display Tweaks).
- Removed Cutting Room Floor.
- Removed Multiple Floors Sandboxing (it can be toggled in the NFF MCM).
- Removed Sovngarde - Mist's Font Replacer (it was added to the new Interface Customisation section).
- Removed SkyUI - Flashing Savegame Fix (included in Remove QuickSave Button from SkyUI Systems Menu).
- Removed Extended UI. People constantly missed instructions to delete the BSA plus it seems a little buggy at times.
- Removed Cutting Room Floor - Lighting Overhaul.
- Removed Enhanced Landscapes - Solstheim 3D Trees (moved to the 3D Tree LOD Customisation section)
- Removed MD's Alternate Farmhouse Textures (replaced by newer version).
- Removed Trifle from Hiro - Solitude Gate (moved to Retextures Customisation section).
- Removed Real 3D Walls (doesn't blend well with other retextures).
- Removed Smithing Perk Overhaul (replaced by Adamant).
- Removed Spider Webs and Particles for ENB.
- Removed ElSopa HD - Meridia's Beacon (replaced with Meridia's Luxon Beacon Replacer).
- Removed HD Sabre Cat Tooth Mesh and Texture (included in HD Meshes and Textures for Animal and Creature Drops).
- Removed The Divine Amulets Retexture - Dragonborn Amulets (in favour of RUSTIC AMULETS).
- Removed Better Looking Amulets (in favour of RUSTIC AMULETS).
- Removed ElSopa HD - Akatosh Amulet (in favour of RUSTIC AMULETS).
- Removed ElSopa HD - Bonehawk Amulet (in favour of RUSTIC AMULETS).
- Removed Fangs and Eyes - A Vampire Appearance Mod (replaced with standalone version of the TRI files we need).
- Removed Encounter Zones Reborn (replaced with Arena - An Encounter Zone Overhaul).
- Removed College of Winterhold - Missing Apprentices Fix (requires Cutting Room Floor which was removed).
- Removed Container and Levelled List Fixes - Complete Loot Overhaul.
- Removed Lock Related Loot.
- Removed Helarchen Creek (moved to Customisation).
- Removed Telengard (moved to Customisation).
- Removed Keld-Nar (moved to Customisation).
- Removed Oakwood (moved to Customisation).
- Removed The Fall of Granite Hill (moved to Customisation).
- Removed Immersive Patrols - Plugin Replacer (replaced with Immersive Patrols Simplified).
- Removed Beast Skeletons (Bitter Edition) (replaced with custom replacer plugin).
- Removed AMB Content Addon Fixes (replaced with a scratch-made replacer plugin of our own).
- Removed Cloaks of Skyrim (they just look ugly).
- Removed Cloaks of Skyrim - MLU-Friendly Fixes.
- Removed Cloaks of the Nords.
- Removed Rally's Five Cities Cloaks.
- Removed Morrowloot Miscellania - Ancient Nord Hero Weapons (similar functionality included in Hybrid Loot).
- Moved Step 5 - Skyrim Realistic Overhaul to Setup. Now the separator numbers align with the Steps.
- Moved Quality of Life Improvements below Immersion.
- Moved Reduced Glow FX from Step 7 to Step 8.
- Moved Fire Halo Remover from Step 7 to Step 8.
- Moved Subtle Wind FX from Step 7 to Step 8.
- Moved Ruins Clutter Improved from Step 15 to Step 5.
- Moved Ruins Clutter Improved - Fixes from Step 15 to Step 5.
- Moved Karstaag - The Frost King Reborn from Step 21 to Step 30.
- Moved Bring Meeko To Lod from Step 27 to Step 30.
- Moved Keeper Carcette Survives from Step 27 to Step 30.
- **Step 7:** Renamed from "Lighting & Visual FX" to "Lighting"
- **Step 8:** Renamed from "Combat & Spell FX" to "Visual FX"
- **Step 8:** Updated order of mods to reflect recent changes.
- **Step 9:** Updated order of mods for better overwrite order.
- **Step 10:** Renamed from "Trees & Plants" to "Flora"
- **Step 18:** Renamed from "Clothes & Jewelry" to "Clothes & Jewellery" (because apparently that's the British spelling).
- Swapped Steps 9 and 10 around (now: Step 9 Landscape, Step 10 Flora).
- Removed the entirety of the ENB Particle Lights step (all added to the ENBSeries Customisation section now).
- **1.4:** Added SSE Display Tweaks.
- **1.6:** Updated download instructions for Performance Optimised Textures.
- **2.6:** Updated FOMOD instructions for Skyrim Landscape and Water Fixes.
- **2.7:** Updated FOMOD instructions for Landscape Fixes For Grass Mods - Patches for Arthmoor's Mods.
- **2.8:** Updated download instructions for NARC Remade (file update).
- **2.8:** Added instructions to select The Forgotten City patch in the NARC FOMOD.
- **2.23:** Added Bug Fixes (the mod, by meh321).
- **3.2:** Changed FOMOD instructions for Dwemer Gates Don't Reset (using the Dwemer Only USSEP version now).
- **3.3:** Added Andrealphus' Gameplay Tweaks.
- **3.5:** Added Helgen Keep Bandit Chief Executioner.
- **3.10:** Re-added No NPC Greetings (to replace the previously removed To Your Face which is suspected of causing crashes).
- **3.12:** Added note to Random Encounter Tweaks about which parts of the mod are actually used.
- **3.16:** Updated instructions for Simply Smaller Wolves (removed CRF related instructions, added screenshots).
- **4.3:** Added Remove QuickSave Button from SkyUI Systems Menu.
- **4.5:** Added Favorite Things - Extended Favorites Menu for SkyUI.
- **4.10:** Updated FOMOD instructions for Undiscovered Means Unknown.
- **4.11:** Updated Download Instructions and added Additional Instructions for moreHUD (file update).
- **4.12:** Now downloading the regular (BSA-packed) version of moreHUD Inventory Edition.
- **4.14:** Added my personal preset for A Matter of Time.
- **5.5:** Updated FOMOD instructions for Ruins Clutter Improved (no longer installing two options).
- **5.5:** Removed additional instructions to delete files (no longer necessary).
- **5.8:** Added instructions for the new FOMOD for High Poly Project, and removed now obsolete Additional Instructions.
- **5.9:** Updated FOMOD instructions for aMidianBorn - Dragonborn DLC.
- **5.10:** Updated download instructions for CBBE.
- **7.6:** Changed FOMOD instructions for STAC to use the "Optimized" option for candles and prevent FPS drops.
- **8.1:** Updated download instructions and removed CTD warning for Frozen Electrocuted Combustion.
- **8.3:** Now using the full version of Enhanced Blood Textures.
- **8.13:** Added Glow Be Gone - Updated.
- **9.1:** Updated instructions for Majestic Mountains.
- **9.2:** Updated additional instructions for Cathedral Landscapes (deleting the entire textures\plants folder for Cath Plants).
- **9.3:** Added The Elder Scrolls - Veydosebrom.
- **9.4:** Added Cathedral Landscapes - Veydosebrom Swamp Grass Addon.
- **9.5:** Added Pfuscher's Rapid Rocks.
- **9.6:** Updated FOMOD instructions for Majestic Mountains - Northside (now selecting the Rapid Rocks option).
- **9.7:** Added instructions to Realistic Water Two to delete one mesh that should not be overwriting Rapid Rocks.
- **9.19:** Updated FOMOD instructions for Lanterns of Skyrim II (no longer selecting patches for some removed mods).
- **10.1:** Slightly changed FOMOD instructions for Enhanced Vanilla Trees (now using Lush Trees (small) and SFO Branches v4).
- **10.3:** Added Tree Bark in High Definition.
- **10.8:** Added Cathedral Plants.
- **10.9:** Added Realistic HD Mushrooms Remastered.
- **11.1:** Added MD's Farmhouses.
- **11.6:** Removed CAO processing instructions from RUSTIC MONUMENTS AND TOMBSTONES (optimisation not required).
- **11.7:** Added instructions to download the new, optional Blue Palace Floor file for HQ Solitude.
- **11.7:** Fixed file paths for files to be deleted from HQ Solitude.
- **11.19:** Updated download instructions for Soul Cairn HD (file update).
- **13.13:** Updated FOMOD instructions for Obscure's College of Winterhold and moved them here.
- **14.2:** Added Hall of the Dead - Stained Glass Windows.
- **15.1:** Updated Underground FOMOD instructions (no longer installing the Dwemer textures).
- **15.1:** Added instructions to remove certain files from Underground.
- **15.2:** Added instructions to remove certain files from Rudy HQ - Nordic Ruins.
- **15.3:** Added Ice Cave Parallax Improved.
- **15.11:** Re-added CC's Enhanced Ore Veins - Fixed Iron Ore Cubemap.
- **15.15:** Removed CAO processing instructions from Ancient Dwemer Metal (not actually required).
- **16.16:** Added instructions to merge main and optional files.
- **16.17:** Added instructions to merge main and optional files.
- **16.18:** Added Rally's Werewolf Totems.
- **16.19:** Added Meridia's Luxon Beacon Replacer.
- **17.5:** Added True Homecooked Meal.
- **17.6:** Added HD Meshes and Textures for Animal and Creature Drops.
- **17.7:** Removed instructions to download Hagraven Claw file (included in previous mod).
- **17.8:** Added Improved Dragonfly.
- **18.3:** Updated the FOMOD instructions for Gemling Queen Jewelry (merely updated to use the same logic as all others).
- **18.3:** Added a screenshot to the Additional Instructions section for Gemling Queen Jewelry.
- **18.5:** Added RUSTIC AMULETS.
- **19.2:** No longer installing the AMB Content Addon Patch with Practical Female Armors (will be installed separately later).
- **19.4:** Removed CAO processing instructions from AMB Armors (all processed meshes will be replaced by the SSE Patch).
- **19.4:** AMB Armors is no longer optional.
- **19.6:** Added instructions to remove the empty meshes folder for AMB Weapons.
- **19.8:** Updated FOMOD instructions for LeanWolf's Better-Shaped Weapons (file update).
- **19.13:** Removed instructions to download the Better-Shaped Weapons patch for Frankly HD Imperial Weapons and Armor.
- **19.13:** Added instructions to delete two conflicting meshes from Frankly HD Imperial Weapons and Armor.
- **19.26:** Replaced CAO processing instructions with SSE NIF Optimizer instructions for Dragon Priest Weapons Improved.
- **20.5:** Better Shrouded Armor - Ancient Replacer Only is no longer optional.
- **20.6:** Better Shrouded Armor - Ancient Replacer Only - Plugin Replacer is no longer optional.
- **23.1:** Simplified instructions for Vanilla NPCs Ruhmastered.
- **23.8:** Updated FOMOD instructions for Simple Children - Patches.
- **24.3:** Added Optimised Body Meshes for SkySight Skins.
- **24.10:** Added instructions to delete a normal map from Natural Eyes that overwrote Eye Normal Map Fix.
- **24.14:** Added Just Fangs From BVFE (to replace the full mod we used and butchered for the fang TRIs previously).
- **24.16:** Changed FOMOD instructions for Beards (selecting Vanilla Only instead of Full).
  - The "full" version adds some braided beards that were clearly cut for a reason from the vanilla game. Most of them look strange. One of the braids has some transparency issues.
- **25.2:** Added Adamant - A Perk Overhaul.
- **25.4:** Added Complete Crafting Overhaul Remastered - JS Circlet Replacer Patch.
- **26.1:** Added AI Overhaul.
- **26.2:** Added AI Overhaul - Windsong Immersive Character Overhaul Patch.
- **26.3:** Added AI Overhaul - Ethereal Elven Overhaul Patch.
- **26.4:** Updated instructions for Relationship Dialogue Overhaul (CRF Patch is no longer needed).
- **26.6:** The Autorun.txt is located in the Text Files tab, not the INI Files tab (fixed typo).
- **26.6:** Fixed customisation instructions (console command syntax) for Guard Dialogue Overhaul.
- **26.9:** Added Hunters Not Bandits.
- **26.10:** Added Thugs Not Assassins.
- **26.10:** Updated FOMOD instructions for Nether's Follower Framework (now selecting the Interesting NPCs Patch).
- **27.2:** Updated FOMOD instructions for Even Better Quest Objectives (selecting the BCS Patch, skipping CRF Patch).
- **27.5:** Added Save the Icerunner - Lights Out Alternate Routes.
- **27.15:** Updated FOMOD instructions for Finding Velehk Sain (no selecting College Apprentices Fix option).
- **28.3:** Added Arena - An Encounter Zone Overhaul.
- **29.1:** Added Morrowloot Miscellania - Hybrid Loot.
- **29.3:** Added Morrowloot Miscellania - Dremora Bound Weapons.
- **29.10:** Added Reliquary of Myth - Artifact Overhaul
- **29.11:** Re-added Zim's Artifacts (not using all modules).
- **29.12:** Added Unique Items Tweaks - Improved Less Known Artifacts.
- **31.4:** Added Bounty Preview.
- **31.10:** Added additional instructions to Copy and Paste in Console.
- **33.3:** Added Interesting NPCs.
- **33.3:** Added Interesting NPCs - Zora Fair-Child Voice Enhanced.
- **33.4:** Added Cuyima - Interesting NPCs.
- **33.6:** Added missing FOMOD instructions for Immersive College NPCs.
- **33.8:** Added Morrowloot Ultimate - INIGO Patch.
- **34.1:** Updated download instructions for Immersive Patrols (now using the new Lite version without warzones).
- **34.2:** Added Immersive Patrols Simplified.
- **34.4:** Added numbers to the overview picture for the DWC Player Werewolf Replacer FOMOD.
- **34.10:** Added Beast Skeletons - Plugin Replacer.
- **35.4:** Updated AMB Content Addon (LE version) instructions.
- **35.5:** Added aMidianBorn Content Addon - SSE Port.
- **35.6:** Added Practical Female Armors - aMidianBorn Content Addon as a separate file.
- **36.6:** Added Choose Your Own Arch-Mage.
- **37.1:** Added instructions to download the Enhanced Blood Textures patch for Audio Overhaul Skyrim.
- **38.1:** ENB Light is no longer optional.
- **38.2:** Removed AOS+ENB Light+Mysticism patch (conflicts are resolved in the guide's CRP now).
- **39.3:** Added XPMSSE Fixes - Automated Patcher.
- **39.4:** Added All Geared Up Derivative - AllGUD.

#### Finalisation

- Moved FNIS instructions to Step 2.
- Added Step 3 for All Geared Up Derivative.
- Split the ENBSeries setup instructions into two steps (4 and 5).
- Expanded Step 7 a little (the ingame testing section).
- Clarified instructions in Step 4 (mod order and waiting for scripts to finish before closing xEdit).
- **1.1:** Moved FOMOD instructions for Obscure's College of Winterhold to the mod's instructions.
- **1.1:** Expanded and updated FOMOD instructions for Misc College of Winterhold Tweaks.
- **1.5.2:** Updated and expanded list of plugins that should be ESL-ified.
- **5.4:** Added installation instructions for the performance-friendly The Truth ENB preset.
- **6.3:** Removed change to texture compression in TexGen.
- **6.4:** Clarified instructions on where to place TexGen Output in the mod order.
- **6.6:** Users now need to choose between the three profiles in DynDOLOD. Updated the screenshot.
- **6.7:** Updated recommendations to rename the Output mod folder.

#### Customisation

- Basically re-did this section and expanded it at least with WIP directories.
- Updated list of of rougeshot's skeleton replacers.
- Added several new Interface related sections.
- Added Tree Tweaks section.
- Added Arthmoor's New Towns section.

#### New Game

- Split up instructions.
- Moved ENB Shader Cache instructions to Step 1.
- Instructions to turn down the DOF slider ingame were moved to the Finalisation.
- Add / updated MCM recommendations for multiple mods:
  - All Geared Up Derivative
  - Complete Crafting Overhaul Remastered
  - moreHUD
  - Realistic Water Two
  - Relationship Dialogue Overhaul
- Added more screenshots.
- Removed recommended change for the Lanterns of Skyrim II MCM.
  - We previously changed the script to check only every 60s instead of every 5s whether the lanterns are on and what time of day it is but with the Always On option, the script shouldn't check in the first place (since lanterns aren't disabled during the day.)
