# ahmedjafer.github.io

Personal website and portfolio: a single static page, no build step.
Live at https://ahmedjafer.github.io

## Where things live

| What | File |
| --- | --- |
| The whole site | `index.html` |
| CV download | `Ahmed_Jafer_CV.pdf` |
| Portrait (hero card) | `photo.jpg`, 800×1000 |
| Link-preview image | `photo-share.jpg`, 600×600 |

`.nojekyll` tells GitHub Pages to serve the files as-is.

## Preview locally

```bash
python3 -m http.server 8000   # then open http://localhost:8000
```

## Publish

Push to `main`. GitHub Pages serves the repo root of `main`
(Settings → Pages → Source: *Deploy from a branch*, `main` / `/ (root)`).
