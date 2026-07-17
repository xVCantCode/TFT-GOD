# TFTGOD Overlay

TFTGOD Overlay is a desktop team planner for Teamfight Tactics focused on fast comp generation, clean overlay pinning, and quick in-game reference.

This branch is intended to stay public-safe: product information, downloads, and release assets only. Internal implementation details are intentionally not documented here.

## What It Does

- Generates team options around a selected carry.
- Lets you include or exclude specific champions and traits.
- Lets you choose the exact trait breakpoint you want to include, such as 2 or 3 Primordian.
- Supports multiple emblem paths through the emblem picker.
- Lets you tune results toward stronger capped boards or cheaper transition boards.
- Tracks wasted traits so off-breakpoint traits are easier to avoid.
- Shows more paths in batches when extra valid teams are available.
- Pins a compact overlay above the game for quick reference.
- Stays focused on speed and usability during live matches.

## How It Works

Build your comp around a carry, tune the filters for traits and emblem lines you want, then pin the result you want to keep visible in-game.

Use the planner controls to:

- Set your target team size.
- Set how much trait waste you are willing to allow.
- Add included or excluded champions.
- Add included traits with a minimum breakpoint.
- Exclude traits you do not want in the final board.
- Sort paths by balance, cost, wasted traits, or active trait strength.
- Use Strength vs Cost to decide whether the planner should prefer stronger boards or cheaper boards.
- Click Show More to reveal additional paths 8 at a time.

Each result shows the board, total cost, wasted trait count, active traits, and pin controls.

<img width="800" height="436" alt="TFTGOD" src="https://github.com/user-attachments/assets/382c02f5-267c-453c-8368-379a97c3ed03" />

## Download

Grab the latest Windows build from the latest release page:

- [Latest release](https://github.com/xVCantCode/TFT-GOD/releases/latest)

Downloads should always be taken from the latest published GitHub Release rather than tracked repo files.

## Public Branch Policy

- Public branch: README, release assets, and other public-facing files only.
- Private branch: main buildable source and project files.
## Release Notes

Version `0.1.0`

- Desktop planner and pinned overlay workflow
- Carry-based comp search with champion, trait, emblem, cost, waste, and strength controls
- Selectable included-trait breakpoints
- Expandable path results with Show More
- Windows installer packaging
