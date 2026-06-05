# FORDIA Industrial Solutions - Official Website

This repository contains the official corporate website for **FORDIA Industrial Solutions**, a leading manufacturer of sheetfed offset printing inks, flexo inks, screen inks, varnishes, printing spare parts, and chemicals.

## 🚀 Deployment Instructions for GitHub Pages

This is a fully static website. You can host it directly on **GitHub Pages** for free.

1. Create a new repository on GitHub (e.g., `fordia-website`).
2. Initialize this `dist/` directory as a Git repository and push it to GitHub:
   ```bash
   git init
   git add .
   git commit -m "Initial commit of optimized site"
   git branch -M main
   git remote add origin https://github.com/YOUR_USERNAME/YOUR_REPOSITORY.git
   git push -u origin main
   ```
3. On GitHub, go to your repository **Settings** -> **Pages**.
4. Under **Build and deployment**, select **Deploy from a branch**.
5. Set the branch to `main` and directory to `/ (root)`.
6. Click **Save**. Within a few minutes, your site will be live at `https://YOUR_USERNAME.github.io/YOUR_REPOSITORY/`!

## ⚙️ Features & Optimizations Included
- **Offline Assets**: All external Google image links have been downloaded locally to `assets/images/` to prevent broken links due to Google Stitch link expiration.
- **Responsive Layout**: Cleared visualization editor viewport constraints (`width`, `height`, and scrolling locks) from `<html>`/`<body>` tags to ensure complete mobile-responsive behavior.
- **Search Engine Optimization (SEO)**: Tailored meta descriptions, responsive viewport tags, and Open Graph tags (for social share previews) are automatically injected on all 84 pages.
- **Search Engines Routing**: Configured standard `sitemap.xml` and `robots.txt` paths for Google search crawler indexing.
