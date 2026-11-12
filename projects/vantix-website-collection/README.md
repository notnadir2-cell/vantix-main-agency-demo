# Vantix Website Collection

Seven individually designed business website concepts and an editorial collection page.

Custom HTML, CSS, and JavaScript. No Wix runtime or build step.

## Run locally

From `projects/vantix-website-collection/`, run:

```sh
python3 -m http.server 8000 --directory dist
```

Open http://localhost:8000. Serve the entire `dist` folder so shared assets and links resolve correctly.

## Deploy to Netlify

Import this repository in Netlify and set the base directory to `projects/vantix-website-collection`. The project’s `netlify.toml` sets the publish directory to `dist`; leave the build command empty. Create a separate Netlify site for each project folder.

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

## Included websites

| Folder | Concept |
| --- | --- |
| `dist/relay-local/` | Relay / Local — missed-call workflow |
| `dist/missed-call-pilot/` | Manual seven-day pilot |
| `dist/polished-mile/` | Auto detailing |
| `dist/northline-studio/` | Barbershop |
| `dist/fieldmark-build/` | Construction |
| `dist/common-thread/` | Independent retail |
| `dist/cedar-stone/` | Landscaping |

## Repository directory

The collection above contains the newest independent redesigns. The earlier standalone demos below are retained as separate projects.

| Group | Repository | Purpose |
| --- | --- | --- |
| Current collection | [vantix-website-collection](https://github.com/notnadir2-cell/vantix-main-agency-demo/tree/main/projects/vantix-website-collection) | Seven rebuilt concepts and gallery |
| New standalone concept | [after-hours-listening-bar](https://github.com/notnadir2-cell/vantix-main-agency-demo/tree/main/projects/after-hours-listening-bar) | Listening bar experience |
| Agency demo | [vantix-main-agency-demo](https://github.com/notnadir2-cell/vantix-main-agency-demo) | Original agency concept |
| Service workflow | [northline-missed-call-demo](https://github.com/notnadir2-cell/northline-missed-call-demo) | Missed-call recovery demonstration |
| Manual pilot | [missed-call-pilot-demo](https://github.com/notnadir2-cell/missed-call-pilot-demo) | Original manual prototype |
| Pilot revision | [missed-call-pilot-generated-revision-demo](https://github.com/notnadir2-cell/missed-call-pilot-generated-revision-demo) | Alternative pilot revision |
| Auto detailing | [polished-mile-auto-detailing-demo](https://github.com/notnadir2-cell/polished-mile-auto-detailing-demo) | Original business demo |
| Barbershop | [northline-studio-barbershop-demo](https://github.com/notnadir2-cell/northline-studio-barbershop-demo) | Original business demo |
| Construction | [fieldmark-build-co-demo](https://github.com/notnadir2-cell/fieldmark-build-co-demo) | Original business demo |
| Retail | [common-thread-goods-demo](https://github.com/notnadir2-cell/common-thread-goods-demo) | Original business demo |
| Landscaping | [cedar-stone-landscaping-demo](https://github.com/notnadir2-cell/cedar-stone-landscaping-demo) | Original business demo |

Use the `vantix-websites` topic to find this website group, `missed-call-recovery` for workflow prototypes, and `business-website` for industry demos.
