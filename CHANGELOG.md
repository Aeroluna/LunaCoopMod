# Changelog

## 8/26/2026

- Fixed an issue where Kerrigan P3 played the wrong death sound.
- Fixed an issue where Kerrigan P4 played the death sound at the start of the map.
- Fixed an issue where Emperor's Shadow's Rank 3 Pyrokinetic Immolation always exploded when expiring, regardless of the target being alive.
- Fixed an issue where the shield fizzle animation played on invulnerable units, e.g. Disruptor orb, Adept shade.
- Fixed an issue where upon researching Warpgate Research, Gateways will automatically transform into Warpgates, even if a unit is in production.
- Fixed an issue where Overlords did not have the Load Nearby command.
- Fixed an issue where Horner's units did not have the Dominion decal after researching their unit's respective upgrade.
- Fixed an issue where Deimos Vikings with the Shredder Rounds upgrade dealt damage to their main target an extra time.
- Fixed an issue where the pierce effect from Deimos Viking's Shredder Rounds did not factor weapon range.
- Fixed an issue where Deimos Vikings with the Shredder Rounds upgrade would play the firing sound/muzzle flash/beam for each enemy hit.
- Reworked Deimos Viking's Shredder Rounds visuals to scale with weapon range.
- Fixed an issue where Xel'naga Abrogators had no visual birth effect for the Purification Nova.
- Fixed an issue where some Zeratul units did not play a level up visual effect when picking up an artifact.

yeah.

- Added a new Zeratul unit: Shadewalker
  - Adept variant.
  - Artifact passive 1: When a Shadewalker uses Psionic Transfer, it will create a tornado that deals 16 damage per second and applies a 30% slow to nearby enemies.
  - Artifact passive 2: Increases Shadewalker attack speed by 45%.
  - Artifact passive 3: Tornadoes from the Shadewalker's Psionic Transfer will persist for an additional 6 seconds.

Zeratul has 6 different units to pick from, he deserves more variety! I wanted to add a unit that takes micro to use, so my first thought was making a High Templar variant. However, Zeratul technically already has a High Templar in the form of Telbrus, and 3 other commanders have their own High Templar, so I went with an Adept instead.

- Fixed an issue where Shock Division firing from Intercessors did more damage than intended while below rank 3.
- Increased weapon speed of Shock Division firing from Intercessors from 4.5 to 4.

Fun fact: Shock Division in Intercessors actually *lost* damage when they hit max rank due to a bugged value. The attack speed has been slightly increased to compensate.

- Added a visual glaze to units targeted by a Emperor's Shadow's Pyrokinetic Immolation ability.
- Adjusted Emperor's Shadow's Pyrokinetic Immolation ability visual effect scale.
- Changed Nuclear Annihilation's cursor splat.
- Added a cursor splat to Dogs of War.

Make some Mengsk stuff prettier.

- Buffed Tempest's Disintegration ability to no longer require research.
- Added Tectonic Destabilizers upgrade:
  - Improves the Tempest's weapon to deal +40 damage vs structures.
- Reduced Tempest visual scale by 10%.
- Decreased Tempest life from 300 to 200.
- Decreased Tempest shield from 150 to 200.
- Decreased Tempest cost from 300/200 to 250/175.
- Increased Tempest speed from 1.875 to 2.25.
- Decreased Tempest ground damage from 60 to 40.
- Decreased Tempest air damage from 60 to 30 (+22 vs Massive).
- Increased Tempest air weapon range from 6 to 13.

Copied from Versus. In Versus, Tempests are much better skirmishers with increased movement speed and better range.

- Increased Destabilizing Residuum damage from 20 to 30.
- Renamed Destabilizing Residuum to Unstable Residuum.

Compensatory buff for Artanis specific upgrade. Renamed because it sounded too similar to Tectonic Destablizers.

- Renamed Artanis's Mothership to Shield of Aiur.

This Mothership was significantly stronger than normal Motherships so it's been given a unique name to represent that.

- Increased Sentry damage from 6 to 6 (+4 vs Shields).
- Increased Viking ground damage 12 to 12 (+8 vs Mechanical).

I'm usually hesistant to directly buff Amon, but I have an addiction to Versus parity.

- Decreased Yamato Cannon damage from 300 to 240.
- Removed random delay between shots from Battlecruiser's weapon.
- Reduced Battlecruiser air damage from 6 to 5.
- Buffed Battlecruisers to move while shooting.

Copied from Versus. All the commanders get the moving-while-shooting Battlecruiers, now Amon gets them too. Battlecruisers still have energy to keep them susceptible to feedback effects.

- Changed Battlecruiser's Yamato Cannon to still cost energy when it gets cancelled.
- Changed Hybrid Dominator's Plasma Blast to still cost energy/cooldown when it gets cancelled.

Makes dodging these single target nukes way easier.

- Increased Sentry speed from 2.25 to 2.5.
- Increased Guardian Shield duration from 15 to 18 seconds.
- Increased Guardian Shield radius from 4 to 4.5.
- Removed Light attribute from Sentry.

Copied from Versus.

## 8/15/2026

- Fixed an issue where killing Kerrigan while burrowed would spawn a duplicate Kerrigan actor after reviving.
- Fixed an issue where Amon's Ghosts and Wraiths could use Cloak before their upgrades are researched.
- Fixed an issue where Nova's P1 only applied if at least one charge was used.
- Fixed an issue where H.U.G.S. Overload shield could target invulnerable units.
- Fixed an issue where the Fear Mutator could target Frenzied units.
- Fixed an issue where some burrowed units could be pulled by Fatal Attraction.
  - Affected units:
    - Infested Civilian
    - Infested Trooper
    - Volatile Infested
    - Kerrigan
    - Spider Mine
    - Widow Mine
    - Sabotage Drone
    - Ravager
    - Infested Banshee
    - Zagara
- Fixed an issue where Amon's Swarm Host's Spawn Locust ability used the wrong tooltip.
- Fixed an issue where Abathur's Swarm Host's Spawn Locust ability did not have a descriptive tooltip.
- Fixed an issue where Dehaka's Primal Host's Spawn Locust ability did not have a descriptive tooltip.
- Fixed an issue where Dehaka's Creeper Host's Spawn Locust ability did not have a descriptive tooltip.
- Fixed an issue where Artanis's P3 Unbound Fanatics would spawn slightly before the Orbital Strike landed
- Fixed an issue where Colossi could still deal damage if their current target became invulnerable.
- Fixed an issue where Hybrid Reaver/Behemoth's Consume DNA ability could still deal damage if the target became invulnerable.
- Fixed an issue where lava damage on The Vermillion Problem could still deal damage if the target became invulnerable.
- Fixed an issue where Dehaka's P1 could affect map objectives, e.g. Aurana's Transport, Harvesting Bots.
- Fixed an issue where Dehaka's P2 disadvantage could be negated by loading Dehaka into a Nydus Worm before using Pack Leaders.
- Fixed an issue where when either Dehaka gains Deadly Reach with P3, both benefit from the upgrade.
- Fixed an issue where Zweihaka would rally towards a random unit if no rally is set.
- Fixed an issue where invulnerable units could trigger Stasis Wards.
- Fixed an issue where Adepts and Talis could permanently be unable to use Psionic Projection if stasised while on cooldown.
- Fixed an issue where Fenix's Champion A.I.s had the wrong resources costs (This affected calculations like Han & Horners salvage).
- Fixed an issue where Warbringer ignored armor.
- Fixed an issue where Dominion Starports did not respawn if killed by a Propagator.
- Fixed an issue where Parasitic Bomb did not work on Han & Horner's Reapers while flying.
- Fixed an issue where Parasitic Bomb did not work on some ground/air units like Void Thrashers.
- Fixed an issue where some structure disabling effects did not affect Supply Bunkers/Infested Bunkers.
- Fixed an issue where Stetellites only respawned once with the Eminent Domain mutator.
- Fixed an issue where Infest Structure spawned double the Broodlings when used on conjoined ally units.
- Fixed an issue where researching Regenerative Bio-Steel overrides health regen effects.
- Fixed an issue where Lt. Nikara could not heal non-biological/mechanical units, e.g. Archons.
- Fixed an issue where Banelings affected by time slows would have a delay before exploding.
- Fixed an issue where Hardened Will did not get removed/added while affected by time slows.
- Fixed an issue where Black Death damage counted as self-damage.
- Fixed an issue where Zagara's Baneling Barrage did Double Edged damage against structures.
- Fixed an issue where Zeratul's P3 tornadoes could not deal damage to units affected by time slows.
- Fixed an issue where Void Templar had access to Blink before unlocking the level 3 perk.
- Fixed an issue where units created by Mutators can once again drop Biomass/Essence after being devolved.
- Fixed an issue where Han & Horner's SCVs could not Halt from their command card.
- Fixed an issue where Assault Galleon construction could not Halt from their command card.
- Fixed an issue where mind controlling a unit affected by Han & Horner's Theia Raven's Analyze Weakness did not break the effect.
- Fixed an issue where mind controlling a unit affected by Alarak's Havoc's Target Lock did not break the effect.
- Fixed an issue where Death Grip Crystals could target units warping in.
- Fixed an issue where units with Dehaka's P1 thorns buff have their spikes come from Dehaka instead of the unit themselves.
- Fixed an issue where Taldarin did not have turret tracking.
- Fixed an issue where Taldarin had no visual effect when Barrier is used.
- Fixed an issue where Banshee Airstrikes that expire while being knockbacked will use the wrong expire animation.
- Fixed an issue where casting Assimilation Aura while leaping can cause the visual to be rotated incorrectly.
- Fixed an issue where killing a missile from Missile Command with Just Die! active caused the respawn animation to occur on the killing unit instead of the missile.

I'm back with a ton of bug fixes. I might have found [https://starcraft2coop.com/resources/bugs](https://starcraft2coop.com/resources/bugs).

- Increased Abathur's Swarm Host life from 120 to 160.

Parity with Amon's Swarm Host.

- Added a burrowed splat when Dehaka P2 exits the map.

Don't forget where you parked your Dehaka!

- Fixed an issue where Zagara's P1 removed the gas cost of Scourge.

That one is my fault.

## 8/2/2026

- Fixed an issue where Abathur's Ravagers had no burrowed splat when burrowed.
- Fixed an issue where rooted Infested Bunkers had no death animation (Uprooted are still missing a death animation).
- Fixed an issue where Fenix P2 did not affect phasing Conservators.
- Fixed an issue where Han & Horner P1 did not affect Theia Ravens in Silent Mode.

yeah.

- Increased movement speed of Ravens from 2.25 to 2.75.

Ravens have had increased movement speed since LotV released, but somehow that change didn't make it into Co-op.

- Increased Theia Raven life from 140 to 300.
- Increased Theia Raven supply cost from 2 to 4.
- Incraesed Theia Raven cost from 100/200 to 200/250.
- Increased Theia Raven visual scale by 15%.
- Added Anti-Armor Missile ability to Theia Ravens.
  - Deploys a missile which pursues the target unit and, upon contact, reduces the armor and shield armor of affected units by 2 for 30 seconds.

Han & Horner get an elite Viking, Wraith, Battlecruiser, and then randomly a normal statted Raven? Now they also get a cool ability instead of being an a-move unit.

## 7/20/2026

- Replaced the Drakken Laser Drill construction sound.

yeah.

- Added Heroic attribute to Telbrus.
- Added Heroic attribute to Zoraya.
- Added Heroic attribute to Serdath.

They deserve the Heroic attribute!

### Death from Above

- Fixed an issue where Zeratul's artifacts could spawn in unpathable locations.

## 7/17/2026

- Fixed an issue where Vorazun's Void Sanctuary lasted longer than intended.
- Fixed an issue where Tychus P4 could not purchase gear while at 5 outlaws.
- Fixed an issue where Tychus's gear was still visible while at max outlaws.
- Fixed an issue where Tychus's description was still visible on Joeyray's Bar at max Outlaws
- Fixed an issue where Hercules was missing the Load Nearby command.
- Fixed an issue where Imperial Intercessor was missing the Load Nearby command.
- Fixed an issue where Mecha Infestors would sometimes not have their burrowed splat destroyed when unburrowing.
- Changed Avenging Protocol buff tooltip to be more descriptive and show exact speed increase.

yeah.

- Added unused Mass Frenzy VO.
- Added additional "Thanks" VO triggers.
  - Karax's Chrono Wave ability.
  - Zagara's Mass Frenzy ability.
  - Abathur's Mend ability.

They went through the work of recording thank you lines for every commander, then only made Vespene Drone and Shield Overcharge actually trigger them. Now you should hear these lines a little more often. The frequency of hearing these should be lower than normal so they don't become too annoying.

- Changed Murvar to no longer walk over massive units.
- Changed Dakrun to no longer walk over massive units.

Missed these in the last update.

- Added `-wololo X` cheat to set chance to neural killed enemies.

If you want to for some reason you want to replicate the absurdity of pre-nerf Stukov P4. Works on any commander.

- Changed Deconstructive Roach-nites to allow targeting non-heroic units.
- Reduced Deconstructive Roach-nites damage from 500 to 300 (+200 vs Structures).

Unlike regular Infestors, there is almost no incentive to add Mecha Infestors into your army for support, as they work better being massed in your base spawning Roaches. Allowing Deconstructive Roach-nites to have some utility on offense should make having a few Mecha Infestors in your army more appealing.

- Fixed an issue where Fenix P1 did not increase the cooldown or increase regeneration of the Arbiter suit.

The Arbiter suit gets the increased damage and can only last 20 seconds, but for some reason, despite not mentioning this anywhere in the description, they commented out the parts that modify the Arbiter's regen and cooldown.

- Increased Champion A.I. allied push priority from 0 to 1.
- Increased Fenix's (Dragoon) allied push priority from 0 to 1.

Nobody wants their important units stuck in the back. Especially important for Champions because they usually have less range than their non-champion counterparts and often got trapped behind.

- Reworked Kaldalis's Engage ability mover.
  - Now moves at a fixed speed instead of having a fixed duration.

This ability was slower than Charge when close to the target because of the fixed duration. Now it should always feel snappy.

- Added P2 advantage:
  - Champion A.I.s have an increased attack priority.

It was tragic watching everything *but* your Champion get killed. Now enemies will be lured to your Champion like a moth to the flame, giving you that sweet refund.

- Gateway unit train time reduction bonus from researching Warp Gate increased from 40% to 50%.
- Gateway train visuals will no longer trigger if 'Effects' graphics options are set to low.
- Warpgates now have selection subgroup priority over Gateways.
- Warpgates and Gateways are now considered distinct units when issuing 'select all' commands.
- Gateways and Warpgates can now be issued orders to transform regardless of which is the primary subgroup selection.
- Reverted spawned Hallucinations inheriting their caster's order queue.
- Selection radius color is now distinct for primary subgroup selection when Colorblind mode is enabled.
- Fixed an issue in Team games where Cyclones could fail to deal damage to units detected by an ally.
- Ghost Supply reduced from 3 to 2.

5.0.16b hotfix changes.

## 7/16/2026

- Fixed an issue where some buff visuals did not inherit some properties like the cloak effect or unit scale.
- Fixed an issue where Evolve to Leviathan used the wrong Leviathan description.
- Fixed an issue where Zagara's Baneling Barrage would explode prematurely on Adept shades.
- Fixed an issue where Toxic Nests would autocast on Changelings/wrong Polarity/detected Hallucinations.
- Fixed an issue where Mecha Battlecarrier Lord Cocoons did not play their birth animation.
- Fixed an issue where the Gary to Super Gary morph model was the wrong scale.
- Fixed an issue where the 5.0.16 Larva spawn offset change did not affect Stetmann's Larva.
- Fixed an issue where unburrowed Mecha Lurker's dummy weapon did not change icons with weapon level.
- Fixed an issue where Stetmann's units had a delay before starting a morph.
- Fixed an issue where Abathur's Viper's Abduct did not have a range indicator.
- Increased Hybrid Behemoth's allied push priority from 0 to 1.
- Fixed an issue where Colossi could walk through Void Thrashers.
- Fixed an issue where Sirius's Moebius M34 Terror Rounds would affect invulnerable units.
- Fixed an issue where Tychus could not construct Fortified Bunkers. (wtf)
- Fixed an issue where Fortified Bunkers would show the reduced cooldown mastery on the tooltip for all abilities.
- Fixed an issue where the 5.0.16 KD8 Charge changes did not affect Han & Horner's Reapers.
- Fixed an issue where Han & Horner's Reapers had a small delay before they actually died.
- Fixed an issue where Nova P3 Sabotage Drone was doing more damage than intended.
- Fixed an issue where Colossi could not walk over Infested Bunkers.
- Fixed an issue where Baneling Spawn did not play an animation after timing out.

yeah.

- Added effect to Mengsk P4:
  - Dogs of War will continuously deploy more enthralled Zerg slowly.
- Reduced Mengsk P4 cooldown reduction from 100% to 50%.

Just being able to a top-bar more often is boring, so I decided to give it an additional unique effect.

- Added Rally top-bar ability to Raynor P4:
  - 60 second cooldown.
  - Sends all currently existing mercenary squads to the designated point.

Adds a little bit of control to a sometimes frustating prestige. Ideally they are consistent enough that I can finally justify nerfing the cost of these mercenaries at some point.

- Changed Aberrations to no longer walk over massive units.
- Changed Brutalisks to no longer walk over massive units.
- Changed Tyrannazors to no longer walk over massive units.

It was a little disturbing watching Aberrations clip straight through Ultralisks and Thors.

## 7/7/2026

- Fixed an issue where `-solo` did not allow capturing locks alone on Lock & Load.
- Fixed an issue where Kaldalis's movement speed was unaffected by the Charge upgrade.
- Reduced Kaldalis's movement speed from 3 to 2.25.
- Fixed an issue where Legionnaires had the Reconstruction button on their command card despite not having Reconstruction.
- Fixed an issue where Stukov's unit cocoons spawned too closely together.
- Fixed an issue where Vipers did not display rank/kill count.
- Fixed an issue where Blinding Cloud's visuals were larger than intended.
- Fixed an issue where Evolve to Brutalisk did not have a descriptive tooltip.
- Fixed an issue where Evolve to Leviathan did not have a descriptive tooltip.
- Fixed an issue where canceling Evolve to Brutalisk would remove the Biomass material glaze.
- Fixed an issue where canceling Evolve to Leviathan would remove the Biomass material glaze.
- Fixed an issue where burrowed Ravagers could not use Evolve to Brutalisk.

everytime i open the editor again, i find 10 new bugs.

- Changed Evolve to Brutalisk to have autocasting off by default.
- Changed Evolve to Leviathan to have autocasting off by default.
- Toggling autocast on Evolve to Brutalisk/Leviathan will now toggle autocast for all units of the same unit type.

Nothing more tragic than building 100 Biomass on your Swarm Host just to accidentally morph it into a Brutalisk. Now you can choose which unit types should automatically evolve (probably Roaches and Mutalisks).

- Added a sound effect for Symbiote's Spike Burst ability.
- Reduced the volume of Symbiote's Stab ability.

Those Symbiotes are loud!

- Renamed Symbiote's Shell ability to Carapace.

Why was this renamed from Carapace in the first place?

## 7/2/2026

- Added Motherships to the Transmutation mutator.
- Renamed Mothership mutator to Purifier.
- Increased scale of Purifier by 25%.
- Changed Purifier model to Golden skin.

Now that Motherships can be found normally, the mutator has been changed to be more distinct.

- Reworked mutator: Trick or Treat
  - Changed alignment to neutral.
  - Trick-or-Treaters visit your Candy Bowl looking for treats, which are found by killing enemies.
  - If no treats are available, the Trick-or-Treaters transform into random enemy units.
  - The candy must be brought back to the Candy Bowl to refill it, or alternatively can be held onto for the buff.
  - Costs 3 points for Brutal+.

Completely reworked and rebalanced. The old version was boring and just acted as a simple mineral tax. This new version requires actually interacting with the Candy Bowl by bringing candy back to it. Additionally, more candy spawns than is consumed, letting you get some buffed up units. The mutator has also gotten some much needed all-around polish.

- Fixed an issue where recall effects wouldn't execute.
- Fixed an issue where the recall visual would not dissipate.
- Fixed an issue where units affected by Gary's recall would not have their tint cleared.
- Fixed an issue where some recall sounds wouldn't play.

Oopsies bugs with recalls.

- Fixed an issue where the previous visual change to researching structures did not affect some variants.
- Fixed an issue where Aurora Veil tooltip listed the wrong healing rate.
- Fixed an issue where Ordnance Depot Retrofit tooltip said nuke instead of Tactical Missile.

yeah.

## 7/1/2026

- Fixed an issue where the Infestor's weapon used the incorrect base attack icon.
- Fixed an issue where new Archon sounds were initialized incorrectly and would play too loudly.
- Fixed an issue where Stasis Wards had a selection priority equivalent to units.
- Fixed an issue where mule repair autocast mechanism was briefly unintentionally visible.
- Fixed an issue where Swarmhost range radius actors would appear at unintended times.
- Fixed an issue where 'Load Nearby' had the wrong default hotkey set.
- Archon merge completion assets are now disabled if the player is using the low 'effects' graphics option.
- Queens will now spawn facing their origin hatchery.
- Units produced out of gateways have been given a visual spawn indicator.
- Fixed an issue where larva spawn rate was faster than intended.

5.0.16 hotfix changes.

## 6/29/2026

- Fixed an issue where many autocast abilities would target disguised Changelings.
- Added target priority to many autocast abilities.
- Fixed an issue where some autocast ablities would target units with the wrong Polarity.
- Fixed an issue where Changelings could not disguise as a Stukov unit.
- Fixed an issue where Abathur's Swarm Host Spawn Locust ability could only target within a small range.
- Reduced the allied push priority of Abathur's Locust from 0 to -1.
- Reduced the allied push priority of Primal Locust from 0 to -1.
- Changed Abathur P2 to double the range of Swarm Host's Spawn Locust weapon.
- Fixed an issue where Primal Host lacked an equipment (weapon) display indicator for the Locust.
- Fixed an issue where Creeper Host lacked an equipment (weapon) display indicator for the Locust.
- Fixed an issue where extra units from the Teeming mutator could get stuck.
- Fixed an issue where Karax P4 did not affect units affected by Reclamation.
- Fixed an issue where Avatar of Form's Summon Charged Crystal ability would track units while preparing when autocasting.
- Fixed an issue where Charged Crystal's Psionic Winds would be place where the target was when the attack started.
- Fixed an issue where Charged Crystal's Psionic Winds visuals would sometimes end prematurely.
- Reworded Avatar of Form's Devolution Wave tooltip to mention heroic immunity.
- Fixed an issue where Blood Hunter upgrades were not restricted to Alarak.

yeah.

- Reduced the max scaling of the Harassment mutator.
- Reduced Harassment mutator Brutal+ point cost from 7 to 6.
- Increased Imposters mutator Brutal+ point cost from 3 to 4.

These are hard!!!!!

## 6/28/2026

- Increased Overseer maximum energy from 0 to 200.
- Increased Overseer energy regeneration rate from 0 to 0.5625.
- Increased Overseer starting energy from 0 to 50.
- Added Spawn Changeling ability to Overseer.
- Added Contaminate ability to Overseer.

Amon's Overseers only (Spawn Changeling and Contaminate are useless for commanders). Giving these energy lets them be vulnerable to feedback abilities. I already did the work of making Changelings work with Commanders, so why not have fun with them!

- Reduced Zealot (and variants) speed from 2.75 to 2.25.
- Increased Charge speed increase from 0.25 to 1.125.

Not sure why the LotV campaign increases their speed but their speeds have been reverted to Versus values.

- Fixed an issue where Terran commanders could donate buildings to their ally.

Why was this behavior even implemented in Versus?

- Fixed an issue where units knocked back by KD8 Charges did not play a flailing animation.
- Fixed an issue where knocking back units with shields would cause shield fizzle animations to play erroneously.
- Reduced the opacity of Reaper KD8 Charge placeholder model.
- Fixed an issue where Changelings could target the wrong player when targeting a Nydus Worm.

yeah.

## 6/25/2026

- Added Blood Hunters.
  - Passive: Obliteration
    - Attacks reduce the max life of targets by 10%.
    - Heroic target max life is reduced by 5% instead.
    - This effect can stack.
  - Passive: Siphon Essence
    - Gains shield equal to 100% of all damage dealt from normal attacks.
    - Researched at the Dark Shrine for 100/100 for 60 seconds.
  - Ability: Shadow Strike
    - Teleport to a nearby target.
    - Acts similar to Zealot's Charge.
    - Researched at the Dark Shrine for 100/100 for 60 seconds.

I know I already gave Alarak a new unit, but I couldn't resist adding Blood Hunters!

- Fixed an issue where EMP visuals did not provide clear visual indication of effect radius/affected units.
- Fixed an issue where Motherships would warp in adjacent to the Nexus rather than overtop.
- Fixed an issue where Guardian Shield visuals would persist even after loaded into a transport.
- Fixed an issue where melee units targeting builder SCVs would lose their attack order when the SCV moved through the structure.
- Fixed an issue where SCVs could not have build orders queued sequentially onto structures already being constructed by another SCV.
- Fixed an issue where Guardian Shield visuals would not update player colour post-initialization.
- Fixed an issue where the KD8 Charge lacked a placement model and AOE effect radius cursor indicator.
- Fixed an issue where the KD8 Charge would be thrown in front of a target unit rather than at the targeted cast point.
- Fixed an issue where some units' spells would not trigger Protoss shield-damage graphics (Purification Nova, Corrosive Bile, KD8 Charge).
- Fixed an issue where units with burrow move would lose their current orders when told to burrow.
- Fixed an issue where attack commands with Adept Shades in the selection behaved erratically (eg. finishing a shade caused the attack target to be lost if the command was not issued by smart command/right click, units could unexpectedly move command etc).
- Fixed an issue where Lurker Attack Spike sounds could be heard through the Fog of War.
- Fixed an issue where Lurker eggs lacked polish during creation/destruction. Eggs now take less time to appear due to faster birth animation and play a death cry to communicate when destroyed early.
- Fixed an issue where the Warp Prism would not display an unload visual model indicator.
- Fixed an issue where the Warp Prism would not display a load range radius actor when the ability was being targeted.
- Fixed an issue where the Warp Prism movement was highly variant/ sluggish if ordered to queue pickup orders or pick up units slightly out of immediate range.
- Fixed an issue where commanding Oracles to build Stasis Wards in areas inside their range could result in slower execution than being commanded to build outside their range.
- Fixed an issue where Oracles would teleport short distances if told to build a Stasis Ward while overlapping with other air units (such as other friendly oracles).
- Fixed an issue where Stasis Wards lacked a distinct audio cue for their death.
- Fixed an issue where players attempting to attack a Stasis Ward could easily accidentally move command underneath it instead.
- Fixed an issue where Voidray Prismatic Alignment lacked a termination audio cue.
- Fixed an issue where beam attack visuals would not terminate if targets were picked up by transports or teleported away (Sentry, Void Ray).
- Fixed an issue where the Sentry's beam attack visuals were misleading due to being significantly delayed during creation and termination. They should now feel much more responsive to control.
- Fixed an issue where the High Templar's basic weapon's visuals and sounds were not proportionate in size/volume to its impact.
- Fixed an issue where killing a Viper prior to its Abduct tongue connecting with a target would not cancel the abduct.
- Fixed an issue where Planetaries lacked or had misleading visual and audio indicators (splash damage impact visuals, sound).
- Fixed an issue where Archons lacked several visual and audio indicators (birth sound, splash damage impact visuals, movement sound, attack physics).
- Fixed an issue where friendly Disruptor Purification Nova range radius actors were displayed permanently, even if the unit was on cooldown, causing unnecessary clutter as unit count increased.
- Fixed an issue where SwarmHost range radius actors were displayed permanently, even if the unit was on cooldown, causing unnecessary clutter as unit count increased.
- Fixed an issue where SwarmHosts lacked an equipment (weapon) display indicator for the Locust.
- Fixed an issue where Hellbat walk animation speed was faster than expected.
- Fixed an issue where casting Generate Creep would only affect a subselection of Overlords or Transport Overlords rather than both variations.
- Fixed an issue where Creep Tumors lacked placement and placeholder models when spreading themselves.
- Fixed an issue where it could be difficult to distinguish if a research structure was active (Twilight Council, Fleet Beacon, Armory, Evolution Chamber).
- Improved an issue where injecting Queens 'shuffle'. Allowed re-issuing inject during ongoing cast so orders are not offloaded to others queen. Long-range orders are invalid if another queen is nearby the target hatchery.
- Improved an issue where units with their primary attack order on a changeling would lose their order if the Changeling subsequently disguised itself.
- Improved an issue where gather orders were clunky for workers. Workers adjacent and move commanding to a geyser now update their command to a gather order if a refinement structure gets built.
- Active Creep Tumors will now take selection precedence over Inactive Tumors.
- Active Creep Tumors in a control group at the time of exhausting their charge will now transfer control group membership to the spread tumor.
- Larva/Eggs will no longer collide with/block player structures or units.
- Neural Parasite will now add the target unit to the current selection if the selection only contains one infestor.
- Protoss structures now generate additional 'damaged' graphical models.
- As larva increases, they will now spread further upwards around the sides of the hatchery. Larva will still start from the bottom of the hatchery.
- Slightly polished Oracles' Revelation and Build animation transitions.
- Casters with weak weapons are now less likely to aggro towards faraway targets.
- Adjusted Warp Prism and Raven visual fly height to minimize clipping inside other models and reduced Warp Prism shadow size on low graphics to minimize shadow-casting on unloaded units.
- Commands to unsiege Warp Prisms will now be issued to all Warp Prisms in the selection.
- The Warp Prism will now attempt to immediately siege when instructed rather than prioritizing deceleration.
- Repair is no longer automatically set to auto-cast for SCVs.
- Mule Repair is now set to auto-cast by default (Mules with a harvest order still do not attempt to repair units).
- Added Load Nearby commands to all transports.
- Reduced Infantry weapons/armor upgrades costs from 100/175/250 to 100/150/200.
- Reduced Zerg Ground Carapace upgrade costs from 100/175/250 to 100/150/200.
- Mutalisk Glaives now prioritize targets.
- Mutalisk arc slop increased to 180.

5.0.16 Versus fixes/changes

- Buffed Warp Gate Research to also reduces the build time of units produced by Gateways by 40%.

Without the 25/25 cost from Versus, I'm not sure what would drive anyone to want to do this, but the option is there.

- Removed Armored attribute from Creep Tumors.
- Added Light attribute to Creep Tumors.

Another Versus change. Hellions and Firebats should be able to roast these things!

- Increased Ghost (and variants) supply cost from 2 to 3.
- Changed Ghost (and variants) damage from 10 (+10 vs Light) to 15.
- Increased Ghost (and variants) attack range from 6 to 7.
- Increased Ghost (and variants) movement speed from 2.25 to 2.75.
- Added Light attribute to Ghosts (and variants).
- Removed Sniper Round.
- Added Steady Targeting.
  - After carefully aiming for 2 seconds, the Ghost fires a sniper round dealing 170 damage. Ignores armor.
  - Can only target biological units.

Copied from Versus. These changes should further solidify Ghosts as backline snipers. Steady Targeting should also be more interruptable than Sniper Round was.

- Fixed an issue where Reaper KD8 Charge ability could knockback burrowed units.
- Fixed an issue where Glevig's Fire Breath impact sounds played on Glevig.
- Added a countdown for tracking barrier abilities.
- Changed Havoc's Target Lock to prioritize attacking units and structures.
- Changed Theia Raven's Analyze Weakness to prioritize attacking units and structures.
- Renamed Void Archon's Chain Reaction passive to Chain Destruction.

yeah.

## 6/4/2026

- Reworked Astral Storm to no longer apply a secondary lingering debuff.
- Fixed an issue where Astral Storm did not negate shield armor.
- Reduced Astral Storm damage from 56 to 50.
- Increased Astral Storm armor reduction from 4 to 5.
- Reduced Astral Storm slow from ~60% to 50%.
- Increased Astral Storm duration from 7 seconds to 8 seconds.

Simplifying an ability that is already a little overloaded.

- Increased Shield Battery starting energy from 50 to 100.
- Reduced Shield Battery maximum energy from 200 to 100.

Karax's Shield Batteries are unaffected.

- Increased Karax's Shield Battery starting energy from 50 to 200.

### Primal Ascension

- Added benign flag to bosses being healed by a crystal.
- Fixed an issue where Amon had the wrong Swarm Host variant.

### Construction Yard

- Added a final attack wave that attacks the last camp.

Makes the ending feel more climactic

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
- Changed Infested Marines to spawn two at a time.
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

### Solar Right

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
