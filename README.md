# Mahdi Ghaznawy Portfolio

This is a static portfolio website prepared for GitHub Pages.

## What is included

- `index.html`
- `styles.css`
- `script.js`
- `assets/Mahdi_Ghaznawy_Resume.pdf`
- `.nojekyll`

## How to publish on GitHub Pages

### Option 1: New repository
1. Create a new GitHub repository.
2. Upload all files from this folder to the root of the repository.
3. Go to **Settings** → **Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select the **main** branch and the **/(root)** folder.
6. Save.
7. Wait for GitHub Pages to publish the site.

### Option 2: Existing repository
1. Open your existing repository.
2. Delete the old website files from the root if needed.
3. Upload the contents of this package to the repository root.
4. In **Settings** → **Pages**, make sure deployment is set to **main** and **/(root)**.

## Notes

- This site has **no build step**.
- It does **not** depend on React, Vite, npm, or GitHub Actions.
- It is designed specifically to avoid the blank white screen issue caused by broken builds.
