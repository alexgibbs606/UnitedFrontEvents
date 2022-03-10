# Change Log

## v0.2 Change Log:

### UF_Kohat_CacheDefense_v1:

- BUG Fixes
- INS hab not viewable by CAF
- Set initial lives for each player to 1
- Updated the map boundary to lower the total playsize of the map
- Updated staging zone timers to match staging time
- Updated temp spawns to end 1 min after staging time ends
- Added new CAF spawnpoint to Bannu Rd with two transports and a Heli
- Added new CAF spawnpoint to FOB Connolly with two transports and two Heli
- Removed the CAF spawnpoint at Lodi Khel (Original Main)
- Removed delay from Heli spawns
- INS defense FOB initial ammo reduced to 200
- INS defense FOB ammo per second to 1 per second (This makes the ammo at "match start" 860, and a total of 2400 over the course of the match)

### UF_Yeho_FOBDefense_v1:

- US defense initial FOB ammo reduced to 200
- US defense FOB ammo per second to 1 per second (This makes the ammo at "match start" 860, and a total of 2400 over the course of the match)

### Known Bugs:

- UF_Kohat_CacheDefense_v1 escape vehicles are not spawning

## v0.3 Change Log:

### UF_Yehorivka_FOBDefense_v1:

- Linked RUS main to invasion path to show up, RUS can now manage supplies in their spawn.
- Added two repair stations in RUS spawn right outside logistics area
- Set spawn limit of 1 on all RUS vehicles
- Altered the build radio on US to cover a larger area. This change does not show on map, but it is extended. resolves #2

### UF_Kohat_CacheDefense_v1:

- Fixed level data object in hopes that it will fix the map change issue, unable to test while PIE

### Known Bugs:

- UF_Kohat_CacheDefense_v1 escape vehicles are not spawning

## v0.4 Change Log:

### UF_Kohat_CacheDefense_v1:

- Ammo box added to upper and lower FOB Connolly
- Repair stations added to FOB Connolly and Bannu Rd
- CIV faction added to fix neutral vehicles spawning. resolves #1
- Fixed issue with CAF sniper kit not being found
- MISC bug fixes
- MISC bug fixes

## v0.5 Change Log

- New steam workshop description

### UF_Yehorivka_ROBDefense_v1:

- Extended US staging area to include surrounding landmarks
- Bug fixes with faction setup
- Increasing game timer to include another 8 min to account for staging phase
- Reduced tickets to RU=100 US=200 (This really doesn't matter)
- Disabled US ability to make HAB's and TOW's
- Disabled vehicle cleanup (vehicles will now last forever on map)
  - Solves being unable to lean

### UF_Kohat_CacheDefense_v1:

- Disabled vehicle cleanup (vehicles will now last forever on map)

## v0.6 Change Log

v0.5 introduced major performance issues, I've rolled back and cherry picked only nessessary changes to alleviate the issue.

Listed changes are things KEPT from the previous version

### UF_Yehorivka_ROBDefense_v1:

- Extended US staging area to include surrounding landmarks.
- Added new US faction that doesn't have HAB, TOW, FOB, vehicle, or commander abilities.
- Removed vehicle collision preventing infantry from leaning.

## v0.7 Change Log

- Added new layer `UF_Mutaha_FOBDefense_v1`
- FOB Defense Gamemode Staging phase reduced from 8 min to 5 min
- Added vehicle cleanup to FOB Defense gamemode

### UF_Yehorivka_FOBDefense_v1

- Sokolov capture point has been tightened to only include inside walls of sokolov
- Replaced all deployables with new blueprints to fix running man issues
- RUS now has 3 logis, 1 transport, and 2 tigrs to use at admins discretion

## v0.7 Change Log

- Added new layer `UF_Sumari_FOBDefense_v1`

## v0.8 Change Log

### UF_Yehorivka_FOBDefense_v1

- Fixed bug about ammo crate not showing up

## v0.9 Change Log

- Removed combat engineer limit for USA OneLife faction
- Added UF_RUS_Infinite_Attackers

### UF_Yehorivka_FOBDefense_v1

- Reduced RU tickets to 100
- Reduced defense capture point time from 120 to 40 seconds
- Changed US spawn icon to rally instead of main base
### UF_Sumari_FOBDefense_v1

- Reduced RU tickets to 100
- Reduced defense capture point time from 120 to 40 seconds
### UF_Mutaha_FOBDefense_v1

- Reduced RU tickets to 100
- Reduced defense capture point time from 120 to 40 seconds

### Known Bugs

- Unable to reproduce inability to primary fire on PIE, will continue to investigate

## v0.10 Change Log

- Added new layer UF_Fallujah_HVTHunt_v1
- added new gamemode HVT Hunt
- Added new CAF Faction for UF_Fallujah_HVTHunt_v1

## v0.11 Change Log

### UF_Fallujah_HVTHunt_v1:

- Removed protection zone in Team1 main that prevented vehicle from working correctly.
- Moved the map camera location to the compound that the teams are fighting over.
- Added a black hawk on team 2 inside the compound, but the vehicle isn't spawning and I'm unable to start it with damage for now
- Disabled 'Force all role availability' in layer config
- INS MG and Sniper set to same access as scoped medic (1 per squad with a squad of 2+)
- CAF MG and Sniper set to same access as scoped medic (1 per squad with a squad of 2+)
- Removing Unarmed from CAF
- CAF Combat Engineer unlimited count
- Reduced INS tickets to 104
- Reduced INS infantry ticket loss to 0
- Reduced INS commander ticket loss to 100
- The result of these changes is that any number of infantry can die, but the commander and a single helicopter will end the match.
- Updated gamemode to restrict each player to only a single life.

## v0.12 Change Log

- Removed `UF_Fallujah_HVTHunt_v1` as the layer has gotten too broken.
- Added `UF_Narva_HVTEscort_v1`

### UF_Narva_HVTEscort_v1:

- Submitted for playtesting, see mod channel for "design image"

### UF_Yehorivka_FOBDefense_v1:

- Overhauled team system to set attackers to team1. This streamlines invasion settings and prevents bugs/unexpected invasion outcomes.

### UF_Mutaha_FOBDefense_v1:

- Overhauled team system to set attackers to team1. This streamlines invasion settings and prevents bugs/unexpected invasion outcomes.

### UF_Sumarai_FOBDefense_v1:

- Overhauled team system to set attackers to team1. This streamlines invasion settings and prevents bugs/unexpected invasion outcomes.


## v0.13 Change Log

- Bug hotfix for UF_Narva_HVTEscort_v1 from Feb 1st playtest

## v0.14 Change Log

- Added BoltyBois gamemode
- Added BoltyBois faction
- Added UF_Logar_BAAS_v1 (boltybois)

## v0.15 Change Log

- Updating Squad version to 1.12

## v0.16 Change Log

### UF_Narva_HVTEscort_v1

- Updating RUS commander spawn from 100 to 1000 tickets
- Updating RUS TRAN spawners to spawn the team included vehicles
- Updated escape zone capture to linear curve as 2 players at 80 seconds to 7 players at 30 seconds
- Updated temp spawn from 90 second lifespan to 210 seconds

## v0.17 Change Log

- Adding new custom flag

## v0.18 Change Log

- Fixing reference that prevented bolty bois from appearing in layer list

### UF_Narva_HVTEscort_v1

- Reduced min required player difference to cap airfield from 3 to 2
- Reduced spawn limit of vehicles on fools road gas station to 1

## v0.19 Change Log

### UF_Logar_Valley_BAAS_v1

- Updating capture points to be in order and appear on game load.

## v0.20 Change Log

- Brought Operation Longbow to state that is ready for playtest on `UF_Kohat_CacheDefense_v2`. v1 remains unplayable and will be deprecated once all assets and data have been transferred.
- Added `UF_SupplyCache` asset that takes the place of a FOB for Cache Defense game mode and supplies defending team with a FOB as well as the objective
- Added FOB exclusion radius table with Cache Defense values
- Additional MISC bug fixes. And I mean misc as in "idk what I changed" and "I hope I didn't break something but I'm committing this anyway"
### UF_SupplyCache
- Ends game when destroyed, looks like INS radio
- Does not require logistics vehicle to place
- Does not require teammate to place
- Does not have exposed ammo per second, ammo, or construction value. This needs to be set in blueprint. It's currently 200 ammo with 1/sec, and 20,000 construction.
- Will require layer to update FOB exclusion radius in data asset and set value to `01_CacheDefense` for 100,000 units build distance and 1,000,000 units exclusion radius, which should prevent another FOB from being built on the same map

### UF_Gamemode_CacheDefense

- Changed game time to 60 min
- Updated display name to 'Cache Defense'
- Added rule set class that prevents vehicle cleanup

### UF_Kohat_CacheDefense_v2

- Fixed lots of game-breaking bugs that were introduced when the layer was first created

- Team 1 - CAF
  - Corrected team on FOB Connolly deployables
  - Altered role requirements to match design doc
  - Repaired vehicle spawn issues

- Team 2 - INS
  - Removed build zone
  - Updated team radio to supply cache, the objective of this game mode
  - Reduced staging phase box size to match expeced bounds
  - Altered role requirements to match design doc

## v0.21 Change Log

- Added new FOB Defense layer `UF_Manic_FOBDefense_v1`

## v0.22 Change Log

- Tweaks on `UF_Manic_FOBDefense_v1`

### UF_Manic_FOBDefense_v1

- Increased staging zone timers to 300 seconds
- Increased defender temp-spawn lifespan to 480 seconds

## v0.23 Change Log

- Added `UF_Tallil_Outskirts_FOBDefense_v1` and ready for playtest

### UF_Manic_FOBDefense_v1

- Removed staging phase box from defenders #4

## v0.34 Change Log

### UF_Manic_FOBDefense_v1

- Updated capture time curve to FOB Defense capture point curve

### UF_Kohat_CacheDefense_v2

- Removed unessessary points
- Updated CAF spawns to die after 660 seconds
- Updated all spawns to be rally spawns
- For now, set all escape vehicles to be owned by CAF to prevent meta from INS
- Did not update CAF role requirements, everything looks as it should be. Riflemen are considered LAT kits and shouldn't be taking. Most INF should be snipers.
- Investigated unlocking escape point at lower mohd zai. This is possible with more work. Point exists while locked for now, will hopefully make progress on soon.

### UF_Logar_Valley_BAAS_v1

- Updated both temp spawns to 240 seconds
- Reduced respawn delay to 0
- Added another bolty bois faction for CAF to have different player skins
- Added SKS to bolty boi factions as a second rifleman

## v0.34 Change Log

### UF_Tallil_Outskirts_FOBDefense_v1:
- Updated spawn location map icons
- Reduced spawn count on northern CAF helis'
- Removed staging phase zone to see if that is what is causing lack of building ability
- Updated level location in asset browser

### UF_Kohat_CacheDefense_v2:
- Another method of removing main spawns at runtime
- Tied destruction of supply cache to capture of another point. This should allow CAF to destroy radio then go to escape.
- Set ticket and escape point requirement to 50% of remaining players once the radio is destroyed.
- Enabled fog of war

### UF_Sumari_FOBDefense_v1:
- Updated layer camera
 
- Added rocket man to US one-life defenders