# Caravan Dice

A dark roguelike dice game. You lead a caravan across a blood-red wasteland to a city on the far side. Your crew are your dice: each turn you choose who rolls, then spend the faces to fight, block, trade and survive.

## Play

Open `index.html` in a browser. It is a single file with no dependencies and works on a phone, offline too.

## How to play

- **The route:** three legs (The Bone Flats, The Scorched Sea, The Brass Road), each a small branching map of Fights, Markets and Camps, ending in a boss: The Bandit King, The Storm Mother, then The Gate Warden at the city gate.
- **Your crew:** four travellers, each a six-sided die: Amir the Guard (attack and block), Zane the Sellsword (big hits, two blank faces), Noor the Medic (mends) and Oskar the Trader (coin).
- **Fights:** the enemy shows its next move. Choose 2 of your 4 crew to roll. Keep the dice you like and reroll the rest (2 rerolls), then end your turn. Your dice then resolve one at a time: each crew member steps up and attacks, blocks, collects coin or mends, before the enemy moves.
- **Wounds and death:** every enemy move names a crew member. If 4 or more damage gets through your block, that person is wounded; wounded and hit like that again in the same fight, they die for the rest of the run. Fewer survivors means fewer dice. Wounds are bound after each fight won, at camps, by Mend faces and by the market physician. You lose if the caravan's health runs out or no one is left.
- **Faces:** Attack hurts the enemy, Block stops its next strike, Coin buys things at markets, Mend binds a wound and repairs the caravan by 3.
- **Health:** the caravan has one health bar. Each wagon adds health and a perk.
- **Markets:** buy wagons, upgrade faces, pay a physician to treat wounds and pay for repairs. After each boss, train a face for free or take 12 coin.
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

Everything is drawn in code as flat SVG: a side-view wasteland at a blood-red dusk, the wagons, the crew and the enemies. Violence is implied rather than shown: impact flashes, a jolt of the scene and cairns for the dead, with no blood. The interface is dark leather in riveted iron frames.
