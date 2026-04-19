# Channel 5.0 Website

Two-page site: Landing (index.html) + Dashboard/Leaderboard (dashboard.html)

## File Structure
```
channel5/
├── index.html         ← Landing page
├── dashboard.html     ← Leaderboard + referral dashboard
├── assets/
│   ├── 2726.png       ← Your NFT art (rename from uploads)
│   ├── 525.png
│   ├── 1365.png
│   └── 2545.png
└── README.md
```

## Add Your Art
Copy your 4 NFT images (2726.png, 525.png, 1365.png, 2545.png) into an `assets/` folder.
The site references them automatically. If missing, placeholders show instead.

## FREE Deployment Options

### Option 1: Vercel (Recommended — easiest)
1. Go to vercel.com → sign up free
2. Drag and drop the channel5/ folder
3. Done — live URL in 30 seconds

### Option 2: GitHub Pages (Free forever)
1. Create a GitHub account (free)
2. New repo → name it `channel5`
3. Upload all files
4. Settings → Pages → Deploy from main branch
5. Your site: username.github.io/channel5

### Option 3: Netlify (Free)
1. Go to netlify.com
2. Drag the channel5/ folder into the deploy box
3. Live instantly

## Custom Domain ($0 extra on Vercel/Netlify with free DNS)
- Buy domain on Namecheap (~$10/yr) or use a free .xyz on Freenom
- Point nameservers to Vercel/Netlify
- HTTPS included free

## TODO (Backend for real leaderboard)
The leaderboard currently uses demo data. For a real live leaderboard:
- Free option: Supabase (free tier) — Postgres + REST API
- Store: wallet, username, points, referrals, invite_code
- Update points when tasks are verified
- This can be added later without changing the frontend design
