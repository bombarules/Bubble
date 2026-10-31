# Central Park MCA Parks Map (Mapbox)

One file, `index.html`. Real Mapbox map with street and satellite views, a pin for each of the 72 parks, the park list, and a snow removal page for each park.

## Put it on GitHub Pages

1. On github.com click **New repository**, name it (for example `mca-parks-map`), choose **Public**, **Create repository**.
2. Click **uploading an existing file**, drag in `index.html` (and `README.md`), then **Commit changes**.
3. **Settings > Pages > Source: Deploy from a branch > main > / (root) > Save**.
4. After a minute your site is at `https://YOUR-USERNAME.github.io/mca-parks-map/`.

## Lock your Mapbox token to your site (recommended)

1. Go to account.mapbox.com > **Access tokens** and open your public token (starts with `pk.`).
2. Under **URL restrictions** add `https://YOUR-USERNAME.github.io/` and save.
3. If the map ever shows "could not load", check that this URL matches your site exactly.

## Fixing pin positions

Pins use exact coordinates where known, otherwise Mapbox looks up each street address the first time the page loads and the result is remembered on that device. Parks with no street number are placed roughly.

To correct pins: open your site with `?edit=1` on the end of the address, drag the pins to the right spots, then tap the small square button on the map. Copy the text that appears and send it to Claude to build in for everyone.

## Update later

Repo > **Add file > Upload files** > drop in the new `index.html` (same name replaces it) > **Commit changes**.
