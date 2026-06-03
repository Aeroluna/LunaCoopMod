# Changelog

## 6/3/2026

- Increased Shield Battery starting energy from 50 to 100.
- Reduced Shield Battery maximum energy from 200 to 100.

Karax's Shield Batteries are unaffected.

- Increased Karax's Shield Battery starting energy from 50 to 200.

### Primal Ascension

- Added benign flag to bosses being healed by a crystal.
- Fixed an issue where Amon had the wrong Swarm Host variant.

## 6/2/2026

- Fixed an issue where Reavers could not path through force fields.
- Fixed an issue where Kerrigan's Expeditious Evolutions mastery reduced the time of Muscular Augments more than intended.
- Fixed an issue where Kerrigan's Expeditious Evolutions mastery affected Adaptive Talons more than intended.
- Fixed an issue where Kerrigan's Expeditious Evolutions mastery affected Seismic Spines more than intended.
- Fixed an issue where Amon's Vipers did not cast abduct.
- Fixed an issue where Primal Mutalisk's Slicing Glaive weapon could bounce to the same target twice.
- Fixed an issue where Primal Mutalisk Chrysalis used the wrong wireframe.
- Fixed an issue where Ravasaurs could not damage friendly targets.

yeah.

- Increased the scale of Primal Mutalisk's projectiles by 30%.

Primal Mutalisks are about 30% larger than normal Mutalisks, so their projectiles have been scaled to match.

- Adjusted Ravasaur weapon projectile mover.

These projectiles flew crazy high against distant targets.

- Increased Oracle's Activate Pulsar Beam energy cost from 0 to 25.

Amon's Banshees cost 25 energy to activate Cloak, but it's free for Raynor. Why shouldn't it be the same for Vorazun's Oracles?

### Skyfall

- Added a final attack wave.
- Adjusted timings of small meteorite waves.
- Fixed an issue where giant meteorites did not have the "about to drop" warning on the minimap.
- Fixed an issue where the small meteorite aoe was not centered for giant meteorite waves.
- Separated the bonus objective into two and added timers.

### Death from Above

- Adjusted attack wave sizes.
- Adjusted attack wave spawn points.

Attack waves should be generally more difficult.

## 5/31/2026

- Fixed an issue where structures could be irradiated using the Supercritical Isotope upgrade.
- Added visual effects while the Drakken Laser Drill is under construction.
- Added VO when using Nova P4 abilities.
- Fixed an issue where Nova's Dash Attack did not ragdoll targets.
- Added VO when Stukov's P4 successfully triggers.

yeah.

- Fixed an issue where Abathur's Viper's Abduct ability had the wrong tooltip.
- Fixed an issue where Abathur's Viper's Abduct ability could not target Heroic units.

oopsies

### Skyfall

- Fixed an issue where player 1's expansion vespene geysers had the incorrect amount of resources.
- Fixed an issue where Amon had Nova's Ghost Academies instead of the normal Ghost Academies.
- Fixed an issue where the final Giant Meteorite wave didn't fall.
- Fixed an issue where the Giant Meteorite warning didn't play until the meteorite lands.
- Changed the allowed Giant Meteorites missed from 2 to 3 on Hard difficulty.

### Solar Right

- Fixed an issue where workers would sometimes return to the wrong node after returning.
- Increased the speed that Solarite generates near the final checkpoint.
- Added a minimap ping when the truck attacked warning plays.
- Increased the sound volume of transmissions.

### Death From Above

- Fixed an issue where the Mothership had infinite life regen.
- Fixed an issue where the Mothership was not an enemy with Amon.

what am i even doing

## 5/30/2026

- Fixed an issue where Supplicants could not be warped in from a Warp Gate.
- Fixed an issue where Brood Lords were not affected by attack speed changes.
- Fixed an issue where Hybrid Nemesis's weapon was not affected by attack speed changes.
- Fixed an issue where Mecha Battlecarrier Lords listed the wrong attack speed.

yeah.

- Changed Brood Lord's weapon tooltip attack count to 2.

Fun fact: For some reason Kerrigan's Brood Lords spawn two Broodlings at a time instead of one, doubling its DPS.

### Skyfall

- Fixed an issue where Giant Meteorites didn't fall.

I accidentally disabled them while debugging... I can't believe the main map objective has been broken for so long!

## 5/29/2026

- Fixed an issue where using the random commander selection would cause issues with the console skin.
- Reduced Interceptor attack priority from 20 to 19. (Attackers now prioritize other units over Interceptors)
- Fixed an issue where some units were missing ragdolls.
  - Affected units:
    - Primal Mutalisk
    - Primal Host
    - Mecha Drone
    - Mecha Overlord
    - Mecha Infestor
    - Mecha Lurker
    - Enthralled Mutalisk
    - Mecha Overseer
    - Enthralled Zergling
- Fixed an issue where P2's tooltip listed the wrong energy cost.
- Fixed an issue where Volatile Infested used the wrong icon/wireframe.
- Removed the voiceset from Carrier Repair Drones.
- Fixed an issue where Zealots would not ragdoll to certain effects.

yeah.

- Lowered subgroup priority of Enthralled Zerg.

They are uncommandable anyways, they shouldn't have higher priority than your real units.

- Added Archon Merge ability to Dark Templar.
- Added Shadow Stride ability to Dark Templar.
- Added Shadow Stride upgrade:
  - Amon will gain this upgrade after never/never/1200/900 seconds.
- Added Shadow Stride AI to Dark Templar.

These guys are pushovers anyways, give them Blink!

- Added Deploy Hellion Rangers to the Factory.

Nova can now directly deploy Hellions instead of Hellbats. I'm not sure why you would want to, but nothing wrong with having the option.

- Fixed an issue where many hotkeys were missing or conflicting.

The problem with using Grid hotkeys is you become completely oblivious to how badly you are screwing up all the hotkeys. Unfortunately, to make all the hotkeys play nice, some hotkeys had to be changed (Just use grid you psychos!).

- Reverted Infested Barracks rework.

I liked free Infested Marines, but the Corruption mechanic ended up more complicated than I liked, so it has been replaced with a lite rework.

- Reduced Infested Marine supply cost from 1 to 0.5.
- Reduced Infested Barrack's Spawn Infested Marine max charges from 10 to 5.
- Increased Infested Barrack's Spawn Infested Marine charge cooldown from 5 to 20.
- Changed Infested Barrack's Spawn Infested Marine to be autocastable.
- Reworked Stukov level 6 perk.
  - Now reduces cost of Infested Marine by 20% instead of increasing max charges.

These changes should make Infested Marines more spammable.

- Removed the weapon from Amon's Vipers.
- Changed the model for Amon's Vipers to the Versus model.
- Changed the model for Amon's Brood Lords to the Versus model.

Only commanders get cool campaign variants!

### Solar Right

- Removed enemy gatherers.

I really resisted removing mechanics from the original map, but these guys demanded way too much multi-tasking.

- Fixed an issue where Hybrid did not spawn.
- Fixed an issue where Gather Solarite command were canceled if the Solarite left vision.
- Removed delay before returning Solarite.
- Adjusted attack wave timings.
- Fixed an issue where some bullies were not disabled.

This map is my achilles heel.

## 5/21/2026

- Added a tooltip to the Destroyer's weapon that shows it ignores armor.
- Added a tooltip to the Drakken Laser Drill's weapon that shows it ignores armor.
- Fixed an issue where Drakken Laser Drill's weapon showed the wrong attack speed.
- Fixed an issue where Drakken Laser Drill wasn't affect by attack speed changes.
- Fixed an issue where Thor's ground weapon did not benefit from Advanced Optics after researching Multi-Lock Weapons System.
- Fixed an issue where Infested Colonist Compound upgrades listed the wrong amount of infested.
- Fixed an issue where Lurkers did not benefit from attack upgrades.
- Fixed an issue where Colossus-type units could walk through Havoc Force Fields.
- Fixed an issue where Liberators that are Abducted don't unsiege instantly.
- Fixed an issue where Blackhammers that are Abducted don't have their Overwatch Mode cancelled.
- Fixed an issue where Primal Impaler's Weapon used the wrong icon at level 0.
- Changed Shadow Guard voice set.
- Fixed an issue where Shadow Guard's Void Prison animation played erroneously.
- Fixed an issue where Vorazun's Dark Templar had the wrong Blink icon.
- Fixed an issue where Shadow Guard's Permanently Cloaked tooltip incorrectly stated they had increased shield regeneration while undetected.
- Fixed an issue where Shadow Guards did not have a kill display.

yeah.

- Changed Drakken Laser Drill model to campaign model.

The co-op model is weird and missing some visual effects on the attack and has some clipping issues on its build animation.

- Removed Detector passive from Choker.
- Removed Detector passive from Hunterling.
- Removed Detector passive from Kaboomer.
- Reduced Spotter's Glare movement speed buff from 100% increase to 50% increase.

Dear Blizzard, not every heroic unit needs to be a detector! Spotters still get to be detectors because they're Overseers, but let's bring their movement speed buff to a more reasonably level.

- Reduced the cooldown of Spec Ops Ghost's Snipe ability from 10 seconds to 15 seconds.
- Reduced the cooldown of Spec Ops Ghost's EMP Round ability from 10 seconds to 15 seconds.
- Reduced the cooldown of Marauder Commandos's Magrail Munitions ability from 10 seconds to 15 seconds.

These cooldowns are probably still way too low but they definitely need a nerf.

## 5/20/2026

- Added `-allyresources` command to enable showing ally resources.
  - Removed `-allysupply` command.
  - Has persistence.
- Added visual effect when Fenix's (Arbiter) Cloaking Field is active.
- Rewored Fenix's (Arbiter) Cloaking Field tooltip.
- Fixed an issue where Fenix (Arbiter) used incorrect voice lines when casting Stasis Field.
- Renamed Artanis's Mothership's Mass Recall to Mass Teleport.
- Fixed an issue where Arbiter's Stasis Field debuff had no tooltip.
- Fixed an issue where Colossus could not attack again until their current attack was finished.
- Fixed an issue where attack speed slows could cause Alarak's Mothership to not use Thermal Lance on cooldown.
- Fixed an issue where already created Spider Mines did not update their model after researching Cerberus Mines.
- Fixed an issue where Infested Banshees did not play a sound when enabling/disabling Cloak.

yeah.

- Fixed an issue where beam weapons were unaffected by attack speed changes.

Kinda insane that Blizzard never added a native way to make persistents be affected by attack speed.

- Reworked Infested Diamondback attack to beam instead of projectile.

It might have looked like a beam, but it was actually shooting an invisible projectile. For some reason it was still a channel though so attack speed changes didn't affect it. Seriously, Stukov's mech attack speed mastery didn't event work on Infested Diamondbacks!

- Changed Mothership's Time Warp ability color to red.
- Reworked Mothership's Time Warp ability to slow attack and movement speed of affected units by 40%.
- Added 1 second delay to Mothership's Time Warp ability.
- Reworked Mothership's Mass Recall ability to teleport targeted units to the Mothership.
- Reworked Mothership AI to more consistently cast Time Warp and to cast Mass Recall.
- Added chance for Motherships to appear in late-game skytoss comps.

When asking "why did they add that?", the answer is usually "cause it sounded interesting". With that being said, Motherships now randomly Mass Recall in random units on the map.

- Added new Zerg composition: "Raptor Brood"
  - A savage brood of Zerg evolved for relentless close-quarters assaults. Their swarms overwhelms defenses through sheer speed and ferocity.
  - Key Units:
    - Zergling
    - Baneling
    - Ultralisk
    - Viper (Hard+)

A new melee zerg composition! Zerg could use the variety.

- Added new Terran composition: "Steel Tempest"
  - This terrifying fusion combines the precision of Dominion covert operatives with the power of Terran's strongest mech.
  - Key Units:
    - Hellbat
    - Ghost
    - Siege Tank
    - Thor

The infamous Ghost mech composition, the horror of all ladder Zerg players.

### Emporer's Justice

- Increased total damage of Leviathan's Bio Stasis from 120 to 180.
- Increased the radius of Leviathan's Bio Stasis from 2 to 3.
- Reduced the duration of Leviathan's Bio Stasis from 8 seconds to 6 seconds.
- Added a timer to the primary objective.
- Added new objectives tracking the capital ship bosses.
- Increased time before bonus objective starts from 350 seconds to 400 seconds.
- Increased time to complete bonus objective from 390 seconds to 430 seconds.

## 5/11/2026

- Fixed an issue where repairing Swann's Siege Tank/Thor wreckages would give minerals if the mineral cost reduction mastery was taken.
- Fixed an issue where Amon's Science Vessels had the Supercritical Isotope button on their command card.
- Fixed an issue where Liberators (and variants) could cast Defender Mode up to 1 range farther than intended.
- Fixed an issue where Amon's Infested Siege Tanks had Zerg Flyer Carapace instead of Zerg Ground Carapace.
- Added a looping sound effect while Parasitic Bomb is active.

yeah.

- Added a looping sound effect while Infested Liberators are in Cloud Dispersal.
- Added a launch sound effect when Infested Liberators enter Cloud Dispersal.
- Added an impact visual effect when Infested Liberators deal damage with their AA attacks.
- Reworked Infested Liberator Cloud Dispersal attack logic.
- Fixed an issue where Infested Liberators could still deal Cloud Dispersal damage while in Defender Mode.

Some added flair to Infested Liberators.

- Changed Stukov P4 to remove negative debuffs after mind controlling a unit.
- Fixed an issue where Stukov P4 could mind control hallucinations.
- Reduced chance of Stukov P4 mind control from 100% to 25%.
- Increased supply cap with Stukov P4 from 100 to 150.
- Added 2 second 100% damage reduction to newly mind controlled units.

Kinda insane how I let this prestige be as OP as it is. The mind controlled units are now much harder to get, but in return, the supply nerf is cut in half. This should make the prestige less snowbally and make the mind controlled units add to your army instead of being the brunt of it.

- Removed the ability to mind control friendly units with Stukov P4.

As funny as it is, now that the mind control chance has been reduced, I don't like the idea of killing your ally's units hoping that you can steal one.

- Increased radius of Blackhammer Overwatch Mode by 50%.
- Changed Blackhammer Rank 1 bonus to "Overwatch Mode can target ground units."
- Changed Blackhammer Rank 2 bonus to "Increase Overwatch Mode radius by 33%."

Blackhammers feel like something you make one of for the aura and thats it. Improving their reliability should make them more appealing.

### Death from Above

- Fixed an issue where Artanis could not warp in Observers.

I have no idea why the original map even broke this in the first place.

- Fixed an issue where air units could activate the bonus objectives.

### Skyfall

- Fixed an issue where the "Gold Rush" mutator did not affect mineral fields.
- Fixed an issue where the loading screen was missing images.

The layout is still a mess and I don't really know why.

### Construction Yard

- Changed the "Do Not Allow APCs To Be Destroyed" to no longer decrease when a new APC is launched.

I was initially concerned with having to defend such a large area causing random APC losses, but realistically, this made it impossible to lose.

## 4/28/2026

- Fixed an issue where Snipe tracers would follow the target.
- Fixed an issue where Spec Ops Ghost's EMP Round ability was not affected by damage modifiers.
- Fixed an issue where issuing multiple move commands to a Banshee with a speed upgrade would cause the boost visual to spawn multiple times.

yeah.

- Reworked Nova P3:
  - Advantage: All units are cloaked and deal 50% increased damage. Units that are permanently cloaked gain Super Cloak instead.
  - Disadvantage: Attacking or using an offensive ability disables this effect and causes the unit to deal 25% reduced damage for 2 seconds.
  - Added Hold Fire ability to Nova instead of just being passive while cloaked.

I hated P3's design. It was very polarizing which maps/compositions it was useful against, i.e. some maps it would stomp defenses with zero risk, and on other maps it would do nothing but take away your early-game AOE. Even on maps where it was good, it was just super unfun to play with a P3 ally. Hopefully by making this prestige more army-focused, there is more depth with how to play while not sacrificing the original concept.

- Changed Nova's Sabotage Drone's model.
- Changed Nova's Sabotage Drone from flying to ground.
- Added birth visual effects to Nova's Sabotage Drone.
- Increased volume of Nova's Sabotage Drone detonation.
- Fixed an issue where Nova's Sabotage Drone's weapon incorrectly says it can target air.
- Fixed an issue where Nova's Sabotage Drone explosion visual effect could randomly be smaller.

Sabotage Drones looked so comically silly. Just this big stupid tube floating around. Now, they instead use the unused Shredder model.

- Changed P4 Dusk Wings to only autocast Cloak with at least 10 energy.

Fixes them strobing their cloak when out of energy.

- Added new map: Skyfall
  - Amon's fleet in high orbit keeps attacking Cybros with aerolites. You and your ally need to protect the ship until purifiers finish the emergency reboot of the core matrix. Use Solar crystals to activated shield generators, destroy the giant meteorites before they hit the ship.
  - Made by FroggyCatty.
  - Originally featured in RTC 2017.
  - Contains numerous fixes.

Can I take a moment to appreciate FroggyCatty? This map was already very polished and handled all the races/compositions. The assets were also uploaded separately so I didn't even have to reupload them. How was this not even top ten in 2017? If only all the RTC maps were this easy to modernize.

## 4/25/2026

- Changed Tempest's Destablizing Residuum to no longer be affected by Artanis P1.
- Fixed an issue where Reaver placement and warp-in were not scaled properly.
- Fixed an issue where High Templar Feedback was not affected by Artanis P1.
- Fixed an issue where units did not flee from Tempest's Destablizing Residuum.
- Reduced the damage of Tempest's Destablizing Residuum from 40 to 20.
- Reworked the map launcher to allow enabling/disabling entire categories.
- Fixed an issue where Vipers could Consume invulnerable structures.
- Added a max scale to Psi Storm impact visual effects.
- Fixed an issue where units under construction could trigger Han & Horner's Salvage.
- Fixed an issue where `-production` would still be active when it was suppose to be disabled.

yeah.

- Added a settings button in the minimap panel. Currently allows toggling UI commands.

graphic design is my passion. Seriously, I hate doing UI, but at least theres a way to toggle these without commands. May contain more settings in the future.

- Fixed an issue where Lurker spines would still fire at max range, even when their weapon range is reduced.
- Fixed an issue where Lurker spines did not go past 12 range, even if the weapons range is boosted somehow.
- Fixed an issue where Lurkers could not fire again until the previous spines were finished.
- Changed Lurker weapons to be disabled while unburrowed.
- Increased Amon Lurker damage from 20 to 20 (+10 vs Armored).
- Fixed an issue where Mecha Lurkers had no range indicator when burrowed.

Various Lurker fixes copied from Versus.

- Added new map: Death from Above.
  - Amon's forces have been deployed to the Tal'Darim outpost Trion IX, trying to corrupt the planet's large vespene supply. Assist Second Ascendant Zal'adas and escort the Tal'darim Mothership to ensure the Death Fleet has the resources needed for the reclamation of Aiur.
  - Made by CybrosX.
  - Originally featured in RTC 2017.
  - Contains numerous fixes.

Another map where only one enemy race was set up... This map didn't even use unit compositions properly, it was just hardcoded to spawn specific units!

### Construction Yard

- Added 1 mineral field to each expansion on Brutal.

Maps seem weirdly inconsistent on whether Brutal removes a mineral field from the expo or not. I decided to go with "if it's uncontested, remove a mineral field", so CY and PA do not get one removed.

### Primal Ascension

- Added 1 mineral field to each expansion on Brutal.

## 4/19/2026

- Fixed an issue where Wraiths had no banker.
- Fixed an issue where Wriaths/Void Rays that get targetd by Graviton Beam would have their actor detached from the unit.
- Fixed an issue where Fenix's Mass Recall did not work.
- Fixed an issue where Night of the Living special infested played ambience sounds.
- Fixed an issue where Night of the Living special infested did not use their ablities outside of Dead of Night.
- Fixed an issue where Nova's Assault Mode tooltip would incorrectly color appended mastery text.
- Fixed an issue where the `-aitech` debug command did not affect all enemies.
- Fixed an issue where using the Arbiter Recall ability while having Fenix in-game would play the Fenix Recall VO.
- Fixed an issue where a unit will lose its Abathur P4 Symbiote after finishing morphing.
- Fixed an issue where P4 Abathur could place Symbiotes on Larva.
- Added visual effects when a Symbiote is created using P4.
- Reduced the delay on Toxic Nest autocast slightly.
- Fixed an issue where the random commander select button was misaligned on non-16:9 aspect ratios.

yeah.

- Added Tissue Regeneration button to Mutalisks.
- Changed icon for Mutalisk's Rapid Regeneration upgrade.

Just to be clear, I did not change Mutalisk life regen, I just added back the button from Versus that tells you about it.

- Fixed an issue where Nova's Blink shield duration was paused while in stealth mode.
- Changed Stim Infusion to be disabled after entering stealth mode.
- Changed Apollo Cloak Suit to be disabled after entering assault mode.
- Reduced attack speed of Nova's Monomolecular Blade from 1 to 1.5.
- Reduced the damage of Nova's Monomolecular Blade from 120 to 100.
- Reduced the damage of Nova's Dash Attack from 100 to 50.
- Reduced the hit count of Nova's Fury of One from 11 to 9.

In hindsight, it was kinda insane how much I buffed the Monomolecular Blade over the campaign version. Now the gear should more closely align with the campaign version.

### Construction Yard

- Adjusted attack wave/APC timings.

Map should play faster, particularly around the final waves.

- Fixed an issue where certain bullies would not get disabled.

### Solar Right

- Changed workers to go back to gathering the same node after returning Solarite.

## 4/17/2026

- Added a random option to the commander selection screen.
- Fixed an issue where the player colors in the commander selection screen were inconsistent.
- Fixed an issue where the animation did not play for Kerrigan's Chrysalis.
- Fixed an issue where Kerrigan could not build Lurker Dens.
- Fixed an issue where the Teeming mutator would always attack with the newly created units.
- Fixed an issue where the Teeming mutator would copy invulnerable units.
- Fixed an issue where the checkboxes for Neutral/Positive/Negative mutators were not synced across players.
- Changed the icon for Stukov's P3.
- Fixed an issue where Mengsk's Sky Fury were missing a portrait.
- Fixed an issue where Zagara could not build Swarm Networks
- Fixed an issue where AI commanders did not have a Coop caster unit.
- Fixed an issue where Kerrigan's P1 did not increase attack speed or life regen.
- Fixed an issue where Banelings Spawns created from Splitterlings from Swarm Locus did not timeout.
- Fixed an issue where the challenge selection dropdown was not synced across players.

yeah.

- Added friendly fire to Amon.

Honestly, I just thought it would be funny.

- Reduced the rate of Hybrid Facility gaining Fissile Material stacks from the Hybrid Domestication mutator from one per 120 seconds to one per 180 seconds.

Too easy to fill your supply cap with Hybrid instead of your actual units.

- Reduced chance for a bounty from the Bounty Hunter mutator from 15% to 10%.
- Reduced resources gained from the Bounty Hunter mutator from 150/75 per supply to 100/50.
- Removed the ability for units with less than 1 supply to have a bounty from the Bounty Hunter mutator.
- Reduced healing of Thrill of the Kill from the Bounty Hunter mutator from 50% of max health to 20% of max health.
- Reduced attack/movement speed of Thrill of the Kill from the Bounty Hunter mutator from 30% to 20%.
- Increased damage of a Wanted unit from the Bounty Hunter mutator from 40% increased damage to 60% increased damage.

This mutator was unhinged with how much money and healing it gave.

- Removed the 50% increased Swarm Network units count from Zagara's P4.

Sorry free unit enjoyers, but it's just too strong! (And also laggy)

- Reworked Han & Horner P3 exclusive upgrade to allow changing to a different upgrade after researching one.

You'll still only be allowed one at a time, but if you get buyer's remorse then you can pay for a different upgrade instead.

- Reduced Valkyrie count of Ordnance Towers from 6 to 4.
- Increased cost of Ordnance Towers from 600/100 to 600/200
- Reduced attack speed of Ordnance Towers from 1.75 to 2.

I love these things but they are stupidly strong.

### Emperor's Justice

- Removed the ability for the ally AI to detect Changelings (No ignoring my new mutator!).
- Reduced the amount of Vikings the ally AI sends towards bosses.
- Fixed an issue where the bonus could still be completed after failing.
- Removed the Neosteel Armor upgrade from all ally AIs.
- Removed the Fortified Bunker upgrade from all ally AIs.
- Increased the time before the first Battlecruiser reinforcements from 11 minutes to 15 minutes.
- Increased the time before the second Battlecruiser reinforcements from 18 minutes to 21 minutes.

AI ally was too good at holding without players.

### Construction Yard

- Removed the ability for the ally AI to detect Changelings.

### Solar Rite

- Increased the amount of Solarite player workers can carry from 15 to 20.
- Increased the hit test scale of Solarite (should be easier to click).
- Changed Solarite to be visible through the Fog of War.

I know that increasing the carrying capacity isn't a perfect solution to the fact that collecting Solarite is kinda tedious, but it can't hurt.

## 4/15/2026

- Fixed an issue where Swann's P3 did not lower the cooldown of Hercules Tactical Jump.
- Fixed an issue where the P3 tooltip on Hercule's Rapid Deployment passive would always show regardless of prestige selected.
- Reworked Upgrade Resource Cost mastery to affect unit upgrades as well.
- Renamed Upgrade Resource Cost to Research Resource Cost.
- Removed ability for Mecha Hydralisk Dens to morph into Mecha Lurker Dens.
- Added ability for Mecha Drones to morph into Mecha Lurker Dens.
- Fixed an issue where units dropped from Mecha Overlords did not play an unload animation.
- Fixed an issue where Stetmann's structures did not play the zerg building sound.
- Fixed an issue where Ravager's Environmentally Unfriendly Eruption could target units.
- Fixed an issue where Mecha Zergling Synthetic Adrenal Pumps tooltip showed incorrect energy drain.
- Changed the visual missile of Contaminated Strike to be directional.

## 4/13/2026

- Increased cost of Void Archon's Maelstrom ability from 50 to 100.
- Fixed an issue where Ordnance Towers had different voicelines/portrait while constructing.
- Fixed an issue where Ordnance Towers did not play the proper placement sound.
- Fixed an issue where P4 Ordnance Towers could still send Strike Fighters while stunned or stasised.
- Fixed an issue where Han & Horners reapers were gaining more movement speed from Jet Pack Overdrive than intended.
- Reworded the tooltip of Supplicant's Blood Shields upgrade.

## 4/10/2026

- Added crater visual effects to Purifier Beam.
- Reworked Purifier Beam movement to be floatier.
- Reworked automatic movement of Purifier Beam.
- Fixed an issue where Purifier Beam had no death animation.
- Fixed a bug with Karax's Solar Effiency upgrades that was granting way more energy than intended.
- Removed upgrade requirement from Science Vessel's Defensive Matrix ability.
- Added Supercritical Isotope upgrade at the Starport Tech Lab.
  - Allows Science Vessels to cast Irradiate and Defensive Matrix in an area of effect.
- Fixed an issue where Science Vessel's Irradiate visual effect rotated with the unit.
- Seperated Irradiate into two different buffs to more easily differentiate between friendly and enemy casts.
- Changed voicelines for Ordnance Tower.
- Added new positive mutator: Hybrid Domestication
  - Players gain access to the Hybrid Facility, allowing them to train Hybrid of their own.
  - Costs -3 points for Brutal+.
- Fixed an issue where Hybrid Reaver's Consume Essence did not play a spell animation.
- Added a warp-in effect for Hybrid.
- Fixed an issue where Hybrid Behemoth's Slimed! debuff had no tooltip.
- Fixed an issue where Hybrid Destroyer's Graviton Prison did not play a spell animation.

## 4/7/2026

- Fixed an issue where the Terran building burn visual was not visible on Supply Depots built using Orbital Depots.
- Fixed an issue where Medic/Medivacs could not heal Mechanical units after researching Stablizer Medpacks.
- Reverted change that allowed some heal abilities to heal structures (I changed my mind, ok?)
- Removed ability for Medics to heal structures.
- Added new negative mutator: Imposters
  - Imposters are among your forces! Root them out before they call in reinforcements.
  - Costs 3 points for Brutal+.

## 4/5/2026

- Added new Medic ability: Signal Flare
  - Reveals an area of the map, detecting cloaked and burrowed units. Lasts 20 seconds.
- Fixed an issue where Swarmling's wireframe did not update after researching Metabolic Boost.
- Reduced visual scale of Emperor's Shadows by 14%.
- Reduced the radius of Emperor's Shadows from 0.5 to 0.375.
- Fixed an issue where Strike Fighter's Napalm Payload debuff used a non-button icon.
- Fixed an issue where Han & Horner's P4 could target invisible units.
- Added visual effects when Adept/Talis creates a shade.
- Changed Adept/Talis shades to spawns to spawn directly on top of the Adept instead of in front.
- Added a sound effect when Adept/Talis spawns a shade.
- Added a small animation on Adept/Talis when a shade is active.
- Fixed an issue where Lt. Nikara did not use a fake heal.

### Chain of Ascension

- Fixed an issue where Ji'nara had wrong beam attachments.

## 4/3/2026

- Updated news ticker.
- Fixed an issue where the Ultralisk Anabolic Synthesis upgrade visual was still visible while using Burrow Charge.
- Fixed an issue where some heal abilities could be able to heal unrepairable units.
- Fixed an issue where some heal abilities could be able to heal under construction units.
- Fixed an issue where some heal abilities could be unable to heal invulnerable units.
- Fixed an issue where some heal abilities could be unable to heal uncontrollable units.
- Fixed an issue where some heal abilities could be able to heal stasised units.
- Fixed an issue where some heal abilities would not fake cast on attacking units.
- Fixed an issue where some heroes did not display a rank.
- Fixed an issue where Queen's Transfusion ability could be cast on full health structures.
- Fixed an issue where Baneling Nests with Zagara P2 can still rally despite Spawn Banelings being disabled.
- Changed Reconstruction Beam to prioritize units and attacking structures.
- Added "Prototype Warrior" rank to Fenix's suits unit info panel.
- Added a crater visual to the Mothership's Planet Cracker ability.
- Fixed an issue where Artanis's Mothership attacks would keep attacking dead units.
- Fixed an issue where Artanis's Mothership attacks would kill all beams if any beam leashed.

### Chain of Ascension

- Fixed an issue where Alarak's rank changes to "Challenger" when playing Chain of Ascension.
- Removed rank display from Ji'nara/Amon's Champion.
- Removed health display from Ji'nara/Amon's Champion.

## 3/25/2026

- Added a difficulty select to the commander selection menu.
- Changed Kerrigan's Cocoon model to the Chrysalis from Zerus02.
- Renamed Kerrigan's Cocoon to Kerrigan's Chrysalis
- Increased the status bar offset for Nova's hero.
- Adjusted the pathing for units from the Harassment mutator.
- Adjusted AI for units from the Harassment mutator.
- Fixed an issue where the Harassment mutator was not scaling correctly.
- Fixed an issue where when Artanis cancels building a Warp Gate, it used the wrong death animation.
- Adjusted the animation for Reaver Scarabs.
- Fixed an issue where Reaver Scarabs did not count as a missile.
- Fixed an issue where Jinara's respawn beacon was not scaled properly.
- Fixed an issue where Nova's respawn beacon was not scaled properly.
- Fixed an issue where Alarak's respawn beacon was not scaled properly.
- Reduced Nova's scale slightly.
- Fixed an issue where Alarak/Fenix used the wrong Warp Gate death model.
- Fixed an issue where Alarak's Bane Blades showed attack count despite only having one attack.
- Fixed an issue where Alarak's Imposing Presence tooltip did not list Massive unit immunity.
- Reworked Teeming modifier.
  - Only increases units by 60% instead of double.
  - Now increases units from attack waves as well.
- Removed changes to `-ally` command (TIL `-share` exists).
- Changed `-test` to invoke `-share` instead of `-ally`.

### Construction Yard
- Adjusted attack wave timings.
- Changed corresponding camp bullies to immediately be deactivated when the APC leaves instead of when the camp is built.
- Fixed an issue where attack waves for the bonus objectives did not spawn when fighting Zerg compositions.
- Fixed an issue where the bonus intro transmission only played one line.

### Solar Right
- Increased time before bonus expires.

### Primal Ascension
- Changed bosses to stay revealed while waking up.
- Added behavior to suppress attack priority on bosses while being healed by a crystal.
- Changed Ash Worm health to scale with time (1600/2000/2600/3200).
- Changed Ash Worms to stay revealed while spawning.
- Removed permanent vision of bosses.
- Adjusted attack wave timings.
- Renamed boss debuffs.
- Fixed an issue where Void Crystals could be affected by knockback effects.
- Removed life regen from bosses/Ash Worms/Void Crystals.
- Reduced turning rate of Uldra.
- Fixed an issue where Ash Worms could be seen through the fog of war.
- Improved some Ash Worm visuals.
- Increased time for Ash Worm to burrow.

## 3/23/2026
- i guess i should have one of these
- HOPEFULLY THE LAUNCHER ISNT BROKEN NOW
