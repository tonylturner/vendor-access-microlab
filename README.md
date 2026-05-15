# Find the Persistent Paths

> A 30-minute tabletop micro-lab for ICS / OT security practitioners.

[![License: CC BY-NC 4.0](https://img.shields.io/badge/License-CC%20BY--NC%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by-nc/4.0/)
[![Status: WIP](https://img.shields.io/badge/status-work%20in%20progress-yellow.svg)](#)
[![Worksheet](https://img.shields.io/badge/worksheet-live-blue.svg)](https://tonylturner.github.io/vendor-access-microlab/)

Look at a fictional electric distribution utility three weeks after a substation emergency, identify how vendor remote-access paths quietly become permanent, and confront one of the most underdiscussed problems in operational technology: **vendor access is not temporary.**

A SANS ICS Summit workshop on securing vendor access in industrial environments.

---

## At a glance

| | |
|---|---|
| **Duration** | 30 minutes |
| **Audience** | ICS / OT security practitioners |
| **Format** | Digital — attendee phones / laptops + projector |
| **Setup needed by attendees** | None. No app, no account, no downloads. |
| **Setup needed by instructor** | ~20 minutes, once |

---

## How it runs

The lab moves through three phases. Your instructor drives pacing from the projector. You work on your own device.

| Phase | Time | What you do |
|---|---|---|
| **1 — Classify** | ~7 min | A network map appears on the projector. Open the worksheet on your phone, tap a sticker on each vendor access path you spot, note how long it has been active, and hunt six hidden risks embedded in the map. |
| **2 — Kill three** | ~7 min | A simulated incident occurs. Pick three access paths to disable under an operational budget. Vote in the projector poll. The room's collective choices appear in real time. |
| **3 — Time leap** | ~10 min | Six months pass. No incident occurs. Look at what you did — and did not — remove. Vote once more. See what the room actually thinks about its own environment. |

---

## What you need

Bring a phone or laptop with a working camera and a web browser. That's all.

During the lab the instructor projects two QR codes:

1. One scans to the **worksheet** — a single web page where you work through all three phases.
2. One scans to the **live polls** — run in Mentimeter or Slido, where you vote during the lab.

---

## Live links

These will be active during the lab:

- **Worksheet:** <https://tonylturner.github.io/vendor-access-microlab/>
- **Polls:** filled in by your instructor at the start of the lab
- **Network map:** [`network_map.png`](./network_map.png) — in case you want it on your own device during phase 1

---

## About the worksheet

The worksheet saves your work automatically to your browser. If your phone goes to sleep, your tab closes, or you accidentally refresh, your progress is restored when you come back. A small "saved" indicator flashes briefly after each action.

To start over at any point, hit **Reset** in the top-right header.

Phase 1 is open immediately. Phases 2 and 3 nominally wait for the instructor's cue, but you can preview them — the lab works best in sequence, but nothing stops you.

---

## What you will *not* need

- You will not need to type long answers. The worksheet uses tap-to-select almost everywhere.
- You will not need an account on any platform.
- You will not need to download an app.
- You will not need to install a QR code scanner. Modern phone cameras handle QR codes natively.

---

## After the lab

Your browser keeps your final state saved — reopen the worksheet URL anytime to see what you did. The aggregate room results from the polls will be shared by your instructor.

---

## Repository contents

| File | Purpose |
|---|---|
| [`index.html`](./index.html) | The attendee worksheet (single-page app, no backend) |
| [`network_map.png`](./network_map.png) | The network map shown on the projector |
| [`README.md`](./README.md) | This file |
| [`LICENSE`](./LICENSE) | CC BY-NC 4.0 license |

Instructor delivery materials (deployment guide, poll script, runbook) live alongside this repo locally during lab design and are intentionally **not** committed to the public repository.

---

## License

This work is licensed under the **Creative Commons Attribution-NonCommercial 4.0 International** license (CC BY-NC 4.0). See [`LICENSE`](./LICENSE) for the full text.

You're welcome to share and adapt this lab for non-commercial use as long as you give appropriate credit and link to the license. For commercial use, please get in touch.

---

*A SANS ICS Summit workshop on securing vendor access in industrial environments.*
