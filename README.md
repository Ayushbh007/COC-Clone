# COC-Clone

Terminal version of Clash of Clans using OOP concepts in Python.

- Everything mentioned in the assignment has been implemented.
- **Bonus** :
    - King’s Leviathan Axe has also been implemented.
    - Dragon Character has been added, it can fly over walls.
    - Queen's Eagle Arrow has been added.
    - Movement avoiding walls has also been implemented.

## How to Run

- To run the game: `python3 game.py`
- To view replays: `python3 replay.py` and select the replay based on the date and time.
- **Victory Condition:** All buildings except walls are destroyed in all three levels.
- **Defeat Condition:** All troops and the King die before destroying all buildings except walls.

## Controls

### Hero

- `w`: move up
- `a`: move left
- `d`: move right
- `s`: move down
- `1`: Special Attack
- `space`: Normal Attack

### Barbarian

- `z`: spawn at point 1
- `x`: spawn at point 2
- `c`: spawn at point 3

### Dragon

- `v`: spawn at point 1
- `b`: spawn at point 2
- `n`: spawn at point 3

### Archer

- `i`: spawn at point 1
- `o`: spawn at point 2
- `p`: spawn at point 3

### Balloon

- `j`: spawn at point 1
- `k`: spawn at point 2
- `l`: spawn at point 3

### StealthArcher

- `e`: spawn at point 1
- `f`: spawn at point 2
- `m`: spawn at point 3

### Healer

- `7`: spawn at point 1
- `8`: spawn at point 2
- `9`: spawn at point 3

- `q`: Quit Game

## Assumptions

- Rage and Heal Spell can be applied multiple times.
- The troop limits per level are:
    - Barbarians: 10
    - Archers: 7
    - Balloons: 5
    - Dragons: 3
    - Stealth Archers: 5
    - Healers: 2
- You choose the type of troop movement at the start of the game.
- You choose the hero after each level.
- For the heal effect and wall splash damage, **Euclidean distance** is used.
