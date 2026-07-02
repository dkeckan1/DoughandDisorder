# Dough & Disorder — Pizza Map

The official website for the **Dough & Disorder** YouTube channel: an interactive map and scoreboard of every pizza spot we've reviewed, starting with Cleveland, OH.

🍕 **YouTube:** [Dough & Disorder — Pizza Reviews](https://www.youtube.com/playlist?list=PLQ5KN6SeUn5_gjoQOZVI-CgpcV3RcV1ke)

## What's on the site

- **Map** — every reviewed spot pinned on an interactive map. Tap a pin to watch the review. Filter by pizza style or minimum score, or search by name.
- **Pizza Ratings** — the full scoreboard, ranked by score, each linking to its video.
- **Pizza Styles** — a cheat sheet of the styles we tag reviews with (New York, Cleveland Crimp, Neapolitan, and more).
- **About** — the mission.

## The rating scale

- **8+** Elite — drop everything
- **6–8** Solid — worth a stop
- **< 6** Skip it

## Editing the site

Open the site and click **✎ Edit Site** (bottom-left) to:

- Add, edit, or delete reviews (name, score, style, video link, map location, verdict)
- Manage pizza styles (name, accent color, photo, description)
- Change any headline, subtitle, or page text

Edits are saved in your browser (localStorage). To publish them for everyone, export the site from the edit panel and upload the new file to your host.

## Hosting

The site is a single self-contained HTML file — no build step or server needed.

1. Rename the exported file to `index.html`
2. Upload it to any static host: **Netlify Drop**, **GitHub Pages**, **Cloudflare Pages**, or **Vercel** (all free)

## Credits

Map tiles © [OpenStreetMap](https://www.openstreetmap.org/copyright) contributors, rendered with [Leaflet](https://leafletjs.com/). Fonts: Anton, Oswald, Yellowtail, Libre Baskerville (Google Fonts).
