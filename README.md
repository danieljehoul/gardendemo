# Mali Vrtlari - Garden Landscaping Website

A professional garden landscaping service website for Mali Vrtlari.

## 🌿 About

Mali Vrtlari offers professional garden landscaping and maintenance services including:
- Garden landscaping
- Lawn maintenance
- Irrigation system installation
- Landscape planning
- Tree and flower planting

## 🚀 Deployment

This website is automatically deployed to GitHub Pages when changes are merged to the `main` branch.

### Automatic Deployment (Recommended)

1. **Merge your changes to the `main` branch**
   ```bash
   git checkout main
   git merge your-feature-branch
   git push origin main
   ```

2. **GitHub Actions will automatically deploy**
   - The deployment workflow is triggered on every push to `main`
   - View the deployment progress in the "Actions" tab of your repository
   - The site will be live at: `https://danieljehoul.github.io/gardendemo/`

3. **Manual trigger (if needed)**
   - Go to the "Actions" tab in your GitHub repository
   - Select the "Deploy to GitHub Pages" workflow
   - Click "Run workflow" and select the `main` branch

### First-Time Setup

To enable GitHub Pages for this repository:

1. Go to your repository settings: `https://github.com/danieljehoul/gardendemo/settings/pages`
2. Under "Build and deployment":
   - **Source**: Select "GitHub Actions"
3. Save the settings
4. Push a change to the `main` branch or manually trigger the workflow

### Manual Deployment (Alternative)

If you prefer to deploy manually without GitHub Actions:

1. **Using GitHub Pages directly**:
   - Go to repository Settings → Pages
   - Select "Deploy from a branch"
   - Choose the `main` branch and `/ (root)` folder
   - Save

2. **Using a different hosting provider**:
   - Simply upload all files (`index.html`, `assets/css/styles.css`, `robots.txt`, `sitemap.xml`) to your web hosting service
   - No build process is required as this is a static HTML website

## 📁 Project Structure

```
gardendemo/
├── index.html      # Main website page
├── assets/css/styles.css  # Styling
├── robots.txt      # SEO configuration
├── sitemap.xml     # Sitemap for search engines
├── assets/         # Static assets (images, CSS, JS, fonts)
│   ├── images/     # Image files
│   ├── css/        # Additional CSS files
│   ├── js/         # JavaScript files
│   ├── fonts/      # Custom fonts
│   └── README.md   # Assets documentation
└── .github/
    └── workflows/
        └── deploy.yml  # Automatic deployment configuration
```

## 🔧 Development

This is a static HTML website. To make changes:

1. **Edit the files locally**
   ```bash
   # Clone the repository
   git clone https://github.com/danieljehoul/gardendemo.git
   cd gardendemo
   
   # Make your changes
   # Edit index.html, assets/css/styles.css, etc.
   ```

2. **Preview your changes**
   - Open `index.html` in your web browser
   - Or use a local web server:
     ```bash
     python -m http.server 8000
     # Visit http://localhost:8000
     ```

3. **Commit and push your changes**
   ```bash
   git add .
   git commit -m "Description of your changes"
   git push origin your-branch-name
   ```

4. **Create a Pull Request**
   - Go to GitHub and create a PR to merge into `main`
   - Once merged, the site will automatically deploy

## 🌐 Live Website

After deployment, your website will be accessible at:
**https://danieljehoul.github.io/gardendemo/**

## 📝 Technologies Used

- HTML5
- CSS3
- Formspree (for contact form)

## 📄 License

© 2026 Mali Vrtlari. All rights reserved.



