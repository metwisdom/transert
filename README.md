# Transert

Transert is a lightweight freight load-board prototype for Kenya. It explores how shippers and carriers could find and filter loads on key routes, beginning with Nairobi–Mombasa and expanding to other regional corridors over time.

The current project is a static front-end prototype. It has no backend, user accounts, live load feed, or booking workflow. The loads shown on the page are hard-coded examples, and the truck filters run locally in the browser.

## Features

- Responsive landing page for the Kenya freight market
- Example load board with filters for truck type
- Product and corridor overview
- Standalone HTML, CSS, and browser JavaScript with no build step

## Run locally

You can open `Index.html` directly in a browser. To serve it locally instead:

```sh
python3 -m http.server 8000
```

Then visit <http://localhost:8000>. The page loads Archivo and IBM Plex fonts from Google Fonts, so those fonts require an internet connection; system font fallbacks are defined in the stylesheet.

## Project files

- `Index.html` — page content and client-side load filtering
- `styles.css` — layout, responsive rules, and visual styles

## Current scope

The prototype is intended to communicate the product direction and test the load-board presentation. The next product work would include validated listing data, a backend, and a real posting and booking flow. WhatsApp message parsing is a proposed capability, not implemented functionality in this prototype.