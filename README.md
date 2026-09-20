# 🎮 Tetris

A classic **Tetris game built from scratch** in a single HTML file. It has the core mechanics of the original, a synthesized soundtrack, sound effects, and works on both desktop and phones. No libraries, no build step.

## 🕹️ Play

- **Online:** https://abhinavsahu343.github.io/Tetris/
- **Locally:** download the repo and open `index.html` in any modern browser.

## ✨ Features

- 🧩 All 7 tetrominoes (I, O, T, S, Z, J, L) with the standard Super Rotation System and wall kicks
- 🎲 7-bag randomizer, so you never wait long for the piece you need
- 👻 Ghost piece showing where the current piece will land
- 📦 Hold slot and a preview of the next 3 pieces
- ⬇️ Soft drop, hard drop, key auto-repeat and a short lock delay for smooth control
- 🧹 Line clearing with a flash animation and Single / Double / Triple / Tetris callouts
- 📈 Levels that get faster every 10 lines
- 🏆 Score tracking with a best score saved in your browser
- 🎵 Background music: an arrangement of *Korobeiniki*, the folk tune the classic Tetris theme is based on. The music speeds up as your level rises
- 🔊 Sound effects for moving, rotating, landing, hard drops, holding, line clears, level ups and game over
- ⏸️ Pause menu with **Resume**, **Reset game**, **Main menu**, and music and sound toggles
- 📱 Touch controls and a responsive layout for phones and tablets
- 🌗 Automatic dark and light theme

## 🎯 Objective

Arrange falling blocks to form complete horizontal lines. Completed lines are cleared and score points. The game ends when the blocks stack up to the top of the board.

## ⌨️ Controls

| Action | Keyboard |
| --- | --- |
| Move left / right | `←` `→` |
| Rotate clockwise | `↑` or `X` |
| Rotate counter-clockwise | `Z` |
| Soft drop | `↓` |
| Hard drop | `Space` |
| Hold piece | `C` or `Shift` |
| Pause / resume | `P` or `Esc` |
| Mute / unmute all sound | `M` |
| Start / resume | `Enter` |

On phones and tablets, use the on-screen buttons below the board: Left, Soft drop, Right, Hold, Rotate, Hard drop and Pause.

## 🧮 Scoring

| Move | Points |
| --- | --- |
| 1 line | 100 × level |
| 2 lines | 300 × level |
| 3 lines | 500 × level |
| 4 lines (Tetris) | 800 × level |
| Soft drop | 1 per row |
| Hard drop | 2 per row |

You move up a level every 10 lines cleared.

## ⏸️ Pause menu

Press `P` (or tap **Pause**) to open the pause menu:

- **Resume** continues where you left off
- **Reset game** starts a fresh game (asks you to confirm)
- **Main menu** returns to the start screen (asks you to confirm)
- **Music** and **Sounds** turn each one on or off. Your choice is remembered

Your best score is kept when you reset or leave to the main menu.

## 🛠️ Tech Stack

- HTML
- CSS
- JavaScript (no dependencies)
- Canvas API for the graphics
- Web Audio API for the music and sound effects. Everything is generated in code, so there are no audio files

## 🚀 Getting Started

Clone the repository:

```bash
git clone https://github.com/AbhinavSahu343/Tetris.git
cd Tetris
```

Then open `index.html` in your browser. No server is needed.

### Host it on GitHub Pages

1. Go to **Settings → Pages** in your repository.
2. Under **Build and deployment**, choose **Deploy from a branch**.
3. Select the `main` branch and the `/ (root)` folder, then save.

After a minute or two the game is live at `https://<your-username>.github.io/Tetris/`.

## 📝 Notes

- Browsers only allow sound after you press a key or click, so the music starts when you press **Play**.
- The page loads the Chakra Petch font from Google Fonts and falls back to a system font when offline.
- This is a fan-made learning project. Tetris is a trademark of The Tetris Company.

## 👨‍💻 Author

**Abhinav Sahu**