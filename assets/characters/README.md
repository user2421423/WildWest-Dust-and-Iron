# Cinematic duelist portraits

This directory holds transparent WebP portrait overlays used by the game's face-upgrade system.

Upload these exact files here (GitHub > Add file > Upload files):

- `coyote-jack.webp` — first duel
- `silas-vane.webp` — third duel
- `marshal-crow.webp` — fifth duel

The project's `index.html` automatically loads these assets for the corresponding duel. When an image is missing, it falls back to the procedural character model; nothing breaks.

These are high-detail **2D portrait overlays**, not rigged 3D character models. The weapon, arms, and body animations remain procedural.

Image pack: provided in the ChatGPT conversation that prepared this integration.
