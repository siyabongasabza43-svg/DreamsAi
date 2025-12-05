# Dreams AI — Ecom Store Audit (Static Site)

This repo contains a single-page static site (index.html) built with Tailwind CDN. The page includes a mock client-side form (no server endpoint configured). Replace the form submission TODO with your webhook or Google Form action.

How to use / deploy
1. Locally
   - Open `index.html` in your browser.

2. GitHub Pages (recommended simple option)
   - Push these files to a GitHub repo (e.g. `owner/repo`).
   - In the repository Settings → Pages, set source to the `main` branch (root) or `gh-pages` branch.
   - The site will be available at `https://<owner>.github.io/<repo>/` (or your custom domain if configured).

3. Quick deploy with Git (example)
   ```bash
   git init
   git add index.html README.md
   git commit -m "Add Dreams AI static site"
   # create a remote repo on GitHub (or use the web UI)
   git remote add origin git@github.com:OWNER/REPO.git
   git branch -M main
   git push -u origin main
   ```
   Replace OWNER/REPO with your repository.

4. Deploy with Netlify or Vercel
   - Drag-and-drop the site folder in Netlify, or connect the GitHub repo.
   - For Vercel, import the repo and select static site settings.

Customization
- Replace the client-side form handler's TODO with a webhook endpoint (Zapier, Make, or your server) to receive submissions.
- If you want post-submission PDF generation from an AI backend, I can help wire up a server endpoint or serverless function.

Next steps I can take for you
- Upload these files to a GitHub repository (I need the repository owner/name).
- Enable GitHub Pages (choose branch: `main` or `gh-pages`) so the site is live.
- Wire the form to a webhook (Zapier/Make) and confirm submissions.
- Add a basic GitHub Actions workflow to build/deploy if you prefer a build step.