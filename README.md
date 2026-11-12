# Vantix Digital — website projects

The original agency demo lives at the repository root. The two newest website builds live in separate, self-contained project folders.

| Project | Source | Local preview from its folder |
| --- | --- | --- |
| Original agency demo | [Root website](index.html) | `python3 -m http.server 8000` |
| Seven-site collection | [projects/vantix-website-collection](projects/vantix-website-collection) | `python3 -m http.server 8000 --directory dist` |
| After Hours listening bar | [projects/after-hours-listening-bar](projects/after-hours-listening-bar) | `python3 -m http.server 8000 --directory dist` |

Both new projects use custom HTML, CSS, and JavaScript, with bundled assets and no build step or Wix runtime. Their forms are browser-only demonstrations; they do not send messages, take payments, or book appointments.

## Deploy an individual project

In Netlify, import this repository and set the base directory to the chosen `projects/<name>` folder. Each project includes `netlify.toml` with `dist` as its publish directory. Leave the build command empty. Use a separate Netlify site for each folder.

The root agency demo remains at its original location and has not been replaced.

## Browse the wider portfolio

[Repository directory](REPOSITORIES.md) groups the existing public website repositories by purpose and explains how the new builds relate to the earlier demos.

## Assets and verification

Each new project includes an `ASSETS.md`, font licenses, and documentation of demo behavior. Local asset and anchor checks, JavaScript syntax checks, and initial Netlify HTTPS checks passed. Visual browser QA remains outstanding.
