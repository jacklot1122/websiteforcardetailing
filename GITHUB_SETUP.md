# GitHub Repository Setup

## Step 1: Create Repository on GitHub

1. Go to https://github.com/new
2. Repository name: `TW-AutoDetailing-Website`
3. Description: `Professional auto detailing website for T&W Auto Detailing - Central Coast & Hunter Area`
4. Choose: Public or Private
5. **DO NOT** initialize with README, .gitignore, or license (we already have these)
6. Click "Create repository"

## Step 2: Push to GitHub

After creating the repository, run these commands:

```bash
cd ~/Desktop/TW-AutoDetailing-Website

# Add GitHub as remote (replace YOUR_USERNAME with your GitHub username)
git remote add origin https://github.com/YOUR_USERNAME/TW-AutoDetailing-Website.git

# Push to GitHub
git branch -M main
git push -u origin main
```

## Step 3: Deploy to Vercel

After pushing to GitHub:

1. Go to https://vercel.com
2. Sign in with GitHub
3. Click "Add New" → "Project"
4. Import your GitHub repository
5. Click "Deploy"

Done! Your site will be live on Vercel! 🚀

## Alternative: Use GitHub Desktop

1. Download GitHub Desktop from https://desktop.github.com
2. Open GitHub Desktop
3. File → Add Local Repository
4. Select the TW-AutoDetailing-Website folder
5. Click "Publish repository"
6. Choose public/private and publish

---

**Current Status:**
✓ Git repository initialized
✓ All files committed
✓ Ready to push to GitHub

**Repository Info:**
- Branch: main
- Files: 27 files
- Commit: Initial commit with complete website
