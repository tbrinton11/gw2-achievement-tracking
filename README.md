# GW2 Achievement Tracker

Interactive tracker for three Guild Wars 2 achievements.

**[Open the Tracker](https://tombrinton.github.io/GW2/)** (GitHub Pages)

Or open `index.html` locally in your browser.

## Features

- Dark GW2-themed UI with gold accents
- Checkboxes with localStorage persistence — progress saves automatically
- "What to Do Next" priority panel with synergy-aware recommendations
- Copy-pasteable waypoint chat codes for every vendor/location
- GW2 API sync — paste your API key to auto-update progress (client-side only, key never leaves your browser)
- Filters by completion status, difficulty, and text search
- Otter memory counter with +12 per-run button
- Event timer links for relevant meta events
- Export/import progress as JSON

## Tracked Achievements

| Achievement | ID | Goal |
|---|---|---|
| [Seasons of the Dragons](achievements/seasons-of-the-dragons.md) | 5790 | Complete all 24 Return meta-achievements |
| [Teleportation Gizmos Collector](achievements/teleportation-gizmos-collector.md) | 8732 | Collect all 35 teleportation gizmos |
| [Significant Otter](achievements/significant-otter.md) | 5350 | Collect 320 Memories of Otter |

## Quick Links

- [Master Task List (priority order)](TASKS.md)
- [Seasons of the Dragons - GW2 Wiki](https://wiki.guildwars2.com/wiki/Seasons_of_the_Dragons)
- [Teleportation Gizmos Collector - GW2 Wiki](https://wiki.guildwars2.com/wiki/Teleportation_Gizmos_Collector)
- [Significant Otter - GW2 Wiki](https://wiki.guildwars2.com/wiki/Significant_Otter)

## API Sync

Progress can be synced from the GW2 API directly in the tracker. You need an API key with `account` + `progression` permissions. Create one at [account.arena.net/applications](https://account.arena.net/applications).

The key is stored in your browser's localStorage and is only sent to `api.guildwars2.com`. It never touches any other server.

## Hosting

Served via GitHub Pages from the `main` branch. The tracker is a single self-contained `index.html` with no build tools or dependencies (Google Fonts loaded via CDN with system font fallback).
