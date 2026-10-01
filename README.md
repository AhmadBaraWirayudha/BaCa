# Our First Year — Pink Android Edition

A lightweight, self-contained anniversary time capsule designed for mobile browsers, including Samsung Galaxy A56 5G-class Android devices.

## Included
- 31 photographs, EXIF orientation normalized and encoded as WebP
- Supplied `music.mp3`
- Pink/pastel UI
- Lazy/on-demand image loading
- Local progress persistence
- Touch-friendly controls and safe-area handling
- Final personal message

## Deploy
Place this folder in a GitHub repository and enable GitHub Pages. `index.html` is at the root. No build step or external library is required.

## Mobile performance
Images are capped at a 1400 px long edge and WebP quality 78. Only the selected photograph is assigned to the main image element, with adjacent images lightly preloaded. Heavy blur, continuous particle animation, and hover-only interactions are avoided.
