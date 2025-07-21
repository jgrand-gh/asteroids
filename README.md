# Asteroids Game

This project is a simple Asteroids-style arcade game built with Python and Pygame. Control a spaceship, dodge and destroy asteroids, and try to survive as long as possible!

## Features

- Player spaceship with rotation, movement, and shooting
- Asteroids spawn from screen edges and split when shot
- Collision detection between player, asteroids, and shots
- Sprite-based game loop with smooth animation

## Requirements

- Python 3.12 or newer
- Pygame (see [requirements.txt](requirements.txt))

## Getting Started

1. **Clone the repository**
2. **Install dependencies:**
   ```sh
   pip install -r requirements.txt
   ```
3. **Run the game:**
   ```sh
   python main.py
   ```

## Controls

- `W` / `S`: Move forward/backward
- `A` / `D`: Rotate left/right
- `Space`: Shoot

## Project Structure

- [`main.py`](main.py) — Entry point, game loop and event handling
- [`player.py`](player.py) — Player spaceship logic
- [`asteroid.py`](asteroid.py) — Asteroid behavior and splitting
- [`asteroidfield.py`](asteroidfield.py) — Asteroid spawning
- [`shot.py`](shot.py) — Player shots
- [`circleshape.py`](circleshape.py) — Base class for circular game objects
- [`constants.py`](constants.py) — Game constants

## License

This project is for educational purposes as part of a Boot.dev learning module.