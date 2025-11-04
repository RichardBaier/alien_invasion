🛸 Alien Invasion

Alien Invasion is a simple 2D arcade-style shooter built using Python and Pygame.
It was created as my first Python game project and includes score tracking and persistent high scores.

<!-- optional; delete if you don’t have one -->

✅ Features

Player-controlled ship that moves and shoots

Waves of descending alien enemies

Score tracking

Persistent high-score system

Game-over and restart support

🚀 Requirements

You’ll need:

Python 3.11+ (or whatever version yours uses)

Pygame

Install pygame:

pip install pygame

▶️ How to Run

Clone the repository

git clone https://github.com/yourusername/alien-invasion.git
cd alien-invasion


Run the game

python alien_invasion.py


If the file is in a subfolder, update the path accordingly.

🎮 Controls

Action	Key

Move Left	- A

Move Right	- D

Shoot	- Space

Quit	- Q

📁 Project Structure

alien_invasion/

│

├── alien_invasion.py      # Main game entry point

├── settings.py            # Configuration values

├── ship.py                # Player ship

├── alien.py               # Enemy logic

├── scoreboard.py          # Score + high score UI

├── game_stats.py          # Tracks gameplay stats

└── images/                # Sprites


(Adjust this to match your actual file structure.)

🧠 How It Works

The game initializes Pygame, loads settings, and spawns the ship, scoreboard, and alien fleet.
As the player shoots, aliens disappear and points are awarded.
Game stats are stored and the high score persists between sessions.

📈 Planned Improvements

 Sound effects / music

 Multiple levels

 Alien movement patterns

 Power-ups

 Title screen + menus

🤝 Contributing

This project was created as a learning exercise, but contributions and tips are welcome!
Feel free to open an issue or make a pull request.

📜 License

MIT — free to use and modify.

👤 Author

Rick (R1CKisME)
GitHub: https://github.com/RichardBaier
