
# SynthWorld (Godot 4) — Cynthia Builder/Repair Starter

This project boots to:
- A **surface** you can build on.
- **Cynthia** (agent) who can **place props** from `/data/commands/build.json`.
- A **repair loop**: damaged props are auto-detected and fixed by Cynthia.

## Quickstart
1) Install Godot 4.x (Standard).
2) Open `game/project.godot` in Godot → Run ▶
3) Watch Cynthia place a tree, then repair a dummy damaged prop.

## Files you'll tune
- `/data/commands/build.json` — queued build orders.
- `/game/Scripts/AI/Cynthia.gd` — builder/repair behavior.
- `/game/Scenes/Props/` — add your own buildable prefabs (duplicate Tree.tscn).
