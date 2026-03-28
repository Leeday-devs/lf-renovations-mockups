# LF Renovations — Mockup Preview (GitHub Pages)

GitHub **does not render HTML files as a “real website”** when you click them in the repo. To let a customer view these
mockups properly in a browser, deploy them with **GitHub Pages**.

## What’s in this folder

- `index.html` — landing page that links to all 4 mockups
- `lf-mockup-1-luxury.html`
- `lf-mockup-2-modern.html`
- `lf-mockup-3-fresh.html`
- `lf-mockup-4-warm.html`

## Option 1 (easiest): Upload to GitHub + enable Pages

1. Create a new GitHub repository (public is simplest for client viewing).
2. Upload these files (`index.html` + the 4 mockup files) to the repo root.
3. In the repo go to **Settings → Pages**.
4. Under **Build and deployment**, choose:
   - **Source:** Deploy from a branch
   - **Branch:** `main` (or `master`)
   - **Folder:** `/ (root)`
5. Wait for the deployment to finish.

Then share:

- `https://YOUR-USERNAME.github.io/YOUR-REPO/`

Your customer can open each mockup from the landing page.

## Option 2: GitHub Desktop (if you prefer)

1. Create a new repo in GitHub Desktop and put these files in it.
2. Publish the repository to GitHub.
3. Enable GitHub Pages the same way as Option 1.

