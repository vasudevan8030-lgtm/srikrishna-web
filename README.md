# Sri Krishna Cabs - Static Website

This folder contains the complete, standalone static website for **Sri Krishna Cabs** ([srikrishnacabs.in](https://srikrishnacabs.in)), ready to be hosted on **GitHub Pages** or any static hosting service (Cloudflare Pages, Netlify, Vercel).

## 📁 Directory Structure
```
srikrishnacabs-website/
├── index.html       # Complete website with hero carousel, fleet, services, team, gallery & contact
├── CNAME            # Custom domain configuration (srikrishnacabs.in)
├── README.md        # Instructions
└── images/          # All image assets
    ├── logo1.jpg
    ├── logo.jpg
    ├── sedan.jpg
    ├── innova.jpg
    ├── van.jpg
    ├── driver11_1.jpg
    ├── driver21_1.jpg
    └── driver31_1.jpg
```

## 🚀 How to Host on GitHub Pages

1. **Initialize Git inside this folder:**
   ```bash
   cd srikrishnacabs-website
   git init
   git add .
   git commit -m "Initial commit for Sri Krishna Cabs static website"
   ```

2. **Create a new repository on GitHub** (e.g. `srikrishnacabs` or `srikrishnacabs.github.io`).

3. **Link and push to GitHub:**
   ```bash
   git branch -M main
   git remote add origin https://github.com/<your-username>/<repo-name>.git
   git push -u origin main
   ```

4. **Enable GitHub Pages:**
   - Go to your repository on GitHub.
   - Click **Settings** > **Pages**.
   - Under **Source**, select `Deploy from a branch`.
   - Choose `main` branch and `/ (root)` folder, then click **Save**.
   - If using custom domain `srikrishnacabs.in`, ensure the Custom domain field shows `srikrishnacabs.in` and check **Enforce HTTPS**.
