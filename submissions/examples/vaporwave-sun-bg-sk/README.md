# Retro Vaporwave Sun Background

A deeply nostalgic 1980s "Outrun" aesthetic background featuring a glowing neon sun and a moving 3D perspective grid.

## Files
- `demo.html`: The HTML layout for the vaporwave container.
- `style.css`: The complex gradients and 3D transforms that generate the aesthetic.
- `README.md`: This file.

## Features
- **CSS-Only Sliced Sun:** The iconic sliced sun is built entirely with CSS `linear-gradient` (to create the sunset colors) overlaid with a repeating transparent gradient (to create the horizontal slices).
- **Infinite 3D Grid:** The floor grid is created using repeating linear gradients to draw a mesh, which is then tilted flat using `transform: perspective(600px) rotateX(60deg)` and animated continuously towards the user.
- **Deep Glow Effects:** Uses heavy `box-shadow` and `filter: drop-shadow` to create the intense neon glare characteristic of the synthwave genre.

## Usage
Add the `.vaporwave-container` to your background. Make sure the container has `overflow: hidden` to prevent the rotated grid from expanding the page width.
