# DEORUM

A controller-first 2D action RPG prototype inspired by the feel and readability of classic 16-bit top-down adventures, built as an original DEORUM game.

## First playable slice

- 8-direction movement
- Keyboard and standard HTML5 Gamepad API input
- Backbone-friendly gamepad mappings
- Melee attack
- Enemy chase, damage, health, invulnerability frames
- Collision walls
- Interactable treasure chest
- Tiny objective / win loop
- Pixel-scaled 16:9 canvas suitable for mobile browsers

## Controls

| Action | Keyboard | Controller |
| --- | --- | --- |
| Move | WASD / arrows | Left stick / D-pad |
| Attack | Space | A / south face button |
| Interact | E | X / west face button |

## Run

Serve the repository as static files and open `index.html` in a modern browser. Gamepad support is provided through the browser Gamepad API. On mobile, connect the Backbone before launching the game page.

## Next milestone

Replace prototype geometry with a real DEORUM overworld room, animated player sprites, authored enemies, NPC dialogue, transitions, audio, inventory, and save state.
