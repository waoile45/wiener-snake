# Wiener Snake

A pixel-style snake game where a dachshund gets longer with every bone.

## Play

- Arrows, WASD or ZQSD to move
- Space or Enter to start
- P or Escape to pause
- Left / Right on the menu to change skin
- On mobile: swipe on the board or use the on-screen pad

## Features

- **Floors**: Bathroom, Kitchen, Living room, Garden or Beach, picked at random when a game starts and kept until the end.
- **Skins** unlocked by best score: Classic, Black & Tan (10), Long Hair (20), Harlequin (35), Winter Sweater (50).
- **Obstacle**: from 3 bones, a cat regularly crosses the floor after a warning sign.
- **Power-ups**: turbo sausage (faster, double points), tennis ball (slow motion), soap bubble (absorbs one hit).
- **Accessories** earned during a run: party hat (10), sunglasses (20), crown (35).
- **Game over**: camera zooms on the dog, then the end screen shows it stretched out on a ruler with its final length.

Regular bones are worth 1 point, golden bones 5.

## Run locally

Open `index.html` in any modern browser. No build step, no dependencies.

## Deploy on GitHub Pages

1. Create a new repository and push `index.html` (and this README) to the `main` branch.
2. In the repository, go to Settings > Pages.
3. Under "Build and deployment", choose "Deploy from a branch", select `main` and `/ (root)`, then save.
4. The game will be live at `https://<your-username>.github.io/<repo-name>/` after a minute or two.
