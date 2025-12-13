# Asteroids

A classic Asteroids arcade game clone built with Python and Pygame.

![Asteroids gameplay](gameplay.gif)

## About

Fly a spaceship, shoot asteroids, watch them split into smaller pieces. Simple as that.

Built this as part of my learning journey through [Boot.dev](https://boot.dev). Took about 15 days from start to finish.

## What I learned

- Object-oriented programming in Python (classes, inheritance, method overriding)
- Pygame's sprite and sprite group system
- Game loops and delta time for frame-rate independent movement
- Collision detection
- Vector math for movement and rotation

## How to play

- **W** - Move forward
- **A / D** - Rotate left / right
- **Space** - Shoot

## Running the game

Make sure you have Python 3 and Pygame installed:

```bash
pip install pygame
```

Then run:

```bash
python main.py
```

## Project structure

```
├── main.py           # Game loop and initialization
├── player.py         # Player ship class
├── asteroid.py       # Asteroid class
├── asteroidfield.py  # Spawns asteroids
├── shot.py           # Bullet class
├── circleshape.py    # Base class for circular game objects
├── constants.py      # Game constants (screen size, speeds, etc.)
├── logger.py         # Event logging
├── game_events.jsonl # Game event logs
└── pyproject.toml    # Project config
```