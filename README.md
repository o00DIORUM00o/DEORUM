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

## Phase 2 — First DEORUM vertical slice

Phase 2 now spans two authored locations and carries progression between them.

### Evergreen Edge

- DEORUM forest/path environment rendered directly in canvas
- Player walk bob / directional presentation
- NPC: **Mosskeeper Elri**
- Enemy: **Thornling**
- NPC interaction and dialogue
- Objective flow: meet Elri, defeat the Thornling, recover the Green Relic

### Greenwatch Trail

- Second authored room connected to Evergreen Edge
- Bidirectional room transition system
- Progression gate requiring the Green Relic before leaving Evergreen Edge
- Trail signage and environmental dressing establishing the road toward Greenwatch Harbor

### Game systems added in Phase 2

- Tiny inventory with the **Green Relic** as the first persistent item
- Browser save/load via `localStorage`
- Automatic saves on important progression events and room transitions
- Keyboard debug/manual save (`K`) and load (`L`)
- Room-specific collision, landmarks, encounters, and presentation
- DEORUM: THE THIRD CHAPTER title presentation

## Controls

| Action | Keyboard | Controller |
| --- | --- | --- |
| Move | WASD / arrows | Left stick / D-pad |
| Attack | Space | A / south face button |
| Interact | E | X / west face button |
| Save | K | Automatic saves |
| Load | L | Save auto-loads on start |

## Run

Serve the repository as static files and open `index.html` in a modern browser. Gamepad support is provided through the browser Gamepad API. On mobile, connect the Backbone before launching the game page.

## Next milestone

Continue Phase 2 with authored sprite sheets, a real inventory screen, audio, a second NPC/quest beat on Greenwatch Trail, and the first destination beyond the trail.
