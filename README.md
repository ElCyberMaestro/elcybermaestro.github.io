# Personal Portfolio Website

This is the source for my personal portfolio website hosted on GitHub Pages.

## Setup Instructions

### 1. Create GitHub Repository

1. Go to GitHub and create a new repository
2. Name it: `YOUR_GITHUB_USERNAME.github.io` (replace with your actual GitHub username)
3. Make it **public**
4. Do NOT initialize with README (we already have one)

### 2. Update Configuration

Before pushing, update these files with your information:

**File: `_config.yml`**
- Replace `YOUR_GITHUB_USERNAME` with your GitHub username
- Replace `YOUR_LINKEDIN_USERNAME` with your LinkedIn username

**File: `index.md`**
- Update GitHub, LinkedIn, and email links

**File: `about.md`**
- Update GitHub, LinkedIn, and email links
- Add your professional background in the "Background" section

### 3. Push to GitHub

```bash
cd portfolio-site
git init
git add .
git commit -m "Initial portfolio site setup"
git branch -M main
git remote add origin https://github.com/YOUR_GITHUB_USERNAME/YOUR_GITHUB_USERNAME.github.io.git
git push -u origin main
```

### 4. Enable GitHub Pages

1. Go to your repository on GitHub
2. Click **Settings** → **Pages**
3. Under "Source", select **main** branch
4. Click **Save**

Your site will be live at: `https://YOUR_GITHUB_USERNAME.github.io` (wait 1-2 minutes)

## Updating Your Site

### Weekly Blog Updates (Fridays)

1. Edit `blog.md` to add your weekly update
2. Commit and push:

```bash
git add blog.md
git commit -m "Add Week N blog update"
git push
```

### Adding Project Updates

1. Edit `projects.md` to update project status or add details
2. Add architecture diagrams to the `images/` folder
3. Update project links when GitHub repos are ready

### Adding Images

1. Place images in the `images/` folder
2. Reference them in markdown:

```markdown
![Architecture Diagram](/images/project1-architecture.png)
```

## Local Testing (Optional)

To preview changes locally before pushing:

```bash
# Install Jekyll (one-time)
gem install bundler jekyll
bundle init
bundle add jekyll

# Run local server
bundle exec jekyll serve

# View at: http://localhost:4000
```

## Changing Theme

To use a different Jekyll theme, edit `_config.yml`:

```yaml
# Choose one:
theme: jekyll-theme-minimal
theme: jekyll-theme-cayman
theme: jekyll-theme-slate
```

Browse themes at: https://pages.github.com/themes/

## Maintenance Schedule

- **Weekly (Fridays):** 30-minute blog update
- **As needed:** Update project pages when completing milestones
- **Week 10:** Final portfolio polish

## Resources

- [GitHub Pages Documentation](https://docs.github.com/en/pages)
- [Jekyll Documentation](https://jekyllrb.com/docs/)
- [Markdown Guide](https://www.markdownguide.org/)

## Troubleshooting

**Site not loading?**
- Check repository name is exactly: `yourusername.github.io`
- Verify repository is public
- Wait 2-5 minutes for initial deployment

**Images not showing?**
- Use absolute paths: `/images/photo.png`
- Ensure images are in the repository

**Build errors?**
- Check GitHub Actions tab for error logs
- Validate YAML syntax in `_config.yml`

---

For detailed setup guide, see: `website_setup_guide.md`
