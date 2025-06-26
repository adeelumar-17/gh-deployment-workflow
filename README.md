```markdown
# GitHub Pages Deployment with Actions

This project demonstrates how to automatically deploy a static website to **GitHub Pages** using **GitHub Actions**, but **only when `index.html` is changed**.

## 📄 Project Structure

- `index.html` — Simple HTML file with "Hello, GitHub Actions!" message.
- `.github/workflows/deploy.yml` — GitHub Actions workflow for deployment.
- `README.md` — Explains the setup and purpose.

## 🚀 How It Works

- The GitHub Actions workflow runs **only** when changes are pushed to the `main` branch **and** the `index.html` file is modified.
- When triggered, the workflow publishes the site to **GitHub Pages**.
- The site is accessible at:

```

https\://<username>.github.io/gh-deployment-workflow/

```

(Replace `<username>` with your actual GitHub username.)

## 🌐 Project Link

Official Project Page:  
🔗 [https://roadmap.sh/projects/github-actions-deployment-workflow](https://roadmap.sh/projects/github-actions-deployment-workflow)

## 🛠️ Setup Instructions

1. Create a new GitHub repo (e.g., `gh-deployment-workflow`).
2. Add a basic `index.html` file.
3. Add the `deploy.yml` workflow under `.github/workflows/`.
4. Enable GitHub Pages in repo settings:
   - Source: `Deploy from a branch`
   - Branch: `gh-pages`
5. Push changes to the `main` branch — if `index.html` is modified, deployment runs automatically.
```
