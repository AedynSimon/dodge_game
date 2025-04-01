# Dodge Game

A simple arcade-style game made with **Pygame** where the goal is to dodge falling stars for as long as possible. How long can you survive?

## Gameplay

- You control a red rectangle (the player) using the **left** and **right arrow keys**.
- White stars fall from the top of the screen.
- If a star hits the player, it's **game over**.
- The game keeps track of how long you survive.
- The longer you last, the faster the stars appear!

## Requirements

- Python 3.6+
- [Pygame](https://www.pygame.org/)

## Installation

1. Clone this repository or download the script.
2. Install the required Python module:

```bash
pip install pygame
```

3. Make sure you have an image named `background.jpg` in the same directory as the script.

## How to Play

Run the game using:

```bash
python dodge_game.py
```

Use:
- `Left Arrow` to move left
- `Right Arrow` to move right

Avoid all the falling stars!

## Assets

- **background.jpg** – Place your preferred background image in the same folder and name it `background.jpg`.

## Notes

- The game speeds up over time.
- You can easily tweak difficulty by changing:
  - `STAR_VELOCITY` (how fast stars fall)
  - `star_add_increment` (how often stars appear)
 
Feel free to contribute or fork the project!
