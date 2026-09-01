# cntrldesign.com

Static site for **CNTRL Design**, served via GitHub Pages at `https://cntrldesign.com`.

## Contents
- `index.html` — landing page (apex root)
- `template/` — reusable privacy-policy template for future apps (see `template/README.md`)
- `style.css` — shared site styles (black / white / red brand)
- `img/logo-black.png`, `img/logo-white.png` — CNTRLD wordmark (light / dark)
- `favicon.png` — red **D** mark
- `CNAME` — custom domain for GitHub Pages (`cntrldesign.com`)
- `.nojekyll` — serve files as-is (no Jekyll build)
- `.gitignore` — keeps `assets/` (raw PSDs, paid Intro fonts, packaging) out of the public repo

## Updating
Edit the HTML/CSS and push to the default branch. GitHub Pages redeploys automatically.

## ⛔ FIFO removed 2026-09-01
FIFO was delisted from the App Store and unpublished from Google Play after its keep/kill gate
returned zero paid subscribers. Every FIFO surface has been removed from this site: the product
block on the landing page, the two SEO pages (`fifo/best-pantry-apps-2026`, `fifo/nowaste-alternative`),
the privacy policy (`fifo/privacy`), and the screenshots (`img/fifo/`). All of it is recoverable from
git history if ever needed.

⚠️ **The next app will need its own privacy policy page before it can be submitted** — Apple requires
a working privacy-policy URL for every App Store app, with no exception. Use `template/` to build it;
`template/README.md` still refers to FIFO as the worked example, which now lives only in git history
(see the commit that removed it).

## Brand
- Colours: black `#0a0a0a`, white `#ffffff`, red `#ff0000`
- Wordmark typeface: **Intro** (Fontfabric, licensed — desktop only; not embedded as a webfont)
- Body/UI type: Inter / system sans
