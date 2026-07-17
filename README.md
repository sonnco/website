# Sonnco website

Static marketing landing page for Sonnco, styled with Tailwind CSS.

## Structure

```
index.html          Page markup (Tailwind utility classes)
src/input.css        Tailwind entry — @theme tokens, @font-face, custom @utility gradients
css/site.css         Built stylesheet (generated — do not edit by hand)
fonts/               Self-hosted Geist (latin variable subset, woff2)
images/              Screenshots and image assets
```

## Develop

```bash
npm install
npm run dev      # rebuild css/site.css on change
npm run serve    # serve at http://localhost:8000
```

## Build

```bash
npm run build    # minified css/site.css
```

The site is fully static — open `index.html` through any web server (or the
`npm run serve` helper). No runtime dependencies; the Geist font is self-hosted
in `fonts/`, so nothing is fetched from a third-party CDN.
