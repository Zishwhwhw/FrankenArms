# FrankenArms project instructions

Before implementing gameplay, read:

1. `Docs/PROJECT_CONTEXT.md`
2. `Docs/SESSION_HANDOFF.md`
3. `Docs/DECISIONS.md`
4. `Docs/FrankenArms_GDD_RU.html`

The GDD is authoritative for game design. This is a clean project; do not bring back the deleted game's assets, scenes, or scripts unless the owner asks for them.

## Technical direction

- Unity `6000.6.7f1`, Universal 2D / URP 2D.
- Use Unity Input System for player input.
- Use ScriptableObjects for content definitions.
- Build dungeon routes as controlled graphs and place reviewed room templates; do not use pure random walk or global BSP.
- Keep work small, update `Docs/SESSION_HANDOFF.md` after each substantial task, and check Unity Console after code changes.
- Do not commit Unity caches (`Library`, `Temp`, `Logs`, `UserSettings`) or generated IDE files.
- Do not add asset packs or plugins without recording their license and decision in `Docs/DECISIONS.md`.
