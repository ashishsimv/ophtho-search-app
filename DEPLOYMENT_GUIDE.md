# 🚀 GitHub Pages Deployment Guide

Follow these steps to deploy your Ophthalmology Search Tool on GitHub Pages:

## Step 1: Create a GitHub Repository

1. Go to [GitHub.com](https://github.com)
2. Click the "+" icon in the top right corner
3. Select "New repository"
4. Name your repository (e.g., `ophtho-search-app`)
5. Add a description: "Web-based ophthalmology reference search tool"
6. Choose "Public" (required for free GitHub Pages)
7. Click "Create repository"

## Step 2: Upload Your Files

### Option A: Using GitHub Web Interface (Easiest)

1. In your new repository, click "uploading an existing file"
2. Drag and drop all files from the `ophtho-search-app` folder:
   - `index.html`
   - `README.md`
   - `.gitignore`
3. Click "Commit changes"

### Option B: Using Git Command Line

If you have Git installed:

```bash
cd ophtho-search-app
git init
git add .
git commit -m "Initial commit: Ophthalmology search tool"
git branch -M main
git remote add origin https://github.com/YOUR-USERNAME/ophtho-search-app.git
git push -u origin main
```

Replace `YOUR-USERNAME` with your actual GitHub username.

## Step 3: Enable GitHub Pages

1. In your repository, click on "Settings" (top menu)
2. Scroll down to find "Pages" in the left sidebar
3. Under "Source", select "Deploy from a branch"
4. Under "Branch", select "main" and folder "/ (root)"
5. Click "Save"

## Step 4: Access Your Live App

1. Wait 1-2 minutes for GitHub to build your site
2. Your app will be live at:
   ```
   https://YOUR-USERNAME.github.io/ophtho-search-app/
   ```
3. GitHub will show you the URL in the Pages settings

## Step 5: Share Your App

Now you can share your live URL with colleagues, students, or anyone who needs ophthalmology reference search!

### Custom Domain (Optional)

If you have a custom domain:
1. Go to Pages settings
2. Add your custom domain under "Custom domain"
3. Configure DNS settings as per GitHub's instructions

## Troubleshooting

**Problem**: Page shows 404 error
- **Solution**: Wait a few minutes and refresh. GitHub Pages can take up to 10 minutes to deploy.

**Problem**: Changes not showing up
- **Solution**: Clear your browser cache or do a hard refresh (Ctrl+F5 or Cmd+Shift+R)

**Problem**: Repository not showing Pages option
- **Solution**: Make sure your repository is Public, not Private

## Updating Your App

To make changes later:
1. Edit the files in your repository
2. Commit the changes
3. GitHub Pages will automatically rebuild (takes 1-2 minutes)

---

## Quick Summary

1. ✅ Create GitHub repository
2. ✅ Upload `index.html`, `README.md`, `.gitignore`
3. ✅ Go to Settings → Pages
4. ✅ Select "main" branch and "/ (root)" folder
5. ✅ Wait 1-2 minutes
6. ✅ Share your URL: `https://YOUR-USERNAME.github.io/REPO-NAME/`

Need help? Check [GitHub Pages Documentation](https://docs.github.com/en/pages)
