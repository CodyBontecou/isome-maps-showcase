# iso.me Maps Showcase

This repository is a tiny Obsidian vault that shows the intended loop between **iso.me**, your local location history, and Obsidian:

1. Record your day privately with the [iso.me iOS app](https://apps.apple.com/app/id6761960794) ([source](https://github.com/CodyBontecou/isome)).
2. Export the visits and GPS points as human-readable files.
3. Render those exports inside Obsidian with the [iso.me Maps Obsidian plugin](https://github.com/CodyBontecou/obsidian-iso-me-maps).

The point is not just to draw a map. It is to make your movement history feel like part of your journal: local-first, inspectable, portable, and owned by you.

## What is in this vault

- `Daily Note.md` — a simple note containing an `iso-me` code block.
- `Exports/` — synthetic iso.me exports for a sample San Francisco week.
- `.obsidian/plugins/iso-me-maps/` — the Obsidian plugin files used by this showcase vault.
- `.obsidian/plugins/obsidian42-brat/` — BRAT, used to install/update the beta plugin from GitHub.

The sample export data is synthetic. It is here so anyone can open the vault and immediately see how iso.me exports become interactive maps.

## How to view the showcase

1. Clone this repository.
2. Open the folder as a vault in [Obsidian](https://obsidian.md/).
3. Enable community plugins if Obsidian asks.
4. Open `Daily Note.md` in Reading view.

You should see an interactive Leaflet map generated from this block:

````md
```iso-me
source: Exports/iso.me - Friday 2026-05-01 - all.md
title: Generated SF Trip
interactive: true
```
````

## Why this exists

iso.me is built around a simple belief: your location history is useful, intimate, and should remain yours. The app keeps tracking data on-device and lets you export it to files you can read, archive, sync, or delete.

This showcase demonstrates the next step: turning those files into a visual memory layer inside Obsidian. A daily note can contain where you went, how long you stayed, and the route between places — without needing a cloud dashboard or external account.

## Links

- [iso.me on the App Store](https://apps.apple.com/app/id6761960794)
- [iso.me source code](https://github.com/CodyBontecou/isome)
- [iso.me Maps Obsidian plugin](https://github.com/CodyBontecou/obsidian-iso-me-maps)
