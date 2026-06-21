# Maze Escape Game

A terminal-based C++ maze game built to demonstrate object-oriented design, STL usage, and grid-based pathfinding.

## Features

- Object-oriented architecture with `Maze`, `Player`, `Enemy`, `Pathfinder`, and `Game`
- BFS-driven enemy pursuit logic on a grid map
- Collectibles, score tracking, turn counting, and exit conditions
- Replay mode for deterministic testing without interactive input
- Multiple sample levels

## Build

```bash
make
```

## Run

```bash
./maze_escape
```

## Controls

- `w` move up
- `a` move left
- `s` move down
- `d` move right
- `q` quit

Press Enter after each move.

## Useful Options

```bash
./maze_escape --level levels/level2.txt
./maze_escape --no-clear
./maze_escape --replay dddssaww
./maze_escape --turn-limit 150
```

## Tile Legend

- `#` wall
- `.` empty path
- `C` collectible
- `E` exit
- `P` player
- `M` enemy

## Project Layout

```text
Maze-Escape-Game/
├── include/
├── levels/
├── src/
├── Makefile
└── README.md
```
