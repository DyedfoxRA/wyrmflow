# Wyrmflow

**A Jujutsu-native VCS GUI for macOS, Windows, and Linux.**

<!-- SCREENSHOT_TODO: hero -->
![Wyrmflow screenshot](docs/screenshots/hero.png)

Wyrmflow brings a polished, fast desktop interface to [Jujutsu (jj)](https://github.com/martinvonz/jj) — the next-generation version control system that makes branching, rebasing, and conflict resolution feel effortless. If you live in the terminal but wish your VCS had a GUI that didn't get in the way, Wyrmflow is for you.

---

## Install

| Platform | Download |
|---|---|
| macOS 13+ Apple Silicon (M1/M2/M3) | [Wyrm\_aarch64.dmg](https://github.com/DyedfoxRA/wyrmflow/releases/latest) |
| macOS 13+ Intel | [Wyrm\_x64.dmg](https://github.com/DyedfoxRA/wyrmflow/releases/latest) |
| Windows 10+ (x64) | [Wyrm\_x64-setup.msi](https://github.com/DyedfoxRA/wyrmflow/releases/latest) |
| Linux (x64) | [Wyrm\_amd64.AppImage](https://github.com/DyedfoxRA/wyrmflow/releases/latest) |

> **Early access** — Wyrmflow is in active development. See [docs/known-issues.md](docs/known-issues.md) for the current list of known limitations.

---

## Why Jujutsu?

Jujutsu is a VCS built on top of Git that reimagines how version control should feel. Every working-copy state is a real commit. There are no index/staging conflicts. Rebasing is as safe as any other operation. Conflicts are first-class citizens you can set aside and come back to. The operation log gives you unlimited undo — across every command, including `jj git push`.

Wyrmflow puts a native GUI on top of all of that without hiding the model that makes jj powerful.

---

## Features

### Operation log — unlimited undo
<!-- SCREENSHOT_TODO: operation-log -->
Every action is recorded. Step backwards through any operation in the log and restore your exact repository state in one click. No more `git reflog` archaeology.

### Visual commit graph
<!-- SCREENSHOT_TODO: log-graph -->
A live, interactive commit graph built for jj's change-ID model. Drag commits to rebase, drag files to squash, drag bookmarks to move — direct manipulation instead of command memorisation.

### Bookmark management
<!-- SCREENSHOT_TODO: bookmarks -->
Create, rename, move, push, fetch, track, and untrack bookmarks from a dedicated panel. Push previews show exactly which commits will land before you hit send.

### Diff & conflict resolution
<!-- SCREENSHOT_TODO: diff-conflict -->
Side-by-side and unified diff views with syntax highlighting. Three-way conflict resolver lets you accept theirs, ours, or edit per hunk — backed by jj's conflict-first model so partial resolutions are safe to commit.

### Multi-workspace support
<!-- SCREENSHOT_TODO: workspaces -->
Open multiple jj workspaces side-by-side in tabs, each with its own working copy. Switch between feature branches without stashing anything.

### Settings & theming
<!-- SCREENSHOT_TODO: settings -->
Light and dark mode. Font size, diff whitespace, and signing preferences. All jj config layers surfaced in a UI — no TOML editing required.

---

## Pricing

| Tier | Repositories | Price |
|---|---|---|
| Free | 1 open repository per machine | Free forever |
| Pro | Unlimited repositories | See [wyrmflow.com/pricing](https://wyrmflow.com/pricing) |

The free tier is a real tier, not a trial — use Wyrmflow on one repo for as long as you like at no cost.

---

## Reporting issues

Found a bug or have a feature request? [Open an issue](https://github.com/DyedfoxRA/wyrmflow/issues/new/choose) — please use the appropriate template so we can triage quickly.

For paid-tier support, email **support@wyrmflow.com**.

---

## Links

- **Website & docs:** [wyrmflow.com](https://wyrmflow.com)
- **Issue tracker:** [github.com/DyedfoxRA/wyrmflow/issues](https://github.com/DyedfoxRA/wyrmflow/issues)
- **Discussions:** [github.com/DyedfoxRA/wyrmflow/discussions](https://github.com/DyedfoxRA/wyrmflow/discussions)
- **License:** [LICENSE](LICENSE) *(subject to revision pending legal review)*

---

*Wyrmflow is proprietary software. Source code is not published here. See [LICENSE](LICENSE) for terms.*
