# 🎓 Your Academic Website

A clean, responsive personal research website — ready for GitHub Pages.

## 📁 File Structure

```
your-username.github.io/
├── index.html        ← Main website (edit this!)
├── cv.pdf            ← Your CV (upload here)
├── photo.jpg         ← Your profile photo (upload here)
└── README.md         ← This file
```

## 🚀 Deploy on GitHub Pages (Step-by-Step)

### 1. Create the Repository
- Go to [github.com](https://github.com) → click **+** → **New repository**
- Name it exactly: **`your-username.github.io`** (replace `your-username` with your actual GitHub username)
- Set it to **Public**
- Click **Create repository**

### 2. Upload Files
- On the repo page, click **"uploading an existing file"** (or use the **Add file → Upload files** button)
- Drag and drop: `index.html`, `cv.pdf`, and `photo.jpg`
- Click **Commit changes**

### 3. Enable GitHub Pages
- Go to repo **Settings** → **Pages** (left sidebar)
- Under **Source**, select **Deploy from a branch**
- Branch: **main**, Folder: **/ (root)**
- Click **Save**

### 4. Visit Your Site!
- After 1-2 minutes, your site will be live at:  
  **`https://your-username.github.io`**

---

## ✏️ How to Edit Your Content

Open `index.html` and search for `REPLACE` — every placeholder is marked with a comment like:

```html
<!-- REPLACE: Your title -->
```

### Key things to update:
1. **Name & title** — search "Your Name"
2. **Bio** — search "your field"
3. **Photo** — replace the placeholder div with: `<img src="photo.jpg" class="hero-photo" alt="Your Name">`
4. **Research areas** — edit the research cards
5. **Publications** — add/remove `pub-item` blocks
6. **News** — add/remove `news-item` entries
7. **Links** — update email, Google Scholar, GitHub, ORCID URLs
8. **CV** — upload `cv.pdf` and the download button will work

### To add more publications:
Copy this template and fill in your details:
```html
<div class="pub-item">
    <div class="pub-title">Paper Title</div>
    <div class="pub-authors"><strong>Your Name</strong>, Co-Author</div>
    <div class="pub-venue">Journal Name, Year</div>
    <div class="pub-links">
        <a href="LINK">PDF</a>
        <a href="LINK">DOI</a>
    </div>
</div>
```

### To add a new year section:
```html
<div class="pub-year">2023</div>
```

---

## 🎨 Customization

### Change accent color
Edit the `--accent` variable at the top of the CSS in `index.html`:
```css
--accent: #2d5a7b;      /* Current: steel blue */
--accent-light: #3a7ca5;
```

Some nice alternatives:
- Deep teal: `#0d7377` / `#14919b`
- Academic red: `#9b2335` / `#c1374e`  
- Forest green: `#2d6a4f` / `#40916c`
- Warm amber: `#b5651d` / `#cc7722`

---

## 📝 License
Feel free to use and modify this template for your personal website.
