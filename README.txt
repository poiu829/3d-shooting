SKY DUEL - 3D Arcade Air Combat Prototype

Files
- index.html : the playable browser game

How to run
1. Upload index.html to a static web host (GitHub Pages, Render Static Site, etc.), or
2. Run a local web server in this folder, for example:
     python -m http.server 8000
   Then open http://localhost:8000 in a modern browser.

The game loads Three.js from jsDelivr, so an internet connection is required.
Opening index.html directly as a file may be blocked by browser module security; use a web server instead.

Controls
PC:
- W / Up Arrow: climb
- S / Down Arrow: dive
- A / Left Arrow: bank left
- D / Right Arrow: bank right
- Space: fire energy shots
- Shift: boost

Phone / tablet:
- Drag the left virtual stick to steer and climb/dive
- FIRE: shoot
- BOOST: accelerate

Prototype notes
- Arcade-style fictional aircraft and energy projectiles.
- One player versus one CPU rival.
- A rival is replaced after being defeated. Score: 100 per victory.
- This is an early gameplay prototype; models, sound, menus, and balancing can be expanded.
