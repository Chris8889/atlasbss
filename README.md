# Atlas BSS
Atlas is a new Bee Swarm Simulator script currently being developed with safety as its focus. Atlas currently supports both tween and pathfinding.

![Atlas BSS](https://extron.netlify.app/atlas.png)

### Version 0.2 Beta Changelogs:
- Fixed auto sprinklers still being placed even after they are placed
- Tween to mountaintop field instead of through cave
- Fixed auto sprinklers config not saving

### Version 0.3 Beta Changelogs:
- Fixed pathfinding getting stuck if no path is found by resetting
- Added boss timers in combat tab
- Added auto kill mobs

### Version 0.4 Beta Changelogs:
- If the script is executed twice, all the previous tasks are stopped to prevent the script from running twice, not just the previous UI
- Auto kill mobs now checks if field is unlocked
- Added auto memory match

### Version 0.4 Beta Changelogs (just bug fixes so no version change):
- Added the option to reset or walk 5 studs if pathfinding is not able to find a path
- Added a trial for pathfinding to visualize where it is moving
- Improved performance when auto kill mobs is enabled
- Fixed a bug that caused auto kill mobs to not work
- Dropdowns now show the title, not just the value

### Version 0.5 Beta Changelogs:
- Cooldowns of toys (memory matches, etc) are now saved, no need to recheck every time the script is executed
- Added auto dispensers (except coconut, royal jelly and glue)
- Added the option to use the red cannon if pathfinding

### Version 0.6 Beta Changelogs:
- Added auto beesmas (polar bear feast, gingerbread house, samovar, stockings)
- Added half baked auto quest (only does pollen and field quests)
- Added pathfinding for coconut field and pepper patch
- Auto convert now also converts balloon

- Disabled pathfinding when farming tokens to remove the delay from calculating path, character now walks directly to token
- Fixed auto sprinker and memory match by finding the correct position of gui items
- Fixed memory match clicking on already matched tiles
- Fixed not being able to pathfind into field