# Setup Guide

## ✅ Completed Steps

- ✅ Project structure created
- ✅ All pages implemented
- ✅ Git repository initialized
- ✅ Initial commit created

## 📋 Next Steps

### 1. Install Node.js (if not already installed)

Download and install Node.js from [nodejs.org](https://nodejs.org/) (LTS version recommended).

After installation, verify it works:
```bash
node --version
npm --version
```

### 2. Install Dependencies

Once Node.js is installed, run:
```bash
npm install
```

### 3. Test Locally (Optional)

Run the development server to preview the site:
```bash
npm run dev
```

Then open [http://localhost:3000](http://localhost:3000) in your browser.

### 4. Create GitHub Repository

1. Go to [GitHub](https://github.com) and sign in
2. Click the "+" icon in the top right → "New repository"
3. Name your repository (e.g., `itu-works-council-site`)
4. **Don't** initialize with README, .gitignore, or license (we already have these)
5. Click "Create repository"

### 5. Push to GitHub

After creating the repository, GitHub will show you commands. Use these (replace `<your-username>` and `<repo-name>`):

```bash
git remote add origin https://github.com/<your-username>/<repo-name>.git
git branch -M main
git push -u origin main
```

### 6. Enable GitHub Pages

1. Go to your repository on GitHub
2. Click **Settings** → **Pages** (in the left sidebar)
3. Under "Source", select:
   - **Branch**: `main`
   - **Folder**: `/ (root)` or `/out` (depending on your setup)
4. Click **Save**

Alternatively, the GitHub Actions workflow (`.github/workflows/deploy.yml`) will automatically deploy when you push to the `main` branch.

### 7. Customize Content

Edit the files in the `app/` directory to replace placeholder content with your actual information:
- `app/who-we-are/page.tsx` - Contact information
- `app/media-events/page.tsx` - Blog posts
- `app/announcements/page.tsx` - Announcements
- `app/reports/page.tsx` - Reports
- `app/surveys/page.tsx` - Surveys

## 🎉 You're All Set!

Your site will be available at:
- `https://<your-username>.github.io/<repo-name>` (if using GitHub Pages)
- Or the custom domain you configure

