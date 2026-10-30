# Transert

Transert is a lightweight freight load-board prototype for Kenya. It explores how
shippers and carriers could find and filter loads on key routes, beginning with
Nairobi–Mombasa and expanding to other regional corridors over time.

The current project is a static front-end prototype. It has no backend, user
accounts, live load feed, or booking workflow. The loads shown on the page are
hard-coded examples, and the truck filters run locally in the browser.

## Features

Everything below is prototype-only — please read Current scope before treating
any of it as working functionality.

- Responsive landing page for the Kenya freight market
- Example load board with truck-type filters — hard-coded sample loads, filtered
  client-side in the browser; no live feed
- Product and corridor overview — a statement of direction, not a service
  currently on offer
- Standalone HTML, CSS, and browser JavaScript with no build step

## Run locally

You can open `index.html` directly in a browser. To serve it locally instead:

```sh
python3 -m http.server 8000