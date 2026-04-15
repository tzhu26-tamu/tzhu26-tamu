# 🎓 Academic Website Template

A clean, minimal personal academic website for researchers and PhD students.  
Built with plain HTML & CSS — **no build tools, no npm, no Jekyll** — just GitHub Pages.

**Live demo:** [rayford295.github.io/academic-website-template](https://rayford295.github.io/academic-website-template)

---

## ✨ Features

- Sticky navigation with smooth scroll
- Hero section with photo or initials avatar
- Research interest tags
- Publications list with PDF/DOI/Code links
- Project cards linked to GitHub repos
- Contact section
- Mobile-responsive
- One file to edit

---

## 🚀 How to Use (5 Minutes)

### Step 1 — Create your repo from this template

Click the green **"Use this template"** button at the top of this page.

- Repository name: `your-github-username.github.io`  
  *(replace `your-github-username` with your actual GitHub username — must match exactly)*
- Set to **Public**
- Click **Create repository**

### Step 2 — Enable GitHub Pages

In your new repo:

1. Go to **Settings** → **Pages** (left sidebar)
2. Under **Source**, select `main` branch → click **Save**
3. Wait about 60 seconds

Your site will be live at: `https://your-username.github.io`

### Step 3 — Customize the content

Open `index.html` and press `Ctrl+F` (or `Cmd+F`) to search for **`✏️ EDIT`**.

Every line you need to change is marked. Edit directly on GitHub (click the pencil icon) or clone and edit locally.

**What to change:**

| Marker location | What to edit |
|----------------|--------------|
| `<title>` tag | Your name and role |
| `.nav-name` | Your name in the navbar |
| `<h1>` in hero | Your full name |
| `.position` | Your degree and department |
| `.university` | Your university and advisor |
| Hero links | Email, GitHub, Google Scholar, CV URLs |
| `YN` in avatar | Your initials (or add a photo — see below) |
| About section | Your bio paragraph |
| Research tags | Your actual research areas |
| Publications | Your papers (copy the `<li>` block for each) |
| Projects | Your GitHub repo links |
| Contact | Your email, office, links |
| Footer | Your name |

### Step 4 — Add a profile photo (optional)

1. Create a folder called `assets/` in your repo
2. Upload your photo as `assets/photo.jpg`
3. In `index.html`, inside the `<div class="avatar">`, delete `YN` and uncomment:
   ```html
   <img src="assets/photo.jpg" alt="Your Name">
   ```

### Step 5 — Add your CV (optional)

1. Upload your CV PDF as `assets/cv.pdf`
2. The CV download link in the hero already points to `assets/cv.pdf`

---

## 🎨 Changing Colors

All colors are CSS variables at the top of the `<style>` block:

```css
:root {
  --navy:  #1a2e4a;   /* header, nav, year badges */
  --teal:  #0ea5e9;   /* accent, links, tags */
  --bg:    #f8fafc;   /* page background */
  --text:  #1e293b;   /* main text */
  --muted: #64748b;   /* secondary text */
}
```

Change `--navy` and `--teal` to match your personal style.

---

## 📁 File Structure

```
your-username.github.io/
├── index.html          ← The entire site (edit this)
├── assets/
│   ├── photo.jpg       ← Your profile photo (optional)
│   └── cv.pdf          ← Your CV (optional)
└── README.md
```

---

## 🛠 Common Issues

| Problem | Fix |
|---------|-----|
| Site not showing up | Wait 2–5 minutes after enabling Pages; check Settings → Pages for the URL |
| Photo not loading | Confirm the file is named exactly `assets/photo.jpg` (case-sensitive) |
| Changes not updating | GitHub Pages caches — hard refresh with `Ctrl+Shift+R` |
| Broken on mobile | Make sure you haven't deleted the `<meta name="viewport">` tag |

---

*Template created for GIS Practicum, Texas A&M University, April 2026.*
