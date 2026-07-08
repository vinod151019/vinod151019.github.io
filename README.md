# Satya Vinod Kantipudi — Portfolio (2026 redesign)

A modern, single-file portfolio reflecting my current role as an **AWS Solutions Architect** (Startups & ISVs). Dark theme, animated hero, and sections for impact, thought leadership, projects, experience, education, and writing.

## Files
- `index.html` — the entire site (HTML + CSS + JS inline, no build step, no dependencies beyond Google Fonts + Font Awesome via CDN).
- `SatyaVinodKantipudideiResume.pdf` — résumé linked from the hero (swap with your latest copy anytime).

## Preview locally
Just open the file:
```bash
open index.html
```
or serve it:
```bash
python3 -m http.server 8000   # then visit http://localhost:8000
```

## Deploy to GitHub Pages
This replaces the old site at `vinod151019.github.io`.

```bash
# from this folder
git init
git add .
git commit -m "Redesign portfolio for AWS Solutions Architect role"
git branch -M main
git remote add origin https://github.com/vinod151019/vinod151019.github.io.git
git push -u origin main --force   # only if you intend to overwrite the old repo
```
Then enable Pages: repo → Settings → Pages → Source = `main` / root. Live within a minute or two.

> Tip: keep the old repo on a branch (e.g. `git branch old-site`) before force-pushing if you want a backup.

## Notes
- All content is drawn from real engagements. **No confidential figures** (deal amounts, ARR, revenue, or account health scores) are included — engagements are described by their technical solution and outcome only.
- To edit content, everything is plain HTML in `index.html`; search for the section `id` (e.g. `#impact`, `#leadership`) to find it.
