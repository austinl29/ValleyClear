# Valley Clear Analytics — Portfolio Page

A standalone project page showcasing the Valley Clear marketing analytics dashboard (real data) and the Q3 2026 growth projection (modeled data), built in Splunk.

## What's in this folder
- `index.html` — the full page (self-contained, styles included)
- `images/` — 5 cleaned dashboard screenshots (Windows watermark removed)

## Setting up the new repo

1. Go to **github.com** → click the **+** icon (top right) → **New repository**
2. Name it something like `valley-clear-dashboard` (this becomes part of your live URL)
3. Set it to **Public** (private repos don't support free GitHub Pages)
4. Don't initialize with a README (you're uploading your own files) → **Create repository**
5. On the new repo's page, click **uploading an existing file**
6. Drag in `index.html` and the entire `images` folder (make sure the folder structure stays intact — `images/01-arizona-top.png`, etc.)
7. Commit the files

## Turning on GitHub Pages

1. In your new repo, go to **Settings** → **Pages** (left sidebar)
2. Under "Build and deployment" → Source: **Deploy from a branch**
3. Branch: **main**, folder: **/ (root)** → **Save**
4. Wait 1-2 minutes, then your page will be live at:
   ```
   https://austinl29.github.io/valley-clear-dashboard/
   ```
   (replace `valley-clear-dashboard` with whatever you actually named the repo in step 2)

## Important: update your resume link

Your resumes currently point to:
```
https://austinl29.github.io/Personal-Profile/valley-clear-dashboard
```

Once this new repo is live, that link needs to change to match your actual new repo's URL (e.g. `https://austinl29.github.io/valley-clear-dashboard/`). Let me know the final repo name once you've created it and I'll update all three resume files to match — otherwise the link on your resume will 404.

## One thing to double check

The "Projected" dashboard screenshots still show the old title **"Valley Clear — Projected next 2 months"** rather than the final "Projected Rest of 2026" name. The page copy doesn't repeat that title directly, so it's not a glaring mismatch, but if you want it fully consistent, re-screenshot just that dashboard's title bar (same crop rules — no browser chrome, no sidebar) and I'll swap the image in.
