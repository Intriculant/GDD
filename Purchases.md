# User Datastore
{
	credits_earned: 0,
	client_purchases: {ItemName = 1},
	client_loadout: {UnitName = 1},
	client_hotkeys: {},
}

# End of round reward
- Win: 100
- Lose: 80
- Saviour: 20
- Formula: TotalEarned * math.min(1, MinutesPlayed / 30)

# Prices
- Variant (Beginner) :: 150
- Variant (Normal) :: 1,000
- Variant (Rare) :: 10,000
- Variant (Legendary) :: 100,000
- Soldier Recolor :: 1,000,000
- Consumable :: 1,000