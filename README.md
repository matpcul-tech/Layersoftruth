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
- **Cinematic presentation** — eleven procedurally painted, animated scenes (the cooperative
  street with its looping identical pedestrians, the diner with metronome rain and a flickering
  neon sign, the maintenance tunnels, the stairwell) rendered live on canvas, with graphic-novel
  style character portraits, expressions, and Wolf-Among-Us-style name cards on first appearance.
- **Synthesized sound** — per-location ambient drones, timer ticks, choice clicks, anomaly
  stings, and the neighbor's violin in apartment scenes (the same phrase, the same flat note
  at the same place, the same pause — every time), all generated with WebAudio (no audio
  files). Toggle with the SOUND button.
- **Cinematic staging** — characters walk on and off between scenes and persist across cuts,
  and the camera pushes in for close-ups on the story's biggest dialogue beats.
- **Timed dialogue choices** — the bar drains, and if you don't speak, Marcus stays silent.
  **Silence is always an option**, it is tracked, and it matters.
- **"Vera will remember that."** — characters (and the Purpose Engine) log your choices.
- **Anomaly catalog** — noticing the seams in reality is rewarded… and observed.
  Per the novel: your investigation causes the very anomalies you're trying to catalog.
- **End-of-episode cohort data** — Telltale-style choice statistics, framed in-fiction as
  comparisons against the other 47 subjects.
- **QTE sequences** — the valve sabotage (mash) and the run through the rearranging city
  (arrow-key prompts), plus a point-and-click investigation of the hidden markings.
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

Everything lives in `index.html` with zero dependencies and zero external assets:

- a small scene-graph engine (text pages, timed choices, QTEs, hotspots, stat effects)
- ~115 story nodes as plain data objects
- procedural canvas painters for each location (animated, deterministic, seeded)
- SVG character portrait generator (per-character features, four moods)
- a WebAudio synth for ambience and UI sound

No build step; adding a scene is adding an object to `STORY`.

---

*Based on the novel by Matthew Culwell. The cooperative welcomes you back.*
