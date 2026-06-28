# Personal site — Yoshith Kotla

Single-file portfolio for GitHub Pages. No build step, no dependencies.

## Deploy (you already have a `main` branch)

1. Drop `index.html` and `.nojekyll` into the **root** of your repo.
2. Commit and push to `main`.
3. In the repo: **Settings → Pages → Build and deployment → Source: Deploy from a branch → Branch: `main` / `(root)` → Save**.
4. Wait ~1 minute. Your site is live at:
   - `https://USERNAME.github.io` if the repo is named `USERNAME.github.io`
   - `https://USERNAME.github.io/REPONAME` otherwise

`.nojekyll` just tells Pages to serve the file as-is instead of running it through Jekyll.

## Fill these in before publishing

Search `index.html` for these placeholders:

- `USERNAME` — your GitHub and LinkedIn handles (footer links)
- `you@example.com` — your email (footer)
- `data-link="..."` — the `href="#"` on each project title and the **live / code** links currently point nowhere. Replace each `#` with the real demo URL or repo URL.

## To confirm / fix (I drafted, didn't assume)

- **Sea-level math** — I described standard tide-gauge trend estimation (OLS on monthly mean sea level, seasonal harmonics removed, autocorrelation-adjusted confidence interval). If your implementation differs, tell me and I'll rewrite that block exactly.
- **Current research** — I featured **Drishti**. If the "current working one" is ECRC-CR (or something else), say so and I'll swap it.
- **Degree titles / dates** — education years are placeholders; correct them.
- **CWRU PhD line** — included as an "admitted, deferred" credential. Remove it if you'd rather keep it off a public page.
