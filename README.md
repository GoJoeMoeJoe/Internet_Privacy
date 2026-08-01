# InternetPrivacy

Personal toolkit for finding and removing my information from data brokers and
people-search sites.

## Contents

- **`removal-tracker.html`** — a self-contained, offline checklist tracker. Open
  it directly in a browser (no server or internet needed). Features:
  - ~60 data brokers grouped into 5 tiers (do-first → long-tail).
  - Per-broker **Confirm** link (find your listing) + **Remove** link + method +
    difficulty flag.
  - Checkboxes with live progress bar; state saved in the browser (localStorage).
  - Auto-set **recheck date** 6 months out — brokers re-scrape public records, so
    removals are recurring, not permanent.
  - Built-in step-by-step walkthroughs (Spokeo, Whitepages, and the general pattern).

## How to use

1. Open `removal-tracker.html` in your browser.
2. Start with **Tier 1** (Spokeo, Whitepages first — highest impact).
3. For each broker: Confirm your listing → open Remove → submit → click any
   confirmation email → check the box.
4. Recheck twice a year (the tracker sets reminder dates for you).

## Notes

- Broker opt-out URLs change occasionally. If a **Remove** link 404s, search the
  broker name + "opt out"; the **Confirm** link still gets you to the site.
- Automated alternatives (not required): Optery (free exposure scan), DeleteMe,
  Kanary, Privacy Bee.

## ⚠️ Privacy

`removal-tracker.html` contains personal identifiers (name, city, birth year).
**This repository must stay private.** If it is ever made public, remove or
redact that file first.
