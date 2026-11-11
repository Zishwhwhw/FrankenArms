# FrankenArms

Fresh Unity project for the game described in [`Docs/FrankenArms_GDD_RU.html`](Docs/FrankenArms_GDD_RU.html).

- Unity Editor: `6000.6.7f1`
- Template: Universal 2D (URP 2D Renderer)
- First target: Windows PC
- Design and technical decisions: `Docs/`

The previous game was not copied into this project. The GDD is the design source of truth.

## Unity CLI

Unity CLI is installed on this computer. Open this project with:

```powershell
unity open "D:\game\2dRoguelike\FrankenArmsFresh"
```

To control a running Editor from the CLI, install the Unity Pipeline package after Unity Package Registry access is available:

```powershell
unity pipeline install --project-path "D:\game\2dRoguelike\FrankenArmsFresh"
```

The current Codex environment cannot reach the registry because its proxy points to `127.0.0.1:9`. See `Docs/GITHUB_SETUP.md` for the remaining setup steps.
