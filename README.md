# DUST & IRON: Frontier Cinematic

A standalone, browser-playable 3D Wild West quickdraw game. Challenge five gunslingers outside a frontier saloon, with first-person and over-the-shoulder third-person views.

## Play

Open [`index.html`](index.html) locally in a modern WebGL2-capable browser (Chrome recommended), or use the repository's GitHub Pages site after enabling Pages.

**No installation, npm packages, or network connection required.** Images, textures, shaders, and game logic are embedded in the HTML file.

## Controls

| Input | Action |
| --- | --- |
| Mouse movement | Aim |
| Left click | Shoot |
| V | Toggle first-/third-person camera |
| H | Toggle Ultra/Balanced graphics |
| M | Toggle sound |
| P | Pause |
| Enter | Continue or retry |

## Gameplay

- Five progressively more challenging quickdraw opponents
- A randomized DRAW signal and false-start detection
- Headshots, reaction-time scoring, and bounties
- Saloon-street scenery, PBR-inspired shading, dynamic lighting, and atmospheric effects
- Procedural character models, poses, clothing, and detailed revolvers

## Requirements and limitations

- A desktop browser with WebGL2 and hardware acceleration enabled
- The default Ultra setting may run slowly on some laptops; press **H** for Balanced
- Character models and animations are procedural, not scanned assets or motion capture
- This project is not equivalent to AAA productions such as *Red Dead Redemption 2*
- Full GPU rendering has not been independently tested on every browser/device

## Deploy with GitHub Pages

In GitHub, open **Settings → Pages → Build and deployment**, choose **Deploy from a branch**, set **main** and **/(root)**, and save. Your site will normally become available at `https://<your-username>.github.io/<repo-name>/` after deployment.

## Project files

- `index.html`: the complete playable game
- `README.md`: this guide
- `.nojekyll`: bypasses Jekyll processing for GitHub Pages

## Attribution and usage

The game was generated for a user project. No open-source license is specified in this repository; do not assume permission to redistribute or relicense it beyond the repository owner's rights.