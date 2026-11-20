# Aaron's Scoop Bucket

Personal [Scoop](https://scoop.sh) bucket for Windows applications maintained by `aaron-c-s-ramos`.

## Usage

Add the bucket and install `sdelete-gui`:

```powershell
scoop bucket add aaron https://github.com/aaron-c-s-ramos/scoop-bucket
scoop install aaron/sdelete-gui
```

## Available Manifests

| Manifest | Application | Repository |
|---|---|---|
| `sdelete-gui` | SDelete Gui (Rust) | [aaron-c-s-ramos/SDelete-Gui](https://github.com/aaron-c-s-ramos/SDelete-Gui) |

## Automatic Updates

The [Excavator](.github/workflows/excavator.yml) GitHub Actions workflow runs every 4 hours to detect new GitHub Releases, verify SHA-256 hashes, and update manifests automatically.
