# Planet 28 Warband Builder

A small, unofficial warband builder for **Planet 28 (2nd edition)** by Mammoth Miniatures, made for our gaming group.

**Open it:** https://idontknowwhatimdoing-beep.github.io/Planet28-Unit-Builder/

## What it does

- Build characters with live points: skills (A, S, F, P, AW), hit-points, traits, abilities, weapons, armour, ammo and items
- Squads of 3–10 members (profile cost × members)
- Rule checks: minimum 2 characters, points limit, Barbaric vs Complex, Animal abilities, missing ammo for Reload weapons, clashing traits
- Character sheets laid out like the book's (Ctrl/Cmd+P to print)
- A photo for each character or vehicle (shown on the roster and sheets)
- Vehicles: types, the building grid with sections and facings, hard points and turrets with weapons, traits and abilities
- Campaigns: credits and campaign points, recording games, the injury and vehicle damage tables, hidden agendas, paying for upgrades and recruits
- Custom weapon forge using the book's formula (max damage + range, +10 one-handed, + special rules)
- Several saved warbands per browser; copy a warband as text to share it

Warbands are stored in your own browser. Use **Saved warbands → Copy as text** to move one to another device or send it to a friend.

## Editing the rules data

Everything is in `index.html`. The rules tables (traits, abilities, weapons, armour, items, special rules) are near the top of the `<script>` block under `RULES DATA`, with book page numbers. Fix a cost or add an entry there and commit.

## Not yet included

- Solo and co-op rules (single character warbands, enemy warbands)
- Tracking section damage during a game
