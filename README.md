# UC Student Services Agent Site

GitHub Pages-ready website for a University of California Student Services Agent built with Azure AI Foundry, custom web grounding, and Foundry Work IQ guidance.

## Local preview

Open `index.html` directly in a browser.

## Deploy to GitHub Pages

1. Create a new GitHub repository.
2. Push this folder to `main` (or `master`).
3. In GitHub: **Settings > Pages > Source = GitHub Actions**.
4. The included workflow (`.github/workflows/deploy-pages.yml`) deploys automatically on push.

## Optional CLI publish

```powershell
git init
git add .
git commit -m "Initial UC student services agent site"
gh repo create uc-student-services-agent-site --public --source . --remote origin --push
```
