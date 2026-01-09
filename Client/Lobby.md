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

--

alternative to room countdown:
insta tp players when player count is reached (or after like 3 secs)
when tped, you pick variants in the actual game, while the map loads assets
10 sec timer there, then the match begins
