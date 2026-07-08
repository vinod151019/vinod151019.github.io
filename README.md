# Satya Vinod Kantipudi — Portfolio

Modern single-file portfolio for my role as an **AWS Solutions Architect** specializing in **AI/ML, Generative AI, and Agentic AI**. Live at **https://vinod151019.github.io**.

## Files
- `index.html` — the entire site (HTML + CSS + JS inline; no build step; only external deps are Google Fonts + Font Awesome via CDN).
- `SatyaVinodKantipudideiResume.pdf` — résumé linked from the hero. **Swap this with your latest SA résumé anytime.**
- `.nojekyll` — tells GitHub Pages to serve files as-is.

## Hosting
Served by **GitHub Pages** from the **`master`** branch (root) of `vinod151019/vinod151019.github.io`.
- The previous (2024 data-engineer) site is preserved on the **`old-site-2024`** branch — nothing was lost.

## Make an edit & republish
```bash
git clone https://github.com/vinod151019/vinod151019.github.io.git
cd vinod151019.github.io
# edit index.html (search for a section id like #impact, #focus, #education)
git add -A
git commit -m "Update portfolio"
git push origin master     # Pages redeploys automatically in ~1 min
```

## Preview locally
```bash
open index.html            # or: python3 -m http.server 8000
```

## Content notes
- **No customer names** appear anywhere — engagements are described by industry and outcome only (customer identities confidential).
- **No confidential figures** (deal amounts, ARR, revenue, account health scores) are included.
- Certifications: 3 are listed by name + "8× AWS Certified" total. Add the remaining specific names in the `#education` section's certifications block when ready.
