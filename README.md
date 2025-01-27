# Car Racing Game

A fun and interactive car game developed using **Python** and **Pygame**. Navigate your car through traffic, avoid collisions, and rack up points as you speed up!

## Features

- **Dynamic Gameplay**: Speed increases as your score rises.
- **Interactive Controls**: Use arrow keys to change lanes.
- **Realistic Effects**: Crash animations, background music, and sound effects.
- **Scoreboard**: Tracks your current score and speed in real-time.
- **Replay Option**: Restart the game after crashing.

## Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/sandeepkumar009/Car-Racing-Game.git
   
   cd Car-Racing-Game
   ```
2. Install the required dependencies:
   ```bash
   pip install pygame
   ```
3. Add the required assets in a folder named `New Folder`:
   - `SportCar.png` (Player car)
   - `car1.png` to `car7.png` (Traffic cars)
   - `fire.png` (Crash effect)
   - `background_music.wav` (Background music)
   - `crash.wav` (Crash sound effect)

## How to Play

1. Run the game:
   ```bash
   python Car_Game.py
   ```
2. Use **Left Arrow Key** (`←`) to move left and **Right Arrow Key** (`→`) to move right.
3. Avoid collisions with other cars.
4. Try to score as high as possible!

## Game Rules

- **Score**: Increases by 1 for every car you pass.
- **Speed**: Increases by 20 km/h after passing every 10 cars.
- **Collision**: Hitting another car ends the game.

## Screenshots

*Coming soon!*

## Directory Structure

```
Car_Racing_Game/
├── Car_Game.py          # Main game logic
├── New Folder/          # Assets folder
│   ├── SportCar.png     # Player car image
│   ├── car1.png         # Traffic car images
│   ├── fire.png         # Crash effect
│   ├── background_music.wav # Background music
│   └── crash.wav        # Crash sound effect
└── README.md            # Documentation
```

## Acknowledgements

- **Pygame**: For the amazing library that made this project possible.
- **Open Source Assets**: For the images and sounds used in the game.

---

Feel free to fork this repository and add new features or enhancements. Happy coding! 🚗💨
