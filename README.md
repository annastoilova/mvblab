# MVB Lab — LinkedIn Module

## Deploy to Vercel

### Option 1: Drag and drop (fastest)
1. Go to vercel.com/new
2. Drag this entire folder into the deploy window
3. Vercel auto-detects the static site — click Deploy
4. Connect your custom domain in Project Settings → Domains

### Option 2: GitHub (recommended for updates)
1. Push this folder to a GitHub repo
2. Import the repo at vercel.com/new
3. Vercel detects it as a static site automatically — no build settings needed
4. Connect your custom domain in Project Settings → Domains

## Files
- `index.html` — the full LinkedIn module (all 6 lessons, gating, interactive builder)
- `vercel.json` — deployment config with security headers
- `README.md` — this file

## Notes
- No API key required — the module is pure HTML/CSS/JS
- No build step required — deploys as a static site
- The premium password is hardcoded in the JS — to change it, find `const PW = '...'` near the bottom of index.html and update the value
- The Skool upgrade link points to skool.com/mvb — update if your URL changes

## Custom Domain
In Vercel: Project → Settings → Domains → Add your domain
Vercel provides free SSL automatically.
