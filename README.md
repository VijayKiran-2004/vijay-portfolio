# Vijay Kiran Kesanapalli — Portfolio

This repository contains a static portfolio site (HTML/CSS/JS). It can be hosted on GitHub Pages or any static hosting provider.

To preview locally:

1. Start a simple HTTP server from the project root (Windows PowerShell):

```powershell
cd "C:\Users\vijay\vijay portfolio"
python -m http.server 8000

# Then open http://localhost:8000 in your browser
```

Deployment notes (GitHub Pages):

- I included a GitHub Actions workflow `.github/workflows/deploy.yml` which publishes the repository root to the `gh-pages` branch on push to `main`.
- After creating a remote repo on GitHub, push your `main` branch and Actions will run to publish the site.

If you'd like, I can initialize the repo locally and help push it to GitHub.
