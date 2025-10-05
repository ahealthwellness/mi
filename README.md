# Manifest Inkara (Mi) — Landing Site

**Purpose:** Fast, free deployment on Vercel or Netlify under your domain `manifestproject.io`.

## Deploy to Vercel
1) Create a new GitHub repo (e.g., `manifest-inkara-site`).
2) Add these files and push.
3) Go to vercel.com → New Project → Import the repo.
4) Build & deploy (defaults are fine).

## Map your domain
- In Vercel: Project → Settings → Domains → Add `manifestproject.io`.
- In your registrar (GoDaddy/Namecheap): set the DNS A/ALIAS/CNAME as instructed by Vercel (one-click).

## Netlify (alt.)
- Drag-and-drop the folder in Netlify → Set domain later.
- Or connect the GitHub repo; Netlify builds automatically.

## Customize
- Edit copy in `index.html`.
- Colors & spacing in `styles.css` (variables at top).
- Replace `/assets/og.jpg` and `/assets/mi.svg` if you have custom art.
- Update form endpoint in the Commission section.
