# Kos · Landing

Landing page for Kos (kos-ia.com). It is independent from the platform: the platform lives in its own repository and on a separate subdomain.

The page copy is in Spanish (it is written for Spanish-speaking doctors). Code, comments, commits and docs in this repository are in English.

## Files

- `index.html`: the page, including the hero animation script.
- `kos-landing.css`: all styles. Colors come from the Kos platform (deep cobalt palette) and are changed only in `:root`.
- `assets/`: logo and icon.
- `serve.mjs`: tiny local server for previewing.

## Preview locally

```bash
node serve.mjs
```

Then open http://localhost:8795

## Preview online

GitHub Pages publishes `main` at https://paulaparradiaz-lab.github.io/kos-landing/ and updates it on every push. The page carries `<meta name="robots" content="noindex, nofollow">` so search engines skip it while it is a preview; remove that line at launch.

## Before publishing

Fill in the texts marked `[DATO: …]` on the page: Founders pricing and seats, real testimonials, and what happens to the audio. Confirm with Jhoan that a normal consultation becomes a clinical record in 2 minutes or less: the hero promises it. Links to the platform point to dev.med-kos.com until the final subdomain is set.
