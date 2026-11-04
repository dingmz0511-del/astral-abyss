# 星渊纪元：神域战争 | ASTRAL ABYSS

An original 2D top-down anime cosmic-fantasy PVE action RPG prototype.

## Vision
Explore a vast universe of ancient dungeons, alien ruins, celestial realms and demonic domains. Battle monsters, angels, dragons, gods and other cosmic beings using a character-action system built around elemental skills and reactions.

The combat takes broad inspiration from elemental action RPGs, while the setting, characters, names, visuals and story are original.

## Prototype
The first playable browser build focuses on:
- Top-down movement and mouse aiming.
- Basic attacks, dodge, elemental skill and elemental burst.
- Fire, water, lightning and ice.
- Elemental reactions such as vaporize, freeze, electro-charged and melt.
- PVE enemy waves, elite encounters, a dragon boss and reward loop.

## Run locally
No game engine installation is required for the browser prototype.

```bash
python -m http.server 8000
```

Open http://localhost:8000 in a browser.

If Node.js is installed and a test script is present:

```bash
npm test
```

## Deploy
The project is intended for Vercel static hosting:
1. Import this GitHub repository into Vercel.
2. Keep the project root as the repository root.
3. Use no build command for a plain static HTML build.
4. Deploy the production branch (`main`).

## Controls
Controls are shown in the in-game HUD. Keyboard and mouse are the primary input method.

## Project files
- `AGENTS.md` — persistent AI/developer rules.
- `PROJECT_STATUS.md` — progress, known issues and next steps.
- `README.md` — overview and setup instructions.
- `index.html` — browser entry point.

## License
All original project code and creative content are maintained in this repository. Add license notices for any third-party assets before distributing them.
