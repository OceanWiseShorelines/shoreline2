# Shoreline Cleanup Data Explorer — BC + Ontario

Combined Ocean Wise Shoreline Cleanup explorer for 2018–2025.

## Geographies
- Vancouver Neighbourhoods
- BC Municipalities
- Toronto Neighbourhoods
- Ontario Lower + Single-Tier Municipalities

## Deployment
This build is intentionally self-contained. `index.html` includes Leaflet, the map geometry, annual summary data, styles, and explorer logic.

Upload both files in this ZIP directly to the root of a GitHub repository:
- `index.html`
- `README.md`

Then enable GitHub Pages under:
Settings → Pages → Deploy from a branch → `main` → `/ (root)`

No `data.js`, `css`, or `js` folders are required for this build.

## Explorer
The interface supports geography switching, area search, metric selection, mean/total measures, single-year analysis, grouped-year analysis, dynamic legends, highlighting, and popups.

Takeout Containers and Coffee Cups & Lids are available in the BC/Vancouver data. They are hidden for Ontario because those fields are not present in the current Ontario annual polygon summaries.
