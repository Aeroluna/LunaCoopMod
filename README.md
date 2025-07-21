# LunaMod

A set of changes and additions to the StarCraft 2 Co-op mode.

## General

- Added console skins for all commanders.
- Added voice packs for all commanders.

Some console skins were missing for commanders. Many commander have corresponding voice packs, why not use them?

- Added Shield Batteries to Artanis, Vorazun, Alarak, and Fenix.
- Increased Shield Battery range by 2.

Shield Batteries can help other Protoss commanders that rely on armies to defend rather than Photon Cannons.

- Removed Armored attribute from Queens.

No more getting obliterated by Immortals.

- Added autocast for Queen's Transfusion.

Won't cast efficiently but does help if you are overcapping energy anyways.

- Reordered many command cards to match Versus.

Help muscle memory from Versus for people who use grid hotkeys.

- Added Unload Heroic ability to Nydus Worms.

Implemented by [Maguro](https://www.maguro.one/2019/06/uiux-tweaks.html), this feature has been slightly improved to not show the ability if you have no Heroic units loaded.

- Fixed Protoss warp-in animations.

For some reason, warp in animations had a fixed duration of 16 seconds, so it was broken for any unit that didn't take 16 seconds to warp in.

- Removed Wait Until Stopped flag from Viking Assault Mode and Fighter Mode.

Makes Raynor and HH Viking feel smoother to land.

## Amon

- Removed slow from Viper Disabling Cloud.

Possibly number one most infurating spell to get hit by? Abathur Vipers are unaffected.

## Raynor

- Added Medivacs.
  - Heal more efficiently than Medics, but same heal speed.
  - Added Caduceus Reactor upgrade available at the Fusion Core that doubles energy regen for Medivacs.
  - Stabilizer Medpacks also affect Medivacs.
  - Units unloaded benefit from the Drop Pod Haste mastery.
  - Can carry sieged Siege Tanks.
  - Have lower cooldown Ignite Afterburners (20 seconds).

Medivacs are cool, what more needs to be said? The more efficient healing and increased energy regen can be very useful when paired with P1. Can also be useful to have a flying medic when going Starport units. The Drop Pod haste along with the autocast stim allows for a fun strat of doom dropping.

- Increased Siege Tank (Sieged) cargo size to 8.

Necessary so Medivacs can only carry one Siege Tank. Unintentially nerfs Swann so this might need to be revisited.

- Changed Medic portrait.

Changed to be distinct from the Medivac portrait.

- Buffed Ignite Afterburners to additionally increase acceleration by 1000.
- Removed the random delay on Battlecruiser weapons.
- Reworked P2.
  - Removed Ignite Afterburners cooldown.
  - Added autocast to Ignite Afterburners.
  - Ignite Afterburners no longer requires research.

Copied from CXL. Stimmed Siege Tanks chew up attack waves and the properly working stimmed Battlecruisers just look comical.

- Reduced Firebat weapon backswing and damage point.

Small change to make stutter-stepping with Firebats feel smoother.

- Added new Medic ability: Restoration.
  - Removes any negative effects on target allied unit.
  - Can remove Seeker Missile, Parasitic Bomb, and Irradiate.

*I come to cleanse this land.* A niche ability that helps Raynor against spellcasters. Is also a powerful tool against the Black Death mutation. Gives Medics more depth than just an a-move unit.

- Added autocast to Stimpack.

Potentially too OP having units perfectly stim, but if Nova's marines can have it, why not Raynor?

- Added double MULEs.

Old Raynor nerf reverted. Should help out P0 Raynor.

- Buffed Viking Ripwave Missiles to additionally grant Gatling Cannons splash.
- Added +8 vs. Mechanical damage to Viking Gatling Cannons.
- Added faster transformation speed to Phobos Weapons System.

Some ground Viking buffs because why not.

- Reworked Hyperion weapons.
  - AOE attack turned into a proper weapon and is affected by buffs like attack speed.
  - Attack speed of single target and AOE weapon changed to 0.11.
  - Unit info shows single "ATX Laser Battery" weapon.
  - Will prioritize using AOE weapon unless issued attack order.

No longer have to queue a bunch of move commands to get value out of the Hyperion, it now gets full attack speed from just a-moving. Attack speed was slightly nerfed to 0.11 to adjust for Raynor's level 15 perk now properly affected the weapon.

- Changed Hyperion portrait and sounds back to Horner.

Just because he's a commander now doesn't mean he forgot how to pilot the Hyperion!

- Added cosmetic flame jets to Vultures when moving.

## Kerrigan

- Fixed a bug where P1 and P3 used each other's icons.
- Reworked P2.
  - Disadvantage makes Kerrigan unavailable instead of removing Nydus Networks.
  - Advantage additionally increases combat unit health by 50% and grants the Twin Drones upgrade. Creep Tumors gain Super Cloak when burrowed.

Malevolent Matriach was kinda boring, so lets turn the dial up to 11. The prestige is now strictly focused on Kerrigan's army. The twin drones upgraded is added to help ease the massive nerf to Kerrigan's early game.

- Added P4: Champion of the Brood War
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
  - Replaces all combat units with elite Brood War variants that have 200% more health and 50% more weapon damage but cost 200% more resources and supply.
  - Replaces Zergling with Devouring One.
    - Gains Cannibalize passive.
      - Heals for 20 life when a biological unit dies nearby.
  - Replaces Queen with Brood Matron.
    - Gains Protective Brood passive.
      - Grants 3 life regeneration and 0.5625 energy regeneration to nearby friendly units.
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

What if Nova's design met Kerrigan? Hunter Killers, Devouring Ones, and Torrasques return from Brood War with some new friends. Kerrigan has also been rebranded with a new Brood War themed skin, which is much better than the boob sacs and bone heels of SC2's design (Seriously, why did they try to make her sexy?).

Elite Zerglings are my personal favorite, their Cannibalize passive fits their name perfectly and greatly improves their survivability when fighting in packs, espescially when fighting bio armies. The Queen passive should help sustain the massive health pools of the new units. Mutalisks with extra damage massively benefit from their 2 glaive upgrades, and now that their one weakness, being squishy, has been mitigated, they are monsters. The improved Broodling lifetime sounds small at first, but it snowballs fast into a huge army of elite Broodlings.

- Changed P3 voice lines.

Now uses the pre-infested voice lines from Heart of the Swarm.

## Artanis

- Reworked Phoenix weapon damage from 7 (+5 vs Light) to 10 (+2 vs Light).
- Reduced Phoenix price from 150/100 to 150/50.

Phoenixs were extremely dependent on enemy composition. Moving some damage from the bonus should help. Also decreased the vespene price to make them easier to mass when going skytoss.

- Added the Mothership.
  - Available from the Nexus for 1000/1000 after building a Fleet Beacon.
  - Uses energy to cast abilities.
  - Can use Mass Recall for 50 energy.
    - Identical effect to Alarak's Mass Teleport.
  - Can use Vortex for 50 energy.
    - Similar to Wings of Liberty Vortex.
    - Enemy units no longer get invulnerability while leaving the vortex (Still stunned).
    - Friend units are no longer stunned while leaving the vortex (Still invulnerable).
    - Deals up to 100 damage to enemy units within the Vortex.
    - Damage doubles with P1.
  - Can use Planet Cracker every 360 seconds.
    - Briefly charges up before scorching the ground beneath the Mothership for 20 seconds, causing 1200 (1800 vs Armored) damage in an area below. Deals more damage closer to the beam.
    - Damage doubles with P1.
  - Provides a power field nearby.
  - Uses Cloaking Field to cloak nearby friendly units/structures.

An iconic unit thats missing from co-op, is now back. Mass Recall should help with Artanis's mobility problems. Vortex no longer grants invulnerability to enemy units so Archon toilets are back on the menu. Planet Cracker is such an iconic ability, it had to be added. Projecting a constant power field stays in line with Artanis's design of quickly warping in reinforcements during combat.

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

## Swann

- Added Thor's High Impact Payload mode from Versus for single-target long-range damage.
- Buffed Multi-Lock Weapons System upgrade to additionally affect the Thor.
- Buffed Infernal Plating upgrade to additionally grant Thor armor and increase Hellbat/Hellion armor by 60.

These changes should make Thors much more competitive. Increased Hellion/Hellbat health should make mineral dumping into them more efficient and make them more viable as a frontline.

- Changed Cyclones to visually have their red lazer sights with Mag-Field and large missiles when locking on from Versus.
- Buffed Cyclone's Lock On to no longer be affected by armor.

The little missile that was fired during Lock On was just sad, now Cyclones look as cool as they do in Versus. Also Lock On is a spell, and should not be affected by armor.

- Added Widow Mines.
  - Added Hellburst Payload upgrade that increases Sentinel Missile direct damage by 20 and splash damage by 80.
  - Cyclone's Targeting Optics upgrade additionally increases Sentinel Missile range by 3.

Why not give the mech commander more mech? Widow Mines go well with Swann's defensive design. The Hellburst Payload massively improved splash damage can be absolutely devastating.

- Added Smart Servos upgrade that increases the morph rate of Hellions, Hellbats, Thors, Siege Tanks, and Widow Mines.
- Added Overdrive Actuators upgrade at the Armory that increases ground vehicle movement speed by 20% and ship movement speed by 10%.
- Added Pulse-Loop Capacitors upgrade at the Armory that decreases all unit cooldowns by 20%.

These general improvements should make playing ground mech much smoother (Why does Raynor have fast Siege Tank morph speed but Swann doesn't?). Smart Servos helps deploying Widow Mines during combat, Overdrive Actuators helps playing battle mech (Hellion/Cyclone) much easier to kite with, and Pulse-Loop Capacitors helps Widow Mines and Cyclones deal more consistent damage.

- Added the ability to morph Orbital Commands that have access to Calldown: Extra Supplies and Scanner Sweep.

Scanner Sweeps should help Cyclones keep their Lock On active and provide detection without having to rely on the slow Science Vessels. Additionally, Calldown: Extra Supplies to help with the constant supply blocks on Swann.

- Added the ability to morph Planetary Fortresses.
  - Swann level 3 perk additionally upgrades Planetary Fortresses to Big Berthas, increasing damage and splash range.
  - Planetaries are considered turrets for all turret upgrades.

An iconic defensive Terran structure for the defensive Terran commander.

- Reworked Defense Matrix to no longer require research.

https://www.maguro.one/2017/10/upgrades-in-co-op.html

- Added P4: Rolling Thunder
  - Advantage: Combat units can attack while moving. Start with the Multi-Lock Weapons System upgrade. Cyclones can use Lock On while moving. Only Thor anti-air weapons can attack while moving. Hellbat, Thor heavy air, and Goliath ground weapons can only fire in an arc in front of them while moving.
  - Disadvantage: Hercules are unavailable. Turrets are 100% more expensive.

Allows for fun playstyles like running around with battle mech or flying Wraiths around like Phoenixes. The disadvantage is probably not powerful enough to warrent how strong the advantage is.

## Zagara

- Reworked Bile Launchers.
  - Can now target enemies automatically.
  - Bombardment ability now uses smart casting.
  - Bile Bombs now reveal a radius of 3 around them.

Idea stolen from CXL, should make Bile Launchers more effectively than just on infested maps.

- Added Defilers.
  - Can use Dark Swarm for 100 energy.
    - Creates a micro-organism cloud preventing all incoming ranged and splash damage for 30 seconds.
  - Can use Plague for 150 energy.
    - Infects all enemy units and buildings in the target area, inflicting 300 damage over 20 seconds. Cannot reduce units or buildings below 1 life. Ignores shields. Reveals infected cloaked units.
  - Can use Consume.
    - Kills target friendly biological unit metabolizing it into 75 energy.
  - Added Metasynaptic Node upgrade at the Infestation Pit.
    - Adds 50 max energy and starts at full energy.

Gives Zagara a unit that isn't just a-move. Mixing defilers allows for taking far more efficient trades. Defilers can also easily get energy from consuming Zagara's cheap units.

- Increased visual scale of Hunter Killers by 20%

When Hunter Killers were given the webby skin, their scale was accidently reset to the normal Hydralisk scale.

- Buffed Infested Drop Roaches to Corpser Roaches.

Corpser representation!

- Reduced Scourge vespene cost by 25.
- Removed Simplified Genome.
- Added Dampening Membrane upgrade that reduces the splash and spell damage dealt to Scourge by 75%.
- Increased Corruptor damage from 14 (+14 vs Armored) to 28 (+14 vs Armored).

Scourge were incredibly inefficient to morph before evolving Simplified Genome, so it has been made baseline. If you've ever felt the pain of watching your Scourge die to one storm, the new upgrade should help increase the reliability of Scourge against AOE. Corruptor damage has also been buffed so they have actual DPS instead of just tickling air comps. These changes should improve Zagara's anti-air capabilities.

- Increased max supply from 100 to 150.

One of Zagara's greatest weaknesses is the inability to hit a critical mass of units to trade efficiently.

- Changed Zagara's temporary units to visually burrow away instead of exploding when expiring.
- Added Swarm Networks.
  - Can summon Swarm Locus at a targeted location that will unload temporary units to fight.
  - Temporary zerg last 60 seconds, are uncontrollable, and attack closest enemies.
  - Queen will try to place Creep Tumor if too few other Creep Tumors nearby.
  - Limited to 4.

If there is one think Stukov P3 has taught me, it's that throwing free units at Amon is fun as hell. The Creep Tumors also act as a form of creep spread that Zagara is lacking. These act as a sort of top bar ability that Zagara is missing.

- Added P4: Subterranean Tide
  - Advantage: Swarm Networks are no longer limited, cost 25% less, and spawn 50% more units.
  - Disadvantage: Combat units cost 25% more. Swarm Networks cost 100 more minerals for every one built.

I added a whole new mechanic to Zagara and then created a whole prestige surrounding it. Hell yeah.

## Vorazun

- Changed Vorazun to use custom Nerazim skinset.

Green warp ins! Dark Templar now use both variants and Shadow Guard use the Golden skinset. Centurions, Stalkers, Dark Templar, Dark Archons, Corsairs, and Void Rays are given a makeover. Also changes some icons.

- Added Vespene Crystalization, increasing vespene harvest rate by 25%.

Vorazun is one of the most vespene limited commanders. Increasing her vespene harvest rate should help with the large amount of upgrades she needs and her extremely gas heavy army.

- Buffed Vorazun level 1 perk to additionally increase the shields of all combat units (except Dark Templar) by 40.

This should help increase the survivability of all her other units. Pairs well with her level 7 perk for increased shield regeneration rate.

- Buffed Disruption Web to no longer require research.
- Added Flux Vanes upgrade that increases the movement speed and acceleration of Void Rays.

Disruption Web research has been replaced with Flux Vanes. Baseline Disruption Web should help increase the value of the first few Corsairs while the Flux Vanes upgrade should help Void Rays feel better to kite with.

- Added Signifiers, an astral-themed High Templar.
  - Available after building a Templar Archives.
  - Can use Aurora Veil for 50 energy.
    - Grants cloak to friendly units in an area and heals their hitpoints over time for 30 seconds.
  - Can use Astral Storm for 75 energy.
    - Does less damage in a large area than Psionic Storm for 20 seconds.
    - Applies Astral Smolder to enemy units hit, revealing cloaked units, reducing movement speed, and reducing armor. This effect stacks up to 4 times.
    - Applies P2, dealing massive damage.
  - Can use Fading Star after researching at a Templar Archives.
    - Grants super cloak, 50% increased movement speed, and ignores collision for 4 seconds.
    - Can be autocast when damaged.
  - Argus Crystal additionally grants Signifiers full energy.
  - Dark Archon upgrades moved to Templar Archives.

A cut unit from the LOTV campaign reimagined. Astral Storm provides detection outside of Oracles. Aurora Veil massively helps non-cloaked units like Stalkers, Centurions, Dark Archons, and Void Rays benefit from Vorazun's stealth perks and makes them viable. The addition of a damaging spellcaster also helps improve the value of increased energy regeneration from Vorazun's level 15 perk.

- Reworked Dark Archons to no longer be trained at a gateway, but instead from merging two Dark Templar or Signifiers.
- Increased Dark Archon weapon damage to 25 (+10 vs Biological)

Should make massing Dark Archons more viable instead of watching them tickle units.

- Changed Dark Archon skin.
  - Visually green instead of red.

The Dark Archon skin has been used by Tal'darim (Both as Warchest skins and as a skin in NCO), so instead, the Dark Archon is given a unique Nerazim themed skin. As a cool added bonus, using two Signifiers will create a female Dark Archon instead.

- Buffed P2 to reduce Stasis Ward duration by 50% instead of 75%

For the prestige focused on stasising things, the P2 just makes Stasis Wards sad. This slight buff should help with that.

- Reworked Void Stasis to target air units and no longer make the unit invulnerable.

Ever get annoyed when your Dark Templar would run in and automatically stasis Missile Turrets you were trying to snipe? Removing the invulnerability makes it much easier to snipe detection while fighting. Being able to stasis air units additionally makes Dark Templar much sneakier against flying detectors like Overseers.

- Buffed Emergency Recall to cleanse negative debuffs.

No more recalling Black Death straight into your mineral line.

- Added autocast to Stalker Blink.

Unsurprisingly, autocasting the shield restoring Blink when out of shields is strong.

## Karax

- Implemented [Maguro's Karax 2.0](https://www.maguro.one/p/karax.html) with some changes.
- Reworked Carrier Repair Drone behavior to previous version, but with improved autocasting to no longer require stopping.
- Removed Combat Chrono Wave.
- Removed the ability to Chrono Boost defensive structures.
- Nerfed Improved Reconstruction to 120 seconds.
- Reworked Phoenix weapon damage from 7 (+5 vs Light) to 10 (+2 vs Light).

Karax 2.0 has great quality of life changes for Karax, so lets use them. Chrono Boosting defensive structures removed to not step on P1's toes. Nerfed Improved Reconstruction because Sentinels are pretty much unkillable anyways.

- Reworked Karax P2 disadvantage to increase the price of Photon Canon and Khaydarin Monlith by 100% instead of disabling them.

Copied from CXL. Keeps it unviable to use static defense aggressively without completely removing the option defensively. Especially useful for dealing with ghosts.

- Added Instigators.
  - A Purifier variant Stalker.
  - Added Displacement Matrix upgrade that lowers the cooldown of Blink to 4 seconds and allows up to 3 charges.
  - Blink can be set to autocast to automatically blink when the hull takes damage.

Karax's anti-air is very lackluster, adding a ranged gateway unit helps greatly with that. The Adept is already used by Fenix, so why not add the unused Purifier unit, the Instigator? Having up to three low-cooldown Blinks on autocast lets these units skirmish effectively and can get pretty chaotic.

- Added Disruptors.
  - Has Fenix Disruptor upgrades.
  - Has regular controllable nova.
  - Increased nova speed from 2.25 -> 3.25
  - Reduced cooldown of Purification Nova from 30 seconds to 10 seconds.
  - Increased Purification Nova radius by 20%.
- Reduced price of Cloaking Module from 100/100 to 50/50.
- Reduced price of Purification Nova from 150/150 to 100/100.

Disruptors are rarely used with Fenix because it benefits from none of Fenix's Champion AI perks. Hopefully they are a better fit for Karax along with some extra buffs to make it more appealing.

## Abathur

- Buffed Viper Consumption to also target structures.
- Buffed Virulent Microbes upgrade to additionally increase the radius of Viper abilities by 2.
- Buffed Biomass to additionally increase max energy by 1% per biomass.
- Buffed Biomass to additionally increase spell damage for casters (not Ravagers) by 1% per biomass.
- Buffed Abduct to allow abducting Heroic units (will pull but not stun).

Vipers rarely were worth mixing into your army, now they should be much more usable and be competitive in anti-air with Devourers.

- Added autocast to Corrosive Bile (initially off).

Should help keeping Corrosive Bile on CD with the Biomass CDR. It won't predict so it might be better to leave this off in some circumstances.

- Buffed Swarm Host by upgrading to Creeper strain.

Abathur's Swarm Host already got the Deep Tunnel ability, now they poop creep as well.

## Alarak

- Changed Ascendant shadow trail model to be red.

## Stukov

- Added Rotwing Rotors upgrade that increases Infested Banshee speed by 2.
- Reworked Infested Banshee P2 Deploy ability to allow casting while moving.

These two simple changes make playing P2 infinitely smoother to play.

- Added Infested SCV portrait.
- Added Infested Diamondback portrait.
- Added Infested Liberator portrait.
- Changed Infested Siege Tank portrait to Infested Diamondback portrait.
- Changed Infested Civilian portrait.
- Added Infested Trooper model and portrait.

Blizzard got lazy and only reused portraits for Stukov, this adds new ones!

- Reworked Infested Marines
  - Buffed supply cost from 1 to 0.5.
  - Doubled cost but spawns 2 from 1 egg.
  - Halved max charges and doubled charge cooldown on Infested Barracks.

These guys clog up your supply until they time out, this should help mitigate that.

## Fenix

- Remove Disruptors.

Disruptors are rarely used with Fenix because it benefits from none of Fenix's Champion AI perks. The disruptors have been moved to Karax.

## Dehaka

- Changed Primal Impaler model.

The unit previously used the Primal Lurker skin, now it uses a proper Impaler skin.

- Nerfed the damage from using Consume on a psionic unit from 2x weapon damage to 1x weapon damage.
- Added a cleave to Dehaka's Claws weapon.
- Added splash damage to Dehaka's Mammoth Beam weapon.
- Increased the damage of Dehaka's Mammoth Beam by 50%.

Should reduce Dehaka's reliance on psionic units for clearing waves. Dehaka gains a frontal cone cleave to his Claws and splash damage to his Mammoth Beam to compensate. Also increased the damage of the Mammoth Beam so it feels more desireable to get.

## Tychus

- Added ability to reorder Tychus outlaws.

https://www.maguro.one/2019/06/uiux-tweaks.html

## Zeratul

- Reworked Xel'naga Ambusher Predictive Blink autocast.

For some reason, Predictive Blink would autocast once and then kinda just chill out for a while, now they will use up all charges when taking damage.

- Changed to Ihan-rii skin set.
- Added Xel'Naga Ambusher portrait.
- Added Xel'Naga Enforcer portrait.

## Stetmann

- Buffed Stetellites by adding Map Boss attribute.

Grants immunity to certain mutators like Propagators. Previously, if you put a Stetellite to far forward, a Propagator could just feast on them for free.

## Mutators

- Reworked Fatal Attraction to no longer make the units uncommandable.
  - No longer disables units attacks, abilities, and movement.
  - Pull strength increased by 20%.
  - Dehaka's Primal Impalers are no longer pulled.

The most infurating mutator because it can permastun your units as well as interrupt all their orders. The obnoxious stun has been removed and given stronger pull stength as compensation.

## Credits

- Warp Stargate Alternate - DaveSpectre
- Nerazim Corsair V2 - DaveSpectre/HammerTheTank107
- Signifier - Nerazim High Templar (Based on concept by Phill-Art) - DaveSpectre
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
- Alternate Medic & Medivac Portraits - miazmatic
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
