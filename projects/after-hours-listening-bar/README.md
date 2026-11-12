# After Hours

A fictional listening bar website with warm art direction, drink filters, and an interactive evening planner.

Custom HTML, CSS, and JavaScript. No Wix runtime or build step.

## Run locally

From `projects/after-hours-listening-bar/`, run:

```sh
python3 -m http.server 8000 --directory dist
```

Open http://localhost:8000. Serve the entire `dist` folder so shared assets and links resolve correctly.

## Deploy to Netlify

Import this repository in Netlify and set the base directory to `projects/after-hours-listening-bar`. The project’s `netlify.toml` sets the publish directory to `dist`; leave the build command empty. Create a separate Netlify site for each project folder.

Alternatively, with Netlify CLI installed and authenticated:

```sh
netlify deploy --dir dist --no-build --prod
```

Earlier anonymous Netlify previews were temporary. Import this repository into your own Netlify account for ongoing hosting. No claim links, deployment tokens, or account credentials are stored here.

## Project structure

- `dist/`: ready-to-publish website and local assets.
- `netlify.toml`: hosting configuration and HTTP headers.
- `ASSETS.md`: photography and font sources.

## Demo behavior

These are fictional presentation concepts. Forms only update the browser UI. They do not send inquiries, make bookings, process payments, or persist personal data.

## Verification

Local links and asset references were checked, JavaScript syntax checks passed, and the initial Netlify deployment was verified over HTTPS. A full visual browser and accessibility audit has not been completed.
