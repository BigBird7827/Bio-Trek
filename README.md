# Bio-Trek

Bio-Trek is a single-page, front-end **Star Trek** biography browser. It lets you explore character and actor bios, major story arcs, and curated “Hall of Fame / Hall of Shame” episodes from across the Star Trek franchise using an interactive, card-based UI.

## What it does

- Provides **series hubs** for:
  - TOS, TNG, DS9, VOY, ENT, DIS, PIC, SNW, plus a Guest List
- Displays **crew and actor biographies** loaded from external JSON files
- Shows **story arcs** with overviews, chapter breakdowns, and key characters
- Includes **curated episode lists** (best and worst) with detailed writeups
- Runs as a **pure front-end app** (single `index.html` + JSON + images, no backend)

## How it works

- `index.html` contains:
  - Main layout and navigation buttons
  - Card grid for series, arcs, and curated episodes
  - Overlay panels for detailed views
- Embedded JavaScript:
  - Fetches biography, story arc, and episode JSON from the repo
  - Dynamically builds cards and overlays
  - Handles navigation between series, arcs, and episode views

## Getting started

1. Clone or download the repository.
2. Open `index.html` in a modern desktop browser.
3. Use the main menu buttons to browse series, story arcs, and curated episodes.

No build step, database, or server is required—everything runs locally in the browser.

## Legal

This is a **fan-based Star Trek project** created for personal enjoyment and non-commercial use.

**Star Trek**, including all related marks, logos, characters, and elements, is the property of **Paramount Global (Paramount Pictures / CBS Studios)** or their respective rights holders.  
This project is not endorsed by, sponsored by, or affiliated with Paramount, CBS, or any official Star Trek rights holder.  
No copyright or trademark infringement is intended.
