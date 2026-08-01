# The Distopia: Layers of Truth — The Game

A Telltale-style narrative adventure based on the novel **_The Distopia: Layers of Truth_** by Matthew Culwell.

You are Marcus. Three days ago you stepped out of the simulation into the real world.
The sun is rising in the wrong sky.

## Play

Open **`index.html`** in any modern browser — no build step, no server, no dependencies.
It's a single self-contained file, so it also works hosted anywhere (GitHub Pages, etc.).

## What's inside

- **Five episodes** following the novel's arc: *Surface Tension*, *The Weight of Watchers*,
  *Breadcrumbs and Broken Code*, *The Freedom Paradox*, *The Last Layer*.
- **Timed dialogue choices** — the bar drains, and if you don't speak, Marcus stays silent.
  **Silence is always an option**, it is tracked, and it matters.
- **"Vera will remember that."** — characters (and the Purpose Engine) log your choices.
- **Anomaly catalog** — noticing the seams in reality is rewarded… and observed.
  Per the novel: your investigation causes the very anomalies you're trying to catalog.
- **End-of-episode cohort data** — Telltale-style choice statistics, framed in-fiction as
  comparisons against the other 47 subjects.
- **A QTE sabotage sequence** (the valve is now both open and closed).
- **The prediction engine finale** — moral dilemmas where the system posts its prediction
  of your choice before you make it, and its model accuracy rises or collapses with you.
- **Four endings**: The Apparatus · Comfortable Delusion · The Null State · Authentic Darkness.
- Hidden stats — defiance, compliance, integrity, silences, and your bonds with Sarah and
  Vera — shape the epilogue you receive.

## Controls

| Input | Action |
|---|---|
| Click / tap / `Space` / `Enter` | Advance text |
| Click a choice or press `1`–`4` | Choose |
| Do nothing on a timed choice | Stay silent (this is a choice) |
| Any key / tap rapidly | Quick-time events |

Progress autosaves to your browser (`localStorage`). Completed episodes unlock in the
title menu for replay.

## Structure

Everything lives in `index.html`: a small scene-graph engine (~200 lines) and the story
data (~110 nodes). Scenes are plain objects — text pages, choices with stat effects,
timers, and branch targets — so adding or editing scenes requires no engine changes.

---

*Based on the novel by Matthew Culwell. The cooperative welcomes you back.*
