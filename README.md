# settings

My personal editor and IDE settings, kept in one place so I can set up a new
machine quickly.

## Contents

| Editor | Config |
| --- | --- |
| Cursor | [`cursor/settings.json`](cursor/settings.json) |
| Visual Studio Code | [`vscode/settings.json`](vscode/settings.json) |
| JetBrains | see [below](#jetbrains) |

## JetBrains

JetBrains settings live in the IDE, not in a file, so here they are for the record.

### Font

| Where | Font | Size | Line height |
| --- | --- | --- | --- |
| `Editor` › `Font` | JetBrains Mono | 13 | 1.2 |
| `Editor` › `Color Scheme` › `Color Scheme Font` | JetBrains Mono | 13 | 1.2 |
| `Editor` › `Color Scheme` › `Console Font (Terminal)` | MesloLGS NF | 12 | 1.2 |

### Theme

Material UI, **Material Oceanic** (Contrast, no compact).

## Usage

Copy the relevant `settings.json` into your editor's config location:

- Cursor: `~/Library/Application Support/Cursor/User/settings.json`
- VS Code: `~/Library/Application Support/Code/User/settings.json`
