# Hunting Trip Planner

Installable offline web app for planning hunting trips, tracking kit and sharing a PDF trip sheet.
No server, no accounts. Everything you enter stays in your own browser.

## Publish on GitHub Pages (free)

1. Create a new **public** repository on GitHub (Pages is free for public repos), e.g. `trip-planner`.
2. Upload every file in this folder to the repository root, including the `icons` folder and the hidden `.nojekyll` file.
3. Go to **Settings > Pages**. Under **Build and deployment**, set Source to **Deploy from a branch**, branch **main**, folder **/ (root)**, then Save.
4. After a minute your app is live at `https://<your-username>.github.io/<repo-name>/`.

Only this code is public. Trip details, medical notes and map images are stored on each device and are never uploaded.

## Install on a phone

- Android (Chrome): open the link, tap **Install app**.
- iPhone (Safari): open the link, tap Share, then **Add to Home Screen**.

## Moving existing data

Saved data is per web address. In your old copy tap **Export backup**, then in the new app tap **Import backup**.

## Updating

Edit `index.html`, then change `CACHE = 'trip-planner-v3'` in `sw.js` to a new value (v2, v3...) so installed copies refresh.
