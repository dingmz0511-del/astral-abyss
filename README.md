# 星渊纪元：神域战争 | ASTRAL ABYSS

An original 2D top-down anime cosmic-fantasy PVE action RPG prototype.

## Vision
Explore a vast universe of ancient dungeons, alien ruins, celestial realms and demonic domains. Battle monsters, angels, dragons, gods and other cosmic beings using a character-action system built around elemental skills and reactions.

The combat takes broad inspiration from elemental action RPGs, while the setting, characters, names, visuals and story are original.

## First playable browser Demo
- Top-down movement with WASD / arrow keys.
- Mouse aiming and click / J basic attacks.
- Dodge with Shift; elemental skill with E; burst with Q.
- Four starter elements: fire, water, lightning and ice.
- Reactions: vaporize, melt, electro-charged and freeze.
- Three PVE encounter waves, including an ancient dragon boss.
- Health, energy, kill count, timer, pause and restart.
- Responsive browser layout; no external runtime dependencies.

## Run locally
Open `index.html` directly in a modern browser, or start a local server:

```bash
python -m http.server 8000
```

Then visit http://localhost:8000.

## Deploy
This is a static HTML5 Canvas project. Import the repository into Vercel with the repository root as the Root Directory. No framework preset, build command or output directory is required; Vercel can serve `index.html` directly.

## Controls

| Action | Input |
|---|---|
| Move | WASD / Arrow keys |
| Aim | Mouse |
| Basic attack | Mouse click / J |
| Elemental skill | E |
| Elemental burst | Q |
| Dodge | Shift |
| Switch element | 1 / 2 / 3 / 4 |
| Pause | Esc / Pause button |

## Project files
- `index.html` — self-contained playable browser prototype.
- `AGENTS.md` — persistent development rules and constraints.
- `PROJECT_STATUS.md` — progress, known issues and next steps.

## License
All original project code and creative content are maintained in this repository. Add license notices for any third-party assets before distributing them.
