# Mercenary Command Dashboard

A self-contained campaign manager for **Classic BattleTech** mercenary campaigns, built on a
simplified ruleset streamlined from *Campaign Operations* (the companion rules document is in
[`docs/`](docs/)). One HTML file, no build step, no server, no dependencies.

The campaign opens in **January 3049** — and the timeline knows what's coming.

## Quick start (GitHub Pages)

1. Create a repository and upload the contents of this folder.
2. In the repo: **Settings → Pages → Source: Deploy from a branch → `main` / root**.
3. Your dashboard is live at `https://<username>.github.io/<repo>/`.

Or just open `index.html` locally in any modern browser — everything works offline.

## Saving

- **💾 Save** (or `Ctrl/Cmd+S`) stores the campaign in the browser's local storage. It survives
  page refreshes and never advances the game clock.
- **End Month** silently captures a pre-payday backup (last 12 kept, also refresh-proof). Rewind
  from **Save / Load**.
- **Save / Load** also offers copy/paste JSON, save-file download, and load-from-file — use those
  to move a campaign between machines or keep off-site copies.
- Browser saves live in one browser on one machine. Download a save file before switching devices.

## What's inside

| Group | Pages | What they do |
|---|---|---|
| Company | Overview · 'Mechs · Pilots · Personnel · Repair Bay · Finances · Timeline | Roster and assignments, pilot XP/advancement/wounds, staff with rules effects (negotiator, surgeon), day-by-day repair queue with tech rolls, parts stores, ledger and projections, a 3049-anchored campaign calendar |
| Mission | Debrief | Post-battle processing: 'Mech damage, wounds, ejection and wreck rolls, XP awards, clause-aware salvage |
| Market | Contract · Marketplace · Galaxy Map | Dice-driven contract offers with era-aware lore and negotiation, monthly 'Mech/equipment market, a 179-system Inner Sphere map with travel time & cost |
| Game Master | DM Tools | Pilot-adjusted lance Battle Value calculator, contract forge (injects into the players' next offer roll), reputation overrides |
| Reference | Rules Ref | The complete simplified ruleset, generated from the same data the dashboard runs on |

Money, reputation, healing, repairs, travel, and the era's events all follow the rules in
`docs/Mercenary_Field_Manual` — the dashboard is the automation, the document is the authority.

## Fair-use notice

This is a free, unofficial fan project for personal tabletop use. *BattleTech*, *'Mech*,
*BattleMech* and related marks are trademarks of The Topps Company, Inc.; the tabletop game is
published by Catalyst Game Labs. This project is not affiliated with, endorsed by, or sponsored
by any of them, and includes no rules text or art from any published product.
