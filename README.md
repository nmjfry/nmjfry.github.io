# nmjfry.github.io

Personal academic website — Nicholas Fry, PhD researcher at Imperial College London.

## Setup

1. Push this repo to `github.com/nmjfry/nmjfry.github.io`
2. Go to **Settings → Pages → Source** → set to `Deploy from a branch`, branch `main`, folder `/root`
3. Site is live at `https://nmjfry.github.io` within ~60 seconds

## Structure

```
index.html          ← the entire site (single file, no build step)
cv.pdf              ← downloadable CV (linked from the hero)
assets/
  portrait.jpg      ← your photo (add this — see below)
  [paper teasers]   ← replace the SVG placeholders when papers are public
```

## To-do before shipping

- [ ] Add `assets/portrait.jpg` (any aspect ratio works — CSS crops to 180×220)
- [ ] Update author lists on the three papers (currently "N. Fry, et al.")
- [ ] Update Google Scholar link (currently generic)
- [ ] Verify github.com/nmjfry is correct
- [ ] Optional: replace SVG paper teasers with real renders once papers are public
- [ ] Optional: add a `CNAME` file for a custom domain

## Custom domain (optional)

1. Buy a domain (e.g. `nicholasfry.com`)
2. Add a `CNAME` file to the repo root containing just the domain name
3. Configure DNS: CNAME record pointing to `nmjfry.github.io`
4. In GitHub Settings → Pages, enter the custom domain

## Tech

Single-file static site. No framework, no build step, no dependencies.
Fonts loaded from Google Fonts (Cormorant Garamond, JetBrains Mono).
Dark mode via `prefers-color-scheme`. Accessible (`prefers-reduced-motion` respected).
