# CSS 3D Interactive Flip Card

A highly interactive card component that uses true CSS 3D space to flip over when hovered.

## Files
- `demo.html`: The HTML structure containing the front and back faces.
- `style.css`: The CSS that establishes 3D perspective and handles the rotation.
- `README.md`: This file.

## Features
- **True 3D Transforms:** Uses `perspective: 1000px` on the container to establish a 3D camera view.
- **Preserved 3D Space:** The inner wrapper uses `transform-style: preserve-3d` so that its children (front and back) rotate together in the same 3D space.
- **Hidden Backface:** Uses `backface-visibility: hidden` to ensure the back side of the front card doesn't show when flipped, allowing the back card to become visible.

## Usage
Ensure the exact DOM structure is kept: a `.flip-card-container` wrapping a `.flip-card-inner`, which holds the `.flip-card-front` and `.flip-card-back`.
