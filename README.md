# Singapore bus advertising routes

Interactive map of 18 bus advertising routes across Singapore, on an
OpenStreetMap basemap with real road-aligned route geometry.

- `index.html` — interactive map (toggle individual lines or City / City–Outer clusters)
- `routes.html` — roads listed per service

Each chip shows the route's bus-stop count. As you select routes, a live bar
reports the total bus stops and the unique bus stops (deduplicated across the
selection), so overlapping coverage is visible at a glance.

Self-contained: basemap tiles and route data are embedded, no network calls at runtime.
Basemap © OpenStreetMap contributors © CARTO. Routing via OSRM.
