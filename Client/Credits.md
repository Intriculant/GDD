# User Data
{
	credits_earned: 0,
	client_purchases: {Item1 = 1, Item2 = 1},
	client_loadout: {UnitName = 1},
	client_hotkeys: {},
}

# Rewards

100 credit for a win.
80 credit for a loss.
20 credit for filling a match.

These credits get rewarded when a match finishes.

All of these numbers are added, then multiplied by:
min(1, minutes_played / 30)

So the maximum credit you could get is 120,
if you fill for a 30+ minute match and win.
But if the match lasted 15 minutes, you would only receive 60 credit.