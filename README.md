# Delta website

A static site: `index.html`, `privacy.html` and the `assets/` folder. Upload the whole folder to any static host.

## GitHub Pages (free)
1. Create a public repository, for example `delta`.
2. Upload everything in this folder to the repository root.
3. Settings › Pages › Source: "Deploy from a branch", branch `main`, folder `/ (root)`.
4. The site goes live at `https://<username>.github.io/delta/`. The privacy policy is at `…/delta/privacy.html`: use that URL in Play Console.

## Before launch
- The Google Play buttons point to `https://play.google.com/store/apps/details?id=com.delta.strategist`. That page works once the app is published. The `utm_*` tags show in Play Console › Store analysis which buttons bring installs.
- For the official "Get it on Google Play" badge, download it from Google's badge generator and swap it for the hero button (optional).
- The race-weekend card and the season grid update themselves from the built-in 2026 data and the visitor's clock. For 2027, the data needs regenerating from the app.
