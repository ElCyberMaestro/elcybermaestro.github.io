# Quick Start Checklist

Follow these steps to get your portfolio site live in under 30 minutes.

## Pre-Setup (5 minutes)

- [ ] Have your GitHub username ready
- [ ] Have your LinkedIn profile URL ready
- [ ] Have your email ready for contact info

## Step 1: Update Files (10 minutes)

### Update `_config.yml`
- [ ] Replace `YOUR_GITHUB_USERNAME` with your actual username
- [ ] Replace `YOUR_LINKEDIN_USERNAME` with your LinkedIn username

### Update `index.md`
- [ ] Update GitHub link (line 40)
- [ ] Update LinkedIn link (line 41)
- [ ] Update email address (line 42)

### Update `about.md`
- [ ] Add your professional background (line 9)
- [ ] Update GitHub link (line 61)
- [ ] Update LinkedIn link (line 62)
- [ ] Update email address (line 63)

## Step 2: Create GitHub Repository (5 minutes)

1. [ ] Go to [GitHub](https://github.com/new)
2. [ ] Repository name: `YOUR_USERNAME.github.io` (use your actual username)
3. [ ] Set to **Public**
4. [ ] Do NOT check "Add a README file"
5. [ ] Click **Create repository**

## Step 3: Push to GitHub (5 minutes)

Open Terminal and run these commands from the `portfolio-site` folder:

```bash
cd portfolio-site
git init
git add .
git commit -m "Initial portfolio site"
git branch -M main
git remote add origin https://github.com/YOUR_USERNAME/YOUR_USERNAME.github.io.git
git push -u origin main
```

Replace `YOUR_USERNAME` with your actual GitHub username in the URL.

## Step 4: Enable GitHub Pages (2 minutes)

1. [ ] Go to your repository on GitHub
2. [ ] Click **Settings** (top right)
3. [ ] Click **Pages** (left sidebar)
4. [ ] Under "Source": select **main** branch
5. [ ] Click **Save**

## Step 5: Verify (3 minutes)

- [ ] Wait 1-2 minutes
- [ ] Visit: `https://YOUR_USERNAME.github.io`
- [ ] Your site should be live!

## Troubleshooting

**If site doesn't load:**
1. Verify repository name is exactly: `yourusername.github.io`
2. Make sure repository is public
3. Check Settings → Pages shows "Your site is live at..."
4. Wait up to 5 minutes for initial deployment

**If you see errors:**
- Go to repository → Actions tab to see build logs
- Check that all files were pushed with `git status`

## Next Steps

After your site is live:

- [ ] Share the link on LinkedIn
- [ ] Add link to your resume
- [ ] Set up weekly Friday updates (30 min/week)
- [ ] Add project pages as you complete projects (Weeks 5-10)

---

**Need help?** Check `README.md` or `website_setup_guide.md` for detailed instructions.
