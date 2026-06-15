# Animated Hamburger to Cross Menu

A classic UI staple implemented flawlessly in pure CSS. A 3-bar hamburger menu icon that seamlessly animates into an 'X' shape.

## Files
- `demo.html`: The HTML structure using a hidden checkbox and three span lines.
- `style.css`: The CSS that rotates and translates the lines when the checkbox is toggled.
- `README.md`: This file.

## Features
- **Pure CSS State Management:** Uses the `<input type="checkbox">` `:checked` pseudo-selector to handle the toggle state without requiring any JavaScript.
- **Smooth Animation:** Transforms the `translateY`, `rotate`, and `opacity` properties, resulting in a silky-smooth, hardware-accelerated animation.
- **Accessible & Scalable:** Built with `em` units so the entire hamburger menu scales perfectly based on the `font-size` of its container.

## Usage
Copy the `.hamburger-menu` container. The hidden `.hamburger-checkbox` must stay as the first child so the `~` sibling selector in CSS can target the `.hamburger-line` elements.
