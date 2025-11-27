# Bio-Trek

Bio-Trek is a single-page, front-end Star Trek biography browser. It lets you explore character and actor bios, major story arcs, and curated “Hall of Fame / Hall of Shame” episodes from across the Star Trek franchise using an interactive, card-based UI.

## What it does

- Shows **series-based hubs** (TOS, TNG, DS9, VOY, ENT, DIS, PIC, SNW, plus a Guest List).
- Displays **crew and actor biographies** loaded from external JSON files.
- Provides **story arc** overviews with chapter breakdowns and links to related characters.
- Includes **curated episode lists** with detail pages for each featured episode.
- Uses a **single HTML file** (`index.html`) plus JSON data and images—no backend required.

## How it works

- `index.html` contains the main layout, navigation buttons, card grid, and overlay panels.
- JavaScript inside `index.html` fetches JSON biography, story arc, and episode data from the repo.
- Cards are generated dynamically from that JSON and open detail overlays when clicked.

## Getting started

1. Clone or download the repository.
2. Open `index.html` in a modern desktop browser.
3. Use the main menu buttons to browse series, story arcs, and curated episodes.

No build step, database, or server is required—everything runs in the browser.
