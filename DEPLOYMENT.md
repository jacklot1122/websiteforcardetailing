# Vercel Deployment Instructions

## Quick Deploy

1. **Install Vercel CLI** (if not already installed):
   ```bash
   npm install -g vercel
   ```

2. **Deploy to Vercel**:
   ```bash
   cd ~/Desktop/TW-AutoDetailing-Website
   vercel
   ```

3. **Follow the prompts**:
   - Set up and deploy: Y
   - Which scope: Select your account
   - Link to existing project: N
   - Project name: tw-auto-detailing (or your choice)
   - Directory: ./ (just press enter)
   - Want to modify settings: N

## Alternative: Deploy via Vercel Website

1. Go to https://vercel.com
2. Sign in with GitHub/GitLab/Bitbucket or Email
3. Click "Add New" → "Project"
4. Import Git Repository or drag/drop the folder
5. Configure:
   - Framework Preset: Other
   - Root Directory: ./
   - Build Command: (leave empty)
   - Output Directory: (leave empty)
6. Click "Deploy"

## Custom Domain (Optional)

After deployment, you can add a custom domain:
1. Go to your project settings in Vercel
2. Navigate to "Domains"
3. Add your domain (e.g., twautodetailing.com)
4. Follow DNS configuration instructions

## Files Ready for Deployment

✓ vercel.json - Vercel configuration
✓ .gitignore - Ignore unnecessary files
✓ README.md - Project documentation
✓ All HTML, CSS, JS, and image files optimized

Your site is ready to deploy! 🚀
