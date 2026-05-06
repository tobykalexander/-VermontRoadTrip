# Vermont Road Trip 🗺️

A driving guide & map for our 3-day trip from Ballwin, MO → Colchester, VT.

## How to deploy

### Option 1 — Drag & Drop (easiest, no account changes needed)
1. Go to **[vercel.com/new](https://vercel.com/new)**
2. Drag this entire folder onto the page
3. Click **Deploy** — done in ~10 seconds

### Option 2 — From your phone
1. Open the **Files app** and find this folder
2. Long-press → **Compress** to make a ZIP
3. Email/AirDrop to your computer, then drag onto vercel.com/new

### Option 3 — Upload to GitHub (then auto-deploy to Vercel)
1. Go to **[github.com/new](https://github.com/new)** and create a new repo
2. Use the **"uploading an existing file"** link to upload `index.html` and `vercel.json`
3. In Vercel, click **Add New Project** → import your GitHub repo
4. Future edits pushed to GitHub auto-deploy to Vercel ✨

### Option 4 — Vercel CLI (for developers)
```bash
npx vercel
```
Run from inside this folder. Follow the prompts — first time will create a project, subsequent runs deploy updates.

## Files
- `index.html` — the entire site (all CSS/JS embedded)
- `vercel.json` — tells Vercel to serve it as a static page
