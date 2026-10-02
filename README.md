# Daylight UI

An original productivity UI inspired by spacious typography, vibrant blue, pill controls, rounded surfaces, and soft elevation. No source-brand logos, assets, or proprietary fonts are included. Uses a system sans-serif font for a self-contained package.

## Open

Extract the folder and open `index.html` in a modern browser. No installation or build is required. For consistent local storage behavior, run `python -m http.server 8000` inside the folder, then visit http://localhost:8000.

## Files

- `index.html`: landing page, responsive app preview, and functional planner.
- `styles.css`: reusable tokens, components, breakpoints, dark theme, and reduced-motion support.
- `app.js`: task creation, completion, deletion, filtering, focus editing, and local persistence.
- `reference/`: supplied visual reference, for personal reference only; never used as a site asset.

## Customize

Change the `:root` variables in `styles.css` for colors and card radius. Replace Daylight and its copy in `index.html`. The planner is a frontend demo: data stays in the browser and is not synced to a server. Clearing browser storage removes saved tasks. The app preview at the top is illustrative; the working planner is below.

For Laravel, move the markup to a Blade view and load the CSS and JavaScript through your preferred asset pipeline. Add server routes and a database if you want account-based persistence.
