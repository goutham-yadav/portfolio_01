# Personal Portfolio

This repository contains a static HTML portfolio (`index.html`, `style.css`, `script.js`).

## Deploy to GitHub Pages (Step-by-step)

### 1) Push this repository to GitHub
1. Create a new GitHub repository (for example: `portfolio_01`).
2. In this local project, add your remote:
   ```bash
   git remote add origin https://github.com/<your-username>/portfolio_01.git
   ```
3. Push your branch:
   ```bash
   git push -u origin work
   ```
   > If your default branch is `main`, you can push there instead.

### 2) Choose a publishing method
GitHub Pages can publish from either:
- **Branch** (simple static sites)
- **GitHub Actions** (more control)

For this project, branch publishing is easiest.

### 3) Enable GitHub Pages from the repository branch
1. Open your repository on GitHub.
2. Go to **Settings** → **Pages**.
3. Under **Build and deployment**, set:
   - **Source**: `Deploy from a branch`
   - **Branch**: `main` (or whichever branch contains `index.html`)
   - **Folder**: `/ (root)`
4. Click **Save**.

### 4) Wait for deployment
1. GitHub will start a Pages deployment.
2. After a minute or two, refresh **Settings** → **Pages**.
3. You should see the live URL.

### 5) Open your live site
- If this is a **project repo** named `portfolio_01`, the URL is usually:
  `https://<your-username>.github.io/portfolio_01/`
- If this is a **user site repo** named `<your-username>.github.io`, the URL is:
  `https://<your-username>.github.io/`

### 6) Update and redeploy
Any time you push updates to the published branch, GitHub Pages redeploys automatically.

## Optional: Custom domain
1. In **Settings** → **Pages**, add your domain under **Custom domain**.
2. Update DNS records with your domain provider.
3. Enable **Enforce HTTPS** after DNS is configured.
