# Raas Masood — Portfolio

Static one-page site (plain HTML/CSS/JS, no build step).

## Files
- `index.html` — the whole site
- `favicon.svg` — browser tab icon

## Deploy to Vercel (free `.vercel.app` domain)

### Option A — Vercel CLI (fastest)
1. Install Node.js (if you don't have it), then open a terminal in this folder.
2. Run:
   ```
   npx vercel login
   npx vercel --prod
   ```
3. When asked:
   - Set up and deploy? → **Y**
   - Project name → e.g. **raasmasood** (this becomes `raasmasood.vercel.app`)
   - Directory → **./**
   - Override settings? → **N**
4. Done. Vercel prints your live URL.

### Option B — GitHub + Vercel dashboard
1. Create a new GitHub repo (e.g. `portfolio`) and upload `index.html` and `favicon.svg`.
2. Go to vercel.com → **Add New… → Project** → import the repo.
3. Framework preset: **Other**. Leave build settings empty. Click **Deploy**.
4. To pick your URL: Project → **Settings → Domains** → edit the `.vercel.app` domain (e.g. `raasmasood.vercel.app`).

Every push to the repo redeploys automatically.

## Editing content
All text lives in `index.html`. Sections are marked with comments:
`<!-- 01 HERO -->`, `<!-- 02 IMPACT -->`, `<!-- 03 WORK -->`, `<!-- 04 EXPERIENCE -->`,
`<!-- 05 ABOUT -->`, `<!-- 06 SKILLS -->`, `<!-- 07 CERTIFICATIONS -->`.

Accent color: change `--accent` near the top of the `<style>` block.
