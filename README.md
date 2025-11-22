# Sets Playground

A tiny HTML canvas sandbox for sketching set diagrams. Draw circles with labels, explore unions/intersections via a prefix DSL, zoom/pan, and save/load scenes—all in one page (`index.html`).

## Quick start
- Open `index.html` in your browser.
- Scroll to change the pending radius; Shift+Scroll to zoom at cursor; Space+drag to pan.
- Hold a letter/number while clicking to place a labeled circle; Backspace clears.
- Console (bottom): enter prefix commands like `(union A B)`, `(intersection A (union B C))`, `(complement A)`. Use `(save name)` / `(load name)` for snapshots, Up/Down to recall history, click past commands to rerun, Esc to return focus to the canvas.
- Undo recent geometry changes with Ctrl+Z / Cmd+Z.

## Live demo
- Hosted at https://boris-volkov.github.io/sets/

## Notes
- Same-label circles visually merge for highlighting but each still shows its own label to avoid ambiguity.
- Highlights from commands stay vivid; default stacking is intentionally subtle.***
