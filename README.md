# Cozy Sorter

Open `Cozy Sorter.html` in a modern browser to play.

Each sorted item earns 1 Sortcoin. Completing all copies of an item type earns 1 Completion Coin. Coin balances and upgrades are saved in browser storage.

Item rarity is based on the stack's percentile within the configured copy-count range. The rarity tier weights are 1:1:3:5:17 (Legendary, Epic, Rare, Uncommon, Common); the game scales these proportions across `MIN_COPIES` to `MAX_COPIES`, so changing the stack-size range automatically adjusts the copy-count cutoffs.

## Item Summon

Select an unsorted item on the current page and choose **Summon** to move matching unsorted copies from other pages onto this page. It does not create extra items. Unlock Item Summon for 3 Completion Coins. Each level summons one additional matching copy per activation; the first upgrade costs 5 Completion Coins, and each later upgrade costs 2 more than the previous one.

## Multi-select

Pages contain 24 items. Unlock Multi-select for 20 Sortcoins to click-select 2 items at once. Each upgrade adds one selection slot, up to 24 items, and costs 1.5 times the previous level's price, rounded up (20, 30, 45, 68, ...). Selected items must all belong in the same folder to file them together.

Select an item and press **Ctrl+A** to quickly select copies of that same item on the current page, up to your Multi-select limit.
