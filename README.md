# 🌐 My GitHub Pages Portfolio

A beautiful, zero-framework personal portfolio. **Update your content by editing `data.json` only** — no HTML editing required.

---

## 📁 Folder Structure

```
portfolio/
├── index.html          ← DON'T touch this
├── data.json           ← ✏️  EDIT THIS for all your content
├── resume.pdf          ← Upload your CV here
├── images/
│   ├── avatar.jpg      ← Your profile photo
│   ├── project1.jpg    ← Project screenshots
│   ├── project2.jpg
│   ├── project3.jpg
│   ├── gallery1.jpg    ← Gallery photos
│   ├── gallery2.jpg
│   └── ...
└── README.md
```

---

## 🚀 Setup (5 minutes)

### Step 1 — Create your GitHub Pages repo
1. Go to [github.com/new](https://github.com/new)
2. Name it exactly: `yourusername.github.io`
3. Make it **Public**
4. Click **Create repository**

### Step 2 — Upload these files
1. Click **Add file → Upload files** in your new repo
2. Drag the entire folder contents (index.html, data.json, images/, etc.)
3. Click **Commit changes**

### Step 3 — Enable GitHub Pages
1. Go to repo **Settings → Pages**
2. Source: **Deploy from a branch**
3. Branch: **main**, Folder: **/ (root)**
4. Click **Save**

Your site will be live at `https://yourusername.github.io` in ~2 minutes!

---

## ✏️ How to Update Content

### Edit text & info → `data.json`
Open `data.json` in GitHub's web editor (click the file → pencil icon) and change:
- Your name, tagline, bio
- Email, location
- Social media links
- Skills list
- Experience / work history
- Projects (title, description, tags, links)
- Photo captions

### Add / change photos → `images/` folder
1. Click **Add file → Upload files** in your repo
2. Navigate to the `images/` folder (or create it)
3. Upload your photos with these exact names:
   - `avatar.jpg` → your profile photo
   - `project1.jpg`, `project2.jpg`, etc. → project screenshots
   - `gallery1.jpg`, `gallery2.jpg`, etc. → gallery photos
4. In `data.json`, make sure the `"image"` field matches the filename

### Add your resume
Upload a `resume.pdf` to the root folder of your repo.

---

## 🖼️ Image Tips
- **Avatar**: Square or portrait, minimum 600×800px
- **Project images**: 16:9 ratio works best (e.g., 1280×720px)
- **Gallery photos**: Square crops look great
- Keep files under 2MB for fast loading
- JPG format recommended

---

## 🎨 Customizing Colors
To change the accent color (default: gold `#c9a96e`), open `index.html` and find:
```css
--accent: #c9a96e;
```
Replace with any hex color you like.

---

Made with ♥ using plain HTML, CSS & JavaScript.
