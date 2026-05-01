# GPATools.app

Free GPA & Grade Calculator — part of the Tools.app family.

## Files
- `index.html` — Full single-page site
- `sitemap.xml` — SEO sitemap
- `robots.txt` — Crawler rules
- `vercel.json` — Vercel config with security headers

## Deploy to GitHub + Vercel

### 1. GitHub
```bash
git init
git add .
git commit -m "Initial commit: GPATools.app"
gh repo create gpatools --public
git push -u origin main
```

### 2. Vercel
1. Go to vercel.com → New Project
2. Import your `gpatools` GitHub repo
3. Framework: **Other** (static)
4. Root Directory: `/`
5. Deploy!
6. Add custom domain: `gpatools.app`

## Activate Google AdSense
1. AdSense is already configured with publisher ID ca-pub-2548921396153742
2. Replace `data-ad-slot="XXXXXXXXXX"` with your ad slot IDs
3. Uncomment all `<ins class="adsbygoogle">` blocks and the `<script>` tag in `<head>`
4. Delete the `<!-- Advertisement -->` placeholder divs

## Ad Slots (3 total)
- **Top Leaderboard** (728×90) — below hero
- **In-Content** (fluid) — between calculator and how-it-works
- **Rectangle** (300×250) — sidebar next to GPA scale table
- **Bottom Banner** — above footer

## SEO Checklist
- [x] Title tag with primary keyword
- [x] Meta description
- [x] Canonical URL
- [x] Open Graph tags
- [x] Twitter Card tags
- [x] JSON-LD schema (WebApplication)
- [x] sitemap.xml
- [x] robots.txt
- [x] Mobile responsive
- [x] Semantic HTML
- [x] FAQ section (helps with featured snippets)
