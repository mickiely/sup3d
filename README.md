# Sup3d

3D park operations and guest maps for holiday parks. A park's own site map becomes a clickable 3D model with a **staff view** (arrivals, jobs, owner fees, compliance, seasonal pricing) and a **guest view** (what's free, pick your site, facilities, day planner).

## Pages
- `index.html` – pitch page for park groups
- `guest.html` – concept guest website with nine-park switching and a day planner
- `demo.html` – nine NSW South Coast parks, staff/guest switch (`demo.html#eastsbeach`, `#wallaga`, …)

## Data
- `maps/` – the parks' published site maps (used for the "on the park map" crop)
- `ground/` – cleaned ground textures traced from each map
- Park sites are embedded in `demo.html` / `guest.html`. Bookings, owners, prices and jobs are sample data.

Static HTML site with no framework, package installation, or build step. The existing Netlify configuration (`netlify.toml`) is unchanged.

## Cloudflare Pages

Connect the existing `mickiely/sup3d` GitHub repository to a new Cloudflare Pages project with:

- Framework preset: **None**
- Root directory: repository root (the default)
- Build command: leave blank
- Build output directory: `.`
- Environment variables: none

Use `main` as the production branch after the migration is approved and merged. Git-connected branches can use Cloudflare preview deployments. Do not attach the existing custom domain or change DNS as part of this preparation; the repository's `CNAME` and `.nojekyll` files are preserved.

`robots.txt` blocks search engines while the demos use real park names and maps; remove it when the site is ready to be public.
