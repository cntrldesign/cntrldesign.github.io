# cntrldesign.com

Static site for **CNTRL Design**, served via GitHub Pages at `https://cntrldesign.com`.

## Contents
- `index.html` — landing page (apex root)
- `fifo/privacy/index.html` — FIFO privacy policy → `https://cntrldesign.com/fifo/privacy`
- `template/` — reusable privacy-policy template for future apps (see `template/README.md`)
- `style.css` — shared site styles (black / white / red brand)
- `img/logo-black.png`, `img/logo-white.png` — CNTRLD wordmark (light / dark)
- `favicon.png` — red **D** mark
- `CNAME` — custom domain for GitHub Pages (`cntrldesign.com`)
- `.nojekyll` — serve files as-is (no Jekyll build)
- `.gitignore` — keeps `assets/` (raw PSDs, paid Intro fonts, packaging) out of the public repo

## Updating
Edit the HTML/CSS and push to the default branch. GitHub Pages redeploys automatically.
The FIFO privacy policy's source of truth is `store-assets/privacy-policy.md` in the `fifo` repo;
keep the two in sync when the policy text changes.

## Brand
- Colours: black `#0a0a0a`, white `#ffffff`, red `#ff0000`
- Wordmark typeface: **Intro** (Fontfabric, licensed — desktop only; not embedded as a webfont)
- Body/UI type: Inter / system sans
