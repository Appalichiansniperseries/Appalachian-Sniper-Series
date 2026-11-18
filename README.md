# Appalachian Sniper Series Website

A simple, modern static website for the Appalachian Sniper Series.

## Features
- Home / Hero section
- News & announcements
- Match schedule with signup links
- Season standings overview
- Results section
- About / rules
- Direct links to your Impact Scoring club

## How to Use

1. **Add your logo**
   - Save your logo as `logo.png` (or `.svg`) in this folder.
   - Update the `src` in `index.html` from `logo-placeholder.png` to `logo.png`.

2. **Update Impact Scoring links**
   - Replace all `https://www.impactscoring.net/` placeholders with your actual Club page URL (e.g. `https://www.impactscoring.net/club/view?id=YOUR_ID`).

3. **Customize content**
   - Edit the news cards, schedule table, standings, and about text directly in `index.html`.

## Hosting (Free Options)

### GitHub Pages (easiest)
1. Create a new public GitHub repository named something like `appalachian-sniper-series`.
2. Upload all these files (index.html, styles.css, script.js, logo.png).
3. Go to Settings → Pages → Source: Deploy from main branch / root.
4. Your site will be live at `https://yourusername.github.io/appalachian-sniper-series/`.

### Netlify or Cloudflare Pages
- Drag and drop the folder onto Netlify or Cloudflare Pages.
- Instant HTTPS + custom domain support.

## Custom Domain
Once hosted, you can point a custom domain (e.g. `appalachiansniperseries.com`) to it for a professional look.

---

Built for the Appalachian Sniper Series. Scores & registration powered by Impact Scoring.
