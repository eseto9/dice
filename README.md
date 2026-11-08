# Caravan Dice

A roguelike dice game. You lead a desert caravan to a city on the far side of the sand. Your crew are your dice: each turn you choose who rolls, then spend the faces to fight, block, trade and survive.

## Play

Open `index.html` in a browser. It is a single file with no dependencies and works on a phone, offline too.

## How to play

- **The route:** three legs, each a small branching map of Fights, Markets and Camps (heal 10), ending in a boss: The Bandit King, The Storm Mother, then The Gate Warden at the city gate.
- **Your crew:** four travellers, each a six-sided die: Amir the Guard (attack and block), Zane the Sellsword (big hits, two blank faces), Noor the Medic (mends) and Oskar the Trader (coin).
- **Fights:** the enemy shows its next move. Choose 2 of your 4 crew to roll. Keep the dice you like and reroll the rest (2 rerolls), then end your turn. Your dice then resolve one at a time: each crew member steps up and attacks, blocks, collects coin or mends, before the enemy moves.
- **Faces:** Attack hurts the enemy, Block stops its next hit, Coin buys things at markets, Mend repairs the caravan by 3.
- **Health:** the caravan has one health bar. Each wagon adds health and a perk.
- **Markets:** hire crew, buy wagons, upgrade faces and pay for repairs.
- **Saving:** progress saves after every step, so you can close the page and continue later.

## Wagons

| Wagon | Health | Perk |
|---|---|---|
| Supply Cart | 20 | None |
| Armoury | 20 | Guards get +1 on Attack |
| Bulwark | 18 | Start every turn with 2 block |
| Bell Wagon | 12 | Each matching pair of faces deals +3 damage |
| Cook Wagon | 12 | Heal 4 after every fight |
| Spice Wagon | 12 | Coin faces give +1 coin |

## Art

Everything is drawn in code as flat SVG: a side-view desert scene, the wagons, the crew and the enemies. There are no image or model files.
