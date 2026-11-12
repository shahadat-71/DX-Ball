# DX-Ball

A classic brick-breaker arcade game built with **C++ and OpenGL/GLUT**. Control the paddle, keep the ball in play, break the bricks, and try to achieve a high score across multiple difficulty levels.

## Features

- Classic paddle-and-ball brick-breaking gameplay
- Ball movement and collision detection with the screen, paddle, and bricks
- Multiple difficulty levels: Easy, Medium, and Hard
- Score tracking during gameplay
- Game states and screens for the menu, level selection, level completion, and game over
- Sound effects and background music
- Power-up collision handling
- Separate leaderboard data files for each difficulty level

## Technologies and Libraries

- C++
- OpenGL
- GLUT / FreeGLUT
- GLU
- `stb_image` (image-loading library)

![C++](https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=cplusplus)
![OpenGL](https://img.shields.io/badge/OpenGL-5586A4?style=for-the-badge&logo=opengl)
![GLUT](https://img.shields.io/badge/GLUT-Graphics_Library-green?style=for-the-badge)

## Project Structure

```text
DX-Ball/
├── GameData/
│   ├── easyLd.txt
│   ├── mediumLd.txt
│   └── hardLd.txt
├── music/
│   ├── bgMusic.wav
│   ├── click.wav
│   └── ... sound effects
├── sprites/
│   ├── Backgrounds/
│   ├── ball spr/
│   ├── brickspr/
│   ├── Menuspr/
│   └── paddlespr/
├── iMain.exe
├── OpenGL / GLUT runtime files
└── tasks.json
```

## How to Run (Windows)

1. Download or clone this repository.
2. Extract the project while keeping the original folder structure.
3. Open the `DX-Ball` folder.
4. Run `iMain.exe`.
5. Keep the `GameData`, `music`, and `sprites` folders beside the executable. The game uses relative paths to load these files.

If Windows blocks the executable, check the file's properties and your system's security settings before running it. Only run software you trust.

## Build Information

The included `tasks.json` describes a MinGW GCC build configuration that links:

- `opengl32`
- `glu32`
- `glut32`
- `glaux`
- `stdc++`


## Game Data

The `GameData` directory contains separate leaderboard files:

- `easyLd.txt` — Easy mode
- `mediumLd.txt` — Medium mode
- `hardLd.txt` — Hard mode

These files store player names and scores.

## Future Improvements

- Add the original C++ source code to the repository.
- Document keyboard controls and gameplay rules.
- Add screenshots or a short gameplay video.
- Improve portability and provide build instructions for other platforms.
- Add tests and improve code organization.

## Author

**[Md Shahadat Hossen]**

Computer Science and Engineering

---

