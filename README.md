# Scoring Practice Tracker

A free, single-file web app for tracking golf practice sessions using the 5-drill
format popularized by Will Robins, PGA (creator of *The Scoring Method™*):

1. 1 Putt Circle — short putts
2. 2 Putt Circle — long putts
3. 3 Shot Circle — chipping
4. 3 Shot Scoring Zone — wedges
5. Go To Club

It is an independent companion tool, not affiliated with or endorsed by Will
Robins / The Scoring Method™. See the in-app **Guide** tab for tips sourced
from his public articles/interviews, plus links to his official program.

## Run it locally (no install needed)

Just open `index.html` in any browser — everything (calculations, saved
sessions) runs client-side and is stored in your browser's `localStorage`.

Or serve it locally:

```bash
npx serve scoring-method-app
```

## Deploy it for free

Any static host works since it's a single HTML file:

- **GitHub Pages**: push this folder to a repo and enable Pages on it.
- **Netlify / Vercel / Cloudflare Pages**: drag-and-drop the folder in their
  dashboard, or connect the repo — free tier is enough.

## Features

- Digital version of the paper scorecard: target score, 8 attempt boxes,
  auto-totals, target vs. total pass/fail highlighting, #PP labels, and a
  notes field per drill for reviewing feedback.
- Save/load/delete practice sessions (stored locally in your browser only —
  nothing leaves your device).
- Print / Save as PDF button for a paper-style printout.
- Guide tab with Will Robins' scoring tips and strategy notes.
