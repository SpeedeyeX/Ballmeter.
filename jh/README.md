# jh

Static site with `index.html`, `script.js`, and `style.css`.

## Deploy

This repository is configured to deploy to GitHub Pages via GitHub Actions when you push to the `main` branch.

To create a GitHub repo and push manually:

1. Create an empty repository on GitHub.
2. Run the following commands locally:

```bash
git remote add origin https://github.com/<your-username>/<repo>.git
git branch -M main
git push -u origin main
```

Or, if you have the GitHub CLI installed and authenticated, run:

```bash
gh repo create --public --source=. --remote=origin --push --confirm
```
