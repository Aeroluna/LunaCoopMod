# LunaMod

A collection of changes and additions to the StarCraft 2 Co-op mode. Maguro's Mutators mod is used as a base.

Changes include new prestiges, new units, new enemies, new maps, new mutators, balance changes, quality-of-life changes, and a huge amount of bug fixes.

NOTE: All times in Co-op use in-game time instead of real time e.g. if a tooltip says 10 seconds, that corresponds to ~7.14 real time seconds on Brutal/Faster.

### Table of Contents
<details>
<summary>Details</summary>

- [General](#general)
  - [Mutators](#mutators)
  - [Maps](#maps)
- [Commanders](#commanders)
  - [Amon](#amon)
  - [Raynor](#raynor)
  - [Kerrigan](#kerrigan)
  - [Artanis](#artanis)
  - [Swann](#swann)
  - [Zagara](#zagara)
  - [Vorazun](#vorazun)
  - [Karax](#karax)
  - [Abathur](#abathur)
  - [Alarak](#alarak)
  - [Nova](#nova)
  - [Stukov](#stukov)
  - [Dehaka](#dehaka)
  - [Han & Horner](#han--horner)
  - [Tychus](#tychus)
  - [Zeratul](#zeratul)
  - [Stetmann](#stetmann)
  - [Mengsk](#mengsk)
- [Credits](#credits)

</details>

## General

- Added ability to select a fourth prestige.

All commanders have an added fourth prestige, check their individual sections to see them. Some are very much overpowered, try them out!

- Added console skins for all commanders.
- Added voice packs for all commanders.

Some console skins were missing for commanders. Many commander have corresponding voice packs, why not use them?

- Added short descriptions for every commander on the commander selection screen.

Taken from starcraft2coop.com

- Buffed mind control effects to keep upgrades of targeted unit.

Who cares if it's OP? This affects Vorazun's Dark Archons, Karax's Sentries, Tychus's Vega, and Zeratul's Serdath Legion.

- Reordered many command cards to match Versus.

Help muscle memory from Versus for people who use grid hotkeys.

- Added Unload Heroic ability to Nydus Worms.

Implemented by [Maguro](https://www.maguro.one/2019/06/uiux-tweaks.html), this feature has been slightly improved to not show the ability if you have no Heroic units loaded.

- Fixed an issue where Protoss warp-in animations did not match up with the warp in progress.

For some reason, warp in animations had a fixed duration of 16 seconds, so it was broken for any unit that didn't take exactly 16 seconds to warp in. On a unrelated note, I'd like to complain about all the warp-in animations made in LotV. Why do half of them warp in from the top and the other half from the bottom???? They're suppose to always be from the bottom to match with the hexagon moving through the middle, but whichever artist worked on these models just *forgot* to flip the warp-in texture UV!

- Changed alignment of all neutral buffs to either positive or negative.

This changes causes all buffs to be tinted either green for positive buffs or red for negative buffs on the unit info panel. Previously many random buffs were set as neutral and weren't being tinted.

- Fixed an issue where many stun/slow effects could still affect units with the Frenzy passive.

It was very arbitrary which effects could or could not go through the Frenzy passive. Now it is more consistent.

- Removed snare immunity from commander Heroes.

This was applied weirdly where some heroes go it and others didn't. Heroes are OP anyways so who cares if they don't get slow immunity!

- Fixed an issue where only certain temporary units would be affected by commander buffs (i.e. Vorazun's Strike from the Shadows, Artanis's Guardian Shell, e.t.c.).
  - Affected units:
    - Spider Mine (Raynor/Nova)
    - Broodling (Kerrigan/Zagara/Abathur/Stukov)
    - Explosive Creeper (Dehaka)
    - Locust (Abathur/Dehaka)
    - Bio-Mechanical Repair Drone (Nova)
    - Infested Civilian (Stukov)
    - Infested Marine (Stukov)
    - Volatile Infested (Stukov)
    - Infested Trooper (Stukov)
    - Mecha Broodling (Stetmann)

It might be a little strong making all of the temporary units have Guardian Shell, but hey it's co-op, whats the harm in being OP?

- Changed Void Rays to "look" at their targets.

thanks Enoki.

- Added targeting beam to Widow Mine (and variants) attack.
- Increased visibility of Widow Mine attack targeting line and targeted unit (Targeted unit is tinted).
- Added a visual indicator to Colossus (and variants) attacks after Extended Thermal Lance is researched.
- Added a visual indicator to Phoenix (and variants) attacks after Anion Pulse Crystals is researched.
- Added a visual blue trail to Marauder (and variants) attacks after Concussive Shells is researched.
- Added a visual green effect to Hydralisk (and variants) attacks after Muscular Augments is researched.
- Added a visual red lazer sights when Mag-Field Accelerators is researched.
- Changed Cyclone's Lock On ability visual missiles to the large missiles from Versus.
- Increased Zealot (and variants) animation walk speed from 2.25 to 3 (Makes Zealots visually bounce around less at high movement speeds).
- Increased Infestor (and variants) animation walk speed from 1.875 to 2.25.
- Increased Hydralisk (and variants) animation walk speed from 2.086 to 2.6484.
- Increased Hydralisk (and variants) attack animation speed.
- Added turret tracking to Colossi (and variants).
- Fixed an issue where burrowing a Ravager directly after casting Corrosive Bile would visually bug.
- Changed town hall structures to automatically rally to a mineral field when built or landed.
- Added an AOE indicator to Disruptor's Purification Nova ability.
- Changed Protoss units AoE indicator to an updated version.
- Added pre-placement visual indicator and sound to Oracle's Stasis Ward ability.
- Added a very short cooldown to Stimpack to prevent rapid re-cast.
- Fixed an issue where Cyclone Lock-On projectiles would damage targets even if the target had escaped detection before impact.
- Fixed an issue where Guardian Shell would not affect units on a different cliff level.
- Increased Ultralisk (and variants) allied push priority from 0 to 1 (now pushes allied units out of the way when moving).
- Increased Mothership (and variants) allied push priority from 0 to 1.
- Reduced Archon (and variants) collision radius with structures from 0.75 to 0.56 (Does not affect collision with other units).
- Changed Burrow and Unburrow to use two separate buttons.
- Changed Burrowed and Unburrowed Zerg unit types to be on the same tab-select, and both will be selected when double clicking on units.
- Fixed an issue where Locusts spawned simultaneously would have perfectly synchronized animations rather than behaving like a swarm.
- Changed Disruptor Purification Nova ability to be cancelled and deal no damage if the Disruptor is stunned.
- Changed Orbital Command Scanner Sweep visual to use team color.
- Reduced visual scale of Disruptor by 9%.
- Increased Disruptor radius from 0.5 to 0.625.
- Changed the name of the Disruptor Purification Nova unit from "Disruptor" to "Purifier Orb".
- Fixed an issue where Disruptor Purification Nova unit showed a kill count.
- Fixed an issue where Disruptor Purification Novas would show life and shield in the unit info despite being invulnerable.
- Changed morphing to Overseer (and variants) to no longer require decelerating to cast.
- Changed Overseer (and variants) Oversight ability to no longer require decelerating to cast.
- Changed Observer (and variants) Surveillance Mode ability to no longer require decelerating to cast.
- Changed Viking (and variants) Assault Mode ability to no longer require decelerating to cast.
- Changed morphing to Brood Lord (and variants) to no longer require decelerating to cast.
- Increased Void Ray (and variants) movement speed from 2.25 to 2.75.
- Increased Reaper (and variants) movement speed from 2.9531 to 3.75.
- Changed undetected burrow move visual effects to be more visible.
- Changed Infested Swarm Egg model to an updated version.
- Reduced Infestor (and variants) radius from 0.75 to 0.625.
- Reduced Infestor (and variants) model scale from 0.85 to 0.75.
- Added Burrow Move passive icon to the Infestor's (and variants) command card.
- Increased visual scale of Cyclone's weapon missile by 100%.
- Changed mineral field/vespene geyser footprint to match Versus.
- Increased Ultralisk (and variants) armor from 1 to 2.

Copied from Versus.

- Fixed an issue where Phoenixs would not face their Graviton Beam target if they were attacking a unit when Graviton launched.
- Increased the arc of Phoenix Graviton Beam from 0 to 360 for commanders.
- Increased Lurker attack spine animation speed by 75%.
- Increased Lurker attack impact model scale by 75%.
- Removed variance in Lurker spine visual positioning.
- Fixed an issue where moving a Ravager directly after casting Corrosive Bile would visually keep the legs stationary and appear to glide.
- Changed Hi-Sec Auto Tracking to additionally visually increase the upgrade level on the unit info panel.
- Changed Phoenix weapon attack priority to attempt to keep hitting the same target.
- Added turret tracking to Hellions.
- Fixed an issue where Hellions would not play their attack animation.
- Reduced visual scale of High Templar's Psionic Storm ability.
- Increased visual scale of Psionic Storm impact effect.
- Added Disruptor tint when firing and when on cooldown.
- Fixed an issue causing Liberators to first decelerate when ordered to siege within their range.
- Removed Blinding/Disabling Cloud impact visual from Nexuses (They don't even have a weapon anymore!).
- Increased visibility of Blinding/Disabling Cloud impact visual on Planetaries.
- Fixed an impactful balance issue where Motherships were not playing their coolest available visual animation while constructing. This is intended to buff Protoss visually.
- Added smooth visual turning animations to Reapers, Hellions, and Cyclones. Reapers also hover further off the ground.
- Fixed an issue where Dark Templar attack sounds would complete regardless of whether a unit had been dealt damage.
- Increased allied push priority for Thors and Siege Tanks. Intended to assist bulky units in pathfinding when surrounded by many small friendly units.
- Fixed an issue where Reaper's rapid regeneration model would persist above its transport.
- Fixed an issue where Siege Tank impact fire model would persist above its target's transport.
- Fixed an issue where Siege Tank impact craters would disappear and reappear if the target was picked up/dropped out of a transport.
- Fixed an issue where KD-8 Charge knockback animation would persist on units that were no longer being knocked back.
- Fixed an issue where visual effects from some abilities could not be seen even when large portions of the model were well within vision range (Guardian Shield, Microbial Shroud).
- Fixed an issue where visual effects from some abilities could be seen through the fog of war (Parasitic Bomb, Stimpack).
- Fixed an issue where Liberators (and variants) couldn't designate an attack target while morphing from AA to AG.

thanks OmniSkeptic.

- Added a visual glaze to units targeted by a Science Vessel's Irradiate ability.
- Added an impact visual for Ravager's Corrosive Bile.
- Added visual Snow glaze effect to units on snowy maps (Void Launch).
- Added a visual effect and sound effect when Salvaging structures.
- Added cosmetic flame jets to Vultures when moving.

It just looks nice c:

- Reduced Cyclone life from 200 to 120.
- Increased movement speed of Cyclone from 2.8125 to 3.375.
- Reduced Cyclone's Lock On missile damage from 25 to 20 (Total reduced from 500 to 400).
- Reduced Lock On with Mag-Field Accelerators missle damage from 40 to 30 (Total reduced from 1000 to 600).
- Changed Lock On missile damage from ranged damage to spell damage (No longer affected by armor).
- Changed Lock On autocast to prioritize air units that threaten the Cyclone.
- Increased Lock On autocast range from 7 to 7.5 (Ability is still cast at 7 range).
- Increased dummy weapon range while channeling Lock On (Cyclones will stand farther back when attack moved).

Parity with Versus Cyclones. Not sure why Co-op changed the Lock On ability so much. This change affects Swann.

- Increased Infested Swarm Egg life from 70 to 75.
- Added Biological tag to Infested Swarm Egg.
- Changed Infested Swarm Egg to be selected with Select Army Units.

Copied from Versus. Biological added and a slight health increase to compensate.

- Added Shield Batteries to Artanis, Vorazun, Alarak, and Fenix.
- Increased Shield Battery range by 2.

If it's good enough for Versus, it's good enough for all the Commanders! Karax's are still superior.

- Removed Armored attribute from Queens.
- Added autocast for Queen's Transfusion.

Queens typically aren't built, so some buffs help. Won't cast efficiently but does help if you are overcapping energy anyways.

- Fixed an issue where Carriers would not show how many Interceptors they have under their healthbar (Affects Karax and Fenix).

Fun fact: This bug has existed since Fenix was released. This bug was caused by the ability for Carriers to morph into Clolarion, though I genuinely don't understand why it happens or why it affects Karax's Carriers.

- Increased visual scale of Planetary Fortress's attack impact by 20%.
- Increased sound volume of Planetary Fortress's attack.

Weirdly quiet for how impactful this thing's weapon is.

- Increased Wraith (and variants) sight radius from 8 to 10.

I'm not sure why Blizzard made Wraiths have a sight radius lower than any other air unit, but now it's been increased to match others.

- Increased sound volume of Battlecruiser Tactical Jump ability.

Not sure why this ability had its volume nerfed in co-op.

- Removed hit test from High Templar (and variants) trail (Can no longer be clicked).

If you've ever wondered how you boxed that High Templar you didn't mean to, this is probably why.

- Removed model scale variance from Zerglings.
- Removed model scale variance from Roaches.
- Removed model scale variance from Banelings.
- Removed model scale variance from Mutalisks.

Fun fact: the WOL campaign randomizes these model scales for some reason.

- Added 4 second duplicate wait for hero Yes/Attack lines.

This is how long after a sound is played before another is allowed to play. Can be nice for commonly selected heroes so that they don't spam their voice lines too much. This already existed on some heroes like Alarak/Kerrigan.

- Fixed an issue where multiple units collided with Colossi when they shouldn't have.
  - Affected units:
    - Ultralisk
    - Primal Ultralisk
    - Kerrigan
    - Nova
    - Zagara
    - Blackhammer

Why couldn't Colossi walk over Nova?

- Fixed an issue where various commander-specific upgrades appeared on the command card of Amon's units.
- Fixed an issue where all Zerg building construction sounds would use Stetmann's Mecha variants.
- Fixed an issue where the Infested Swarm Eggs "popping" animation was not playing.
- Fixed an issue where unburrowing effects (e.g. Viper Abduct, Phoenix Graviton Beam) would not unburrow most units.
- Added a range indicator when using the Oracle's Stasis Ward ability.
- Fixed an issue where Disruptor's Purification Nova ability was not affected by damage reduction/increase effects.
- Fixed an issue where Observer's Observation Mode did not play any sounds.
- Fixed an issue where the shield fizzle animation played on zerg units with shields.
- Fixed an issue where Banelings/Volatile Infested would show a buff for a moment before exploding.
- Fixed an issue where Void Shards/Void Slivers had the attack priority of attacking structures.
- Fixed an issue where Marine's Combat Shield passive had a missing tooltip.
- Fixed an issue where Corsair's Disruption Web ability affected invulnerable targets.
- Fixed an issue where Baneling's Explode ability tooltip showed a level.
- Fixed an issue where Arbiters could be affected by cloaking field abilities.
- Fixed an issue where Scourge's weapon would appear disabled in the unit info panel after enabling structure attacks.

yeah.

- Added `-slim` persistence.
  - If enabled, will be saved and automatically reenabled when playing again.
- Added `-production` command to enable the production panel.
  - Made by Kit.
  - Shows progress of current research/upgrades/buildings in production.
  - Has persistence.
- Added `-hotscd` command to enable the cursor cooldown notification from Heroes of the Storm.
  - Made by Parasite.
  - Has persistence.
- Added `-cdtext` command to enable the cooldown text on buttons.
  - Has persistence.

UI customization!

- Added `-test` cheat, combining `-fastbuild`, `-cdr`, `-vision`, `-ally`, `-allysupply`, `-control`, `-pai`, and `-maxsupply`.
- Added `-maxsupply` cheat, which maxes out supply.
- Fixed an issue where `-ally` cheat did not allow spending resources for the ally.
- Added `-aitech` cheat that unlocks all of Amon's timed upgrades instantly.
- Added `-poweroverwhelming X` cheat to add Power Overwhelming/P1 stacks to an Ascendant/Void Archon/mech unit.
- Added `-itsabouttime` cheat that uncaps Outlaws (See [Tychus's P4](#Tychus)).
- Fixed an issue where `-fastbuild` cheat did not affect certain research/upgrades.

Some debug cheats.

### Mutators

- Added Brutal+ system.
  - Can select a Brutal+ level to randomize mutators.
  - Can use refresh button to rerandomize.
  - Can use +Retry option to retry previously played mutators.
  - Added Brutal+ levels 7 - 10.

Added Brutal+ system.

| Difficulty | Min. Points | Max. Points | Min. Mutators | Max. Mutators |
| ---------- | ----------- | ----------- | ------------- | ------------- |
| 1          | 4           | 6           | 2             | 3             |
| 2          | 7           | 8           | 2             | 3             |
| 3          | 9           | 10          | 2             | 3             |
| 4          | 11          | 12          | 2             | 3             |
| 5          | 15          | 16          | 2             | 4             |
| 6          | 19          | 20          | 2             | 4             |
| 7*         | 21          | 22          | 2             | 4             |
| 8*         | 23          | 24          | 2             | 4             |
| 9*         | 25          | 26          | 2             | 5             |
| 10*        | 27          | 28          | 2             | 5             |

\* New difficulties

- Added Mutator alignments.
  - Mutators can either be Negative, Neutral, or Positive.
  - Negative mutators use regular Brutal+ system.
  - Can roll up to two Neutral or two Positive mutators (if enabled).

Now it's possible to roll some helpful mutators! Neutral mutators change the way you play without directly buffing Amon, typically these mutators will buff/debuff you and Amon equally. Positive mutators are straight buffs for you, but in return, they cost negative points, increasing the difficulty of rolled negative mutators.

- Added new negative mutator: Teeming
  - Enemies begin with twice as many units.
  - Costs 1 points for Brutal+.

Makes defensive positions more well defended. Unfortunately not very impactful on defensive maps like Temple of the Past.

- Added new negative mutator: Harassment
  - Enemies will periodically send units to harass player mineral lines.
  - Costs 7 points for Brutal+.

https://github.com/user-attachments/assets/edbf9777-2af3-4900-8ba8-28e4bcdfd038

Be prepared for Battlecruiers tactical jumping in, Nydus Worms popping up, and Dark Templar running through, just to name a few. Amon will send harassment units towards your minerals depending on the race you are up against.

- Added new neutral mutator: Whiteout
  - Adds snowy weather.
  - Occasional whiteouts obscure the battlefield.
  - Slows all units movement speed by 20%.
  - Caps all unit sight radius to 6.
  - Disables shared vision with ally.
  - Disables minimap objective pings.
  - Costs 1 point for Brutal+.

https://github.com/user-attachments/assets/e53dc858-632c-49ef-a309-b6624e74e0af

It's like the Darkness mutator but cooler!

- Added new neutral mutator: Ethereal
  - All spell damage is increased by 100%.
  - Non-spell damage is reduced by 50%.

Get your High Templar ready.

- Added new positive mutator: Gold Rush
  - Player starting resources are enriched for the first 10 minutes.
  - Minerals Fields are replaced with Rich Mineral Fields. (+5 per trip -> +7 per trip)
  - Vespene Geysers are replaced with Rich Vespene Geysers. (+4 per trip -> +6 per trip)
  - Costs -4 points for Brutal+.

Grants an initial boost to your starting economy.

- Added Lucky Envelopes to Brutal+ as a positive mutator costing -1 point.
- Added Gift Exchange to Brutal+ as a neutral mutator costing 0 points.
- Added Fireworks to Brutal+ as a negative mtuator costing 5 points.

Some holiday-exclusive mutators have been added to Brutal+ using the new alignment system.

- Added Infestation Station to Brutal+ costing 3 points.
- Added Great Wall to Brutal+ costing 5 points.
- Added Rip Field Generators to Brutal+ costing 5 points.
- Added Repulsive Field to Brutal+ costing 3 points.
- Added Mothership to Brutal+ costing 7 points.
- Added The Mist to Brutal+ costing 7 points.

Added Maguro mutators to Brutal+ system.

- Reworked Fatal Attraction to no longer make the units uncommandable.
  - No longer disables units attacks, abilities, and movement.
  - Pull strength increased by 20%.
  - Fixed an issue where Dehaka's Primal Impalers were pulled when burrowed.

The most infurating mutator because it can permastun your units as well as interrupt all their orders. The obnoxious stun has been removed and given stronger pull stength as compensation.

- Removed Micro Transaction from Brutal+.
- Removed Micro Transaction from Chaos Studios.

Not even a hard mutation, just SUPER unfun.

- Increased Slim Pickings points from 5 to 10.

Very crippling mutator so its cost has been increased. Unfortunately, doesn't help the fact that hero commanders are kinda unaffected.

- Removed invulnerability from unburrowed Spider Mines from the Minersweeper mutation.

 Raynor lost his invulnerable Spider Mines, but Minesweeper was overlooked.

- Removed Going Nuclear from Brutal+.
- Added Nuclear Mines to Brutal+ costing 3 points.

Replaces Going Nuclear with Nuclear Mines. Going Nuclear can be incredibly frustrating causing you to lose your entire army because you looked away for 2 seconds. Nuclear Mines keeps the scary nuclear explosions without needing constant attention.

- Nerfed Going Nuclear nuke effect to no longer reveal explosion area to Amon.
- Nerfed Nuclear Mines nuke effect to no longer reveal explosion area to Amon.
- Nerfed Mutually Assured Destruction nuke effect to no longer reveal explosion area to Amon.

No more getting revealed for walking in a nuke's area. Especially noticeably when combined with the Laser Drill mutation.

- Fixed an issue where Eminent Domain would cause Han & Horner's Assault Galleons to be unkillable.

yeah.

### Maps

- Added new map: Emperor's Justice
  - The Dominion Core World of Verdonna is under relentless siege. Link up with the Dominion Fleet and help Emporer Valerian defend the city's center.
  - Based on Nova08 "Dark Skies".
  - AI Terran ally will help defend.
  - Occasionally Amon will send a massive capital ship boss.
  - Amon will send periodic waves that get stronger over time.

It's like Temple of the Past but cooler. You can chose to either defend the low ground for the bonus objective or fall back to the high ground for a better position. The AI ally will constantly reinforce the defenses, but can't defend alone. Eventually you'll have to fight a capital ship boss to end the map.

- Added new map: Primal Ascension
  - Amon has corrupted the Primal Pack Ascendants of Zerus. They seek to drain Dehaka's eggs to become the new Primal Pack Leaders. Protect the eggs and slay the Primal Pack Ascendants.
  - Made by OutsiderXE.
  - Originally featured in RTC 2017.
  - Contains numerous fixes.

Boss fights!

## Commanders

### Amon

- Removed Viper Disabling Cloud ability.
- Added Viper Blinding Cloud ability.
- Removed Viper Consumption ability.
- Added Viper Consume ability.
- Increased Viper Abduct energy cost from 25 to 75.
- Added 0.8 second cast finish time to Abduct.
- Removed stun from Abduct.
- Improved Viper Abduct AI to pull siege units.

Is Disabling Cloud the most infurating spell to get hit by? Disabling Cloud and Consumption have been replaced with their Versus variants. Abathur Vipers are unaffected.

- Increased Brutal AI cooldown of Brood Queen's Ensnare from 0 seconds to 5 seconds.
- Fixed an issue where Brood Queens would try to Ensnare units it cannot affect such as structures.
- Buffed Spawn Broodling to allow targeting massive units (This only affects mind controlled Brood Queens).
- Reworked Spawn Broodling casting AI.
  - Will not be used on Normal difficulty and lower.
  - Added a 30 second cooldown.
  - Only targets units with less than 100 max hitpoints.

They explicitly target low health units because otherwise it would just be frustating getting your expensive units sniped without a counter. Fun fact: Spawn Broodling was previously only casted on Siege Tanks (Only Swann/Raynor).

- Removed Detector from Oracles.
- Added Revelation to Oracle.

Returned Revelation to Oracles and in return they lose permanent detection.

- Reduced Liberator's Defender Mode range from 9 to 5.
- Removed bonus sight radius from Defender Mode.
- Reduced Liberator anti-air damage from 7 to 5.
- Reduced Liberator anti-ground damge from 85 to 75.
- Added Advanced Ballistics upgrade:
  - Increases the range of Liberators in Defender Mode by 2.
  - Amon will gain this upgrade after never/never/1200/900 seconds.

Amon is smelly and gets Versus Liberators. Hopefully makes Shadow Tech less oppressive.

- Reverted Battlecruiser Tactical Jump to Versus version.

This includes adding a cast time, the 6 second wait, and some visual changes. This change pretty much only affects mind controlled Battlecruisers, but I needed it for the new Harassment mutator.

- Removed Reaper's D-8 Charge weapon.
- Reduced Reaper's P-45 Guass Pistol weapon damage from 4 (+5 vs Light) to 4.
- Increased Reaper's P-45 Guass Pistol range from 4.5 to 5.
- Increased Reaper's hitpoints from 50 to 60.
- Added Combat Drugs passive.
- Added KD8 Charge ability.

What the hell was Blizzard thinking giving Reapers their structure weapon back for Co-op? Overall the Reaper does less DPS but now they get to be funny with their grenade ability. Get wrecked Shadow Tech.

- Reduced Phoenix's Graviton Beam ability cooldown from 30 seconds to 0 seconds.
- Increased Phoenix's Graviton Beam ability energy cost from 0 to 50.
- Reworked Phoenix AI to try not to have all Phoenixes channeling Graviton Beam at the same time.

Why do Amon's Phoenixes have energy if their one ability doesn't even cost energy? Now EMPing them actually stops them from lifting.

- Changed Adept from Purifier model to Versus model.
- Reduced Adept hitpoints from 90 to 70.
- Reduced Adept shield from 90 to 70.
- Reduced cost from 125/50 to 100/25.
- Reduced Adept weapon range from 5 to 4.
- Reworked Adept weapon to no longer hit air.
- Changed Adept damage from 16 (+6 vs Light) to 10 (+12 vs Light).
- Renamed Adept weapon from Purifier Glaive Cannon to Glaive Cannon.
- Added Resonating Glaives upgrade for Adepts.
  - Increases attack speed by 45%.
  - Adept attacks will have orange projectiles after Resonating Glaives has been researched.
  - Amon will gain this upgrade after never/never/900/600 seconds.
- Reduced sight radius of Adept Shade from 9 to 4.

Nerfed Adept from its Campaign version to its Versus version, but in return it gets Resonating Glaives. It didn't really make sense that Amon had Purifier Adepts anyways.

- Increased Battlecruiser Yamato Cannon prep time from 1.5 seconds to 3 seconds.

For some reason Co-op halves this charge time, this change returns it to normal for Amon.

- Reduced Raven's Point Defense Drone duration from 180 seconds to 20 seconds.
- Reduced Raven's Auto-Turret duration from 180 seconds to 11 seconds.
- Reduced range of Raven's Build Auto-Turret from 3 to 2.
- Increased damage of Auto-Turret's 12mm Gauss Cannon from 8 to 18.
- Reduced Auto-Turret life from 150 to 100.
- Reduced Auto-Turret armor from 1 to 0.

Copied from Versus. Duration of Raven's summons massively reduced, and in return, auto-turret damage is greatly increased. It was a common problem that a Raven from an attack wave would place an Auto-Turret or Point Defense Drone and the map ping would not disappear until the unit timed out 3 minutes later.

- Increased Science Vessel Irradiate cost from 25 energy to 75 energy.
- Increased Science Vessel Defensive Matrix cost from 50 energy to 100 energy.
- Added a limit of 0/2/4/6 Science Vessels per wave.

A full energy Science Vessel could slam out 8 Irradiates before running OOM. A late-game Classic Mech wave would spawn around 8 Science Vessels. Thats 64 Irradiates straight to your face every wave. Increasing the energy cost and limiting Science Vessels should make it less obnoxious fighting Terran with a bio army.

- Added Prismatic Alignment ability to Void Rays.
  - Increases damage vs. armored units by +6 for 20 seconds.
  - Reduces movement speed by 25% while active.

Copied from Versus. Did you know Amon's Void Rays didn't even have a working passive to charge up their attacks? Now Amon will activate Prismatic Alignment against armored targets and will cancel it if there are no armored targets in range.

- Added Hyperflight Rotors upgrade for Banshees.
  - Increases movement speed from 2.75 to 3.75.
  - Banshees will have a boost visual after Hyperflight Rotors have been researched.
  - Amon will gain this upgrade after never/never/1200/900 seconds.

fast banshees go nyoom.

- Reduced cast range of Infestor's Infested Terran ability from 9 to 8.
- Nerfed Infestor's Fungal Growth from a root to a 75% slow.
- Increased Infestor's Fungal Growth radius from 2 to 2.5.
- Reduced Infestor's Fungal Growth damage from 30 to 25.
- Buffed Infestor's Fungal Growth to no longer allow affected units to use Blink, Tactical Jump, or load into transports and buildings.
  - Blocks casting Blink effects for units like Stalkers, Dark Templar, and Zeratul.
  - Blocks casting Tactical Jump effects for units like Battlecruisers, Hercules, and Hyperion.
  - Blocks loading into transport, including Tychus's Medivacs.
- Increased Infestor starting energy from 50 to 75.
- Reduced Burrowed Infestor sight range from 10 to 8.
- Increased Infestor unburrow time from 0.357 - 0.714 seconds to 0.625 - 0.714 seconds.
- Added Neural Parasite ability to Infestor.
  - Amon will never cast this, but mind controlled Infestors can.
- Removed Consumption ability from the infestor.
- Added burrowing AI.
  - Infestors in attack waves will attempt to burrow.
  - Will spawn Infested Terrans while burrowed.
  - Will unburrow to cast Fungal Growths.

Copied from Versus. Transforms Infestors into the sneaky burrowing spellcasters they were always meant to be.

- Reduced Roach Tunneling Claws speed bonus from 2.25 to 1.4.

Copied from Versus.

- Increased Locust duration from 18 seconds to 25 seconds.
- Increased Spawn Locust cooldown from 15 to 60 seconds.
- Reduced Locust life from 65 to 50.
- Reduced Locust attack damage from 12 to 10.
- Increased Flying Locust Swoop range from 4 to 6.
- Buffed Locusts spawned by the Swarm Host to Flying Locusts. Flying Locusts can use Swoop to land and attack.
- Reduced Swarm Host cost from 200/100 to 100/75.
- Limited Swarm Host count to 2/3/4/5 per wave.

Coped from Versus. Should make Swarm Host have a higher initial impact but less sustained poke. Fun fact: this also fixes a bug where the egg animation on their back took 60 seconds despite the cooldown being 15 seconds.

- Reduced cooldown of Disruptor's Purification Nova from 30 seconds to 24 seconds.
- Reduced damage of Disruptor's Purification Nova from 150 (+50 vs shields) to 100 (+100 vs shields).
- Reworked Disruptor AI to use Purification Nova more aggressively.

Disruptors are kinda lame.

- Nerfed Widow mines by making them revealed while Sentinel Missile is on cooldown.
- Added Drilling Claws upgrade:
  - Allows Widow Mines to burrow, unborrow and activate two times as fast.
  - Additionally this grants invisibility while reloading.
  - Amon will gain this upgrade after never/never/900/720 seconds.
- Added Anabolic Synthesis upgrade:
  - Increases the movement speed of Ultralisks off creep.
  - Amon will gain this upgrade after never/never/1200/900 seconds.
- Added Seismic Spines upgrade:
  - Increases the range of Lurkers by 2.
  - Amon will gain this upgrade after never/never/1200/900 seconds.
- Added Adaptive Talons upgrade:
  - Increases the burrow speed of Lurkers.
  - Amon will gain this upgrade after never/never/1300/1000 seconds.
- Added Anion Pulse-Crystals upgrade:
  - Increases the range of Phoenixes by 2.
  - Amon will gain this upgrade after never/never/1200/900 seconds.
- Added Smart Servos upgrade:
  - Allows Hellions, Hellbats, Vikings, and Thors to transform quickly between combat modes.
  - Amon will gain this upgrade after never/never/900/720 seconds.
- Added Hi-Sec Auto Tracking upgrade:
  - Adds +1 attack range to Auto-Turrets, Missile Turrets, and Planetary Fortresses.
  - Amon will gain this upgrade after never/never/900/720 seconds.
- Added Neosteel Armor upgrade:
  - Increases the armor of all Terran structures by 2.
  - Increases the cargo space of Bunkers by 2 and the load space of Command Centers and Planetary Fortresses by 5.
  - Amon will gain this upgrade after never/never/900/720 seconds.

Various fun upgrades copied from Versus given to Amon.

- Removed Science Vessels from the Raiding Party (BioMechStar) composition.
- Added Medivacs to the Raiding Party (BioMechStar) composition.
- Increased Marauder/Marine count in the Raiding Party (BioMechStar) composition.
- Reduced Siege Tank count in the Raiding Party (BioMechStar) composition.

Raiding Party is strikingly similar to Classic Infantry with how many Siege Tanks and Science Vessels there are. Reducing Siege Tanks, removing Science Vessels, and adding more Medivacs/Marines/Marauders should make it more distinct from the Classic Infantry composition as the "SC2 Bio" composition.

- Lowered Science Vessel count in T7 Machines of War (MechStarport) composition.
- Added Widow Mines to T7 Machines of War (MechStarport) composition.
- Added Hellbats to T7 Machines of War (MechStarport) composition.

Throw in some Hellbats/Widow Mines for some extra SC2 flavor for the mech composition. Also lower Science Vessel count cause they smell.

- Added new Terran composition: "Battle Mech"
  - Comprised of the fastest mech Terran has to offer, this force specializes in quick blitz attacks, capable of catching any unsuspecting victim off guard.
  - Key Units:
    - Hellion
    - Vulture
    - Cyclone
    - Banshee
- Added new Zerg composition: "Night of the Living"
  - In a twisted mix of Zerg and Terran, this force features the unfortunate victims of the Zerg Hyper-Evolutionary Virus.
  - Key Units:
    - Infested Marine
    - Infested Siege Tank
    - Special Infested (Kaboomer, Hunterling, Choker, Spotter)
    - Infestor (Hard+)

New compositions, new fights! Protoss has 8 compositions while Terran and Zerg only have 6 and 5 respectively, so more have been added.

- Fixed an issue where Infested Terran eggs used Stetmann's armor icon.
- Fixed an issue where Roaches created after Tunneling Claws was researched did not have the visual change.
- Fixed an issue where Hybrid Destroyer's Graviton Prison could target warping-in units.
- Fixed an issue where Hybrid Destroyer's Graviton Prison did not unburrow units.

yeah.

### Raynor

- Added P4: Mercenary Contractor
  - Advantage: Gain access to the Merc Compound.
    - A squad can be filled by hiring mercenaries. The squad can then be deployed, dropping all hired mercenaries at the rally point.
    - Mercenaries cannot be controlled after being deployed.
    - Mercenaries will wander the map with their squad, looking for enemies to fight.
    - Mercenaries benefit from all researched upgrades, don't forget them!
    - Dropped mercenaries benefit from drop pod haste mastery.
  - Disadvantage: Hyperion and Banshee Airstrike are unavailable.

https://github.com/user-attachments/assets/35807304-8824-42c5-bbbc-aaec11ad40cb

Introducing my legally-distinct-from-Nova mercenaries from the WoL campaign! These mercenaries will run around and do their own thing, sometimes running into their doom. In return, you get stronger units that can be bought instantly and deployed where you want them. For the disadvantage, you lose access to your powerful topbar and have to be more careful with your trades.

- Added Medivacs.
  - Heal more efficiently than Medics, but same heal speed.
  - Added Caduceus Reactor upgrade available at the Fusion Core, which doubles energy regen for Medivacs.
  - Stabilizer Medpacks also affect Medivacs.
  - Units unloaded benefit from the Drop Pod Haste mastery.
  - Can carry sieged Siege Tanks.
  - Have lower cooldown Ignite Afterburners (20 seconds).

https://github.com/user-attachments/assets/a4ac11e2-ed06-460d-a233-0a07f1d901ab

Medivacs are cool, what more needs to be said? The more efficient healing and increased energy regen can be very useful when paired with P1. Can also be useful to have a flying Medic when going Starport units. The Drop Pod haste along with the autocast stim allows for a fun strat of doom dropping.

- Increased Siege Tank (Sieged) cargo size from 4 to 8.

Necessary so Medivacs can only carry one Siege Tank. Unintentially nerfs Swann so this might need to be revisited.

- Buffed Ignite Afterburners to additionally increase acceleration by 1000.
- Added visual boost effect to Medivac and Banshee when using Ignite Afterburners.
- Removed the random delay on Battlecruiser weapons.
- Reworked P2.
  - Removed Ignite Afterburners cooldown.
  - Added autocast to Ignite Afterburners.

Copied from CXL. Stimmed Siege Tanks chew up attack waves and the properly working stimmed Battlecruisers just look comical.

- Added new Medic ability: Restoration.
  - Removes any negative debuffs on target allied unit.
  - Can remove Seeker Missile, Parasitic Bomb, and Irradiate.
- Increased Medic subgroup priority from 104 to 110.

https://github.com/user-attachments/assets/bf93ddc9-d981-41a3-834b-fe9878d93265

*I come to cleanse this land.* A niche ability that helps Raynor against spellcasters. Is also a powerful tool against the Black Death mutation. Gives Medics more depth than just an a-move unit.

- Added Cellular Reactor upgrade, which gives Medics full starting energy.

Anyone who has played P1 knows how painful it is to get energy on these things.

- Reduced Firebat weapon backswing and damage point.

Small change to make stutter-stepping with Firebats feel smoother. What mod doesn't do this?

- Added autocast to Stimpack.
  - Will autocast in Bunkers

Potentially too OP having units perfectly stim, but if Nova's marines can have it, why not Raynor?

- Added double MULEs.
- Added invulnerability to unburrowed spider mines.

Old Raynor nerfs reverted. Double MULEs in particular should help out P0 Raynor.

- Added behavior to Calldown MULE, will try to search for nearby mineral field to gather if not ordered directly.

Ever get annoyed when you *slightly* missed a mineral field and your MULE just AFKed? Does not affect MULEs dropped too far away from minerals.

- Buffed Viking Ripwave Missiles to additionally grant Gatling Cannons splash.
- Increased Viking Gatling Cannon damage from 12 to 12 (+8 vs Mechanical).
- Added faster transformation speed to Phobos Weapons System.

Some ground Viking buffs because why not.

- Reduced cost of Viking from 150/75 to 150/50.
  - Reduced from 150/60 to 150/40 with Raynor's level 1 perk.
  - Reduced from 225/42 to 225/28 with P3.

Due to MULEs, you end up floating WAY more minerals than gas. This price reduction makes it easier to mass Vikings.

- Reworked Hyperion weapons.
  - AOE attack turned into a proper weapon and is affected by buffs like attack speed.
  - Attack speed of single target and AOE weapon changed to 0.11.
  - Unit info shows single "ATX Laser Battery" weapon.
  - Will prioritize using AOE weapon unless issued attack order.
  - Removed random delay from weapon.
  - Reworked mover.

No longer have to queue a bunch of move commands to get value out of the Hyperion, it now gets full attack speed from just a-moving. Attack speed was slightly nerfed to 0.11 to adjust for Raynor's level 15 perk now properly affecting the weapon.

- Changed Hyperion portrait and sounds back to Horner.

Just because he's a commander now doesn't mean he forgot how to pilot the Hyperion!

- Swapped Hyperion command card placement of Yamato Cannon and Hyperjump.
- Changed Hyperion Hyperjump hotkey from Q to T.
- Added hotkey alias for Hyperion Yamato Cannon and Hyperjump to Battlecruiser Yamato Cannon and Tactical Jump respectively.

Changed Hyperion buttons to match Battlecruisers.

- Changed Vulture's Replenish Spider Mine ability to be autocast on intially.

I don't see why you wouldn't want this autocasting.

- Buffed Dusk Wing's Cloaking Field to grant +2 range, similar to the Banshee's Cloaking Field.
- Buffed Hyperion to be affected Mech Attack Speed mastery.
- Buffed Dusk Wing to be affected Mech Attack Speed mastery.
- Added Ignite Afterburners ability to Dusk Wings.

Added parity with non-calldown variants. Those are proud mech units, let them be buffed by mech attack speed!

- Merged Neosteel frame and Structure armor into Neosteel Armor.
  - Upgrades the armor of structures by 2. Increases the cargo space of Bunkers by 2. Also provides extra cargo space for Command Centers.
- Added Hi-Sec Auto Tracking upgrade.
  - Adds +1 range to Shrike Turrets, Missile Turrets, and Point Defense Drones.

Copied from Versus. Missile Turrets and Bunkers could certainly use the buff.

- Fixed an issue where Raynor's Battlecruisers did not visually aim their turrets at their target.
- Fixed an issue where Bunkers did not have Shrike Turrets in their icons.
- Fixed an issue where Bunkers used the Neosteel icon before upgrading Neosteel.
- Fixed an issue where the placement model for Bunkers did not change with the Neosteel upgrade.

yeah.

### Kerrigan

- Added P4: Brood War Sovereign
  - Replaces Kerrigan with Brood War Kerrigan
    - Uses Starcraft: Remastered themed skin.
    - Replaces Leaping Strike with Implosion.
      - Lifts unit, stunning for 3 seconds, before dropping and dealing high damage.
      - Stuns heroic units for 1 second instead.
      - Cannot be used against structures or unstoppable units.
    - Replaces Psionic Shift with Razor Swarm.
      - Does high damage over time in area.
      - Does double damage against structures.
    - Replaces Energy Blast weapon with a Psi Blast weapon.
      - Uses melee animation at short range.
    - Replaces Chain Reaction with Psionic Cleave.
      - Grants AOE damage to weapon attacks.
  - Replaces all combat units with elite Brood War variants that have 200% more life and 50% more weapon damage but cost 200% more resources and supply.
  - Replaces Zergling with Devouring One.
    - Gains Cannibalize passive.
      - Heals for 40 life when a biological unit dies nearby.
  - Replaces Queen with Brood Matron.
    - Gains Protective Brood passive.
      - Grants 3 life and energy regeneration to nearby friendly units.
  - Replaces Hydralisk with Hunter Killer.
    - Gains Envenomed Spines passive.
      - Attacks against units apply venom for 6 seconds, dealing 4 damage per second. This effect stacks up to 5 times.
  - Replaces Lurker with Grave Splitter.
    - Gains Burial Rites passive.
      - Increases the radius and size of each spine by 50%.
  - Replaces Ultralisk with Torrasque.
    - Improved Reincarnation passive.
      - Cocoon is now invulnerable.
  - Replaces Mutalisk with Scythewing.
    - Gains Sundering Glaive passive.
      - Attacks deal +6 vs. armored targets on the first hit.
  - Replaces Brood Lord with Primogenitor.
    - Improves Broodlings.
      - Broodlings have improved stats as well.
      - Lifetime increased by 200%.

https://github.com/user-attachments/assets/89d8bca5-117e-48df-8180-746f344edfa2

What if Nova's design met Kerrigan? Hunter Killers, Devouring Ones, and Torrasques return from Brood War with some new friends. Kerrigan has also been rebranded with a new Brood War themed skin, which is much better than the boob sacs and bone heels of SC2's design (Seriously, why did they try to make her sexy?).

Elite Zerglings are my personal favorite, their Cannibalize passive fits their name perfectly and greatly improves their survivability when fighting in packs, espescially when fighting bio armies. The Queen passive should help sustain the massive health pools of the new units. Mutalisks with extra damage massively benefit from their 2 glaive upgrades, and now that their one weakness, being squishy, has been mitigated, they are monsters. The improved Broodling lifetime sounds small at first, but it snowballs fast into a huge army of elite Broodlings.

- Added prestige tooltip to Malignant Creep when P1 is used.
- Reworked P1.
  - Advantage: Malignant Creep effectiveness increased by 100%. Creep Tumors gain Super Cloak when burrowed.
    - Queens can no longer place tumors off-creep.
    - Queens no longer move full speed off-creep.
  - Disadvantage: Combat unit off-creep movement speed reduced by 50%.
    - Affects air units.
    - Nydus and Omega Networks no longer unavailable.

Losing Omega Networks nerfed Kerrigan too hard. The new disadvantage and the lack of off-creep Queen buffs should be offset by having Omega Networks back. Additionally Creep Tumors were given Super Cloak to make them easier to manage.

- Buffed Malignant Creep to affect structures and air units.

Isn't it funny that vanilla P1 Kerrigan's best unit was Mutalisks? This should allow P1 to interact with more units.

- Increased Lurker burrow time from 2 seconds to 2.5 seconds.
- Added Lurker upgrade: Adaptive Talons.
  - Costs 100/100 and takes 80 seconds.
  - Researched at the Lurker Den.
  - Reduces Lurker burrow time from 2.5 to 1.5 seconds.
- Removed ability for Hydralisk Dens to morph into Lurker Dens.
- Added ability for Drones to morph into Lurker Dens.

Copied from Versus. Separating Lurker Den should make it easier to tech into Lurkers.

- Added Ultralisk upgrade: Anabolic Synthesis.
  - Costs 150/150 and takes 60 seconds.
  - Researched at the Ultralisk Cavern.
  - Increases Ultralisk movement speed off creep.

Copied from Versus. Speedy Ultralisks!

- Reduced Torrasque size to normal Ultralisk size.

Why are Torrasques bigger when they have the same stats as an Ultralisk?

- Buffed P2 to also hit structures.
  - Will prioritize units and attacking structures.

Now P2 Kerrigan doesn't look so sad trying to kill structures.

- Changed Ultralisk Tissue Assimilation upgrade to increase leech by 40% instead of healing a flat amount.

This allows the healing to scale with damage increase or damage reduction effects.

- Changed P3 voice lines.
- Changed P3 minimap icons.

Now uses the pre-infested assets from Heart of the Swarm.

- Fixed an issue where Kerrigan's Assimilation Aura would not affect invisible units (Cloaked and not detected).

Little silly that you need to detect the unit to affect it with an *aura*.

- Buffed Kerrigan's Leaping Strike ability to hit cloaked units.

Not sure why this was nerfed to not hit invisible units at some point.

- Fixed an issue where Kerrigan's Psionic Shift ability was affected by movement speed buffs/debuffs.

yeah.

### Artanis

- Added P4: Reclaimer
  - Advantage: Warped-in combat unit cost reduced by 50%.
  - Disadvantage: Combat units are recalled after 60 seconds, refunding 50% of their cost.

Makes units significantly cheaper at the cost of being unable to sustain an army. Units that die are *not* refunded. Pairs nicely with Artanis's warp haste mastery and increased High Templar starting energy upgrade. Be prepared to make *a lot* of gateways. Motherships and Observers are exempt from being recalled, use them to keep vision on the map for more warp-ins.

- Added the Mothership.
  - Available from the Nexus for 1000/1000 after building a Fleet Beacon.
  - Uses energy to cast abilities.
  - Can use Mass Recall ability for 50 energy.
    - Identical effect to Alarak's Mass Teleport.
  - Can use Vortex ability for 50 energy.
    - Similar to Wings of Liberty Vortex.
    - Enemy units no longer get invulnerability while leaving the vortex (Still stunned).
    - Friend units are no longer stunned while leaving the vortex (Still invulnerable).
    - Friendly heroic units are immune.
    - Deals up to 100 damage to enemy units within the Vortex.
    - Damage doubles with P1.
  - Can use Planet Cracker ability every 360 seconds.
    - Briefly charges up before scorching the ground beneath the Mothership for 20 seconds, causing 1200 (1800 vs Armored) damage in an area below. Deals more damage closer to the beam.
    - Damage doubles with P1.
  - Cloaks nearby friendly units
  - Provides a power field nearby.

https://github.com/user-attachments/assets/f4992063-79b8-434e-a611-e26110228b65

An iconic unit thats missing from co-op, is now back. Mass Recall should help with Artanis's mobility problems. Vortex no longer grants invulnerability to enemy units so Archon toilets are back on the menu. Planet Cracker is such an iconic ability, it had to be added. Projecting a constant power field stays in line with Artanis's design of quickly warping in reinforcements during combat.

- Changed Phoenix weapon damage from 7 (+5 vs Light) to 10 (+2 vs Light).
- Reduced Phoenix price from 150/100 to 150/50.

Phoenixs were extremely dependent on enemy composition. Moving some damage from the bonus should help. Also decreased the vespene price to make them easier to mass when going skytoss.

- Reduced duration of Tempest's Disintegration ability from 20 seconds to 10 seconds (total damage unchanged).
- Reduced cooldown of Tempest's Disintegration ability from 90 seconds to 60 seconds.

Disintegration buffs because this ability usually feels clunky. Cooldown reduced to match Yamato cooldown. Deals damage faster to keep up with the faster kill-time nature of co-op.

- Added Destabilizing Residuum upgrade at the Fleet Beacon.
  - Causes Tempest attacks to leave an AOE field that does 40 damage over 2 seconds.
  - Damage doubled by P2.

https://github.com/user-attachments/assets/1040fc83-a204-4160-b0c8-a2145324ee4c

These changes should make massing Tempests more viable. The new AOE upgrade makes Tempest shots still get value even if their target has already been killed by another Tempest first.

- Changed Tempest voice lines to Versus quotes.

Fun fact: Artanis' Tempests used the campaign Purifier Tempest quotes despite using the Versus model.

- Increased Guardian Shell Life and Shield Regeneration mastery from 0.5% per point to 1.5% per point, increasing max from 15% to 45%.

The Shield Overcharge mastery was so overwhelmingly better, this should help it be more competitive.

- Buffed P2.
  - Unnerfed energy cost from 25 to 10.
  - Increased Project Power Field radius from 6 to 8.

Buff an underperforming prestige.

- Buffed P1.
  - No longer increases vespene gas costs.
  - Combat units still cost 30% more minerals

Should help actually affording the high tech units with abilities like High Templar.

- Changed Warp Stargate model slightly.
- Fixed an issue where High Templar's Psionic Storm ability would no longer show an impact model after researching Plasma Surge.
- Fixed an issue where Shield Overcharge mastery listed its value as `+X Percent` instead of `+X%`.
- Fixed an issue where Feedback/Psionic Storm would only be casted by the selected subgroup when selecting both High Templar and Archons.
- Fixed an issue where Psionic Storms could stack after researching Plasma Surge.

yeah.

### Swann

- Added P4: Rolling Thunder
  - Advantage: Combat units can attack while moving.
    - Start with the Multi-Lock Weapons System upgrade.
    - Cyclones can use Lock On while moving.
    - Only Thor anti-air weapons can attack while moving.
    - Hellbats and Thor heavy air/ground weapons can only fire in an arc in front of them while moving.
  - Disadvantage: Hercules are unavailable. Turrets are 100% more expensive.

https://github.com/user-attachments/assets/d5aaaf7b-72f1-44d4-b1e5-9a86633034cb

Allows for fun playstyles like running around with battle mech or flying Wraiths around like Phoenixes.

- Added Thor's High Impact Payload mode from Versus for single-target long-range damage.
- Added a launch sound effect when shooting High Impact Payload weapon.
- Added a launch sound effect when channeling 330m Barrage Cannon.
- Buffed Multi-Lock Weapons System upgrade to additionally affect the Thor.
- Reduced 330m Barrage Cannon cast and finish time from 2 to 0.75.

https://github.com/user-attachments/assets/165a0113-4501-444b-8ecb-16451e5d9753

These changes should make Thors much more competitive.

- Buffed Infernal Plating upgrade to additionally increase Hellbat/Hellion life by 40.

Increased Hellion/Hellbat life should make mineral dumping into them more efficient and make them more viable as a frontline.

- Added Widow Mines.
  - Added Hellburst Payload upgrade, which increases Sentinel Missile direct damage by 20 and splash damage by 80.
  - Adds a visual red light on top after researching Hellburst Payload.
  - Cyclone's Targeting Optics upgrade additionally increases Sentinel Missile range by 3.

https://github.com/user-attachments/assets/ceab96c4-a010-4430-b91e-972672d985bc

Why not give the mech commander more mech? Widow Mines go well with Swann's defensive design. The Hellburst Payload massively improved splash damage can be absolutely devastating.

- Added Smart Servos upgrade, which increases the morph rate of Hellions, Hellbats, Thors, Siege Tanks, and Widow Mines.
- Added Overdrive Actuators upgrade at the Armory, which increases ground vehicle movement speed by 20% and ship movement speed by 10%.
- Added Pulse-Loop Capacitors upgrade at the Armory, which decreases all unit cooldowns by 40%.

These general improvements should make playing ground mech much smoother (Why does Raynor have fast Siege Tank morph speed but Swann doesn't?). Smart Servos helps deploying Widow Mines during combat, Overdrive Actuators helps playing battle mech (Hellion/Cyclone) much easier to kite with, and Pulse-Loop Capacitors helps Widow Mines and Cyclones deal more consistent damage.

- Added the ability to morph Orbital Commands that have access to Calldown: Extra Supplies and Scanner Sweep.

Scanner Sweeps should help Cyclones keep their Lock On active and provide detection without having to rely on the slow Science Vessels. Additionally, Calldown: Extra Supplies to help with the constant supply blocks on Swann.

- Added the ability to morph Planetary Fortresses.
  - Swann level 3 perk additionally upgrades Planetary Fortresses to Big Berthas, increasing damage and splash range.
  - Planetaries are considered turrets for all turret upgrades.

An iconic defensive Terran structure for the defensive Terran commander.

- Changed Planetary Fortress attack priority to "By Angle" instead of "By Distance".

Should make Planetaries spend less time spinning around randomly when surrounded.

- Added Commander Center Reactor passive from WoL Campaign.

It takes forever to eco up on Swann. Maybe now not so much.

- Added Dual-Fusion Welders passive from WoL Campaign.

The turret/mech commander gets more improvements to sustaining turrets/mech.

- Buffed P2.
  - Upgrades Fire Suppression System to heal structures to 100% life.

P2 suspiciously improved all upgrades but this one.

- Increased Wraith's Displacement Field evade chance from 20% to 30%.

Even with this upgrade, Wraiths are fragile. This should help improve their survivability.

- Merged Neosteel frame and Structure armor into Neosteel Armor.
  - Upgrades the armor of structures by 2. Also provides extra cargo space for Command Centers and Planetary Fortresses.

Copied from Versus.

- Changed Perdition Turrets to knockback units when unburrowing instead of being unable to unburrow.

Stops Perdition Turrets from being unable to attack when units are standing on top.

- Fixed an issue where Hi-Sec Auto Tracking upgrade tooltip listed wrong structures.
- Fixed an issue where Hi-Sec Auto Tracking used the hotkey B instead of H.

yeah.

### Zagara

- Added Swarm Networks.
  - Can summon Swarm Locus at a targeted location that will unload temporary units to fight.
  - Temporary zerg last 60 seconds, are uncontrollable, and attack closest enemies.
  - Queen will try to place Creep Tumor if no other Creep Tumors nearby.
  - Limited to 4.
- Changed Zagara's temporary units to visually burrow away instead of exploding when expiring.

https://github.com/user-attachments/assets/41ea50b6-0778-44a5-b480-a4bd74091235

If there is one think Stukov P3 has taught me, it's that throwing free units at Amon is fun as hell. The Creep Tumors also act as a form of creep spread that Zagara is lacking.

- Added P4: Subterranean Tide
  - Advantage: Swarm Networks are no longer capped, cost 25% less, and spawn 50% more units.
  - Disadvantage: Combat units cost 25% more. Swarm Networks cost 100 more minerals for every one built.

I added a whole new mechanic to Zagara and then created a whole prestige surrounding it. Hell yeah.

- Added Defilers.
  - Can use Dark Swarm ability for 100 energy.
    - Creates a micro-organism cloud preventing all incoming ranged and splash damage for 30 seconds.
  - Can use Plague ability for 150 energy.
    - Infects all enemy units and buildings in the target area, inflicting 300 damage over 20 seconds. Cannot reduce units or buildings below 1 life. Ignores shields. Reveals infected cloaked units.
  - Can use Consume ability.
    - Kills target friendly non-heroic biological unit metabolizing it into 75 energy.
  - Added Metasynaptic Node upgrade at the Infestation Pit.
    - Adds 50 max energy and starts at full energy.

https://github.com/user-attachments/assets/d93f483c-be85-40a6-aff6-ccb6648f8c73

Gives Zagara a unit that isn't just a-move. Mixing defilers allows for taking far more efficient trades. Defilers can also easily get energy from consuming Zagara's cheap units. Try not to consume your friends.

- Increased max supply from 100 to 150.

One of Zagara's greatest weaknesses is the inability to hit a critical mass of units to trade efficiently.

- Buffed P2
  - Increased bonus life regen for Aberrations from 3 to 6.
  - New effect: Incubate Banelings and Incubate Scourge spawn twice as many units.

Fun fact: due to an oversight, the Corruptor bonus life regen is applied twice, effectively increasing their life regen by 6. The Aberration's life regen has been increased to match. Additionally increased the amount of Banelings and Scourge because it's otherwise difficult to spare the vespene to pay for those normally.

- Changed Bile Launcher to target enemies automatically.
- Changed Bile Launcher Bombardment ability to use smart casting.
- Changed Bile Launcher projectiles to reveal a radius of 3 around them.

Idea stolen from CXL, should make Bile Launchers more effectively than just on infested maps.

- Reduced Scourge vespene cost by 25.
- Removed Simplified Genome.
- Added Dampening Membrane upgrade, which reduces the splash and spell damage dealt to Scourge by 75%.

Scourge were incredibly inefficient to morph before evolving Simplified Genome, so it has been made baseline. If you've ever felt the pain of watching your Scourge die to one storm, the new upgrade should help increase the reliability of Scourge against AOE.

- Increased Corruptor damage from 14 (+14 vs Armored) to 28 (+14 vs Armored).
- Buffed Corruptor's Corruption to allow targeting structures.

Corruptor damage has also been buffed so they have actual DPS instead of just tickling air comps. This with the Scourge change should improve Zagara's anti-air capabilities.

- Buffed Roaches to the Corpser strain.

Corpser representation!

- Increased visual scale of Hunter Killers by 20%

When Hunter Killers were given the webby skin, their scale was accidentally reset to the normal Hydralisk scale.

- Added wireframe and group icon to Zagara.

If you thought Zagara's wireframe looked oddly low resolution, you aren't crazy. Zagara doesn't have a wireframe set and just used her unit icon as a fallback.

- Increased speed of Zagara's Acid Spines projectile by 100%.
- Reduced Zagara's Acid Spines attack period from 1.5 to 1 (+50% attack speed).
- Increased Medusa Blade's damage 33% of attack damage to 50% attack damage.

Zagara has a mastery for attack damage but her attacks felt lethargic and she attacked slower than queens. Should make the attack damage mastery competitive with the energy mastery.

### Vorazun

- Added P4: Shadow Hunter
  - Advantage: Vorazun is available as a hero.
    - Passive: Veil of Shadows
      - Permanently cloaked.
      - Shield regen greatly increased while undetected.
    - Passive: Shroud of Adun
      - Upon Vorazun's shield breaking, negate excess damage and become immune to damage for 1 second.
      - Cannot occur again until reaching max shields.
    - Q: Reap (8 seconds)
      - Deals 100 damage to nearby enemies.
      - Can be reactivated to cleave again.
      - Similar to Zeratul's cleave.
    - W: Shadow Assault (15 seconds)
      - Rapidly teleport to random enemies within 3 times, attacking each of them for 60 damage. A single target can be hit more than once.
      - Can target air and ground units.
      - Similar to Shadow Fury, but does not teleport Vorazun back to the cast location.
    - E: Shadow Dash (10 seconds)
      - Teleports Vorazun to the targeted location.
      - For the next 8 seconds, the ability can be reactivated to return to the point where it was cast from.
      - Allows for quickly blinking in and out.
    - R: Void Sanctuary (100 seconds)
      - Creates a large dome in which enemies are slowed to a standstill for 10 seconds.
      - Also stops enemy projectiles.
  - Disadvantage: Deploy Shadow Guard and Time Stop are unavailable.

In case it wasn't obvious, I was heavily inspired by Heroes of the Storm Zeratul. The idea is to blink in, do a bunch of damage, then return and heal back up. Vorazun requires more micro than most heroes but can deal more damage to compensate. In return, you can't rely on Shadow Guard to carry your early game nor Time Stop to take free trades later.

- Added Signifiers, an astral-themed High Templar.
  - Available after building a Templar Archives.
  - Can use Aurora Veil ability for 50 energy.
    - Grants cloak to friendly units in an area and heals their hitpoints over time for 30 seconds.
  - Can use Astral Storm ability for 75 energy.
    - Does less damage in a larger area than Psionic Storm for 7 seconds.
    - Applies Astral Smolder to enemy units hit, revealing cloaked units, reducing movement speed, and reducing armor. This effect stacks up to 4 times.
    - Applies P2, dealing massive damage.
  - Can use Fading Star ability after researching at a Templar Archives.
    - Grants super cloak, 50% increased movement speed, and ignores unit collision for 4 seconds.
    - Can be autocast when damaged.
  - Argus Crystal additionally grants Signifiers full energy.

A cut unit from the LOTV campaign reimagined. Astral Storm provides detection outside of Oracles. Aurora Veil massively helps non-cloaked units like Stalkers, Centurions, Dark Archons, and Void Rays benefit from Vorazun's stealth perks and makes them viable. Can also heal units after they use Emergency Recall.

- Changed Vorazun to use custom Nerazim skinset.

Green warp ins! Dark Templar now use both variants and Shadow Guard use the Golden skinset. Centurions, Stalkers, Dark Templar, Dark Archons, Corsairs, and Void Rays are given a makeover. Also changes some icons.

- Added Vespene Crystalization passive to Assimilators, increasing vespene harvest rate by 25%.

Vorazun is one of the most vespene limited commanders. Increasing her vespene harvest rate should help with the large amount of tech she needs and her extremely gas heavy army.

- Buffed Vorazun level 1 perk to additionally increase the shields of all combat units (except Dark Templar) by 40.

This should help increase the survivability of all her other units. Pairs well with her level 7 perk for increased shield regeneration rate.

- Buffed Disruption Web to no longer require research.
- Added Flux Vanes upgrade, which increases the movement speed and acceleration of Void Rays.

Disruption Web research has been replaced with Flux Vanes. Baseline Disruption Web should help increase the value of the first few Corsairs while the Flux Vanes upgrade should help Void Rays feel better to kite with.

- Dark Archon upgrades moved to Templar Archives.
- Reworked Dark Archons to no longer be trained at a gateway, but instead from merging two Dark Templar or Signifiers.
- Increased Dark Archon weapon damage from 18 to 25 (+10 vs Biological).
- Increased Dark Archon Confusion radius from 2 to 3.
- Buffed Dark Archon Mind Control ability to no longer take up supply.

Should make massing Dark Archons more viable. Why can High Archons do full damage while Dark Archons just tickle?

- Changed Dark Archon skin.
  - Visually green instead of red.

The Dark Archon skin has been used by Tal'darim (Both as Warchest skins and as a skin in NCO), so instead, the Dark Archon is given a unique Nerazim themed skin. As a cool added bonus, using two Signifiers will create a female Dark Archon instead.

- Changed Black Hole to original red model.

Contrasting with the previous change, Black Hole has been changed to red to keep it visually distinct from Vortex.

- Buffed Black Hole to additionally suppress detection.

Why should that Overseer be able to detect you while it's being crushed in a Black Hole?!

- Increased Oracle's Stasis Ward duration from 15 seconds to 30 seconds.

When adding Oracles to co-op, this duration got halved, presumably because it wouldn't be fun to get hit by a 30 second stasis by Amon and they were worried it would be too strong with the Stasis Ward upgrade. Realistically, it's not easy getting big hits with Stasis Wards so reverting this should make Oracles more compelling for more than just detection.

- Buffed P2 to reduce Stasis Ward duration by 50% instead of 75%

For the prestige focused on stasising things, the P2 just makes Stasis Wards sad. This buff combined with the increased duration should help with that.

- Removed deceleration from Oracle's Stasis Ward ability (no longer has to fully stop to cast).

Makes casting much smoother.

- Reduced Corsair subgroup priority from 119 to 115.

This places Corsairs lower than Oracles.

- Reworked Void Stasis into Void Prison.
  - Stuns instead of stasis.
  - Still disables detection.
  - Can target air units.
- Added cast animation for Void Prison.

Ever get annoyed when your Dark Templar would run in and automatically stasis Missile Turrets you were trying to snipe? Removing the invulnerability makes it much easier to snipe detection while fighting. Being able to stasis air units additionally makes Dark Templar much sneakier against flying detectors like Overseers.

- Buffed Emergency Recall to remove negative debuffs.

No more recalling Black Death straight into your mineral line.

- Added autocast to Stalker Blink.

Unsurprisingly, autocasting the shield restoring Blink when out of shields is strong.

- Reworked Centurion's Darkcoil ability from an augment into an instant cast.
- Fixed an issue where Darkcoil would not grant the Centurion shields if the stun fails to hit any enemies.

Augments are so awkward, previously you needed to attack a target to trigger the Darkcoil. Now it is an instant cast, making it easier to activate when you want, e.g. trying to hit a cloaked unit.

- Fixed an issue where Strike from the Shadows would increase the cost of abilities that use energy over time (e.g. Cloak).

Funny that this passive could *nerf* some units. This happened because the buff would multiply energy regeneration by 1.5 and abilities like Cloak cause your energy regeneration to be negative.

- Renamed Shadow Guard weapon from Shadow Scythe to Vorpal Blade.

When Blizzard made Shadow Guard, they just stole the weapon from Vorazun. Now that Vorazun is a proper hero and Shadow Guards no longer use scythes, this weapon has been renamed.

- Fixed an issue where Corsair's Disruption Web ability would autocast on a single unit multiple times.
- Fixed an issue where Shadow Guards casting Shadow Fury did not play their attack animation.
- Fixed an issue where Vorazun's level 7 perk Veil of Shadows would apply inconsistently.
- Fixed an issue where Dark Templar's/Shadow Guard's Shadow Fury had no range indicator.
- Added visual effect to Dark Pylon's Recall ability.
- Fixed an issue where Dark Archons would try to path around Force Fields they could shatter.
- Fixed an issue where targets immune to Black Hole's stun would not have their armor negated.
- Fixed an issue where Void Rays did not get beam attachments when charging up until Prismatic Range was upgraded.

yeah.

### Karax

- Implemented [Maguro's Karax 2.0](https://www.maguro.one/p/karax.html) with some changes listed below.
- Reworked Carrier Repair Drone behavior to vanilla version, but with improved autocasting to no longer require stopping.
- Removed Combat Chrono Wave.
- Removed the ability to Chrono Boost defensive structures.
- Increased Reconstruction cooldown to 240 seconds.
- Increased Improved Reconstruction cooldown to 120 seconds.
- Renamed Improved Reconstruction to Revitalization Matrix.
- Renamed Improved Reclamation to Prolonged Integration Protocols.
- Renamed Improved Shadow Cannon to Photon Reservoirs.
- Renamed Carrier Capacity to Hangar Expansion.

Karax 2.0 has great quality of life changes for Karax, so lets use them. Chrono Boosting defensive structures removed to not step on P1's toes. Nerfed Improved Reconstruction because Sentinels are pretty much unkillable anyways. The upgrades were given more interesting names.

- Added P4: Chronosmith
  - Advantage: Chrono Boost, Chrono Wave, and Chrono Field affect units, increasing their rate of attack, movement speed, and cooldown reduction.
  - Disadvantage: Chrono Boost, Chrono Wave, and Chrono Field no longer affect structures.

Unsurprisingly really strong when used with an ally.

- Added Instigators.
  - A Purifier variant Stalker.
  - Added Displacement Core upgrade, which lowers the cooldown of Blink to 4 seconds and allows up to 3 charges.
  - Blink can be set to autocast to automatically blink when the hull takes damage.

Karax's early/mid game anti-air is extremely lackluster, adding a ranged gateway unit helps greatly with that. The Adept is already used by Fenix, so why not add the unused Purifier unit, the Instigator? Having up to three low-cooldown Blinks on autocast lets these units skirmish effectively and can get pretty chaotic.

- Added Disruptors.
  - Has Fenix Disruptor upgrades.
  - Has regular controllable nova.
- Increased Purification Nova speed from 2.25 -> 3.25
- Reduced cooldown of Purification Nova from 24 seconds to 14 seconds.
- Increased Purification Nova radius by 20%.
- Reduced price of Cloaking Module from 100/100 to 50/50.
- Reduced price of Purification Echo from 150/150 to 100/100.

Disruptors are rarely used with Fenix because it benefits from none of Fenix's Champion AI perks. Hopefully they are a better fit for Karax along with some extra buffs to make it more appealing.

- Replaced Immortals with Annihilators.
  - Only a visual change.

Karax stole Shadow Cannon and gave it to his Aiur Immortals. Karax already stole Khaydarin Monoliths so why not steal Annihilators too to be more distinct from Artanis's.

- Fixed an issue where P1 Chrono Field would not affect ally structures.

Chrono Boost and Chrono Wave affected ally structures, but not Chrono Field.

- Reworked Karax P2 disadvantage to increase the price of Photon Canon and Khaydarin Monolith by 100% instead of disabling them.

Copied from CXL. Keeps it unviable to use static defense aggressively without completely removing the option defensively. Especially useful for dealing with nuke-happy Ghosts.

- Changed Mirage weapon damage from 7 (+5 vs Light) to 10 (+2 vs Light).
- Reduced cost of Mirage from 150/100 to 150/50.

Phoenixs were extremely dependent on enemy composition. Moving some damage from the bonus should help. Also decreased the vespene price to make them easier to mass when going skytoss.

### Abathur

- Added P4: Symbiotic Hivemind
  - Advantage: Hatcheries, Lairs, and Hives can create a Symbiote on a friendly unit.
  - Disadvantage: Leviathans and Brutalisks no longer start with a Symbiote. Symbiotes now cost resources and supply.

Ever wonder how cool it would be to slap a Symbiote on Dehaka or Nova? Should create interesting combinations with your ally. Each Symbiote is now very expensive in return. Very overpowered with commanders who have few but important units such as hero commanders.

- Added Spike Burst ability to Symbiote.
  - Deals 20 damage to nearby enemies every 10 seconds.
- Changed Stab to prioritize units and attacking structures.

Spike Burst is cool and was pretty much already finished but unused (can you tell I've been playing HotS?).

- Increased additional Biomass from P1 from 25 to 50. (Total 150 Biomass).
- Improved prestige tooltip description.

It's generally not worth losing Ultimate Evolutions for this prestige, so let's give it a little extra oomph.

- Buffed Viper's Consumption ability to also target structures.
- Buffed Virulent Microbes upgrade to additionally increase the radius of Viper abilities by 1.
- Buffed Biomass to additionally increase max energy by 1% per biomass.
- Buffed Biomass to additionally increase spell damage for casters (not Ravagers) by 1% per biomass.
- Buffed Abduct to allow abducting Heroic units (will pull but not stun).

Vipers rarely were worth mixing into your army, now they should be much more usable and be competitive in anti-air compared to Devourers.

- Added autocast to Corrosive Bile.

Should help keeping Corrosive Bile on CD with the Biomass CDR. Will try to break force fields if no other enemies in range.

- Buffed Swarm Host to Creeper strain.

Abathur's Swarm Host already got the Deep Tunnel ability, now they poop creep as well.

- Changed Swarm Host Locust to be able to pick up Biomass for the Swarm Host.

Makes microing Swarm Host much easier. No longer do you have to unburrow your Swarm Host to go pick up Biomass.

- Added small delay to Toxic Nest explode when autocast.
  - Explodes quicker against fast units.

Reduces wasting Toxic Nest value by blowing up 1 Marine out of the 40.

- Fixed an issue where canceling Morph to Brutalisk did not destroy the cocoon model.
- Fixed an issue where Morph to Brutalisk did not play a sound when morphing into a cocoon.
- Increased visual scale of Brutalisk Cocoons by 30%.
- Fixed an issue where Morph to Leviathan ability did not share a set id.
- Fixed an issue where Brutalisk Cocoons used the wrong wireframe image.
- Fixed an issue where Leviathan Cocoons used the wrong wireframe image.
- Fixed an issue where Brutalisk Cocoons did not have the Cancel button on the command card.
- Fixed an issue where Leviathan Cocoons did not have the Cancel button on the command card.
- Changed Morph to Brutalisk to disable autocast when canceled.
- Changed Morph to Leviathan to disable autocast when canceled.

Did you even know you could cancel morphing Brutalisks/Leviathans? The cancel button was removed from the command card but you could still stop the morph by canceling it from the queue. Cancel was likely removed because it would immediately start the morph again if you had autocast on. A little change to disable autocast when you cancel should fix that; no more accidentally turning your Vipers into Leviathans!.

- Fixed an issue where Mutalisk's Sundering Glaive passive tooltip highlighted unit names.
- Fixed an issue where Viper's Virulent Microbes passive tooltip highlighted unit names.
- Fixed an issue where Infestation Pit's Evolve Pressurized Glands tooltip did not highlight unit names.
- Fixed an issue where Locust's Pressurized Glands passive used the Infestation Pit's research button.

Some tooltip fixes. Only the research tooltips should highlight unit names, not passives.

- Fixed an issue where Leviathan's air attack projectiles were all launched from one point.

Leviathan's have four holes, use them all! This bug was caused by using the original WoL Leviathan's attach method instead of one for Abathur's Leviathan. Fun fact: this problem is shared with Kerrigan's Leviathan in the HotS campaign.

### Alarak

- Added P4: First Ascendant
  - Advantage: Ji'nara is available as a hero.
    - Passive: Soul Resurrection
      - When a nearby unit dies, Ji'nara converts its soul into a Soul Shade that lasts 20 seconds.
      - Soul Shades act as Supplicant equivalents.
      - Upon dying, the Soul Shade heals Ji'nara for 20 life and 20 shields per the original unit's supply.
      - Only 10 Soul Shades can exist at a time.
      - Ji'nara steals life from nearby units you control to heal herself when she is near death. This ability has no cooldown.
    - Passive: Forked Lightning
      - When Ji'nara sacrifices a Supplicant or Soul Shade, her next basic attack will deal weapon damage + 30 to 4 enemy units.
    - Q: Chaotic Torrent (100 energy)
      - Unleash a torrent of chaos, dealing 60 damage to enemy units in the target area.
    - W: Chains of Wrath (100 energy)
      - Launch chains at a target enemy unit, slowing their attack and movement speed by 50% for 8 seconds.
      - While chained, enemies will take up to 40 damage.
      - Upon taking damage, chained targets will launch additional chains at nearby enemies.
    - E: Ritual Sacrifice (8 seconds)
      - Sacrifices a Supplicant or Soul Shade to fully restore Ji'nara's energy.
      - Can only target Supplicants or Soul Shades.
    - R: Empower Me (100 seconds)
      - Ji'nara gains increased attack and ability damage for each nearby friendly unit.
      - Alarak's Mechanical units grant her double the power.
      - Ritual Sacrifice has no cooldown while active.
      - This effect lasts for 20 seconds.
    - Upgrade: Imposing Presence
      - Ji'naras attacks stun enemy units for 2 seconds.
      - Massive units are slowed.
    - Upgrade: Weight of Sin
      - Wrath of Chains slow increased by 50%.
      - Wrath of Chains suppresses energy-based ability usage.
    - Alarak will take Ji'nara's place on Chain of Ascension.
  - Disadvantage: Alarak is unavailable.

Replaces Alarak with Ji'nara, a hero who focuses on Sacrifice usage to continue fueling spells. Ji'naras Soul Shade passive allows her to sustain Sacrifice usage during fights and can also benefit Ascendants. Honestly, this hero just exists because I though it would be cool to add Ji'nara as an Adept hero.

- Added red Tal'darim building warp-in skins.
- Added red Tal'darim unit warp-in skins.

Everything looks cooler in red! Also fixed my biggest pet peeve, the Supplicant and Stalker warp-in effects going from top to bottom instead of bottom to top. Seriously, were they drunk when UV mapping these?

- Added Void Archon, merged from two Ascendants.
  - Can use Maelstrom ability for 50 energy.
    - Stuns enemies in an area for 8 seconds.
  - Can use Sacrifice ability to refill energy.
  - Has Power Overwhelming passive.
    - The Void Archon permanently gains +25% damage, +100 shields, and +0.5 shield armor each time it uses Sacrifice.
    - This effect stacks up to a maximum of 20.
    - Inherits stacks from constituent Ascendants.
  - Has Chain Reaction passive.
    - Causes attacks to chain to two additional targets.
    - Requires research at the Templar Archives.
  - Has Supernova passive.
    - Upon death, Void Archons go supernova, stunning and pulling in nearby enemies. After 5 seconds, the supernova detonates for damage equal to the Void Archon's max shields.
    - The supernova's radius increases with Power Overwhelming stacks.

A passive called Power Overwhelming deserves to go to an Archon unit! By accruing stacks on Ascendants and combining them, you can make a *super* archon with chain attacks that each do AOE damage. Inspired by the LotV cinematic, dying Void Archons go out with a bang, dealing massive damage in a nearby radius, though it still isn't worth sacrificing your Archons.

- Reworked Mothership Terminator Beam to only target air units.
- Reworked Mothership Thermal Lance.
  - Only targets ground units instead of all units.
  - Reduced travel speed by 50% speed.
  - Cooldown increased from 1 to 2 seconds.
  - Damage increased from 10 to 100.
- Added a dramatic sound effect when summoning a Mothership.
- Renamed Mothership to Crimson Sovereign.

Changes the Thermal Lance from a 10 damage tickle beam to a slow moving 100 damage death laser. As compensation, the original Terminator Beam can only hit air units and Thermal Lance can only hit ground units (it seemed weird that hitting the ground under air units would damage them anyways). Mothership was renamed to be more distinct from other variants and be in line with other Tal'darim variant unit names.

- Increased Destroyer supply cost from 3 to 6.
- Increased Destroyer price from 125/75 to 250/150.
- Increased Destroyer bounce damage by 1 for each charge level.
- Buffed Protoss Air Weapons upgrades to affect Destroyer bounce damage (+0.333).
- Reworked Destroyer weapon attacks to ignore armor.
- Reworked Level 13 Burning Skies perk.
  - No longer increases the amount of Destroyers spawned.
  - Increases visual scale of Destroyers by 20%.
  - Increases the life/shield of Destroyers by 100%.
  - Increases damage of Destroyers by 50%.
- Reworked P3.
  - Warp in Destroyer charges take 100% longer to accrue.
  - Warp in Destroyer charges max reduced by 50%.

Typically when using the Death Fleet or playing P3, you would end up with a lot of visual clutter of bouncing beams that end up doing 0.5 damage to a Zergling that has +1 armor. Reducing the amount of active Destroyers but making them more impactful should better match the visual intensity of their bouncing attack.

- Increased Destroyer warp-in time from 2 seconds to 5 seconds.

Destroyers having such a low warp-in time made the warp-in finish before the animation, looking buggy.

- Buffed Alarak's Soul Absorption passive to additionally proc when friendly units die.

Friendly units shouldn't be dying anyways, so why not get some value when it happens?

- Buffed Alarak's Deadly Charge ability to hit cloaked units.

Not sure why this was nerfed to not hit invisible units at some point.

- Buffed Alarak's Lightning Surge to also proc when Supplicants are sacrificed by Ascendants.

Seems weird there isn't a way to get Lightning Surge without killing Alarak.

- Buffed Havoc's Force Field ability to no longer be shattered by massive units.
- Buffed Havoc's Force Field ability to start with 3 charges.
- Renamed Havoc's Force Field ability into Subjugation Field.

Some Force Field buffs to make it less niche and a new fancy name to make it distinct.

- Increased Vanguard attack count from 8 to 16.
- Reduced Vanguard range by 1.

Copied from LOTV Nightmare. The nerf from campaign to co-op made training these feel sad. To compensate for unnerfing the damage, the range has been reduced. The reduced range also helps them live up to their name.

- Reworked Wrathwalker attack to hitscan instead of a projectile.

Prevents situations where all your Wrathwalkers mega overkill one unit. Unsuprisingly makes Wrathwalkers significantly stronger against smaller units, especially with P1.

- Fixed an issue where Mothership used standard skin death ragdoll model instead of Tal'darim.
- Changed Ascendant shadow trail model to be red.
- Fixed an issue where Ascendant shadow trail model didn't scale with the Ascendant (noticeable with Power Overwhelming).
- Restored missing beam effect on Ascendant's Psionic Orb.
- Added a visual effect to Mothership's Mass Teleport ability.
- Changed Mothership Mass Teleport ability to teleport to the unit's current location instead of its location when the ability was cast.
- Fixed a bug where Alarak's Destruction Wave model would not face the direction it was cast in.
- Fixed an issue where Alarak's Destruction Wave cast animation would not play while moving.
- Fixed an issue where Alarak's Deadly Charge cast animation would not play while moving.
- Improved Alarak's Deadly Charge visual impact animation.
- Fixed an issue where Alarak's status bar would float much higher than other heroes.
- Fixed an issue where warping-in Supplicants were missing the void warp-in beam.
- Fixed an issue where Destroyers would not play their attack animation during their warp-in animation (It still looks buggy with the beam attachments).
- Fixed an issue where combat units would have a level in their highlight tooltip.

yeah.

### Nova

- Changed Nova to visually change suits between Stealth Mode and Assault Mode.
- Added P4: Covert Crusader
  - Has higher movement speed than normal Nova.
  - Replaces gear in both modes.
  - Stealth Mode:
    - Blazefire Gunblade/Fury of One
      - Fury of One attacks twice as fast from NCO.
    - Apollo Infantry Suit
      - Can be activated for 30 seconds of cloak. Increases max energy by 100.
    - Flashbang Grenades
      - Heroic units are immune.
  - Assault Mode:
    - Monomolecular Blade/Dash Attack
      - Dash Attack reworked, should more reliably charge in target direction, but may get stuck on impassable terrain.
      - Dash Attack also grants a brief amount of invulnerability.
    - Turbojet Jumpsuit
      - Allows cliff jumping. Increases max life by 250.
    - Stim Infusion
  - Operation Efficiency and Infernal Projectiles affect Fury of One and Dash Attack respectively.

Shows some love for the unused gear. Makes Nova less effective at supporting her army but stronger individually.

- Added P2 Advantage: Stuns enemy units in the drop off area for 8 seconds when unloading.
- Added missing prestige tooltip for Tactical Airlift and Griffon Airstrike when using P2.

P2 was such a boring prestige. Stunning enemies at least grants a niche of dropping right on top of enemies and bursting them down.

- Reworked Covert Banshee's Rocket Barrage ability.
  - Now does damage over time rather than instantly.
  - Fixed an issue where missiles would launch from the center of the model instead of the weapons.
  - Changed autocast to prioritize hitting multiple enemies, but can target fewer.
  - Reduced casting arc from 360 to 0 (Now has to face target location).

Looked silly dealing the damage instantly and *then* afterwards the rockets land.

- Reworked Covert Banshee's Advanced Cloaking Field upgrade into Phantom Drive upgrade.
  - Still perma-cloaks but additionally provides movement speed.

Nobody likes slow Banshees.

- Added visual change to Raid Liberator ground attacks after researching Raid Artillery.

Copied from Versus.

- Reworked Marauder Commando's Magrail Munitions.
  - Added 5 second stun (Heroic and Massive units get slowed instead).
  - Reduced damage from 90 to 50.
  - Changed to an ability instead of an attack augment, allowing it to target enemies separate from basic attacking.
  - Changed to be able to hit air units.
  - Changed autocast to prioritize non-stunned units.
  - Changed visual effect.
  - Changed damage from ranged to spell (ignores armor).

Changes Magrail Munitions from a nuke to a CC ability to further reinforce the Marauder's role as a support frontliner.

- Reduced the cooldown of Covert Banshee's Rocket Barrage ability from 15 seconds to 10 seconds.
- Reduced the cooldown of Spec Ops Ghost's Snipe ability from 30 seconds to 10 seconds.
- Reduced the cooldown of Spec Ops Ghost's EMP Round ability from 45 seconds to 10 seconds.
- Reduced the cooldown of Marauder Commandos's Magrail Munitions ability from 30 seconds to 10 seconds.

Many of Nova's unit cooldowns are so long that they usually are used once at the start of a fight and then never again. Reduced cooldowns should help her in longer fights.

- Increased attack speed of Railgun Turrets by 100%.
- Reduced duration of Railgun Turrets built by Raven Type-II from 60 seconds to 30 seconds.

Despite being an elite Raven, they actually end up dropping worse Auto-Turrets with lower DPS and the inability to hit air. Now the Railgun shoots twice as fast but the duration is reduced by half to compensate.

- Fixed an issue where the attack range indicator for Railgun Turrets was larger than intended.

Fun fact: it was using the range for the Build Railgun Turret ability rather than the weapon range.

- Increased the range of Spec Ops Ghost's Triple Tap upgrade from 3 to 5.

This increases the reliability of Ghosts getting the extra snipes off. This is the range of after sniping the first target and looking for a nearby target to hit with an extra snipe.

- Added a new Aegis Plating passive to Hellbat Rangers.
  - Reduced damage taken to a maximum of 20.

Hellbats tend to not even be worth the mineral cost as they die too easily. Giving them Hardened Shield should improve their effectiveness as a frontline, especially when facing high damage burst like Yamatos.

- Reduced Railgun Turret life from 400 to 375.
- Reduced life multiplier from Nova's level 1 perk from 2 to 1.5.
- Buffed Nova's level 1 perk to affect Missile Turrets.
- Added Hi-Sec Auto Tracking upgrade.
  - Adds +1 range to Railgun Turrets, Missile Turrets, Defensive Drones, and Bio-Mechanical Repair Drones.

Showing some love for Nova's static defense. Nova's structure life perk was ridiculous, so its value was reduced. In return, Missile Turrets benefit from it now.

- Fixed an issue where Triple Tap could target undetected units.
- Fixed an issue where Railgun Turret placement models were smaller than their actual model.
- Added a buff/debuff for structures affected by P1.

yeah.

### Stukov

- Added P4: Neural Dominator
  - Advantage: Stukov gains control of units he kills for 120 seconds.
  - Disadvantage: Max supply reduced by 100.

*All your unit are belong to us.* Heroic units are obviously immune. It's much harder to hit a critical mass of army but in return you can just steal Amon's. This prestige causes your pushes to snowball insanely hard. And yes, you can in fact kill your allies units to steal all their units (pls don't be mean).

- Reworked Infested Barracks
  - Costs 1 supply.
  - Automatically spawns free Infested Marines.
  - Can pay 100/50 and 1 supply to increase level of Corruption up to 5 times, decreasing the cooldown of spawning Infested Marines.
  - Can autocast Increase Corruption.
- Changed Infested Siege Tanks to also consume Infested Marines.

Infested Marines were not worth investing into over Bunkers because they are timed. The solution? Make them free! Can now choose to invest in a Bunker for immediate units and static defense, or a Barracks for a long-term investment and slightly stronger infantry.

- Added Infested Rockets weapon from Versus to Infested Marines.

Despite Infested Marines and Infested Troopers being different units, they are pretty much identical. This should give Infested Marines their own niche as a long-range anti-armor AA option, something Stukov doesn't have.

- Increased duration of infested troopers from 30 to 60.

Infested troopers were previously reliant on the infantry duration mastery. This should increase their consistency without the mastery.

- Reduced the cooldown of Spawn Infested Civilians ability from 60 seconds to 15 seconds.
- Reduced the amount of Infested Civilians created from 8 to 2.

Instead of creating huge waves, the Infested Colonist Compound now does many smaller waves. Each infestation upgrade still doubles the amount of infested spawned.

- Buffed Infested Colonist Compound's Spawn Infested Civilian ability to now be affected by Chrono Boost.

What's the worst that could happen?

- Reworked P3.
  - Now increases spawn rate of Infested Bunker, Infested Barracks, and Infested Colonist Compound by 50%.

This prestige was so simple to play, you could just spam down a bunch of bunkers. Lowering the bonus but applying it to more infantry should increase composition diversity.

- Changed Infested Banshee P2 Deploy ability to allow casting while moving.
- Replaced Braced Exoskeleton upgrade with Hyperadaptive Exoskeleton, which additionally increases Infested Banshee speed by 2.
  - Adds visual boosters to the Infested Banshee.

These two simple changes make playing P2 infinitely smoother to play. Seriously, being able to deploy infested while moving is night and day. It was kinda sad that P2 was about picking up your infantry and moving them to the frontline, but the Infested Banshee was about as fast as them walking there.

- Added advantage for P2:
  - Starports and Banshees no longer have tech requirements.

These take super long to tech to before you can get any value from P2. Removing the tech requirements similar to P1 should streamline it.

- Buffed Rapid Hibernation to no longer require research.
- Removed deceleration from Infested Banshee's Burrow ability (no longer has to fully stop to cast).

Rapid Hibernation made baseline to make way for a new upgrade. The QOL change also helps quickly burrowing after moving.

- Added Incubation Chambers upgrade, which adds a Broodling escort to Infested Banshees, similar to Brood Lords.
  - Does not do impact damage on landing, unlike the Brood Lord.
  - Continues to spawn regular Broodlings while burrowed.

Grants a unique to trait to the Infested Banshee other than just burrowing for energy. Borrowing from the P2 idea of ferrying around infested, this upgrade lets Infested Banshees carry around and throw Broodlings. Combined with the new move speed upgrade, these things turn into Brood Lords with turbo boosters. Should make the tech required to build them feel more worth it.

- Added 100 max energy to Infested Liberators.
- Regenerates energy by consuming nearby Infested Troopers or Infested Civilians. Normal means of energy regeneration are suppressed.

Added a new mechanic to Infested Liberators that lets them eat Infested to empower their weapons, similar to Infested Siege Tanks.

- Added Defender Mode ability to Infested Liberators.
  - Uses a slightly slower attack speed version of the Liberator AG weapon.
  - Has a Volatile Spray weapon, which sprays enemies with acid, leaving behind a pool that deals damage and slows, but requires energy to use.

I know they were originally meant to be Valkyries, but hey, they ended up as Liberators, so give them Defender Mode! Defender Mode covers significantly less ground than an Infested Siege Tank, but it has more DPS.

- Added Volatile Fuel passive, which increases attack and movement speed by 25% while attacking with Cloud Dispersal at the cost of 2 energy per second.

*Zoooom*

- Increased damage of Viral Swarm from 10 to 15 (AOE and primary).
- Removed Viral Contamination upgrade.
- Added Necroplasmic Synthesis upgrade, which restores energy equal to 2.5% of damage dealt.
  - Requires Armory to research.
  - Improved by P1.
- Removed Armory requirement from Cloud Dispersal.

Made Viral Contamination upgrade partially baseline in favor of a new upgrade that compliments the Infested Liberator's new mechanics. Also lowered the tech requirement of Cloud Dispersal as it's a must-get upgrade.

- Added strafing movement to Infested Liberator Cloud Dispersal.
- Increased Infested Liberator lateral acceleration to 10 (how quickly the unit turns around while moving in a different direction).
- Increased Infested Liberator Cloud Disperal lingering duration by 1 second.
- Fixed an issue where Infested Liberator were unable to attack while using Hold Position after researching Cloud Dispersal (will use pre-upgrade weapon).

Adding strafing to Cloud Dispersal causes Liberators to spread out more evenly, dealing damage in a greater area and take less damage from AOE effects. It also just looks cooler. Increasing the lingering duration allows running away before the 85% damage reduction fades.

- Buffed P1 to also affect Brood Queens.
- Removed prepare time from Ocular Symbiote and Spawn Broodlings.
- Removed deceleration from Ocular Symbiote and Spawn Broodlings (no longer has to fully stop to cast).
- Changed Spawn Broodlings to spawn flying Broodlings (must land before attacking) when casted on a flying unit.

Some QOL changes for a unit that nobody uses. Seemed weird that Brood Queens were explicitly left out by the P1 advantage.

- Changed Infested Missile Turrets to attack while uprooted.
- Changed Infested Missile Turrets to provide detection while uprooted.
- Added Biomass Coating passive to Infested Missile Turrets, increasing life regen while rooted.
- Changed Regenerative Plating upgrade to additionally affect Infested Missile Turrets.
- Changed Calcified Armor upgrade to additionally affect Infested Missile Turrets.

Bunkers can do it, why not the Missile Turrets? Gives Stukov another funny form of detection.

- Reduced allied push priority of Infested Marine to -2.
- Reduced allied push priority of Infested Trooper to -2.
- Reduced allied push priority of Infested Civilian to -1.
- Reduced allied push priority of Volatile Infested to -1.
- Reduced allied push priority of Broodling to -3.
- Increased allied push priority of uprooted buildings to 1.

It can be frustrating trying to get into the fight when you have a P3 Stukov ally, now you can push all their troopers aside. It also made sense that giant walking buildings could push other smaller units out of the way. This helps trying to push your bunker line up. Ranged infantry have a lower push priority so the melee infantry can push through.

- Added Infested SCV portrait.
- Added Infested Diamondback portrait.
- Added Infested Liberator portrait.
- Changed Infested Siege Tank portrait to previous Infested Diamondback portrait.
- Changed Infested Civilian portrait.
- Added Infested Trooper model and portrait.

Blizzard got lazy and only reused portraits for Stukov, lets add new ones!

- Fixed an issue where if an Infested Civilian has jumped using Anaerobic Enhancement, and an Infested Siege Tank tried to eat it, the Infested Civilian would die without healing or gaining a charge.
- Fixed an issue where the icon of the button for Mech Attack Speed mastery was not colored.
- Fixed an issue where you could not queue multiple upgrades on the Infested Command Center.
- Fixed an issue where Volatile Infested would play a sad little wimpy pop sound effect when dying instead of a acid explosion.

yeah. The Siege Tank bug took way too long to figure out...

### Fenix

- Added P4: Ascendant Chorus
  - Advantage: The number of Champion A.I.s is no longer limited.
  - Disadvantage: All combat shell unit costs increased by 100%. Avenging Protocol is unavailable.

Because each duplicate unit gives the same value now, it's possible to go compositions without one of each champion. The disadvantage is likely not strong enough to counteract how OP this prestige is.

- Changed Kaldalis's Engage ability to require researching Charge at the Twilight Council.
- Changed Talis's Psionic Projection ability to require researching at the Twilight Council.
- Reduced Warbringer's weapon from 9 to 6.
- Changed Extended Thermal Lance to additionally affect Warbringer.
- Changed Graviton Catapult to additionally affect Clolarion.

It seemed weird that these upgrades did not affect their champion counterpart. Fun fact: the Scout range upgrade at the Fleet Beacon *did* affect Mojo. Not sure why this was the exception.

- Reworked Adept/Talis shade attacks from a projectile to a beam.

This should make shade attacks look more distinct from the Adept/Talis.

- Removed Disruptors.

Disruptors are never used with Fenix because it benefits from none of Fenix's Champion AI perks. The disruptors have been moved to Karax.

- Increased Fenix's (Arbiter) Stasis Field ability radius from 1.5 to 5.

Why was the radius nerfed so hard? Increased the match the campaign Arbiter's stasis radius.

- Changed Clolarion's Interdictors to launch with the Interceptors instead of after.

Launch the bombers faster!

- Increased projectile scale of Talis attacks by 20%.
- Increased projectile speed of Talis attacks by 20%.
- Increased projectile scale of Mojo attacks by 20%.
- Increased projectile speed of Mojo attacks by 20%.
- Increased beam scale of Warbringer attacks by 20%.

The champions do more damage than normal units, so their projectiles should be larger to visually show that.

- Fixed an issue where Conservator's Protective Field ability/passive would not affect units on a different cliff level.
- Added a visual effect to Fenix's Recall ability.
- Fixed an issue where Talis's Ricochet Glaive impact visual would move/rotate with the unit.
- Fixed an issue where Clolarion would launch multiple interceptors at a time.
- Fixed an issue where Warbringer's attack beams moved too slowly.

yeah.

### Dehaka

- Added P4: Essence Splitter
  - Advantage:
    - Both units survive and evolve when Primal Combat is used.
    - Gene mutation chance increased to 40%.
  - Disadvantage: Dehaka is unavailable.

All-in on army units. Double evolved units makes maxing much easier and increased mutation chance plus mastery makes it pretty much impossible to not have a mutation.

- Reduced the damage from using Consume on a psionic unit from 2x weapon damage to 1x weapon damage.
- Added a cleave to Dehaka's Claws weapon.
- Added splash damage to Dehaka's Mammoth Beam weapon.
- Increased the damage of Dehaka's Mammoth Beam by 50%.

Should reduce Dehaka's reliance on psionic units for clearing waves. Dehaka gains a frontal cone cleave to his Claws and splash damage to his Mammoth Beam to compensate. Also increased the damage of the Mammoth Beam so it feels more desireable to get instead of feeling like a damage nerf.

- Buffed Ravasaur weapon to deal splash damage.
- Changed Ravasaur weapon to no longer track targets (can miss).

Ravasaurs can be scary in the campaign with their splash damage, so why does Dehaka get a nerfed boring version?

- Fixed an issue where P2 did not increase the damage of Dakrun's Greater Spiked Hide.
- Increased Dakrun's Brutal Charge damage from 200 to 200 (+200 vs Structures).
- Buffed Dakrun's Brutal Charge to affect invisible units.
  - Buried units will not be knockbacked.
- Buffed Dakrun's Brutal Charge to affect structures.
  - Will damage but not knockback structures.
- Changed Dakrun's Brutal Charge to ragdoll/launch killed enemies.

Why did Dakrun slam his giant head into a building and do 0 damage? Also why did it not affect invisible units? Now Dakrun has a niche of smashing into buildings.

- Increased Dakrun's melee attack damage from 100 to 100 (+100 vs Structures).
- Added attack vfx to Dakrun's melee attack.
- Changed Dakrun's melee attack to ragdoll/launch killed enemies.
- Increased Dakrun's radius from 1.5 to 2.

Lets give Dakrun's headbutt more oomph! Radius increased because Dakrun basically had to stand on top of units to hit them.

- Added ranged air attack to Dakrun: Spine Volley.
  - Launches 5 spines in a small AOE that deal 12 damage.

Gives Dakrun an option against air units, but it does have less dps than his ground attack.

- Reworked Pack Leader ability placement.
  - Added a placement preview for Murvar and Dakrun that turns red when placement is invalid.
  - Fixed an issue where Murvar and Dakrun could not be spawned on top of Colossus-like units.
  - Fixed an issue where Glevig could not be placed on top of units, despite the placement showing as valid.
  - Reduced the Dakrun spawn damage from 200 to 50.
  - Changed Dakrun's spawn knockback to ragdoll/launch killed enemies.
  - Buffed Dakrun's spawn knockback to unburrow affected units.
  - Added Dakrun's spawn knockback to Glevig and Murvar.
  - Fixed an issue where Pack Leaders waited 1 second before playing their unburrow animation.

Why does popping out of the ground only let Dakrun do damage? Let's give that to the other Pack Leaders! Additionally helps with spawning the Pack Leaders when theres a bunch of units blocking placement.

- Reworked Primal Wurm Deep Tunneling.
  - Buffed Primal Wurm/Greater Primal Wurm/Glevig Deep Tunnel to allow tunneling under units.
  - Added Dakrun's spawn knockbak to Glevig's Deep Tunnel.
  - Buffed Primal Wurm and Greater Primal Wurm Deep Tunnel knockback to unburrow units.
  - Reduced Primal Wurm/Greater Primal Wurm/Glevig Deep Tunnel finish time from 3 seconds to 2 seconds.
  - Fixed an issue where Primal Wurms could not Deep Tunnel On to burrowed Roaches.

Deep Tunneling gets the same treatment as Pack Leader spawning. However, Primal Wurms and Greater Primal Wurms don't do spawn damage.

- Lowered tech requirement of Primal Wurms from requiring Glevig's Den to requiring a Primal Warden.

Primal Wurms are Dehaka's only source of detection until evolving to level 5, making Dehaka extremely vulnerable to early stealth such as the We Move Unseen modifier. This buff should counteract that.

- Added the Swoop ability to Primal Locust.
  - Allows manually landing flying Primal Locusts at a target location.
- Added the Swoop ability to Explosive Creeper.
  - Allows manually exploding Explosive Creepers at a target location.

Doesn't seem that useful but why not.

- Changed Primal Impaler model.

The unit previously used the Primal Lurker skin, now it uses a proper Impaler skin.

- Added a visual impact model for Dehaka's Devour.

This visual exists in the [commander preview](https://youtu.be/R2-PzLUzam8?feature=shared&t=93) but was removed before release for some reason. Fun fact: the visual still existed for Carriers and Void Rays only for some reason.

- Changed Primal Igniter weapon attack sounds.

It very clearly sounded like a hellion.

- Fixed an issue where Dehaka's units don't have reduced sight radius while burrowed (Impaler, Primal Host, and Creeper Host excluded).
- Fixed an issue where Tyrannazors had a larger unit radius when burrowed than unburrowed.
- Fixed an issue where Creepers could not damage friendly units.
- Changed Explosive Creeper weapon icon.
- Changed Greater Primal Wurms to visually burrow away instead of exploding when expiring.
- Fixed an issue where Pack Leaders had the hidden Map Boss tag, making them immune to some mutators.
- Fixed an issue where Zweihaka had a highlight tooltip.
- Fixed an issue where Dakrun's Brutal Charge's launch dust particles faced the incorrect direction.
- Fixed an issue where Dakrun/Glevig/Murvar could be loaded into transports.

yeah.

### Han & Horner

- Added Ordnance Towers that can be built by SCVs.
  - These are flying defensive structures with long-range attacks.
  - Spawns up to 6 Valkyries that fly around and defend the area.
    - Valkyries have 100 life and their own long-range missile attack.
  - Can use Nano-Repair ability to heal mech units.
  - Can detect cloaked units.
  - Can use Tactical Jump ability to reposition.

Han & Horner are missing a defensive structure to deal with ground, so why not make it something cool like the scrapped Ordnance Tower? These are very expensive but can defend a large area.

- Added P4: Sky Sovereigns
  - Advantage:
   - Precision Strike cooldown reduced by 50%.
   - Call in the Fleet duration increased by 100%.
  - Disadvantage:
    - Precision Strikes can not be manually targeted, instead automatically targeting enemies near Ordnance Towers and Call in the Fleet.
    - Call in the Fleet attack speed reduced by 50%.

Defensive prestige! This prestige lets Precision Strikes be spammed defensively but in return, they can't be easily be used offensively.

- Increased visual scale of Assault Galleons by 20%.
- Increased life of Assault Galleons from 500 to 750.
- Reduced Assault Galleon limit from 5 to 4.
- Added the ability for Assault Galleons to produce 2 units at once.
- Increased visual scale of Assault Drones by 20%.
- Increased life of Assault Drones from 80 to 100.

Assault Galleons are suppose to be mobile Starports that can turn into aircraft carriers, so lets make them visually match that fantasy. Overall increases the production rate of Han's units.

- Increased Salvage rate from 20% to 40% for Han & Horner and from 10% to 20% for allies.

Mira's units usually trade horribly, this should help mitigate that.

- Reworked P1:
  - Removed Mag Mine improvements.
  - Increases the production speed of Mira's units by 50%.
  - Increases the Salvage rate from 40% to 60%.
  - Fixed an issue where some death effect passives were missing the appended prestige tooltip.

Buffing a top bar ability feels kinda boring, instead P2 now improves how many Mira units you can produce. The improved Salvage value and the Double Salvage mastery can combine to give more minerals than you initially paid. It can look funny seeing your mineral count rubber band as you train a bunch of units and then they all suicide.

- Increased Strike Fighter hitpoints from 50 to 100.
- Buffed Precision Strike to also hit air.
- Added visual trail to Strike Fighter.
- Adjusted Strike Fighter acceleration.

Why is this thing so easy to shoot down? The initial explosion can also now hit air units, but not the fire from the napalm upgrade.

- Reworked P3:
  - Added advantage: Can research one exclusive Precision Strike upgrade.
    - Thermal Cascade Payload: Napalm upgrade but spreads to a larger radius.
    - Cluster Payload: Drops 2 additional bombs behind the target area.
    - EMP Warhead Payload: Additionally deploys an EMP that has similar effects to Mengsk's EMP.
  - Removed Strike Fighter Platform cost disadvantage.
  - Added disadvantage: Salvage is unavailable.

Old P3 had an awkward design where it buffed how many platforms you could build and then made them so expensive that you could never hit the limit anyways. New P3 leans into the Precision Strikes harder by buffing them further and adds a more interesting disadvantage of weakening the ability to trade with an army. These changes incentivize using the Precision Strikes more aggresively to ensure efficient trades.

- Added autocast to Widow Mine Burrow.
- Reworked Executioner Missiles to shoot a missile at a nearby enemy that then splits into 5 missiles.
- Fixed an issue where unburrowed Widow Mines showed a range indicator after researching Black Market Launchers (Fun Fact: It didn't even show the correct range).
- Added a visual red light on top after researching Black Market Launchers.

These changes should make Widow Mines more viable at pushing into enemy bases. Autocasting burrow particularly helps when training Widow Mines at the front lines.

- Buffed Hellbat's Wildfire Explosives to additionally apply Immolation Fluid if researched.

It was very odd to see enemies on fire running in fear and taking no damage.

- Increased projectile speed of Deimos Viking's W.I.L.D. Missiles by 100%.

Often, whatever these were shooting at would already be dead by the time the projectile arrives.

- Increased Deimos Viking's Gatling Cannon damage from 18 to 18 (+12 vs Mechanical).

Copied from Versus.

- Increased range of Sovereign Battlecruiser's Mini Yamato Cannon from 6 to 8.

It's a damn Yamato cannon, it should be long range! Just feels natural, y'know?

- Increased range of Theia Raven's Analyze Weakness from 8 to 10.

This should keep the Raven farther back and not randomly die as easily.

- Removed Junker skins for Deimos Viking, Theia Raven, Sovereign Battlecruiser, and Strike Fighters.
- Added Covert-Ops portraits for Deimos Viking, Theia Raven, and Sovereign Battlecruiser.

Despite being called Han & Horner, once you got all the upgrades, it just turned into "Oops! All Han!". Now you get to keep some of that "elite Dominion" aesthestic in your army. It also felt really silly that upgrading a Battlecruiser with Yamatos would strap two giant knives to its side.

- Fixed an issue where Reaper's death rattle grenades continued their ticking sound after exploding.
- Added a ticking sound to Reaper's KD8 Charge ability.
- Added a cursor splat to Reaper's KD8 Charge ability.
- Increased KD8 Charge damage radius from 1.5 to 2.
- Increased KD8 Charge knockback radius from 1 to 2.
- Removed status bars from placed KD8 Charges.

Some visual QOL and a small buff to the KD8 Charge radius. Not sure why the damage and knockback had different radii.

- Removed random delay between shots from Sovereign Battlecruiser's weapon.

Overall increases attack speed and allows the Sovereign Battlecruiser to be affected by attack speed buffs.

- Changed the Tactical Jump out animation to be reversed.

For some reason, it looked like ships were teleporting backwards from their destination.

- Added Sovereign Battlecruiser Tactical Jump animation.

The Sovereign Battlecruiser has a fully functional teleport animation, so let's use that instead of the generic stand-in.

- Fixed an issue where Call in the Fleet's initial targeting position would be offset when casted over flying pathing blockers.
- Fixed an issue where Call in the Fleet would launch at a different trajectory than intended.

Fun fact: the second bug was caused by trying to launch the missile to a position 500 units away, which would cause strange clamping issues out of bounds.

- Changed Wraith reentry sound effect.

It used the Banshee reentry sound effect, which had a distinct helicopter sound. It's been swapped to the Vikign reentry sound.

- Fixed an issue where canceling building an Assault Galleon would play the Assault Galleon's death animation instead of the generic Terran build cancel animation.
- Fixed an issue where Sovereign Battlecruisers would always visually fire from their anti-air turrets, even when shooting ground targets.
- Fixed an issue where Call in the Fleet targeting reticles would visually bank with the targeted unit.
- Changed Theia Raven Silent Mode ability to no longer require decelerating to cast.
- Added unique visual effect for Theia Raven Silent Mode instead of reusing the Overseer's.
- Fixed an issue where Hellbat's Wildfire Explosives fear effect would stop the AI of affected units.
- Fixed an issue where Hellbat's Wildfire Explosives would affect invulnerable units.
- Fixed an issue where Mag Mines would not play their entire animation when firing.
- Fixed an issue where killing a Strike Fighter Platform while the Strike Fighter is deployed would cause a mysterious Strike Fighter model to show up.

yeah.

### Tychus

- Added P4: Hell's Kingpin
  - Advantage: Outlaws are no longer capped.
  - Disadvantage: Medivac Platforms are unavailable.

The biggest pain the ass was obviously trying to get the UI to accommodate having 4 more Outlaws. Second to that is trying to get 9 abilities to fit on one shared command card. This prestige trades a weaker early/mid game without Medivacs for an overpowered late game, though it is very expensive getting gear for 9 Outlaws.

- Reworked Joeyray's Bar to allow any outlaw as your first outlaw for free instead of only Tychus.
  - It's possible to not have Tychus active at all.
  - Calldown Odin will only revive Tychus if Tychus is recruited.
  - Cannot recruit Tychus while Odin is deployed.
  - Added silly Tychus ejecting animation when Odin dies.

It's probably still optimal to recruit Tychus, but now at least you have a choice.

- Added ability to reorder outlaws.

[Made by Maguro](https://www.maguro.one/2019/06/uiux-tweaks.html). Some additional tweaks were made to make it compatible with the previous changes.

- Reworked Tychus Attack Speed mastery into First Outlaw Attack Speed.
- Reworked Tychus Shredder Grenade Cooldown mastery into First Outlaw Ability Cooldown.

To go with the first outlaw change, this mastery set now affects your first outlaw instead of always buffing Tychus. If you change the Outlaw in the first slot using the UI reordering, the buff will be moved to that Outlaw instead.

- Reordered SCV building menu.
- Added Fortified Bunker that can be built by SCVs.
  - Can hold up to two outlaws.
  - Increases range of units inside by +2.
  - Outlaws inside can autocast abilities.
  - Fortified Bunker has extra armor and life.

Tychus's static defense is super boring, literally just an auto-turret. Hopefully this is more interesting.

- Reduced Crooked Sam's Demolition Charge visual explosion scale by 60%.

It looked like a massive explosion for a single target nuke.

- Reduced Miles "Blaze" Lewis weapon backswing and damage point.

Same change to Raynor's firebats.

- Increased the visual scale of Rattlesnake's projectiles by 45%.
- Increased the speed of Rattlesnake's projectiles by 45%.
- Increased the visual scale of Blaze's attack by 40%.

It looked silly having this giant unit shooting out tiny little attacks.

- Changed Blaze's XCMC-670 Combat Suit visuals to a glaze instead of the Hardened Shield effect.
- Reduced Blaze's XCMC-670 Combat Suit minimum from 30 to 20.

For an ultimate gear, 30 is a high minimum to reach. Reducing the minimum should increase the reliability of the gear.

- Fixed an issue where Odin's weapon tooltip showed the wrong damage.

It was showing the damage numbers from the WOL campaign instead of the Co-op numbers.

- Fixed an issue where the Odin could attack while channeling Barrage.
- Added a launch sound effect when channeling Barrage.
- Reduced cast start time of Barrage from 2 to 1.5.
- Reduced cast finish time of Barrage from 2.5 to 2.
- Increased radius of Barrage from 3 to 4.

Barrage is kinda garbage for something you only get to use once per Odin. These changes should make casting Barrage smoother, especially important for the Big Red Button rework.

- Reduced radius of Big Red Button from 12 to 8.
- Reduced Big Red Button damage falloff (Increased damage to targets far from the center).
- Reworked Big Red Button upgrade.
  - No longer replaces Barrage ability.
  - Upgrades Barrage by adding a nuke to the end of the ability.
- Changed Big Red Button to play audio sting when nuke lands instead of when it launches.
- Increased volume of nuke launch sound effect.

Is an overall nerf as the radius is reduced and now you have to channel Barrage, but it just *feels* satisfying.

- Removed the 2 second stun when Tychus exits the Odin.

Why does this even exist.

- Buffed Cannonball's Critical Response System passive to additionally deal 100 damage and knockback nearby enemies when procced.
- Added sound effect when Cannonball's Critical Response System passive procs.

Just like Artanis's Resurgence from the LotV campaign.

- Buffed Cannonball's Redline Power Cells attack speed increase from 3% to 6% per stack.
- Buffed Cannonball's Redline Power Cells attack damage increase from 3 to 6 per stack.
- Reduced Cannonball's Redline Power Cells max stacks from 20 to 10.

Cannonball is a menance when this gear is stacked, unfortunately he struggles to get there. This should make him more reliable.

- Buffed Cannonball's weapon attack to deal cone splash damage in a small area.

Makes it feel a little less bad when Cannonball crits a single zergling for 500 damage. Fun fact: all I did was uncomment some unused data.

- Reworked Nux's Ultrasonic Pulse ability to apply a damaging debuff.
  - Works like Psionic Storm now.
  - No longer stacks.
- Added an impact visual to Nux's Ultrasonic Pulse ability.

For an ability that's basically a Psionic Storm, the ability is set up weirdly different.

- Added a cursor splat for Rattlesnake's Deploy Revitalizer.
- Fixed an issue where Rattlesnake's weapon would no longer have a visual impact effect after purchasing Hammer Munitions.
- Added a new AOE visual effect after purchasing Hammer Munitions.
- Added blue trail to Rattlesnake's projectiles after purchasing Hammer Munitions.
- Reworked Vega's Psi Projector visuals.
- Fixed an issue where unit's affected by Psi Projector twice in a row would have their height visually reset.
- Added a cast animation for Rattlesnake's Deploy Revitalizer ability.
- Added a cast animation for Sirius's Deploy Warhound Turret ability.
- Fixed an issue where Sirius's Moebius M34 Terror Rounds fear buff used Han & Horner's fear icon.
- Fixed an issue where Sirius's Moebius M34 Terror Rounds fear effect would stop the AI of affected units.
- Fixed an issue where the gear delivery beam sound was classified as UI.

yeah.

### Zeratul

- Added P4: Hand of the Xel'Naga
  - Advantage:
    - Using an Artifact ability replaces it with the next choice.
    - Each choice has its own cooldown.
    - All passives are combined into one.
    - Legions can be directly controlled.
  - Disadvantage:
    - Legion and Support calldowns cooldown increased by 200%.
    - Avatar calldowns cooldown increased by 100%.

This prestige allows for dumping all your cooldowns at once but causes a longer dry spell in-between cooldown usage.

- Changed Avatar Cooldown mastery from -4 seconds per point to -1.33% per point.

Changed from seconds to percent to interact with the new P4 properly.

- Nerfed P2 to additionally increase the cost of Tesseract Cannons from 300 to 375.

It is kinda stupid you can ignore the disadvantage entirely by building Cannons instead.

- Removed the ability for Ancient Nexus to build Ancient Assimilators.
- Added Ancient Assimilators to Xel'Naga Precursor's build menu.

Zeratul already has ridiciously simple macro, let's at least make the Probes have to warp in Assmilators themselves.

- Reduced the cooldown of Stasis Beam from 90 seconds to 45 seconds.

Stasis Beam is the worst calldown out of the three, so the cooldown has been halved to make it more competitive with the other options.

- Fixed an issue where Xel'Naga Ambusher Predictive Blink autocast would only use the first charge.

For some reason, Predictive Blink would autocast once and then kinda just chill out for a while, now they will use up all charges when taking damage.

- Added a warp-out animation when legion calldowns expire.

No more watching all your Void Rays explode horribly at the end of their timed life.

- Reduced Zeratul's Psionic Lightning weapon's damage point from 0.2 to 0.15.

Matches Zeratul's ground weapon's damage point now. Should make stutter stepping slightly more consistent.

- Increased visual scale of Shadow Cleave by 20%.
- Changed Shadow Cleave impact visual to scale with the unit's scale.

Increased Shadow Cleave visual to match its actual radius. Increased the impact visual so its easier to see on bigger units.

- Reduced Dark Archon Maelstrom ability duration from 12 seconds to 8 seconds.
- Fixed an issue where Dark Archon Maelstrom ability tooltip did not display the correct duration.
- Increased radius of Maelstrom from 2 to 3.

Makes this ability more consistent.

- Reduced the visual model scale of the Serdath Legion Dark Archons by 20%.

Matches the visual scale of other archons. Serdath himself gets to stay big.

- Added VO sounds to Telbrus.
- Added VO sounds to Telbrus Legion's Zealots.
- Added VO sounds to Zoraya.
- Added VO sounds to Zoraya Legion's Void Rays.
- Added VO sounds to Serdath.
- Added VO sounds to Serdath Legion's Dark Archons.

Not sure why these guys are dead quiet but now they have a soundset for when you summon/select them.

- Changed to Ihan-rii skin set.
- Added Xel'Naga Ambusher portrait.
- Added Xel'Naga Enforcer portrait.

The Ihan-rii skin is basically a more complete version of Zeratul's skin so it used over his skin. Also added some more lore-accurate portraits.

- Fixed an issue where the warp-in animation for Zoraya Legion was visually attached overhead the Void Ray model.
- Fixed an issue where Xel'naga Abrogators could not attack map objective structures (e.g. Void Shards).
- Fixed an issue where warping in Legions were missing the void warp-in beam.
- Fixed an issue where Telbrus's Psionic Storm did not have a visual impact effect.
- Fixed an issue where Zoraya had blue beam attachments when charged.
- Fixed an issue where Construct of Form's Psionic Gale did not have a visual impact effect.
- Added a cast animation for Telbrus's Feedback ability.
- Fixed an issue where Telbrus's basic attacks used the wrong animation.
- Fixed an issue where Zoraya Legion's Void Rays used Zoraya's wireframe image.
- Fixed an issue where Tesseract Monoliths were missing the Staggering Blast button from their command card.
- Fixed an issue where Zoraya's Prismatic Beam passive tooltip incorrectly says it increases damage against massive targets.
- Fixed an issue where the placement model for the Avatars were not transparent.

yeah.

### Stetmann

- Added P4: Friend 'Til the End
  - Advantage:
    - Recycled units are spawned on Gary.
    - Lovable Little Rascals affects all recyclable units and triples the amount of remnant dropped.
  - Disadvantage:
    - Recyclable units life reduced by 30%.
    - Recycling units has a cooldown.

Units constantly get recycled back to the frontline, but in return, they die a lot easier.

- Buffed P3 to no longer make Mecha Infestors unavailable.

Felt very arbitrary to make Infestors unavailable. Why were Mecha Infestors specifically targeted?

- Added Salvage ability to Stetellites.
  - Refunds Deploy Stetellite charges if possible.
- Changed Deactivated Stetellites to be selectable.
- Added ability to Cancel rebuilding Stetellites, killing it permanently.

Previously, if you put a Stetellite too far forward, a Propagator could just feast on them for free, for the rest of the game, with no way to correct the mistake. Now you can manually take down erroneous Stetellites.

- Added P1 Advantage: Stetellites deploy 100% faster.

This makes it easier to expend charges Stetellites quickly.

- Buffed Mecha Corruptor's Cluster Busters ability to no longer be a channel.
- Fixed an issue where Mecha Corruptor's Cluster Busters ability dealt damage before the missiles landed.
- Fixed an issue where Mecha Corruptor's Cluster Busters ability launched missiles from the center of the model instead of the launchers on the side.
- Added a launch visual effect to the Mecha Corruptor's Cluster Busters ability.
- Added a 3D cursor model to the Mecha Corruptor's Cluster Busters ability.
- Adjusted Mecha Corruptor's Cluster Busters ability missile movement.
- Fixed an issue where Mecha Corruptor's Wide Area Cluster Busters did not visually increase the radius of the missiles.

Some Cluster Busters improvements.

- Reduced Mecha Corruptor's Cluster Busters ability cooldown from 10 seconds to 4 seconds.
- Reduced Mecha Corruptor's Terraclean Solvent ability cooldown from 20 seconds to 4 seconds.

Energy-based abilities should have a low cooldown!

- Changed Mecha Ultralisk's Mecha Mooch Module autocast to cast on enemies even when at full health.
- Changed Mecha Ultralisk's Mecha Mooch Module autocast to no longer prioritize own units over allies.
- Changed Mecha Ultralisk's Mecha Mooch Module autocast to prioritize friendly units with the most life.
- Changed Mecha Ultralisk's Mecha Mooch Module to allow autocasting on other Mecha Ultralisks.
- Changed Mecha Ultralisk's Mecha Mooch Module only autocast friendly units with a greater health percent.
- Changed Mecha Ultralisk's Mecha Mooch Module only autocast friendly units when missing 30 life.
- Buffed Mecha Ultralisk's Mecha Mooch Module to only deal half damage to friendly units, but still heal full.
- Increased Mecha Ultralisk's Mecha Mooch Module absorb amount from 25 to 30.
- Reduced Mecha Ultralisk's Mecha Mooch Module sound volume.

Creates an interesting Spirit Link-like effect where all the Ultralisks are trying to equalize their health.

- Reduced cost of Mecha Battlecarrier Lord's Ready Mecha Broodling ability from 5 to 2 energy.
- Reduced cost of Mecha Battlecarrier Lord's Build Mecha Locusceptor ability from 50 to 25 energy.
- Buffed Mecha Locusceptors to hit air units.
- Changed Mecha Battlecarrier Lord's Mecha Locusceptor weapon icon.

Mecha Battlecarrier Lords use a ridiculous amount of energy just to attack, there no opportunity to swap out of JUICE configuration. Lowering their energy costs should make them stronger in attrition battles.

- Fixed an issue where Mecha Ultralisks would not burrow for their Vectored Burrow Charge ability.
- Fixed an issue where Mecha Ultralisk's Vectored Burrow Charge ability did not play some FX.

The actor xml for Stetmann's units are such a disaster, things were just copy and pasted everywhere randomly. The Mecha Ultralisk model didn't even have the correct animations loaded for the burrow charge; I'm not sure this ability ever had a working burrow charge animation.

- Increased visual scale of Mecha Ultralisk's Electrostatic Surprise! by 33%.
- Changed Electrostatic Surprise! stun visual to auto scale with target model.
- Fixed an issue where the Electrostatic Surprise! stun visual would play synchronously across all stunned targets.

The visual explosion was weirdly small.

- Buffed Mecha Ultralisk's Electrostatic Surprise! to additionally affect air units.
- Buffed Mecha Ultralisk's Electrostatic Surprise! to additionally affect structures.

It's a big lightning explosion, why not hit air and structures?

- Changed Recycle Zergling button to show remnants collected instead of charges available.
- Changed Recycle Hydralisk button to show remnants collected instead of charges available.
- Changed Recycle Infestor button to show remnants collected instead of charges available.
- Changed Recycle Corruptor button to show remnants collected instead of charges available.
- Changed Recycle Ultralisk button to show remnants collected instead of charges available.

Previously the number showed how many times you can spawn the unit, which isn't very useful because its autocast most of the time anyways. Now it shows how many remnants you have collected so you know how many more you need for the next respawn.

- Added animation for Mecha Corruptor's Terraclean Solvent ability.

Copied from Versus.

- Fixed an issue where Mecha Ravagers had no spell animation when casting their Environmentally Unfriendly Eruption ability.
- Added a visual effect to Gary's Semi-Stable Mass Transportation ability.
- Increased Gary's model radius by 33% (Increases scale of certain model attachments like the recall effect).
- Increased Super Gary's model radius by 60%.
- Added flying helper splat when placing Stetellites.
- Added burrow FX to the Mecha Lurker Tunnel of TERROR Algorithm ability.
- Fixed an issue where Mecha Lurker burrow used the wrong tooltip.
- Changed Mecha Ravager's Environmentally Unfriendly Eruption autocast to target forcefields.
- Fixed an issue where Mecha Ravager Eggs used the normal zerg death model instead of the mecha one.
- Fixed an issue where Mecha Roach Eggs used the normal zerg death model instead of the mecha one.
- Fixed an issue where Mecha Ravager Eggs used the Infested Terran wireframe.
- Fixed an issue where Mecha Roach Eggs used the Infested Terran wireframe.
- Fixed an issue where Mecha Ravager Eggs did not have a "popping" animation.
- Fixed an issue where Mecha Roach Eggs did not have a "popping" animation.
- Fixed an issue where Mecha Zergling's Synthetic Adrenal Pumps passive did not drain energy.

yeah.

### Mengsk

- Added P4: Cerberus Director
  - Advantage: Dogs of War refunds 50% of energy cost and has 100% reduced cooldown.
  - Disadvantage: Dogs of War costs minerals. Trooper weapons cost 100% more.

Incentivizes spending your minerals on zerg as your frontline instead of on troopers.

- Reduced Earthsplitter Ordnance Bombardment damage from 100 to 80.
- Added 30% attack and movement speed slow for 5 seconds to Earthsplitter Ordnance Bombardment.
- Changed Earthsplitter Ordnance to target enemies automatically.
- Added visual effect of a missile dropping to the Eathsplitter Ordnance Bombardment.

Earthsplitter Ordnance are in a position where you either build exclusively them and cheese every objective or you build none. Lowering their damage but giving them crowd control and making them easier to micro should lower the ability to cheese objectives with them (which isn't exactly fun for your ally) while improving their ability to support your army.

- Added repair ability to Dominion Trooper (and variants).

https://github.com/user-attachments/assets/4e2fb0a7-a597-409c-8593-9edb9c658d20

When using mech in your army, it can be annoying having to order your troopers to build a bunker, switch to laborer, finally repair, and then switch back. If troopers can build structures, why not repair?

- Removed hit test from Imperial Witness's Amplified Airwaves hologram (Can no longer be clicked).
- Fixed an issue where Imperial Witness's Amplified Airwaves hologram would start rising unexpectedly.

It's happened to everyone, the hologram lifts off and then you accidentally a-move it and kill your own blimp. *Fun fact: this bug is caused by Blizzard attaching the hologram incorrectly, then offsetting the hologram to move it where it should be, then because it's not attached properly, it randomly applies that offset over and over again.*

- Reduced Tactical Missile Strike Delay from 4 to 3 seconds.
- Increased Tactical Missile Strike radius from 2 to 3.
- Added Ordnance Depot Retrofit upgrade to the Royal Academy.
  - Requires an Armory.
  - Allows Royal Academies to arm and store 1 additional missile at a time.

Missile play is cool so lets make it more viable! Lower delay and bigger radius should make missiles more consistent. Storing additional missiles should lower the footprint of building enough academies to constantly be nuking.

- Reduced cooldown of Emperor's Shadow's Pyrokinetic Immolation ability from 5 seconds to 0 seconds.
- Reduced cooldown of Emperor's Shadow's EMP Blast ability from 8 seconds to 0 seconds.

Emperor's Shadows are limited by energy anyways, so why do they have cooldowns on their abilities?

- Reduced cooldown of Emperor's Shadow's Labryinth Cloak ability from 30 seconds to 20 seconds.
- Added Shadow of the Dominion passive to Emperor's Shadows.
  - While cloaked, gain life regen and 30% move speed.

With such a high target priority, Emperor's Shadows tend to get sniped off, even with Labryinth Cloak. Now cloak has increased uptime and grants life regen and move speed to sustain themselves more easily. Additionally, this passive works when cloaked by any means, adding some synergy with commanders who can cloak ally units.

- Changed Emperor's Shadow's Pyrokinetic Immolation ability to apply instantly rather with a projectile (Projectile is purely visual).

It traveled so slow that often the unit is already dead by the time the ability lands, causing the explosion to not happen. Now the debuff is applied instantly for gauranteed big boom.

- Improved autocasting AI for Emperor's Shadows.
  - Autocasts Pyrokinetic Immolation if no enemies near target are immolated.
  - Autocasts EMP Blast if not stunned.
- Fixed an issue where Pyrokinetic Immolation and EMP Blast would have their autocast toggled off after leveling up.
- Changed Pyrokinetic Immolation to no longer allow casting on targets already immolated.

Hopefully prevents dumping all their energy at once. Still probably more efficient to cast these yourself.

- Removed random delay between shots from Pride of Augustgrad's weapon.

Overall increases attack speed and allows the Battlecruiser to be affected by attack speed buffs.

- Added passive to all Royal Guards that reduced spell damage taken by 50%.

Nobody likes having their elite units Yamato'd to death, this should help their survivability against unpreventable bursts of damage.

- Reworked Aegis Guard's Aegis Barrier passive from granting a 300 damage absorb to granting 300 shields.

Makes it possible to track the Shield on the unit info panel. Will now interact with things like EMPs and Shield Batteries.

- Increased Sky Fury's Gatling Cannon damage from 18 to 24 (+16 vs Mechanical).
- Increased Sky Fury's Lanzer Torpedos Damage from 15 (+6 vs Armored) to 28.

Sky Furies have bad damage against non-massive targets, and still do less damage than an Aegis Guard even against massive targets.

- Increased duration of Sky Fury's Tactical Realignment from 5 seconds to 10 seconds.
- Reworked Sky Fury's Tactical Realignment to increase attack speed by 50% instead of attack damage.
- Removed Sky Fury's Tactical Realignment cooldown.

This passive sucked. Increasing the duration and removing the cooldown should make this actually usable. Increase attack speed instead of attack damage to help mitigate overkill.

- Changed Aesir Turbines effect to additionally increase movement speed of Assault Mode Sky Furies by 25%.

The original passive never even explicitly stated it only affects Fighter Mode!

- Added additional effect to Sky Fury's Rank 1 that increases weapon range by +2.

Sky Furies are super fragile until reaching Rank 3. Increased range should help them kite enemies, especially with the Viking speed upgrade.

- Reduced Pride of Augustgrad Yamato Cannon cooldown from 120 seconds to 100 seconds.

They had a longer cooldown than Versus Battlecruisers!

- Removed fake heal from Imperial Intercessors.

It was so annoying when these got stuck too far back, now they'll push up with your army. They might push up *too* far but hey, they have cloak and Ignite Afterburners. Healer AI in general may be revisited in the future.

- Added Pride of Augustgrad portrait.
- Added Sky Fury portrait.
- Added Imperial Intercessor portrait.
- Added Imperial Witness portrait.
- Added Shock Division portrait.
- Added Blackhammer portrait.

Mengsk's infantry had custom portraits, but not his mech.

- Improved Mengsk status bars to show energy/shield and be wider for Thors/Battlecruisers.

Previously the status bar only showed hp.

- Adjusted Labryinth Cloak tooltip to be more accurate.
- Fixed an issue where after researching Scatter Veil, Imperial Intercessor's shield icon tooltip would say "Unknown".
- Fixed an issue where Contaminated Strike's fear effect would stop the AI of affected units.
- Added a warning splat for 2 seconds after casting Contaminated Strike.
- Fixed an issue where Enthralled Mutalisks used Zerg Ground Carapace instead of Zerg Flyer Carapace.
- Fixed an issue where Enthralled Mutalisks used Dehaka's flyer weapon icon instead of the Zerg flyer weapon icon.
- Fixed an issue where Enthralled Zerg weapons/armor did not change icon with weapon/armor upgrades.
- Fixed an issue where Earthsplitter Ordnance would sometimes use the green visual launch effect when using Bombardment.
- Fixed an issue where most structures did not have a visual burn effect when burning down.
- Added a visible debuff when Sky Fury's Phoenix Protocol is on cooldown.
- Fixed an issue where Sky Fury's Phoenix Protocol did not show the cooldown on the command card.
- Fixed an issue where Aegis Guard's Incapacitor Shells tooltip incorrectly states massive units are immune.
- Improved Aegis Guard's Incapacitor Shells debuff tooltip.
- Fixed an issue where Blackhammer's attack muzzle flash only appeared on the right weapon.

yeah.

## Credits

- Warp Stargate Alternate - DaveSpectre
- Nerazim Corsair V2 - DaveSpectre/HammerTheTank107
- Signifier (Lenassa) - Nerazim HT V2 (Based on concept by Phill-Art) - DaveSpectre
- Void Ray Reforged (Updated Void Ray model) - DaveSpectre/HammerTheTank107
- Red Ascendant Shadow Trail - DaveSpectre
- Shadow Guard / Shakuras Signifier (Thrikodias version) - DaveSpectre/Thrikodias
- Shadow Guard / Shakuras Centurion - DaveSpectre
- Shadow Guard / Shakuras Stalker - DaveSpectre
- Improved Dark Templar Models - DaveSpectre
- Winged Archon / Dark protoss Archon portrait - DaveSpectre
- Nerazim Shadow Archon - DaveSpectre
- Female Nerazim Shadow Archon - DaveSpectre
- Mothership Placement & Warp In - DaveSpectre
- Nerazim Probe - DaveSpectre
- SC: Evolution Complete for Creators - SC: Evolution Complete Team
- Infested Kerrigan - StarCraft: Remastered look - DaveSpectre
- Brood Queen / SC1 Queen Portrait + Leviathan Brood Version - DaveSpectre
- Infested SCV Portrait - DaveSpectre
- Infested Diamondback Portrait - DaveSpectre
- Infested Liberator Portrait - DaveSpectre
- Volatile Infested colonist Portrait - DaveSpectre
- Infested Trooper - DaveSpectre
- Primal Impaler - DaveSpectre
- Ambusher (Ihan-rii Stalker) / Alrasz (Ambusher Hero) portrait - DaveSpectre
- Enforcer / Ihan-rii Immortal Portrait - DaveSpectre
- Vulture with flaming Jets - DaveSpectre
- Nerazim Structure Pack (+ effects) - DaveSpectre
- Royal Guard Portraits (Co-op) - DaveSpectre
- Purifier Shield Battery - Enoki
- Better Mengsk Status Frames - Enoki
- Common Sense Balance - OmniSkeptic
- Data-Driven Turrets - Enoki
- Tosh co-op commander icon pack - DaveSpectre
- Taldarim Iconpack - DaveSpectre
- Taldarim Building Warp in Pack (Red) - herdal
- Generic Taldarim Building Death (Red) - herdal
- Taldarim Ground Units Warp in (Red) - herdal
- ProtossBuildRed2345.m3 (It didnt have an actual release, give me a break!) - ordinator
- Red Tal'darim Air Units Warp In Effects & Placements - DaveSpectre
- Red Tal'darim Warp In Stargate Effects (+ Robotics facility Warp Ins) - DaveSpectre
- Tal'darim Stalker (Slayer) blink model. - DaveSpectre
- Tal'darim Heroes Extras - DaveSpectre
- Terrazine Refinery Pack V2 - SheeldWall

DaveSpectre is the goat <3
