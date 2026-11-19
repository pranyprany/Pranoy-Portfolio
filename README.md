# Pranoy M S — portfolio

Static site. No build step, no dependencies.

- `index.html` — the whole page (markup, styles, script)
- `img/` — photos and project images
- `files/` — CV and the AGAR research poster

## Run locally

Open `index.html` in a browser, or serve the folder:

```bash
npx serve .
```

## Deploy

Any static host works. On Vercel, import this repo and keep the defaults:
Framework preset "Other", no build command, output directory `./`.
