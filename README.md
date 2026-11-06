# Lottie Maker

Drop in a background video (mp4) and an SVG overlay, get a Lottie `.json` and `.lottie` back.
Runs entirely in the browser; nothing is uploaded. Open `index.html` or use the GitHub Pages link.

- Canvas size comes from the SVG `viewBox`; the video is scaled to cover it.
- SVG supports `path`, `rect`, `circle`, `ellipse` with solid fills. Gradients and transforms are not supported.
- Use Chrome or Edge (WebP frame export).
