# GUI
- [Bottom-Left] Small minimap with transparency.
- [Top-Right] Players list. (Currently the builtin one).
- [Bottom-Left] Small stats panel.
- Show your money.
- Show your economy.
- [Bottom-Right] A simple buildings panel.
- [Bottom-Middle] A selected units list, with a visual display of the main unit.
	Also show/edit queued waypoints.

# Rooms
Click a room gui to enter/exit it.
When full, match starts.

First player is the host, and can click on the map icon to choose a map.
Can also choose a gamemode within that map.
Choose num players somewhere here.

Have a delay (10sec) before the match starts so people can pick variants quickly.
While the countdown happens, a map/mode change would reset the countdown.

Teleportation sends MapName, PlayerCount, GameMode, PlayerTeams.

Set a player's room by setting a 'room' attribute. Easy.

# Lobby Catalog
Scenarios that can be watched.
Buy variants, test units, and read about units.

# Keyboard Shortcuts

m1 - move command, click-select unit, drag - box select units
m2 - right click menu, orbit camera
m3 - ?
scroll - zoom camera
e - cancel build
z, x - primary, secondary abilities
c - clear selection

# User Data
{
	credits_earned: 0,
	client_purchases: {Item1 = 1, Item2 = 1},
	client_loadout: {UnitName = 1},
	client_hotkeys: {},
}

100 credit for a win.
80 credit for a loss.
20 credit for filling a match.

These credits get rewarded when a match finishes.

All of these numbers are added, then multiplied by:
min(1, minutes_played / 30)

So the maximum credit you could get is 120,
if you fill for a 30+ minute match and win.

# Catalog Prices

beginner variant: 150 credits
	~2 games played, 1-4 variants

normal variant: 1,000 credits
	~10 games played, most variants

rare variant: 10,000 credits
	~100 games played, 5+ variants

legendary variant: 100,000 credits
	~1,000 games played, 1 variant

Cosmetics:

1,000,000 credits for a really expensive and dumb soldier recolor.

Should have a way to use credits in a single-time event.