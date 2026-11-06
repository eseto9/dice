# Caravan Dice

A roguelike dice game. You lead a desert caravan to a city on the far side of the sand. Your crew are your dice: each turn you choose who rolls, then spend the faces to fight, block, trade and survive.

## Play

Serve the folder with any static web server and open `index.html`. For example:

```
python3 -m http.server 8000
```

Then open http://localhost:8000. It works on a phone. A web server is needed (rather than opening the file directly) because the browser loads the 3D models from the `models/` folder. Everything the game needs is in this repository, so it works offline.

## A run

- **Three legs**, each with a branching route map: ambushes, oases, markets, ruins and sandstorms. Each step on the road costs 1 water.
- **A boss at the end of each leg**: The Bandit King, The Storm Mother, then The Gate Warden at the city gate. The map shows a scout report of the boss's moves.
- **Markets** sell new crew, new wagons, face upgrades, water and repairs.
- **Progress saves** after every step, so you can close the page and continue later.

## A fight

- The enemy shows its next move ahead of time.
- Choose up to 4 crew to roll, on their cards or by tapping them on the island. Each crew member is a die with six faces.
- Hold dice and reroll the rest (2 rerolls a turn). Pour water on a die for +2. Coin can bribe the enemy to skip a move.
- Your attacks land, then the enemy moves. Enemies hit the rear wagon first; snipes knock out the crew member they target.

## Wagons

| Wagon | Perk |
|---|---|
| Water Cart | Pour water on a die for +2 |
| Armoury | Guards get +1 on Attack |
| Cook Wagon | After each fight, every wagon heals 3 |
| Bell Wagon | Each matching pair of faces deals +3 damage |
| Spice Wagon | Coin faces give +1 coin |
| Bulwark | Start every turn with 2 block |

## Credits

- 3D models: Kenney (https://kenney.nl), CC0. See `models/README.md`.
- 3D engine: three.js r128, MIT. See `vendor/README.md`.
