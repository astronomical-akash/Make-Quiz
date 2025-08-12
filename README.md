# CGL Science Quiz – Static Site

This is a pure HTML/CSS/JS app that loads a question bank from CSV.

## Quick Deploy

### GitHub Pages
1. Create a new repo, e.g. `cgl-quiz`.
2. Put these files at the repo root (ensure `index.html` is at top level).
3. In **Settings → Pages**, choose **Deploy from a branch** → Branch: `main`, Folder: **root**.
4. Open `https://<your-username>.github.io/cgl-quiz/`.

Optional: for a custom domain, add it in Pages settings and create a CNAME DNS record. Include a `CNAME` file with your domain in the repo root.

### Netlify (drag‑and‑drop)
1. Go to https://app.netlify.com → **Add new site** → **Deploy manually**.
2. Drag this folder or upload the ZIP.
3. Done. You can add a custom domain and get HTTPS automatically.

### Vercel (from Git)
1. Push the folder to GitHub/GitLab/Bitbucket.
2. Import into Vercel → Framework Preset: **Other** → Root Directory: `/`.
3. Deploy. Configure your domain in Vercel.

## Files
- `index.html` – the entire app (Tailwind CDN + Papa Parse CDN).
- `samples/` – sample & template files:
  - `science-quiz-sample.csv`
  - `CGL_Quiz_Template.xlsx` (blank with dropdowns)
  - `CGL_Quiz_Sample.xlsx` (prefilled examples)
  - `CGL_Quiz_Template.csv` (header-only)
