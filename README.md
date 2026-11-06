# Caravan Dice

A roguelike dice game. You lead a desert caravan to a city on the far side of the sand. Your crew are your dice: each turn you choose who rolls, then spend the faces to fight, block, trade and survive.

## Play

Serve the folder with any static web server and open `index.html`. For example:

```
python3 -m http.server 8000
```

Then open http://localhost:8000. It works on a phone. A web server is needed (rather than opening the file directly) because the browser loads the 3D models from the `models/` folder. Everything the game needs is in this repository, so it works offline.

## How to play

- **The route:** three legs, each a small branching map of Fights, Markets and Camps (heal 10), ending in a boss: The Bandit King, The Storm Mother, then The Gate Warden at the city gate.
- **Fights:** the enemy shows its next move. Choose up to 4 crew to roll. Keep the dice you like and reroll the rest (2 rerolls), then end your turn.
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

## Credits

- 3D models: Kenney (https://kenney.nl), CC0. See `models/README.md`.
- 3D engine: three.js r128, MIT. See `vendor/README.md`.
