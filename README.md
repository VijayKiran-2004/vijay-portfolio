# Vijay Kiran Kesanapalli — Portfolio

This repository contains a static portfolio site (HTML/CSS/JS). It can be hosted on GitHub Pages or any static hosting provider.

To preview locally:

1. Start a simple HTTP server from the project root (example using Python 3):

```bash
cd /path/to/vijay-portfolio
python -m http.server 8000

# Then open http://localhost:8000 in your browser
```

How to deploy (GitHub Pages via Actions)

- This repo now includes a workflow at `.github/workflows/deploy.yml` that packages the repository root into a `public/` artifact and deploys it to GitHub Pages whenever you push to `main`.
- Steps to publish the site:

	1. Create a repository on GitHub (if you haven't already).
	2. Add the remote and push your `main` branch:

```bash
git remote add origin git@github.com:<your-username>/<your-repo>.git
git add .
git commit -m "Add site and Pages deployment workflow"
git push -u origin main
```

	3. After push, go to the GitHub repository Actions tab — the "Deploy static site to GitHub Pages" workflow should run. When it finishes, GitHub Pages will publish the `public/` artifact and provide a site URL.

	4. You can also open the Pages settings page to see the published site URL and custom domain settings: `https://github.com/<your-username>/<your-repo>/settings/pages`.

Notes & alternatives

- If you prefer a managed platform with previews and continuous deploys (no workflow needed), Netlify or Vercel both work great for static HTML sites. I can add a `netlify.toml` or create a Vercel config for you and optionally perform the first deploy.
- If you'd like, I can push these changes to the repository for you from this environment (if you provide permission / the appropriate git credentials are available), or I can give step-by-step help to push from your machine.

If you'd like me to continue, tell me whether you want me to:

1. Push these changes to GitHub now from this environment (I will run git commands), or
2. Walk you through pushing from your machine, or
3. Set up Netlify/Vercel config instead.
