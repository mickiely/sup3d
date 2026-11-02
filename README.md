# Sup3d

3D park operations and guest maps for holiday parks. A park's own site map becomes a clickable 3D model with a **staff view** (arrivals, jobs, owner fees, compliance, seasonal pricing) and a **guest view** (what's free, pick your site, facilities, day planner).

## Pages
- `index.html` – pitch page for park groups
- `guest.html` – concept guest website for Easts Beach, Kiama
- `demo.html` – nine NSW South Coast parks, staff/guest switch (`demo.html#eastsbeach`, `#wallaga`, …)

## Data
- `maps/` – the parks' published site maps (used for the "on the park map" crop)
- `ground/` – cleaned ground textures traced from each map
- Park sites are embedded in `demo.html` / `guest.html`. Bookings, owners, prices and jobs are sample data.

Static site, no build step. Deploys on Netlify from the repo root (`netlify.toml`).

`robots.txt` blocks search engines while the demos use real park names and maps; remove it when the site is ready to be public.
