# שבעה ימים · Seven Days

An interactive creation: a world built from tens of thousands of light particles over seven days, driven by your mouse and clicks, with a generative soundtrack written from scratch in Web Audio. On the sixth day the world asks you for one word, takes its shape, and (inside claude.ai) writes you a short Hebrew blessing based on what you actually built.

- `shivaa-yamim.html` — the artifact source (Claude artifact format: no `<html>` wrapper; declares the `sample` and `tts` capabilities).
- `index.html` — the same page wrapped as a standalone HTML file, served by GitHub Pages: https://elnatan613.github.io/seven-days/

Live artifact: https://claude.ai/artifact/PTkWyM51web8e1YAMCbXKn

Built with Three.js (WebGL points + custom shaders), the Web Audio API, procedural noise terrain, L-system style trees, boids, and Hebrew text rasterized into particle targets. No images, no audio files, one HTML file.

Best experienced on a desktop with headphones.
