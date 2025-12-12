# Deployment Instructions

## Step 1: Create New GitHub Repository

1. Go to https://github.com/new
2. Repository name: `Works_Council` (or any name you prefer)
3. **DO NOT** initialize with README, .gitignore, or license
4. Click "Create repository"

## Step 2: Connect and Push

After creating the repository, run these commands (replace `<repo-name>` with your actual repository name):

```bash
git remote add origin https://github.com/tsaroglou/<repo-name>.git
git branch -M main
git push -u origin main
```

## Step 3: Enable GitHub Pages

1. Go to your repository on GitHub
2. Click **Settings** → **Pages** (left sidebar)
3. Under "Source":
   - Select **Deploy from a branch**
   - Branch: **main**
   - Folder: **/ (root)**
4. Click **Save**

## Step 4: Wait and Test

- Wait 1-2 minutes for GitHub Pages to build
- Visit: `https://tsaroglou.github.io/<repo-name>/`
- The `.nojekyll` file is already included to ensure HTML files are served correctly

Your site should now be live!

