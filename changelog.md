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