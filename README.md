# Snake Water Game

Snake Water Game built using HTML, CSS and JavaScript.

<p align="center">
  <img src="https://github.com/BinaryVortex/Snake-Water-Game/blob/main/Screenshot%202024-07-13%20181742.png" alt="Snake Water Game screenshot" width="420" />
</p>

## Demo
A lightweight browser game that reproduces the classic Snake–Water–Gun hand game. Click one of the three options (🐍 Snake, 💧 Water, 🔫 Gun) and play against the computer. Scores are tracked on the screen.

## How to run
1. Clone or download this repository.
2. Open `index.html` in your browser (no server required).

## How to play
- Click one of the three circular buttons to make your choice:
  - 🐍 Snake
  - 💧 Water
  - 🔫 Gun
- The computer will pick a choice at random, the result will be shown and scores updated.

## Rules
The game follows a simple cyclic rule-set similar to Rock–Paper–Scissors:
- Snake beats Water (snake drinks the water)
- Water beats Gun (water can disable/rust the gun)
- Gun beats Snake (gun kills the snake)

(Results and scoring are handled by `script.js`.)

## Files
- `index.html` — game UI and structure
- `style.css` — styles and layout
- `script.js` — game logic and scoring
- `Screenshot 2024-07-13 181742.png` — demo screenshot used above

## Notes
- The project is intentionally minimal and runs entirely in the browser.
- If you'd like improvements (mobile layout tweaks, animations, sound, persistent high scores), open an issue or submit a PR.

## Contributing
Contributions are welcome. Please fork the repo, create a branch for your feature/fix, and open a pull request describing your changes.

## License
No license specified. If you want to add a license, consider adding an `LICENSE` file (e.g. MIT) to make the project's terms clear.

---

Enjoy!