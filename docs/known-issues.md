# Known Issues

> Generated from the private development backlog. For anything not listed here, please [open an issue](https://github.com/DyedfoxRA/wyrmflow/issues/new/choose).

---

## Critical

- **Opening a plain Git repo shows no guidance** — if you open a directory that has `.git` but no `.jj`, Wyrmflow accepts the folder silently without telling you to run `jj git init --colocate`. Fix in progress.

---

## Major

- **Shift-click selection across a merge commit does nothing** — extending a selection through a merge node in the graph doesn't highlight the expected range. Workaround: click each commit individually.
- **Modal focus trap missing** — pressing Tab inside a dialog (e.g. Clone, Settings, Command Palette) can move focus to the background UI. Workaround: use the mouse or Escape to close and reopen.
- **Right-click popup menus stay in English on non-English locales** — the main menu bar translates correctly, but right-click context menus in the graph remain English regardless of the selected language. Fix planned.

---

## Minor

- **Stacked bookmark badges have no context menu** — right-clicking an overflow badge (the `+N` counter that appears when many bookmarks share a commit) does nothing. Workaround: click the badge to expand, then right-click individual bookmarks.
- **Export patch saves to Downloads folder without a path picker** — on macOS and Windows you cannot choose where the patch file lands. A native save-as dialog is planned.
