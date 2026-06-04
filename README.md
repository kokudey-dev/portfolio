# Koku Ocloo — Portfolio

Dark editorial portfolio built with vanilla HTML, CSS, and JavaScript.

## 🚀 Deploy to GitHub Pages

### Option 1 — Automated (Recommended)
1. Push this folder to a repo named `yourusername.github.io`
2. GitHub Pages will serve it automatically at `https://yourusername.github.io`

### Option 2 — Any Repo
1. Push to any repo (e.g. `portfolio`)
2. Go to **Settings → Pages**
3. Set source to `main` branch, `/ (root)`
4. Site lives at `https://yourusername.github.io/portfolio`

---

## 🗂 File Structure

```
portfolio/
├── index.html               ← Main page
├── assets/
│   ├── css/style.css        ← All styles
│   ├── js/main.js           ← Nav, animations, interactions
│   └── img/                 ← Your images go here
│       ├── photo.jpg        ← Your profile photo (4:5 ratio works best)
│       ├── design-ella-jacobs.jpg
│       ├── design-kefa.jpg
│       ├── design-ace.jpg
│       └── design-church.jpg
└── README.md
```

---

## ✏️ What to Customize

### Personal info
- `index.html` line 1: Update `<title>`
- Hero section: Update name and description
- About section: Update bio, chips/skills, stats
- Contact section: Update email and social links

### Experience / Education
- Update the timeline items with your actual roles and dates
- Add or remove `.timeline-item` blocks as needed

### Apps
- Update the two app cards with your real project names, descriptions, and links
- Add more `.app-card` blocks following the same pattern

### Design Work
- Drop your design images into `assets/img/`
- Update `src`, `alt`, and overlay text in each `.design-card`
- The first card is `.wide` (spans 4 columns) — use your best piece there

### Colors / Fonts
Everything is in CSS variables at the top of `style.css`:
```css
--gold: #c9a84c;      /* Accent color */
--black: #0a0a0a;     /* Background */
--white: #f5f2ec;     /* Text */
```

---

## 📸 Image Tips
- **Profile photo**: 800×1000px minimum, JPG
- **Design cards**: 1200×800px minimum, JPG
- Compress with [Squoosh](https://squoosh.app) before uploading

---

Built with intent. No frameworks, no dependencies, no bloat.
