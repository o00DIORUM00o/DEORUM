# DEORUM

A controller-first 2D action RPG built as an original DEORUM game, with the readability and immediacy of classic 16-bit top-down adventures.

## Phase 1 — Playable foundation

- 8-direction movement
- Keyboard and standard HTML5 Gamepad API input
- Backbone-friendly gamepad mappings
- Melee attack
- Enemy chase, damage, health, invulnerability frames
- Collision walls
- Interactable treasure chest
- Tiny objective / win loop
- Pixel-scaled 16:9 canvas suitable for mobile browsers

## Phase 2 — First real DEORUM room

The prototype geometry has been replaced with an authored location: **Evergreen Edge**.

- DEORUM forest/path environment rendered directly in canvas
- Player walk bob / directional presentation
- NPC: **Mosskeeper Elri**
- Enemy: **Thornling**
- NPC interaction and dialogue
- Authored objective flow: meet Elri, defeat the Thornling, recover the Green Relic
- DEORUM: THE THIRD CHAPTER title presentation

## Controls

| Action | Keyboard | Controller |
| --- | --- | --- |
| Move | WASD / arrows | Left stick / D-pad |
| Attack | Space | A / south face button |
| Interact | E | X / west face button |

## Run

Serve the repository as static files and open `index.html` in a modern browser. Gamepad support is provided through the browser Gamepad API. On mobile, connect the Backbone before launching the game page.

## Next milestone

Expand Phase 2 into a multi-room vertical slice with room transitions, authored sprite sheets, inventory, save state, and audio.
