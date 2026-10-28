# karl.preisner.us

My portfolio landing page, served by GitHub Pages at [karl.preisner.us](https://karl.preisner.us).
Plain HTML and CSS, no build step.

Because this is the user site (`KPreisner.github.io`) with a custom domain, my project sites
without their own domain are served under it, e.g. [karl.preisner.us/chip](https://karl.preisner.us/chip/).

## Preview locally

```
python3 -m http.server 8000
```

Then open http://localhost:8000. (`/chip/` only works once deployed.)

## Layout

- `index.html`, `styles.css`: the page
- `images/`: photos and screenshots
- `CNAME`: the custom domain
- `.nojekyll`: serve files as-is, no Jekyll
