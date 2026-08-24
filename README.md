# scoop-bucket

[Scoop](https://scoop.sh) manifests for [SophanaSok](https://github.com/SophanaSok)'s projects.

## Install

```powershell
scoop bucket add sophanasok https://github.com/SophanaSok/scoop-bucket
scoop install ai-usage-tui
```

## Manifests

| Manifest | What it is |
| --- | --- |
| `ai-usage-tui` | A btop-inspired terminal dashboard for AI token usage, cost, and model-routing analytics — [source](https://github.com/SophanaSok/ai-usage-tui) |

## How this is maintained

`bucket/ai-usage-tui.json` is **generated, not hand-edited.** Every tagged release of
[ai-usage-tui](https://github.com/SophanaSok/ai-usage-tui) renders it from the real published
artifact name and its SHA-256 checksum and pushes it here. It carries `checkver` and `autoupdate`
blocks, so `scoop status` sees new releases.
