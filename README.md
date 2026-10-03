# Survey Engineer & GIS Analyst Portfolio

This repository contains the static portfolio website for Ashan Pradeep (Survey Engineer, Land Surveyor, GIS Analyst & CAD Drafter).

## Deploying to GitHub Pages

To make sure your portfolio deploys correctly and renders properly on GitHub Pages, follow these steps in your GitHub repository:

### 1. Enable GitHub Actions for GitHub Pages
1. Go to your repository on GitHub.
2. Click on **Settings** (top tab).
3. In the left sidebar, click on **Pages** (under Code and automation).
4. Under **Build and deployment** -> **Source**, select **GitHub Actions**.

### 2. Deployment Workflow
- The automated deployment workflow is located in `.github/workflows/static.yml`.
- It triggers automatically whenever changes are pushed to the `main` or `master` branch, or when triggered manually via the **Actions** tab.
- A `.nojekyll` file is included in the root directory to prevent GitHub Pages from processing files with Jekyll, ensuring all static assets render as expected.
