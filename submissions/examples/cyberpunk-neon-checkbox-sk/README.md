# Cyberpunk Neon Checkbox

A highly stylized, futuristic glowing checkbox built entirely in CSS.

## Files
- `demo.html`: The HTML structure hiding the native input and using a custom span box.
- `style.css`: The CSS that overrides the browser styling and adds the neon glow + checkmark.
- `README.md`: This file.

## Features
- **Custom Native Input:** We hide the native input visually, but keep it in the DOM for full accessibility and keyboard navigation.
- **Pure CSS Checkmark:** The checkmark inside the box is drawn using CSS `border-bottom` and `border-right` on an absolutely positioned `::after` pseudo-element that is rotated 45 degrees.
- **Neon Glow Animation:** Uses `box-shadow` and `transition` to create an aggressive neon glare when the user checks the box.

## Usage
Wrap the hidden `<input type="checkbox">` and the `.cyberpunk-box` span inside a `.cyberpunk-checkbox-label` container. Click the label text or the box itself to toggle.
