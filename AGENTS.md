# AGENTS.md — 星渊纪元：神域战争

## Project identity
- Project: 星渊纪元：神域战争 (Astral Abyss)
- Genre: original 2D top-down anime cosmic-fantasy PVE action RPG.
- Runtime: browser-based HTML5 Canvas prototype; Vercel static hosting.
- Core fantasy: explore dungeons and fight aliens, demons, angels, dragons and divine beings.

## Long-term rules
1. Keep the game original. Do not copy Genshin Impact characters, names, art, UI assets, story text, music or proprietary content. "Genshin-like" describes broad elemental-team-combat inspiration only.
2. Preserve top-down camera, anime visual direction and PVE focus unless the project owner explicitly changes them.
3. Elemental combat is a core pillar. Keep element application, reaction rules, damage feedback and readable status effects consistent.
4. Keep controls discoverable and support keyboard/mouse. Avoid breaking existing key bindings without updating README.
5. Prefer modular, readable code and small focused changes. Do not silently remove existing gameplay systems.
6. Before changing project structure, inspect the current files and update documentation where needed.
7. Never commit secrets, access tokens, private credentials or personal data.
8. Keep assets original or properly licensed; document external asset licenses.
9. Test locally before pushing. At minimum run the available smoke tests and verify the root page loads.
10. Every game project change must be committed to this GitHub repository before deployment. Vercel production deploys should come from the connected Git repository.

## Required project files
- `AGENTS.md`: persistent development rules and constraints.
- `PROJECT_STATUS.md`: current progress, completed work, known issues and next steps.
- `README.md`: project overview, setup, controls, tests and deployment notes.

## Definition of done
- The game boots without console errors.
- Player movement, attacks and core elemental reactions work.
- README and PROJECT_STATUS reflect the actual implementation.
- Relevant tests pass.
- Changes are committed to GitHub.
