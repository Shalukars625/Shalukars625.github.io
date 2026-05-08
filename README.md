# Shaluka Senevirathna — Personal Academic Website

Clean, minimal academic personal site. Built with pure HTML, CSS, and vanilla JS. No frameworks, no build tools, no dependencies.

## Files

```
shaluka-website/
├── index.html   ← Main site content (edit this to update everything)
├── style.css    ← All styles
├── main.js      ← Scroll effects, mobile menu, reveal animations
├── cv.pdf       ← DROP YOUR CV HERE (replace this placeholder)
└── README.md
```

## How to Customize

Open `index.html` in any text editor and update:

- **Your email** → search for `your.email@okstate.edu`
- **GitHub URL** → search for `github.com/yourusername`
- **LinkedIn URL** → search for `linkedin.com/in/yourusername`
- **Publications** → find the `<!-- RESEARCH -->` section, replace the placeholder entry
- **CV file** → drop your `cv.pdf` into the project folder
- **Photo** → optional, add an `<img>` tag in the About section

---

## Deploy to GitHub Pages (Free Hosting)

### Step 1: Create a GitHub repository

1. Go to https://github.com and sign in
2. Click the **+** button → **New repository**
3. Name it exactly: `yourusername.github.io`
   - Replace `yourusername` with your actual GitHub username
   - Example: if your username is `shalukaK`, name it `shalukaK.github.io`
4. Set it to **Public**
5. Click **Create repository**

### Step 2: Upload your files

**Option A — Drag and drop (easiest):**
1. Open your new repository on GitHub
2. Click **uploading an existing file**
3. Drag all 4 files (`index.html`, `style.css`, `main.js`, `cv.pdf`) into the upload area
4. Scroll down → click **Commit changes**

**Option B — Git (if you have Git installed):**
```bash
cd shaluka-website
git init
git add .
git commit -m "Initial site"
git branch -M main
git remote add origin https://github.com/yourusername/yourusername.github.io.git
git push -u origin main
```

### Step 3: Enable GitHub Pages

1. Go to your repository → **Settings** tab
2. Click **Pages** in the left sidebar
3. Under **Source**, select **main** branch → click **Save**
4. Wait ~60 seconds

### Step 4: Visit your site

Your site will be live at:
```
https://yourusername.github.io
```

That's it. Free, permanent hosting with your own clean URL.

---

## Updating the Site Later

Whenever you want to update content:
1. Edit `index.html` locally
2. Go to your GitHub repository
3. Click on `index.html` → pencil icon (Edit) → paste updated content → Commit
   OR use `git push` if you're using Git

Changes go live in about 30–60 seconds.

---

## Adding a Custom Domain (Optional, still free)

If you want `shaluka.com` or similar instead of `yourusername.github.io`:
1. Buy a domain (~$10/yr from Namecheap or Google Domains)
2. In GitHub Pages settings → add your custom domain
3. Point your domain's DNS to GitHub's servers (instructions at docs.github.com/pages)
