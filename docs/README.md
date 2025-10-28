# AI Leadership & Project Management - Companion Website

This is the companion website for the AI Leadership & Project Management masterclass.

## GitHub Pages Deployment

### Option 1: Deploy from this Repository

1. **Push this course to GitHub** (if not already there)
2. **Enable GitHub Pages:**
   - Go to repository Settings → Pages
   - Source: Deploy from a branch
   - Branch: `main` (or your default branch)
   - Folder: `/courses/01-leadership-pm/docs`
   - Click Save

3. **Access your site:**
   - Will be available at: `https://[username].github.io/[repo-name]/courses/01-leadership-pm/docs/`

### Option 2: Separate Repository (Recommended for cleaner URLs)

1. **Create new repository:**
   ```bash
   # Create new repo on GitHub: ai-leadership-pm
   ```

2. **Copy docs folder to new repo:**
   ```bash
   # Create new local directory
   mkdir ../ai-leadership-pm
   cd ../ai-leadership-pm

   # Copy docs contents to root
   cp -r [path-to-execed]/courses/01-leadership-pm/docs/* .

   # Initialize git
   git init
   git add .
   git commit -m "Initial commit: AI Leadership & PM companion site"

   # Connect to GitHub
   git remote add origin https://github.com/[username]/ai-leadership-pm.git
   git push -u origin main
   ```

3. **Enable GitHub Pages:**
   - Settings → Pages
   - Source: Deploy from a branch
   - Branch: `main`
   - Folder: `/ (root)`
   - Click Save

4. **Access your site:**
   - Will be available at: `https://[username].github.io/ai-leadership-pm/`
   - Much cleaner URL!

### Option 3: Custom Domain

If you have a custom domain:

1. Follow Option 2 above
2. In repository Settings → Pages:
   - Enter your custom domain (e.g., `ai-leadership.yourdomain.com`)
3. Add CNAME record in your DNS:
   - Type: CNAME
   - Name: ai-leadership
   - Value: [username].github.io

## Site Structure

```
docs/
├── index.html              ← Main page (complete)
├── pre-readings.html       ← Pre-course reading materials (complete)
├── pre-readings/           ← Pre-reading files
│   ├── why-ai-projects-fail.html
│   ├── ai-transformation-of-project-management.html
│   └── AI_Impact_on_Project_Management_Report.html
├── activities/             ← Exercise materials (complete)
├── handouts/               ← Downloadable templates (complete)
├── content/                ← Slide decks (complete)
└── README.md              ← This file
```

## Future Enhancements

Additional pages you could create:

1. **frameworks.html** - Detailed framework explanations with examples
2. **exercises.html** - Exercise materials and instructions
3. **retailflow.html** - Complete RetailFlow case study
4. **templates.html** - Downloadable worksheets and templates
5. **resources.html** - Additional reading and resources
6. **faq.html** - Frequently asked questions

## Updating the Site

After making changes:

```bash
git add .
git commit -m "Update companion site"
git push
```

GitHub Pages will automatically rebuild (takes 1-2 minutes).

## Current Status

✅ **index.html** - Complete companion site with integrated sections:
- Home: Course overview with quick links to all materials
- Pre-Readings: 3 curated readings to prepare for the masterclass
- Activities: Exercise materials (case briefs, role cards, constraint scenarios)
- Handouts: Tools and templates (frameworks, decision matrices)
- Content: Presentation slides in multiple formats

✅ **Folders:**
- activities/ - Exercise materials (interactive cards, case briefs, scenario cards)
- handouts/ - Downloadable templates and frameworks
- content/ - Slide decks and presentations
- pre-readings/ - Full pre-reading documents (HTML files)

---

**Note:** The companion site is designed to complement the in-person masterclass,
not replace it. Participants can access frameworks and resources before, during,
and after the course.
