# 🚀 Deployment Guide

## Quick GitHub Pages Setup

### 1. Create GitHub Repository
```bash
# On GitHub.com
1. Click "New repository"
2. Name: "nubank-time-savings-calculator"
3. Description: "Time savings calculator for automation impact measurement"
4. Make it Public
5. Don't initialize with README (we have one)
```

### 2. Upload Files
```bash
# In your terminal (from project folder)
git init
git add .
git commit -m "Initial commit: Nubank Time Savings Calculator"
git branch -M main
git remote add origin https://github.com/YOUR-USERNAME/nubank-time-savings-calculator.git
git push -u origin main
```

### 3. Enable GitHub Pages
```bash
# On GitHub.com
1. Go to repository Settings
2. Scroll to "Pages" section
3. Source: "Deploy from a branch"
4. Branch: "main" / root
5. Click Save
```

### 4. Get Your Link
Your calculator will be available at:
```
https://YOUR-USERNAME.github.io/nubank-time-savings-calculator
```

## Alternative: Netlify Deployment

### Option 1: Drag & Drop
1. Go to [netlify.com](https://netlify.com)
2. Drag the entire project folder to Netlify
3. Get instant link: `https://random-name.netlify.app`

### Option 2: Git Integration
1. Push to GitHub first
2. Connect Netlify to your GitHub repo
3. Auto-deploy on every update

## File Structure
```
nubank-time-savings-calculator/
├── index.html              # Main calculator page
├── assets/
│   └── nubank-logo.svg    # Nubank official logo
├── README.md              # Project documentation
├── DEPLOY.md             # This deployment guide
└── .gitignore            # Git ignore rules
```

## Custom Domain (Optional)
If you want a custom domain like `calculator.nubank.com`:
1. Contact Nubank IT team
2. They can set up CNAME records
3. Configure in GitHub Pages settings

## Sharing the Calculator
Once deployed, share with teams using:
- Direct link in Slack/Teams
- QR code for mobile access
- Bookmark in company wiki
- Include in automation documentation

## Updates
To update the calculator:
1. Make changes to `index.html`
2. Commit and push to GitHub
3. GitHub Pages auto-updates in ~1 minute
4. Share the same link - no changes needed!
