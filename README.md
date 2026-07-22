# Athens transit — interactive map

Interactive public-transport map of greater Athens (metro, tram, trolleybus,
bus) built with MapLibre GL. Click a stop for its name and lines; toggle each
mode on/off; stop names appear as you zoom in.

**Concept/style demo built on the 2016 OASA GTFS feed** (the copy that was
reachable). The network reflects Athens ~2016; the styling/interaction is the
deliverable, and the data would be refreshed from the current feed for
production.

## Run

Open `index.html` — it needs `data.js` (the exported routes/stops/termini) in
the same folder, plus internet for the MapLibre library and basemap tiles.
Served here via GitHub Pages.
