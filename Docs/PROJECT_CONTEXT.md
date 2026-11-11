# FrankenArms project context

This is a new local Unity project started from the FrankenArms GDD supplied in `Unity-AI-Game-Workspace.zip`. The owner explicitly chose to start over rather than reuse the previous game's code and assets.

## Project setup

- Project: `FrankenArms`
- Unity Editor: `6000.6.7f1`
- Render pipeline: Universal 2D / URP 2D Renderer
- Target: Windows PC, keyboard/mouse and gamepad
- Main design document: `Docs/FrankenArms_GDD_RU.html`
- Repository URL: to be created by the owner; see `Docs/GITHUB_SETUP.md`

## Current environment limits

- Unity CLI `1.0.0-beta.13` and Unity Editor `6000.6.7f1` are installed.
- Unity CLI can launch and batch-run projects. Live control of an open Editor requires `com.unity.pipeline`.
- Pipeline installation is pending: the current environment routes HTTP(S) through unavailable `127.0.0.1:9`, and bypassing that proxy fails TLS. Do not claim live Editor control is ready until `unity status` finds this project.
- Unity project creation through the CLI was interrupted by a Unity Licensing Client / local Package Manager failure. The local 2D template files were retained and prepared manually.

## Product principles

1. Follow the new GDD; old project files are intentionally excluded.
2. Prototype a narrow vertical slice before implementing the full 24-floor game.
3. Preserve readable combat, meaningful weapon fusion, and progression that survives a failed run.
