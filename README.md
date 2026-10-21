# Central Park MCA Parks Map

A single-page map and list of the Central Park (Denver 80238) MCA parks, with a snow removal page for each park.

Everything is in one file: `index.html`. There is nothing to install or build.

## Put it on GitHub Pages (free hosting)

1. Sign in at github.com and click **New repository**.
2. Name it (for example `mca-parks-map`), choose **Public**, and click **Create repository**.
3. On the new repo page click **uploading an existing file** (or **Add file > Upload files**).
4. Drag in `index.html` (and `README.md` if you like), then click **Commit changes**.
5. Go to **Settings > Pages**.
6. Under **Build and deployment**, set **Source** to **Deploy from a branch**, pick branch **main** and folder **/ (root)**, then **Save**.
7. Wait 1 to 2 minutes and refresh. The site address appears at the top of that page:
   `https://YOUR-USERNAME.github.io/mca-parks-map/`

## Update it later

1. Open the repo, click **Add file > Upload files**.
2. Drag in the new `index.html` (same file name replaces the old one).
3. Click **Commit changes**. The site refreshes in a minute or two.

## Good to know

- The pin-editing pencil and shared pin positions only work inside Claude. On GitHub the map shows the saved positions and the pencil is hidden.
- Saved parks (the star) are stored in each visitor's own browser.
- To add established dates, snow removal boundaries or photos, edit the `EST` and `SNOW` lines near the bottom of `index.html`, or ask Claude for a new build.
