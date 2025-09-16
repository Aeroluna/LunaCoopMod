# LunaMod

A set of changes, additions, and bug fixes to the StarCraft 2 Co-op mode.

## General

- Added Brutal+ system.
  - Can select a Brutal+ level to randomize mutators.
  - Can use refresh button to rerandomize.
  - Can use +Retry option to retry previously played mutators.
  - Added Brutal+ levels 7 - 10.

Added Brutal+ system. See Mutators section for specific changes to mutators.

- Added ability to select a fourth prestige.

Not all commanders have a fourth prestige yet, but do try the ones that exist!

- Added console skins for all commanders.
- Added voice packs for all commanders.

Some console skins were missing for commanders. Many commander have corresponding voice packs, why not use them?

- Added Shield Batteries to Artanis, Vorazun, Alarak, and Fenix.
- Increased Shield Battery range by 2.

Shield Batteries can help other Protoss commanders that rely on armies to defend rather than Photon Cannons.

- Buffed mind control effects to keep upgrades of targeted unit.
- Buffed Dark Archon Mind Control ability to no longer take up supply.

Who cares if it's OP? If Zeratul exists, what does OP really mean anyways? This affects Vorazun's Dark Archons, Karax's Sentries, Tychus's Vega, and Zeratul's Serdath Legion.

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

- Added cosmetic flame jets to Vultures when moving.

*Bring it on!*

- Fixed a bug where all Zerg building construction sounds would use Stetmann's Mecha variants.

Fun fact: this bug has existed as long as Stetmann has.

- Fixed a bug where Viper Abduct would not unburrow most units.

You are pulling them into the air after all.

- Fixed various commander-specific upgrades appearing on the command card.

This includes upgrades like Virulent Microbes erroneously showing up on mind-controlled Vipers or Extended Thermal Lance missing from Fenix's Colossi.

- Added a range indicator when using the Oracle's Stasis Ward ability.

yeah.

- Fixed a bug where Carriers would not show how many Interceptors they have under their healthbar (Affects Karax and Fenix).

Fun fact: This bug has existed since Fenix was released. This bug was caused by the ability for Carriers to morph into Clolarion, though I genuinely don't understand why it happens or why it affects Karax's Carriers.

- Changed Void Rays to "look" at their targets.

thanks Enoki.

- Added targeting beam to Widow Mine attack (Affects Swann and Horner).
- Increased visibility of targeting line and targeted unit (Targeted unit is tinted).
- Added a visual indicator to Colossus attacks when Extended Thermal Lance is researched (Affects Fenix).
- Added a visual indicator to Phoenix attacks when Anion Pulse Crystals is researched (Affects Artanis and Karax).
- Added a visual blue trail to Marauder attacks after upgrading Concussive Shells (Affects Raynor, Nova, Tychus, and Mengsk).
- Increased Zealot animation walk speed from 2.25 to 3. This makes Zealots visually bounce around less at high movement speeds (Affects Artanis, Vorazun, Karax, and Fenix).
- Added turret tracking to Colossi (Affects Karax and Fenix).

Copied from Versus.

- Increased the arc of Phoenix Graviton Beam from 0 to 360 for commanders.
- Increased Lurker attack spine animation speed by 75%.
- Increased Lurker attack impact model scale by 75%.
- Fixed a bug where moving a Ravager directly after casting Corrosive Bile would visually keep the legs stationary and appear to glide.
- Changed Hi-Sec Auto Tracking to additionally visually increase the upgrade level on the unit info panel.
- Changed Phoenix weapon attack priority to attempt to keep hitting the same target.
- Added turret tracking to Hellions.
- Fixed a bug where Hellions would not play their attack animation.
- Reduced visual scale of High Templar's Psionic Storm ability.
- Increased visual scale of Psionic Storm impact effect.
- Added Disruptor tint when firing and when on cooldown.

thanks Common Sense Balance.

## Amon

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
- Buffed Spawn Broodling to allow targeting massive units (This only affects mind controlled Brood Queens).
- Reworked Spawn Broodling casting AI.
  - Will not be used on Normal difficulty and lower.
  - Added a 30 second cooldown.
  - Only targets units with less than 100 max hitpoints.

Fun fact: Spawn Broodling was previously only casted on Siege Tanks. They explicitly target low health units because otherwise it would just be frustating getting your expensive units sniped without a counter.

- Removed Detector from Oracles.

A leftover from granting detection to Vorazun's Oracles. Vorazun is unaffected.

## Raynor

- Added Medivacs.
  - Heal more efficiently than Medics, but same heal speed.
  - Added Caduceus Reactor upgrade available at the Fusion Core, which doubles energy regen for Medivacs.
  - Stabilizer Medpacks also affect Medivacs.
  - Units unloaded benefit from the Drop Pod Haste mastery.
  - Can carry sieged Siege Tanks.
  - Have lower cooldown Ignite Afterburners (20 seconds).

Medivacs are cool, what more needs to be said? The more efficient healing and increased energy regen can be very useful when paired with P1. Can also be useful to have a flying Medic when going Starport units. The Drop Pod haste along with the autocast stim allows for a fun strat of doom dropping.

- Increased Siege Tank (Sieged) cargo size to 8.

Necessary so Medivacs can only carry one Siege Tank. Unintentially nerfs Swann so this might need to be revisited.

- Changed Medic portrait.

Changed to be distinct from the Medivac portrait.

- Added new Medic ability: Restoration.
  - Removes any negative effects on target allied unit.
  - Can remove Seeker Missile, Parasitic Bomb, and Irradiate.

*I come to cleanse this land.* A niche ability that helps Raynor against spellcasters. Is also a powerful tool against the Black Death mutation. Gives Medics more depth than just an a-move unit.

- Added Cellular Reactor upgrade, which gives Medics full starting energy.

Anyone who has played P1 knows how painful it is to get energy on these things.

- Buffed Ignite Afterburners to additionally increase acceleration by 1000.
- Added visual boost effect to Medivac and Banshee when using Ignite Afterburners.
- Removed the random delay on Battlecruiser weapons.
- Reworked P2.
  - Removed Ignite Afterburners cooldown.
  - Added autocast to Ignite Afterburners.

Copied from CXL. Stimmed Siege Tanks chew up attack waves and the properly working stimmed Battlecruisers just look comical.

- Reduced Firebat weapon backswing and damage point.

Small change to make stutter-stepping with Firebats feel smoother. What mod doesn't do this?

- Added autocast to Stimpack.

Potentially too OP having units perfectly stim, but if Nova's marines can have it, why not Raynor?

- Added double MULEs.
- Added invulnerability to unburrowed spider mines.

Old Raynor nerfs reverted. Double MULEs in particular should help out P0 Raynor.

- Buffed Viking Ripwave Missiles to additionally grant Gatling Cannons splash.
- Added +8 vs. Mechanical damage to Viking Gatling Cannons.
- Added faster transformation speed to Phobos Weapons System.

Some ground Viking buffs because why not.

- Reworked Hyperion weapons.
  - AOE attack turned into a proper weapon and is affected by buffs like attack speed.
  - Attack speed of single target and AOE weapon changed to 0.11.
  - Unit info shows single "ATX Laser Battery" weapon.
  - Will prioritize using AOE weapon unless issued attack order.
  - Removed random delay from weapon.

No longer have to queue a bunch of move commands to get value out of the Hyperion, it now gets full attack speed from just a-moving. Attack speed was slightly nerfed to 0.11 to adjust for Raynor's level 15 perk now properly affecting the weapon.

- Changed Hyperion portrait and sounds back to Horner.

Just because he's a commander now doesn't mean he forgot how to pilot the Hyperion!

- Added behavior to Calldown MULE, will try to search for nearby mineral field to gather if not ordered directly.

Ever get annoyed when you *slightly* missed a mineral field and your MULE just AFKed? Does not affect MULEs dropped too far away from minerals.

- Changed Vulture's Replenish Spider Mine ability to be autocast on intially.

I don't see why you wouldn't want this autocasting.

- Fixed a bug where Raynor's bunkers used the Neosteel icon before upgrading Neosteel.

yeah.

## Kerrigan

- Fixed a bug where P1 and P3 used each other's icons.
- Reworked P1.
  - Disadvantage makes Kerrigan unavailable instead of removing Nydus Networks.
  - Advantage additionally increases combat unit health by 50% and grants the Twin Drones upgrade. Creep Tumors gain Super Cloak when burrowed.

Malevolent Matriach was kinda boring, so lets turn the dial up to 11. The prestige is now strictly focused on Kerrigan's army. The Twin Drones upgrade is added to help ease the massive nerf to Kerrigan's early game.

- Changed Malignant Creep to affect structures and air units.

Isn't it funny that vanilla P1 Kerrigan's best unit is still Mutalisks? This should allow P1 to interact with more units.

- Changed P2 to also hit structures.
  - Will prioritize units and attacking structures.

Now your damage isn't just nerfed against structures.

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
      - Heals for 40 life when a biological unit dies nearby.
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

- Changed Ultralisk Tissue Assimilation upgrade to increase leech by 40% instead of healing a flat amount.

This allows the healing to scale with damage increase or damage reduction effects.

- Changed P3 voice lines.

Now uses the pre-infested voice lines from Heart of the Swarm.

## Artanis

- Changed Phoenix weapon damage from 7 (+5 vs Light) to 10 (+2 vs Light).
- Reduced Phoenix price from 150/100 to 150/50.

Phoenixs were extremely dependent on enemy composition. Moving some damage from the bonus should help. Also decreased the vespene price to make them easier to mass when going skytoss.

- Reduced duration of Disintegration from 20 seconds to 10 seconds (total damage unchanged).
- Added Destabilizing Residuum upgrade at the Fleet Beacon.
  - Causes Tempest attacks to leave an AOE field that does 20 damage over 5 seconds.
  - Damage doubled by P2.

These changes should make massing Tempests more viable. Faster Disintegration reduces Tempests wasting shots on disintegrating targets and allow easier chaining Disintegrations. The new AOE upgrade makes Tempest shots still get value even if their target has already been killed by another Tempest first.

- Changed Tempest voice lines to Versus quotes.

Fun fact: Artanis' Tempests used the campaign Purifier Tempest quotes despite using the Versus model.

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

- Fixed a bug where High Templar's Psionic Storm ability would no longer show an impact model after researching Plasma Surge.

yeah.

## Swann

- Added Thor's High Impact Payload mode from Versus for single-target long-range damage.
- Added a launch sound effect when shooting High Impact Payload weapon.
- Added a launch sound effect when channeling 330m Barrage Cannon.
- Buffed Multi-Lock Weapons System upgrade to additionally affect the Thor.
- Reduced 330m Barrage Cannon cast and finish time from 2 to 0.75.

These changes should make Thors much more competitive.

- Buffed Infernal Plating upgrade to additionally increase Hellbat/Hellion hp by 40.

Increased Hellion/Hellbat health should make mineral dumping into them more efficient and make them more viable as a frontline.

- Changed Cyclones to visually have their red lazer sights with Mag-Field and large missiles when locking on from Versus.
- Buffed Cyclone's Lock On to no longer be affected by armor.

The little missile that was fired during Lock On was just sad, now Cyclones look as cool as they do in Versus. Also Lock On is a spell, and should not be affected by armor.

- Added Widow Mines.
  - Added Hellburst Payload upgrade, which increases Sentinel Missile direct damage by 20 and splash damage by 80.
  - Adds a visual red light on top after researching Hellburst Payload.
  - Cyclone's Targeting Optics upgrade additionally increases Sentinel Missile range by 3.

Why not give the mech commander more mech? Widow Mines go well with Swann's defensive design. The Hellburst Payload massively improved splash damage can be absolutely devastating.

- Added Smart Servos upgrade, which increases the morph rate of Hellions, Hellbats, Thors, Siege Tanks, and Widow Mines.
- Added Overdrive Actuators upgrade at the Armory, which increases ground vehicle movement speed by 20% and ship movement speed by 10%.
- Added Pulse-Loop Capacitors upgrade at the Armory, which decreases all unit cooldowns by 20%.

These general improvements should make playing ground mech much smoother (Why does Raynor have fast Siege Tank morph speed but Swann doesn't?). Smart Servos helps deploying Widow Mines during combat, Overdrive Actuators helps playing battle mech (Hellion/Cyclone) much easier to kite with, and Pulse-Loop Capacitors helps Widow Mines and Cyclones deal more consistent damage.

- Added the ability to morph Orbital Commands that have access to Calldown: Extra Supplies and Scanner Sweep.

Scanner Sweeps should help Cyclones keep their Lock On active and provide detection without having to rely on the slow Science Vessels. Additionally, Calldown: Extra Supplies to help with the constant supply blocks on Swann.

- Added the ability to morph Planetary Fortresses.
  - Swann level 3 perk additionally upgrades Planetary Fortresses to Big Berthas, increasing damage and splash range.
  - Planetaries are considered turrets for all turret upgrades.

An iconic defensive Terran structure for the defensive Terran commander.

- Changed Planetary Fortress attack priority to "By Angle" instead of "By Distance".

Should make Planetaries spend less time spinning around randomly when surrounded.

- Added Commander Center Reactor.

It takes forever to eco up on Swann. Maybe now not so much.

- Added Dual-Fusion Welders.

The turret/mech commander gets more improvements to sustaining turrets/mech.

- Buffed P2.
  - Upgrade Fire Suppression System heals structures to 100% health.

P2 suspiciously improved all upgrades but this one.

- Changed Defense Matrix to no longer require research.

https://www.maguro.one/2017/10/upgrades-in-co-op.html

- Added P4: Rolling Thunder
  - Advantage: Combat units can attack while moving. Start with the Multi-Lock Weapons System upgrade. Cyclones can use Lock On while moving. Only Thor anti-air weapons can attack while moving. Hellbat, Thor heavy air, and Goliath ground weapons can only fire in an arc in front of them while moving.
  - Disadvantage: Hercules are unavailable. Turrets are 100% more expensive.

Allows for fun playstyles like running around with battle mech or flying Wraiths around like Phoenixes. The disadvantage is probably not powerful enough to warrent how strong the advantage is.

## Zagara

- Increased max supply from 100 to 150.

One of Zagara's greatest weaknesses is the inability to hit a critical mass of units to trade efficiently.

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

- Reworked Bile Launchers.
  - Can now target enemies automatically.
  - Bombardment ability now uses smart casting.
  - Bile Bomb projectiles now reveal a radius of 3 around them.

Idea stolen from CXL, should make Bile Launchers more effectively than just on infested maps.

- Reduced Scourge vespene cost by 25.
- Removed Simplified Genome.
- Added Dampening Membrane upgrade, which reduces the splash and spell damage dealt to Scourge by 75%.
- Increased Corruptor damage from 14 (+14 vs Armored) to 28 (+14 vs Armored).
- Buffed Corruptor's Corruption to allow targeting structures.

Scourge were incredibly inefficient to morph before evolving Simplified Genome, so it has been made baseline. If you've ever felt the pain of watching your Scourge die to one storm, the new upgrade should help increase the reliability of Scourge against AOE. Corruptor damage has also been buffed so they have actual DPS instead of just tickling air comps. These changes should improve Zagara's anti-air capabilities.

- Changed Zagara's temporary units to visually burrow away instead of exploding when expiring.
- Added Swarm Networks.
  - Can summon Swarm Locus at a targeted location that will unload temporary units to fight.
  - Temporary zerg last 60 seconds, are uncontrollable, and attack closest enemies.
  - Queen will try to place Creep Tumor if no other Creep Tumors nearby.
  - Limited to 4.

If there is one think Stukov P3 has taught me, it's that throwing free units at Amon is fun as hell. The Creep Tumors also act as a form of creep spread that Zagara is lacking. These act as a sort of top bar ability that Zagara is missing.

- Added P4: Subterranean Tide
  - Advantage: Swarm Networks are no longer limited, cost 25% less, and spawn 50% more units.
  - Disadvantage: Combat units cost 25% more. Swarm Networks cost 100 more minerals for every one built.

I added a whole new mechanic to Zagara and then created a whole prestige surrounding it. Hell yeah.

- Buffed Infested Drop Roaches to Corpser Roaches.

Corpser representation!

- Increased visual scale of Hunter Killers by 20%

When Hunter Killers were given the webby skin, their scale was accidently reset to the normal Hydralisk scale.

- Added wireframe and group icon to Zagara.

If you thought Zagara's wireframe looked oddly low resolution, you aren't crazy. Zagara never had a wireframe set and just used her unit icon as a fallback.

- Increased speed of Zagara's Acid Spines projectile by 100%.
- Reduced Zagara's Acid Spines attack period from 1.5 to 1 (+50% attack speed).
- Increased Medusa Blade's damage 33% of attack damage to 50% attack damage.

Zagara has a mastery for attack damage but her attacks felt lethargic and she attacked slower than queens.

## Vorazun

- Changed Vorazun to use custom Nerazim skinset.

Green warp ins! Dark Templar now use both variants and Shadow Guard use the Golden skinset. Centurions, Stalkers, Dark Templar, Dark Archons, Corsairs, and Void Rays are given a makeover. Also changes some icons.

- Added Vespene Crystalization, increasing vespene harvest rate by 25%.

Vorazun is one of the most vespene limited commanders. Increasing her vespene harvest rate should help with the large amount of tech she needs and her extremely gas heavy army.

- Buffed Vorazun level 1 perk to additionally increase the shields of all combat units (except Dark Templar) by 40.

This should help increase the survivability of all her other units. Pairs well with her level 7 perk for increased shield regeneration rate.

- Changed Disruption Web to no longer require research.
- Added Flux Vanes upgrade, which increases the movement speed and acceleration of Void Rays.

Disruption Web research has been replaced with Flux Vanes. Baseline Disruption Web should help increase the value of the first few Corsairs while the Flux Vanes upgrade should help Void Rays feel better to kite with.

- Added Signifiers, an astral-themed High Templar.
  - Available after building a Templar Archives.
  - Can use Aurora Veil for 50 energy.
    - Grants cloak to friendly units in an area and heals their hitpoints over time for 30 seconds.
  - Can use Astral Storm for 75 energy.
    - Does less damage in a larger area than Psionic Storm for 7 seconds.
    - Applies Astral Smolder to enemy units hit, revealing cloaked units, reducing movement speed, and reducing armor. This effect stacks up to 4 times.
    - Applies P2, dealing massive damage.
  - Can use Fading Star after researching at a Templar Archives.
    - Grants super cloak, 50% increased movement speed, and ignores unit collision for 4 seconds.
    - Can be autocast when damaged.
  - Argus Crystal additionally grants Signifiers full energy.

A cut unit from the LOTV campaign reimagined. Astral Storm provides detection outside of Oracles. Aurora Veil massively helps non-cloaked units like Stalkers, Centurions, Dark Archons, and Void Rays benefit from Vorazun's stealth perks and makes them viable. Can also heal units after they use Emergency Recall.

- Dark Archon upgrades moved to Templar Archives.
- Reworked Dark Archons to no longer be trained at a gateway, but instead from merging two Dark Templar or Signifiers.
- Increased Dark Archon weapon damage from 18 to 25 (+10 vs Biological).
- Increased Dark Archon Confusion radius from 2 to 3.

Should make massing Dark Archons more viable instead of watching them tickle units.

- Changed Dark Archon skin.
  - Visually green instead of red.

The Dark Archon skin has been used by Tal'darim (Both as Warchest skins and as a skin in NCO), so instead, the Dark Archon is given a unique Nerazim themed skin. As a cool added bonus, using two Signifiers will create a female Dark Archon instead.

- Added Revelation to Oracle.

That's their main gimmick, why did they remove it? Oracles are still detectors so using this ability is not necessary.

- Increased Oracle's Stasis Ward duration from 15 seconds to 30 seconds.

When adding Oracles to co-op, this duration got halved, presumably because it wouldn't be fun to get hit by a 30 second stasis by Amon and they were worried it would be too strong with the Stasis Ward upgrade. Realistically, it's not easy getting big hits with Stasis Wards so reverting this should make Oracles more compelling for more than just detection.

- Buffed P2 to reduce Stasis Ward duration by 50% instead of 75%

For the prestige focused on stasising things, the P2 just makes Stasis Wards sad. This buff combined with the increased duration should help with that.

- Removed deceleration from Oracle's Stasis Ward ability (no longer has to fully stop to cast).

Makes casting much smoother.

- Reworked Void Stasis into Void Prison.
  - Stuns instead of stasis.
  - Still disables detection.
  - Can target air units.
- Added cast animation for Void Prison.

Ever get annoyed when your Dark Templar would run in and automatically stasis Missile Turrets you were trying to snipe? Removing the invulnerability makes it much easier to snipe detection while fighting. Being able to stasis air units additionally makes Dark Templar much sneakier against flying detectors like Overseers.

- Buffed Emergency Recall to cleanse negative debuffs.

No more recalling Black Death straight into your mineral line.

- Added autocast to Stalker Blink.

Unsurprisingly, autocasting the shield restoring Blink when out of shields is strong.

- Fixed a bug where Strike from the Shadows would increase the cost of abilities that use energy over time (i.e. Cloak).

Funny that this passive could *nerf* some units.

- Fixed a bug where Corsair's Disruption Web ability would autocast on a single unit multiple times.

yeah.

## Karax

- Implemented [Maguro's Karax 2.0](https://www.maguro.one/p/karax.html) with some changes listed below.
- Reworked Carrier Repair Drone behavior to vanilla version, but with improved autocasting to no longer require stopping.
- Removed Combat Chrono Wave.
- Removed the ability to Chrono Boost defensive structures.
- Nerfed Improved Reconstruction to 120 seconds.
- Changed Mirage weapon damage from 7 (+5 vs Light) to 10 (+2 vs Light).

Karax 2.0 has great quality of life changes for Karax, so lets use them. Chrono Boosting defensive structures removed to not step on P1's toes. Nerfed Improved Reconstruction because Sentinels are pretty much unkillable anyways.

- Reworked Karax P2 disadvantage to increase the price of Photon Canon and Khaydarin Monlith by 100% instead of disabling them.

Copied from CXL. Keeps it unviable to use static defense aggressively without completely removing the option defensively. Especially useful for dealing with nuke-happy Ghosts.

- Added Instigators.
  - A Purifier variant Stalker.
  - Added Displacement Matrix upgrade, which lowers the cooldown of Blink to 4 seconds and allows up to 3 charges.
  - Blink can be set to autocast to automatically blink when the hull takes damage.

Karax's early/mid game anti-air is extremely lackluster, adding a ranged gateway unit helps greatly with that. The Adept is already used by Fenix, so why not add the unused Purifier unit, the Instigator? Having up to three low-cooldown Blinks on autocast lets these units skirmish effectively and can get pretty chaotic.

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

- Buffed Viper's Consumption ability to also target structures.
- Buffed Virulent Microbes upgrade to additionally increase the radius of Viper abilities by 1.
- Buffed Biomass to additionally increase max energy by 1% per biomass.
- Buffed Biomass to additionally increase spell damage for casters (not Ravagers) by 1% per biomass.
- Buffed Abduct to allow abducting Heroic units (will pull but not stun).

Vipers rarely were worth mixing into your army, now they should be much more usable and be competitive in anti-air against Devourers.

- Added autocast to Corrosive Bile (initially off).

Should help keeping Corrosive Bile on CD with the Biomass CDR. It won't predict so it might be better to leave this off in some circumstances. Will try to break force fields if no other enemies in range (sorry Alarak).

- Buffed Swarm Host by upgrading to Creeper strain.

Abathur's Swarm Host already got the Deep Tunnel ability, now they poop creep as well.

- Added Spike Burst ability to Symbiote.
  - Deals 50 damage to nearby enemies every 10 seconds.
- Increased Symbiote's Stab cooldown from 1 second to 1.2 seconds.
- Changed Stab to prioritize units and attacking structures.

Spike Burst is cool and was pretty much already finished but unused (can you tell I've been playing HotS?). Stab DPS slightly nerfed to compensate. Overall single target DPS is identical.

- Added P4: Symbiotic Hivemind.
  - Advantage: Hatcheries, Lairs, and Hives can create a Symbiote on a friendly unit.
  - Disadvantage: Leviathans and Brutalisks no longer start with a Symbiote. Symbiotes now cost resources and supply.

Ever wonder how cool it would be to slap a Symbiote on Dehaka? Should create interesting combinations with your ally. Each Symbiote is now very expensive in return. Highly effective with commanders who have few but important units such as hero commanders.

## Alarak

- Reworked Mothership Terminator Beam to only target air units.
- Reworked Mothership Thermal Lance.
  - Only targets ground units instead of all units.
  - Reduced travel speed by 75% speed.
  - Cooldown increased from 1 to 2 seconds.
  - Damage increased from 10 to 100.
  - Now visible as a weapon.
- Renamed Mothership to Crimson Sovereign.

Changes the Thermal Lance from a 10 damage tickle beam to a slow moving 100 damage death laser. As compensation, the original Terminator Beam can only hit air units and Thermal Lance can only hit ground units (it seemed weird that hitting the ground under air units would damage them anyways). Mothership was renamed to be more distinct from other variants and be in line with other Tal'darim variant unit names.

- Increased Destroyer supply cost from 3 to 6.
- Increased Destroyer price from 125/75 to 250/150.
- Increased Destroyer bounce damage by 1 for each charge level.
- Reworked Destroyer attacks to ignore armor.
- Reworked Level 13 Burning Skies perk.
  - No longer increases the amount of Destroyers spawned.
  - Increases visual scale of Destroyers by 20%.
  - Increases the life/shield of Destroyers by 100%.
  - Increases damage of Destroyers by 50%.
- Reworked P3.
  - Warp in Destroyer charges take 100% longer to accrue.
  - Warp in Destroyer charges max reduced by 50%.

Typically when using the Death Fleet or playing P3, you would end up with a lot of visual clutter of bouncing beams that end up doing 0.5 damage to a Zergling that has +1 armor. Reducing the amount of active Destroyers but making them more impactful should better match the visual intensity of their bouncing attack.

- Increased Vanguard attack count from 8 to 16.
- Reduced Vanguard range by 1.5.

Copied from LOTV Nightmare. The nerf from campaign to co-op made building these feel sad. To compensate for unnerfing the damage, the range has been reduced. The reduced range also helps them live up to their name.

- Reworked Wrathwalker attack to hitscan instead of a projectile.

Prevents situations where all your Wrathwalkers mega overkill one unit. Unsuprisingly makes Wrathwalkers significantly stronger against smaller units, especially with P1.

- Fixed Mothership using Aiur skin death ragdoll model instead of Tal'darim.
- Changed Ascendant shadow trail model to be red.
- Restored missing beam effect on Ascendant's Psionic Orb.

A few visual fixes/changes.

## Nova

- Added P2 Advantage: Stuns enemy units in the drop off area for 4 seconds when unloading.

P2 was such a boring prestige. Stunning enemies at least grants a niche of dropping right on top of enemies and bursting them down.

- Reworked Covert Banshee's Rocket Barrage ability.
  - Now does damage over time rather than instantly.
  - Fixed bug where missiles would launch from the center of the model instead of the weapons.
  - Changed autocast to prioritize hitting multiple enemies, but can target fewer.
  - Reduced casting arc from 360 to 0 (Now has to face target location).

Looked silly dealing the damage instantly and afterwards the rockets land.

- Reworked Covert Banshee's Advanced Cloaking Field upgrade into Phantom Drive upgrade.
  - Still perma cloaks but additionally provides movement speed.

Nobody likes slow Banshees.

- Added visual change to Raid Liberator ground attacks after researching Raid Artillery.

Copied from Versus.

- Reworked Marauder Commando's Magrail Munitions.
  - Added 5 second stun (Heroic and Massive units get slowed instead).
  - Reduced damage from 90 to 50.
  - Changed to an ability instead of an attack augment, allowing it to target enemies separate from basic attacking.
  - Changed autocast to prioritize non-stunned units.
  - Changed visual effect.
  - Changed damage from ranged to spell (ignores armor).

Changes Magrail Munitions from a low-dps nuke to a CC ability to further reinforce the Marauder's role as a support frontliner.

- Reduced the cooldown of Covert Banshee's Rocket Barrage ability from 15 seconds to 10 seconds.
- Reduced the cooldown of Spec Ops Ghost's Snipe ability from 30 seconds to 10 seconds.
- Reduced the cooldown of Spec Ops Ghost's EMP Round ability from 45 seconds to 10 seconds.
- Reduced the cooldown of Marauder Commandos's Magrail Munitions ability from 30 seconds to 10 seconds.

Many of Nova's unit cooldowns are so long that they usually are used once at the start of a fight and then never again. Reduced cooldowns should help her in longer fights.

- Increased attack speed of Railgun Turrets by 100%.
- Reduced duration of Railgun Turrets built by Raven Type-II from 60 seconds to 30 seconds.

Despite being an elite Raven, they actually end up dropping worse Auto-Turrets with lower DPS and the inability to hit air. Now the Railgun shoots twice as fast but the duration is reduced by half to compensate.

- Fixed a bug where the attack range indicator for Railgun Turrets was larger than intended.

Fun fact: it was using the range for the Build Railgun Turret ability rather than the weapon range.

- Increased the range of Spec Ops Ghost's Triple Tap upgrade from 3 to 5.

This increases the reliability of Ghosts getting the extra snipes off.

- Added a new Aegis Plating passive to Hellbat Rangers.
  - Reduced damage taken to a maximum of 15.

Hellbats tend to not even be worth the mineral cost as they die too easily. Giving them Hardened Shield should improve their effectiveness as a frontline, especially when facing high damage burst like Yamatos.

## Stukov

- Changed Infested Banshee P2 Deploy ability to allow casting while moving.
- Replaced Braced Exoskeleton upgrade with Hyperadaptive Exoskeleton, which additionally increases Infested Banshee speed by 2.
  - Adds visual boosters to the Infested Banshee.

These two simple changes make playing P2 infinitely smoother to play. It was kinda sad that P2 was about picking up your infantry and moving them to the frontline, but the Infested Banshee was about as fast as them walking there.

- Added advantage for P2:
  - Starports and Banshees no longer have tech requirements.

These take super long to tech to before you can get any value from P2. Removing the tech requirements similar to P1 should streamline it.

- Changed Rapid Hibernation to no longer require research.
- Removed deceleration from Infested Banshee's Burrow ability (no longer has to fully stop to cast).

As the Infested Banshee's defining trait, it seems odd that it requires research. The QOL change also helps quickly burrowing after moving.

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
- Fixed Infested Liberator being unable to attack while using Hold Position after researching Cloud Dispersal (will use pre-upgrade weapon).

Adding strafing to Cloud Dispersal causes Liberators to spread out more evenly, dealing damage in a greater area and take less damage from AOE effects. It also just plain looks cooler. Increasing the lingering duration allows running away before the 85% damage reduction fades.

- Buffed P1 to also affect Brood Queens.
- Removed prepare time from Ocular Symbiote and Spawn Broodlings.
- Removed deceleration from Ocular Symbiote and Spawn Broodlings (no longer has to fully stop to cast).
- Changed Spawn Broodlings to spawn flying Broodlings (must land before attacking) when casted on a flying unit.

Some QOL changes for a unit that nobody uses. Seemed weird that Brood Queens were explicitly left out by the P1 advantage.

- Increased duration of infested troopers from 30 to 60.

Infested troopers were previously reliant on the infantry duration mastery. This should increase their consistency without the mastery.

- Added Infested Rockets weapon from Versus to Infested Marines.

Despite Infested Marines and Infested Troopers being different units, they are pretty much identical. This should give Infested Marines their own niche as a long-range anti-armor AA option, something Stukov doesn't have.

- Reworked Infested Barracks
  - Costs 1 supply.
  - Automatically spawns free Infested Marines.
  - Can pay 100/50 and 1 supply to increase level of Corruption up to 5 times, decreasing the cooldown of spawning Infested Marines.
  - Can autocast Increase Corruption.
- Changed Infested Siege Tanks to also consume Infested Marines.

Infested Marines were not worth investing into over Bunkers because they are timed. The solution? Make them free! Can now choose to invest in a Bunker for immediate units and static defense, or a Barracks for a long-term investment and slightly stronger infantry.

- Reduced the cooldown of Spawn Infested Civilians from 60 seconds to 15 seconds.
- Reduced the amount of Infested Civilians created from 8 to 2.

Instead of creating huge waves, the Infested Colonist Compound now does many smaller waves. Each infestation upgrade still doubles the amount of infested spawned.

- Reworked P3.
  - Now increases spawn rate of Infested Bunker, Infested Barracks, and Infested Colonist Compound by 50%.

This prestige was so simple to play, you could just spam down a bunch of bunkers. Lowering the bonus but applying it to more infantry should increase build diversity.

- Changed Infested Infantry to be affected by commander buffs, i.e. Vorazun's Strike from the Shadows, Artanis's Guardian Shell, e.t.c.

It might be a little strong making all of the temporary units have Guardian Shell, but hey it's co-op, whats the harm in being OP?

- Changed Infested Missile Turrets to attack while uprooted.
- Changed Infested Missile Turrets to provide detection while uprooted.
- Added Biomass Coating passive to Infested Missile Turrets, increasing life regen while rooted.
- Changed Regenerative Plating upgrade to additionally affect Infested Missile Turrets.
- Changed Calcified Armor upgrade to additionally affect Infested Missile Turrets.

Bunkers can do it, why not the Missile Turret?

- Reduced push priority of infantry to 9.
- Increased push priority of uprooted buildings to 11.

It can be frustrating trying to get into the fight when you have a P3 Stukov ally, now you can push all their troopers aside. It also made sense that giant walking buildings could push other smaller units out of the way. This helps trying to push your bunker line up.

- Added Infested SCV portrait.
- Added Infested Diamondback portrait.
- Added Infested Liberator portrait.
- Changed Infested Siege Tank portrait to previous Infested Diamondback portrait.
- Changed Infested Civilian portrait.
- Added Infested Trooper model and portrait.

Blizzard got lazy and only reused portraits for Stukov, this adds new ones!

- Fixed a bug where if an Infested Civilian has jumped using Anaerobic Enhancement, and an Infested Siege Tank tried to eat it, the Infested Civilian would die without healing or gaining a charge.
- Fixed a bug where the icon of the button for Mech Attack Speed mastery was not colored.
- Fixed a bug where you could not queue multiple upgrades on the Infested Command Center.

A few fixes. The Siege Tank bug took way too long to figure out...

## Fenix

- Remove Disruptors.

Disruptors are rarely used with Fenix because it benefits from none of Fenix's Champion AI perks. The disruptors have been moved to Karax.

## Dehaka

- Reduced the damage from using Consume on a psionic unit from 2x weapon damage to 1x weapon damage.
- Added a cleave to Dehaka's Claws weapon.
- Added splash damage to Dehaka's Mammoth Beam weapon.
- Increased the damage of Dehaka's Mammoth Beam by 50%.

Should reduce Dehaka's reliance on psionic units for clearing waves. Dehaka gains a frontal cone cleave to his Claws and splash damage to his Mammoth Beam to compensate. Also increased the damage of the Mammoth Beam so it feels more desireable to get instead of feeling like a damage nerf.

- Fixed a bug where P2 did not increase the damage of Dakrun's Greater Spiked Hide.
- Increased Dakrun's Brutal Charge damage from 200 to 200 (+100 vs Structures).
- Buffed Dakrun's Brutal Charge to affect invisible units.
- Buffed Dakrun's Brutal Charge to affect structures.
- Buffed Dakrun's spawn knockback to affect structures.

Why did Dakrun slam his giant head into a building and do 0 damage? Also why did it not affect invisible units? Now Dakrun has a niche of smashing into buildings.

- Changed Primal Impaler model.

The unit previously used the Primal Lurker skin, now it uses a proper Impaler skin.

- Added a visual impact model for Dehaka's Devour.

This visual exists in the [commander preview](https://youtu.be/R2-PzLUzam8?feature=shared&t=93) but was removed before release for some reason. Fun fact: the visual still existed for Carriers and Void Rays only for some reason.

- Lowered tech requirement of Primal Wurms from requiring Glevig's Den to requiring a Primal Warden.

Primal Wurms are Dehaka's only source of detection until evolving to level 5, making Dehaka extremely vulnerable to early stealth such as the We Move Unseen modifier. This buff should counteract that.

## Han & Horner

- Added autocast to Widow Mine Burrow.
- Reworked Executioner Missiles to shoot a missile at a nearby enemy that splits into 5 missiles.
- Fixed bug where unburrowed Widow Mines showed a range indicator after researching Black Market Launchers (Fun Fact: It didn't even show the correct range).
- Added a visual red light on top after researching Black Market Launchers.

These changes should make Widow Mines more viable at pushing into enemy bases. Autocasting burrow particularly helps when training Widow Mines at the front lines.

- Increased visual scale of Assault Galleons by 20%.
- Increased life of Assault Galleons from 500 to 750.
- Reduced Assault Galleon limit from 5 to 4.
- Added the ability for the Assault Galleon to produce 2 units at once.
- Increased visual scale of Assault Drones by 20%.
- Increased life of Assault Drones from 80 to 100.

Assault Galleons are suppose to be mobile Starports that can turn into aircraft carriers, so lets make them visually match that fantasy. Overall increases the production rate of Han's units.

- Increased Salvage rate from 20% to 40% for Han & Horner and from 10% to 20% for ally.

Mira's units usually trade horribly, this should help mitigate that.

- Fixed a bug where Mag Mines would not play their entire animation when firing.

The animation was too slow and only got around half way through. I bet no one would even notice this though.

- Reworked P1:
  - Removed Mag Mine improvements.
  - Increases the production speed of Mira's units by 50%.
  - Increases the Salvage rate from 40% to 60%.
  - Added tooltips to death effect passives that were missing.

Buffing a top bar ability feels kinda boring, instead P2 now improves how many Mira units you can produce. The improved Salvage value and the Double Salvage mastery can combine to give more minerals than you initially paid. It can look funny seeing your mineral count rubber band as you train a bunch of units and then they all suicide.

- Increased projectile speed of Deimos Viking's W.I.L.D. Missiles by 100%.

Often, whatever these were shooting at would already be dead by the time the projectile arrives.

- Increased range of Sovereign Battlecruiser's Mini Yamato Cannon from 6 to 8.

It's a damn Yamato cannon, it should be long range! Just feels natural, y'know?

- Increased range of Theia Raven's Analyze Weakness from 8 to 10.

This should keep the Raven farther back and not randomly die as easily.

- Removed Junker skins for Deimos Viking, Theia Raven, Sovereign Battlecruiser, and Strike Fighters.
- Added Covert-Ops portraits for Deimos Viking, Theia Raven, and Sovereign Battlecruiser.

Despite being called Han & Horner, once you got all the upgrades, it just turned into "Oops! All Han!". Now you get to keep some of that "elite Dominion" aesthestic in your army. Plus, it felt really silly that upgrading a Battlecruiser with Yamatos would strap two giant knives to its side.

- Increased Strike Fighter hitpoints from 50 to 100.
- Buffed Precision Strike to also hit air.
- Added visual trail to Strike Fighter.
- Adjusted Strike Fighter acceleration.

Why is this thing so easy to shoot down? The initial explosion can also now hit air units, but not the napalm upgrade.

- Reworked P3:
  - Added advantage: Can research one exclusive Precision Strike upgrade.
    - Thermal Cascade Payload: Napalm upgrade but spreads to a larger radius.
    - Cluster Payload: Drops 2 additional bombs behind the target area.
    - EMP Warhead Payload: Additionally deploys an EMP that has similar effects to Mengsk's EMP.
  - Removed Strike Fighter Platform cost disadvantage.
  - Added disadvantage: Salvage is unavailable.

Old P3 had an awkward design where it buffed how many platforms you could build and then made them so expensive that you could never hit the limit anyways. New P3 leans into the Precision Strikes harder by buffing them further and adds a more interesting disadvantage of weakening the ability to trade with an army. These changes incentivize using the Precision Strikes more aggresively to ensure efficient trades.

- Fixed a bug where Call in the Fleet's initial targeting position would be offset when casted over flying pathing blockers.
- Fixed a bug where Call in the Fleet would launch at a different trajectory than intended.

Fun fact: the second bug was caused by trying to launch the missile to a position 500 units away, which would cause strange clamping issues out of bounds.

- Fixed a bug where Reaper's death rattle grenades continued their ticking sound after exploding.
- Added a ticking sound to Reaper's KD8 Charge ability.
- Added a cursor splat to Reaper's KD8 Charge ability.
- Increased KD8 Charge damage radius from 1.5 to 2.
- Increased KD8 Charge knockback radius from 1 to 2.
- Removed status bars from placed KD8 Charges.

Some visual QOL and a small buff to the KD8 Charge radius. Not sure why the damage and knockback had different radii.

- Removed random delay between shots from Sovereign Battlecruiser's weapon.

Overall increases attack speed and allows the Battlecruiser to be affected by attack speed buffs.

- Added Ordnance Towers that can be built by SCVs.
  - These are flying defensive structures with long-range attacks.
  - Spawns up to 4 Valkyries that fly around and defend the area.
    - Valkyries have 100 hp and their own long-range missile attack.
  - Can use the Nano-Repair ability to heal mech units.
  - Can detect cloaked units.

Han & Horner are missing a defensive structure to deal with ground, so why not make it something interesting like the scrapped Ordnance Tower? These are very expensive but can defend a large area. It's also cool to have a structure that focuses more on Horner's side than Han's.

- Fixed a bug where cancelling building an Assault Galleon would play the Assault Galleon's death animation instead of the generic Terran build cancel animation.

yeah.

## Tychus

- Added ability to reorder outlaws.

https://www.maguro.one/2019/06/uiux-tweaks.html

- Reworked Joeyray's Bar to allow any outlaw as your first outlaw for free instead of only Tychus.
  - Now possible to not have Tychus active at all.
  - Calldown Odin will only revive Tychus if Tychus is recruited.
  - Cannot recruit Tychus while Odin is deployed.

It's probably still better to take Tychus, but now atleast you have a choice.

- Reduced Crooked Sam's Demolition Charge visual explosion scale by 60%.

It looked like a massive explosion for a single target nuke.

- Reduced Miles "Blaze" Lewis weapon backswing and damage point.

Same change to Raynor's firebats.

- Added a cursor splat for Kev "Rattlesnake" West's Deploy Revitalizer.
- Fixed a bug where Rattlesnake's weapon would no longer have a visual impact effect after purchasing Hammer Munitions.
- Added a new AOE visual effect after purchasing Hammer Munitions.
- Added blue trail to Rattlesnake's projectiles after purchasing Hammer Munitions.

yeah.

- Increased the visual scale of Rattlesnake's projectiles by 45%.
- Increased the speed of Rattlesnake's projectiles by 45%.
- Increased the visual scale of Blaze's attack by 40%.

It looked silly having this giant unit shooting out tiny little attacks.

- Reordered SCV building menu.
- Added Fortified Bunker that can be built by SCVs.
  - Can hold up to two outlaws.
  - Increases range of units inside by +2.
  - Fortified Bunker has extra armor and life.

Tychus's static defense is super boring, literally just an auto-turret. Hopefully this is more interesting.

- Fixed Odin weapon tooltip showing wrong damage.

It was showing the damage numbers from the WOL campaign instead of the Co-op numbers.

- Fixed a bug where the Odin could attack while channeling Barrage.
- Added a launch sound effect when channeling Barrage.
- Reduced cast start time of Barrage from 2 to 1.5.
- Reduced cast finish time of Barrage from 2.5 to 2.
- Increased radius of Barrage from 3 to 4.

Barrage is kinda garbage for something you only get to use once per Odin. These changes should make casting Barrage smoother, especiallly important for the Big Red Button rework.

- Reduced radius of Big Red Button from 12 to 8.
- Reduced Big Red Button damage falloff (Does more damage to targets far from the center).
- Reworked Big Red Button upgrade.
  - No longer replaces Barrage ability.
  - Upgrades Barrage by adding a nuke to the end of the ability.
- Changed Big Red Button to play audio sting when nuke lands instead of when it launches.
- Increased volume of nuke launch sound effect.

Is likely an overall nerf as the radius is reduced and now you have to channel Barrage, but it just *feels* satisfying.

## Zeratul

- Fixed Xel'naga Ambusher Predictive Blink autocast.

For some reason, Predictive Blink would autocast once and then kinda just chill out for a while, now they will use up all charges when taking damage.

- Changed to Ihan-rii skin set.
- Added Xel'Naga Ambusher portrait.
- Added Xel'Naga Enforcer portrait.

The Ihan-rii skin is basically a more complete version of Zeratul's skin so it used over his skin. Also added some more lore-accurate portraits.

## Stetmann

- Buffed Stetellites by adding Map Boss attribute.

Grants immunity to certain mutators like Propagators. Previously, if you put a Stetellite too far forward, a Propagator could just feast on them for free.

## Mengsk

- Added P4: Cerberus Director
  - Advantage: Dogs of War refunds 50% of energy cost and has 100% reduced cooldown.
  - Disadvantage: Dogs of War costs minerals. Trooper weapons cost 100% more.

Incentivizes spending your minerals on zerg as your frontline instead of on troopers.

- Removed hit test from Imperial Witness's Amplified Airwaves hologram (Can no longer be clicked).
- Fixed a bug where Imperial Witness's Amplified Airwaves hologram would start rising unexpectedly.

It's happened to everyone, the hologram lifts off and then you accidentally a-move it and kill your own blimp. *Fun fact: this bug is caused by Blizzard attaching the hologram incorrectly, then offsetting the hologram to move it where it should be, then because it's not attached properly, it randomly applies that offset over and over again.*

- Reduced Tactical Missile Strike Delay from 4 to 3 seconds.
- Increased Tactical Missile Strike radius from 2 to 3.
- Added Ordnance Depot Retrofit upgrade to the Royal Academy.
  - Requires an Armory.
  - Allows Royal Academies to arm and store 1 additional missile at a time.

Missile play is cool so lets make it more viable! Lower delay and bigger radius should make missiles more consistent. Storing additional missiles should lower the footprint of building enough academies to constantly be nuking.

- Removed fake heal from Imperial Intercessors.

It was so annoying when these got stuck too far back, now they'll push up with your army. They might push up *too* far but hey, they have cloak and Ignite Afterburners. Healer AI in general may be revisited in the future.

- Removed cooldown from Emperor's Shadow's Pyrokinetic Immolation ability.
- Removed cooldown from Emperor's Shadow's EMP Blast ability.

Emperor's Shadows are limited by energy anyways, so why do they have cooldowns on their abilities?

- Reduced cooldown of Emperor's Shadow's Labryinth Cloak ability from 30 seconds to 20 seconds.
- Added Shadow of the Dominion passive to Emperor's Shadows.
  - While cloaked, gain health regen and 30% move speed.

With such a high target priority, Emperor's Shadows tend to get sniped off, even with Labryinth Cloak. Now cloak has increased uptime and grants health regen and move speed to sustain themselves more easily. Additionally, this passive works when cloaked by any means, adding some synergy with commanders who can cloak ally units.

- Changed Emperor's Shadow's Pyrokinetic Immolation ability to apply instantly rather with a projectile (Projectile is purely visual).

It traveled so slow that often the unit is already dead by the time the ability lands, causing the explosion to not happen. Now the debuff is applied instantly for gauranteed big boom.

- Improved autocasting AI for Emperor's Shadows.
  - Autocasts Pyrokinetic Immolation if no enemies near target are immolated.
  - Autocasts EMP Blast if not stunned.
- Fixed a bug where Pyrokinetic Imomlation and EMP Blast would have their autocast toggled off after leveling up.
- Changed Pyrokinetic Immolation to no longer allow casting on targets already immolated.

Hopefully prevents dumping all their energy at once. Still probably more efficient to cast these yourself.

- Removed random delay between shots from Pride of Augustgrad's weapon.

Overall increases attack speed and allows the Battlecruiser to be affected by attack speed buffs.

- Added 50% spell reduction to all Royal Guards.

Nobody likes having their elite units Yamato'd to death, this should help their survivability against unpreventable bursts of damage.

- Reworked Aegis Guard's Aegis Barrier passive from granting a 300 damage absorb to granting 300 shields.

Makes it possible to track the Shield on the unit info panel. Will now interact with things like EMPs and Shield Batteries.

- Adjusted Labryinth Cloak tooltip to be more accurate.
- Fixed a bug where after researching Scatter Veil, Imperial Intercessor's shield icon tooltip would say "Unknown".

yeah.

- Added Pride of Augustgrad portrait.
- Added Sky Fury portrait.
- Added Imperial Intercessor portrait.
- Added Imperial Witness portrait.
- Added Shock Division portrait.
- Added Blackhammer portrait.

Mengsk's infantry had custom portraits, but not his mech.

- Improved Mengsk status bars to show energy/shield and be wider for Thors/Battlecruisers.

Previously the status bar only showed hp.

## Mutators

- Reworked Fatal Attraction to no longer make the units uncommandable.
  - No longer disables units attacks, abilities, and movement.
  - Pull strength increased by 20%.
  - Fixed bug where Dehaka's Primal Impalers were pulled when burrowed.

The most infurating mutator because it can permastun your units as well as interrupt all their orders. The obnoxious stun has been removed and given stronger pull stength as compensation.

- Removed Micro Transaction from Brutal+.

Not even a hard mutation, just SUPER unfun.

- Increased Slim Pickings points from 5 to 10.

Very crippling mutator so its cost has been increased. Unfortunately, doesn't help the fact that hero commanders are kinda unaffected.

- Removed invulnerability from unburrowed Spider Mines from the Minersweeper mutation.

 Raynor lost his invulnerable Spider Mines, but Minesweeper was overlooked.

- Removed Going Nuclear from Brutal+.
- Added Nuclear Mines to Brutal+ costing 3 points.

Replaces Going Nuclear with Nuclear Mines. Going Nuclear can be incredibly frustrating losing your entire army because you looked away for 2 seconds. Nuclear Mines keeps the scary nuclear explosions without needing constant attention.

- Added Infestation Station to Brutal+ costing 3 points.
- Added Great Wall to Brutal+ costing 5 points.
- Added Rip Field Generators to Brutal+ costing 5 points.
- Added Repulsive Field to Brutal+ costing 3 points.
- Added Mothership to Brutal+ costing 7 points.
- Added The Mist to Brutal+ costing 7 points.

Added Maguro mutators to Brutal+ system.

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
- Royal Guard Portraits (Co-op) - DaveSpectre
- Purifier Shield Battery - Enoki
- Better Mengsk Status Frames - Enoki
- Common Sense Balance - OmniSkeptic
- Data-Driven Turrets - Enoki

DaveSpectre is the goat <3
