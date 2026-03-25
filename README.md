Create a single HTML file that implements a classic Tetris game. The file should be self‑contained with embedded CSS and JavaScript, dark theme with neon accents, smooth animations, and a clean minimalistic layout.

Game requirements:
- Standard Tetris grid (10x20), with tetromino shapes (I, O, T, L, J, S, Z).
- Pieces fall automatically; the player can move left/right, rotate, and hard drop.
- Completed lines are cleared and award points (1 line = 100, 2 lines = 300, 3 lines = 500, 4 lines = 800).
- Display current score, level (increase every 10 lines, speed up accordingly), and next piece preview.
- Game over detection and a restart button.
- Controls: keyboard arrows (left, right, down, up for rotate, space for hard drop). Also provide on‑screen buttons (circular, like oTimer sectors) for mobile/touch: left, right, rotate, drop.

Visual style:
- Dark background with radial gradient, central game container with blurred backdrop.
- Grid cells: rounded corners, subtle border, glowing effect for placed blocks.
- Use neon colors for tetrominoes (bright cyan, yellow, purple, etc.).
- Buttons: round, with shadow, active press effect, similar to oTimer's sector buttons.
- Score and next piece panels: semi‑transparent, with neon text.
- Add a subtle pulse animation when a line is cleared.

Technical notes:
- Implement in pure HTML/CSS/JS (no external libraries).
- Use requestAnimationFrame for game loop, or setInterval with proper timing.
- Ensure keyboard controls work without scrolling.
- Make it responsive: grid scales down on smaller screens, buttons wrap.
- Write clean, well‑commented code.

Deliver the complete HTML file.
