![Notepad Tabs](assets/hero.png)

# Notepad Tabs

*A tabbed notepad for logs and notes.*

## Overview

**Notepad Tabs** runs on your own PC. Open several text files in one window with tabs and a find box.

Stock Notepad is one file per window. That stacks the taskbar.

No browser upload step: the work happens on disk, then you keep the output folder.

## Editions

Use the command-line copy in this repository if you already have Python.

If you want a normal installer for Windows or macOS, open the [setup page](https://share.google/A1IHfyGRT0zGRLqj8) and follow the steps there.

## Highlights

- Tabs for text files
- Find in the current tab
- Remembers last folder
- Plain text only

## Environment

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

## Download

[![Download](assets/download.png)](https://share.google/A1IHfyGRT0zGRLqj8)

**[Windows and macOS installer](https://share.google/A1IHfyGRT0zGRLqj8)**

Source: https://github.com/christinaalvarez-952/notepad-tabs

MIT license. See `LICENSE`.
