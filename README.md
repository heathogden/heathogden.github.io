# Ogden Lab Website

A modern, professional research lab website built for GitHub Pages.

---

## 🚀 Getting Your Site Live on GitHub Pages — Step-by-Step

### Step 1: Create a GitHub Account
1. Go to **https://github.com** and click **Sign up**
2. Choose a username — this will appear in your site URL.
   - If you use `hogden` your site will be at: `hogden.github.io`
3. Verify your email and complete setup

---

### Step 2: Create a New Repository
1. Click the **+** button (top right) → **New repository**
2. Name it exactly: `YOUR-USERNAME.github.io`
   - Example: if your username is `hogden`, name it `hogden.github.io`
3. Set it to **Public**
4. Check **"Add a README file"**
5. Click **Create repository**

---

### Step 3: Upload Your Website Files
1. In your new repository, click **Add file** → **Upload files**
2. Drag and drop all the HTML files from this folder:
   - `index.html`
   - `people.html`
   - `research.html`
   - `publications.html`
   - `join.html`
3. Scroll down, add a commit message like "Add website files"
4. Click **Commit changes**

---

### Step 4: Enable GitHub Pages
1. Go to your repository **Settings** (top menu)
2. In the left sidebar, click **Pages**
3. Under "Source", select **Deploy from a branch**
4. Choose branch: **main**, folder: **/ (root)**
5. Click **Save**

---

### Step 5: Visit Your Site!
- After ~2 minutes, your site will be live at:
  **https://YOUR-USERNAME.github.io**
- GitHub will show the URL in the Pages settings

---

## 📁 File Structure

```
ogden-lab-site/
├── index.html          ← Homepage (this is ready!)
├── people.html         ← Lab members page (customize next)
├── research.html       ← Research detail page
├── publications.html   ← Publications list
├── join.html           ← Prospective students
└── README.md
```

## 🎨 Customizing Your Site

### Updating content in index.html:
- **Your research description** — search for "The Ogden Lab uses" and update
- **Stats** (20+ Years, 10 Projects, etc.) — search for `stat-num` to find these
- **News items** — find `news-list` section and add/remove items
- **Contact info** — update in the `<footer>` section

### Adding photos:
1. Create an `assets/img/` folder in your repository
2. Upload photos there
3. In the HTML, replace placeholder divs with: `<img src="assets/img/your-photo.jpg" alt="..." />`

---

## 🔗 Tips

- Changes take ~1–2 minutes to appear on your live site after pushing
- You can edit files directly on GitHub.com by clicking a file and hitting the pencil icon
- For a custom domain (e.g., ogdenlab.com), see: https://docs.github.com/pages/custom-domain
