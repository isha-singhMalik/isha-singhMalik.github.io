# Security Research Portfolio - Isha Singh Malik

A modern, professional portfolio website showcasing security research, education, and achievements.

## 🚀 Quick Start

### Prerequisites
- Git installed on your computer
- GitHub account
- VS Code (optional but recommended)

### Setup Instructions

#### 1. Create GitHub Repository
1. Go to [github.com](https://github.com)
2. Click "+" → "New repository"
3. Name it: `your-github-username.github.io` (replace with YOUR actual username)
4. Set to **Public**
5. Do NOT check "Add a README"
6. Click "Create repository"

#### 2. Clone Repository Locally
Open terminal/Git Bash and run:
```bash
cd ~/Desktop  # or wherever you want to work
git clone https://github.com/your-username/your-username.github.io.git
cd your-username.github.io
```

#### 3. Add Portfolio Files
Copy all these files into your cloned folder:
- `index.html`
- `about.html`
- `research.html`
- `style.css`
- `script.js`
- `README.md`

#### 4. Push to GitHub
In terminal, run:
```bash
git add .
git commit -m "Initial portfolio launch"
git push origin main
```

(If you get an error about 'main' vs 'master', try: `git push origin master`)

#### 5. Enable GitHub Pages
1. Go to your repository on GitHub
2. Click "Settings" tab
3. Click "Pages" in left sidebar
4. Under "Source", select "main" branch (or "master")
5. Click "Save"
6. Wait 1-2 minutes
7. Visit: `https://your-username.github.io`

## ✏️ Customization Guide

### Essential Edits (Do These First!)

#### Update Contact Information
Open `index.html` and find the contact section (around line 158):

```html
<!-- EDIT THIS: Add your actual contact details -->
<a href="mailto:your.email@example.com">  <!-- Change to YOUR email -->
<a href="https://linkedin.com/in/yourprofile">  <!-- Change to YOUR LinkedIn -->
<a href="https://youtube.com/@yourchannel">  <!-- Change to YOUR YouTube -->
<a href="https://github.com/yourusername">  <!-- Change to YOUR GitHub -->
```

#### Add Your Content (Optional Updates)

##### To add your Udemy/EC-Council course links:
Edit `about.html` - add links in the relevant sections

##### To add your book details:
Edit `about.html` - add information in the "Published author" section

##### To add more case studies:
Edit `research.html` - copy one of the existing `.case-study` sections and modify

##### To update statistics:
Edit `index.html` - find `.hero-stats` section and update numbers

### How to Make Changes Later

#### Option A: Edit on GitHub Website
1. Go to your repository on github.com
2. Click on the file you want to edit
3. Click the pencil icon (Edit)
4. Make your changes
5. Scroll down, add commit message
6. Click "Commit changes"
7. Wait 1-2 minutes, refresh your site

#### Option B: Edit Locally (Better for Multiple Changes)
1. Open your portfolio folder in VS Code
2. Make changes to files
3. Save files
4. Open terminal in VS Code (Ctrl + `)
5. Run these commands:
```bash
git add .
git commit -m "Updated bio and added new case study"
git push
```

## 📁 File Structure

```
portfolio/
├── index.html       # Homepage with hero section
├── about.html       # Detailed about page
├── research.html    # Research case studies
├── style.css        # All styling
├── script.js        # Interactive elements
└── README.md        # This file
```

## 🎨 Design Features

- **Modern & Bold Design** - Eye-catching gradients and animations
- **Fully Responsive** - Works on mobile, tablet, and desktop
- **Fast Loading** - Optimized CSS and minimal JavaScript
- **Accessible** - Semantic HTML and keyboard navigation
- **Professional** - Showcases your work in the best light

## 🔧 Common Issues & Solutions

### Problem: Changes aren't showing on the website
**Solution**: 
- Wait 1-2 minutes after pushing
- Hard refresh browser: Ctrl+Shift+R (Windows) or Cmd+Shift+R (Mac)
- Clear browser cache

### Problem: "Permission denied" when pushing
**Solution**: 
- Make sure you're authenticated with GitHub
- Try: `git config --global user.email "your-github-email@example.com"`
- May need to set up SSH keys or Personal Access Token

### Problem: Website shows 404 error
**Solution**:
- Make sure GitHub Pages is enabled in repository settings
- Check that your repository is named correctly: `username.github.io`
- Verify files are in the root folder, not in a subfolder

## 📝 Adding New Content

### To Add a New Research Case Study:
1. Open `research.html`
2. Copy an existing `<div class="case-study">...</div>` block
3. Paste it where you want the new case study
4. Update all the content:
   - Title
   - Date
   - Severity tag
   - Description
   - CVEs
   - Impact
5. Save and push to GitHub

### To Update Your Stats/Numbers:
1. Open `index.html`
2. Find the `<div class="hero-stats">` section
3. Update the numbers in `<div class="stat-number">`
4. Save and push

## 🌐 Connecting Business Website (When Ready)

When your business website is ready:

1. Open `index.html` and `about.html`
2. Find this line:
```html
<p>Professional services website coming soon</p>
```
3. Replace with:
```html
<a href="https://your-business-site.com" class="btn btn-primary">Visit Business Website</a>
```

## 🎓 Adding New Achievements

As you accomplish more:
- Update stats in hero section
- Add to credentials list
- Create new research case studies
- Update about page with new courses/trainings

## 📱 Social Media Integration

Your portfolio already has placeholders for:
- Email
- LinkedIn
- YouTube
- GitHub

Just update the `href` values in the contact section!

## 💡 Tips for Success

1. **Keep it updated** - Add new research findings regularly
2. **Professional photos** - Consider adding your headshot to About page
3. **Share widely** - Link to portfolio from LinkedIn, resume, email signature
4. **SEO friendly** - Good meta descriptions already included
5. **Mobile first** - Always test on phone after changes

## 🚀 Going Further

Want to enhance your portfolio?

**Easy additions:**
- Add your photo to About page
- Link to your published book
- Embed YouTube videos
- Add testimonials section

**Advanced additions:**
- Custom domain name ($10-15/year)
- Google Analytics tracking
- Contact form integration
- Blog section for writeups

## 📞 Support

If you need help:
1. Check "Common Issues" section above
2. Search GitHub documentation
3. Ask in developer communities
4. Review your Git/GitHub basics

## 🎉 You're All Set!

Your portfolio is now live and ready to impress!

Remember:
- Update regularly with new findings
- Keep content professional
- Share your portfolio URL everywhere
- Use it to land opportunities

---

**Portfolio for:** Isha Singh Malik
**Version:** 1.0
**Last Updated:** February 2026
**License:** Personal Use

Built with dedication to security and education. 🔒