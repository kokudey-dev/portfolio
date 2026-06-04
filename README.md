# Koku Dey — Portfolio

Dark editorial portfolio built with vanilla HTML, CSS, and JavaScript.

## 🚀 Deploy to GitHub Pages

1. Push to any repo (e.g. `kokudey_portfolio`)
2. Go to **Settings → Pages**
3. Set source to `main` branch, `/ (root)`
4. Site lives at `https://yourusername.github.io/kokudey_portfolio`

---

## 🗂 File Structure

```
portfolio/
├── index.html                    ← Main page
├── assets/
│   ├── css/style.css             ← All styles
│   ├── js/main.js                ← Nav, animations, interactions
│   └── img/
│       ├── photo.jpg             ← Profile photo (4:5 ratio recommended)
│       ├── icons/
│       │   ├── logo-rice-again.png
│       │   ├── logo-myhandyman.png
│       │   └── logo-craftverse.png
│       └── design/
│           ├── ella/             ← Ella Jacobs project images
│           ├── kefa/             ← Kefa Engineering project images
│           ├── logos/            ← logo-client-1.jpg … logo-client-13.jpg
│           ├── graphics/         ← Graphic design work images
│           └── presentations/    ← Presentation cover images
│   └── files/
│       ├── c5-love-of-god.pptx
│       ├── gcb-presentation.pptx
│       ├── td-africa-presentation.pptx
│       └── ugbs-presentation.pptx
└── README.md
```

---

## 🧭 Page Sections

The site is one page with six sections, navigated via the top nav:

| Nav Link | Scrolls To | Sections Covered |
|---|---|---|
| About | `#about` | About |
| Background | `#experience` | Experience → Education → Skills & Tools |
| My Projects | `#apps` | Apps → Design Work |
| Contact | `#contact` | Contact |

---

## ✏️ What to Customize

### Personal info
- `index.html` `<title>` tag — update your name
- **Hero**: name, eyebrow tagline, description, and CTA button links
- **About**: bio paragraphs, chips, and stats
- **Contact**: email `href`, phone `href`, WhatsApp link, and all social links

### Experience & Education
- Update `.timeline-item` blocks with your actual roles, dates, and bullets
- Tags available: `work`, `active-role`, `degree`, `cert`

### Skills & Tools
- Add or remove `<span class="skill">` and `<span class="tool">` tags

### Apps
- Update each `.app-card` with your project name, description, tech tags, and link
- App icon images go in `assets/img/icons/`
- Status badges: `active` (In dev) or `early` (Early stage)

### Design Work — Tabs
| Tab | Panel ID | What goes here |
|---|---|---|
| Logos | `panel-logos` | Logo grid — `.design-card.third` cards |
| Graphic Design | `panel-print` | Flyers, banners, social posts |
| Ella Jacobs | `panel-ella` | Web, logo, lookbook cards |
| Kefa | `panel-kefa` | Web, logo, polo shirt cards |
| Presentations | `panel-pptx` | PPTX covers with download links |

### Contact Icons
The contact section uses SVG icon-only links. To update:
- **Email**: change the `href="mailto:..."` on the Gmail icon link
- **Phone**: change the `href="tel:..."` on the phone icon link
- **WhatsApp**: change the number in `href="https://wa.me/..."` 
- **Socials**: update the `href` on GitHub, LinkedIn, X, and Instagram links

---

## 🎨 Colors & Fonts

All design tokens are CSS variables at the top of `style.css`:

```css
--navy:          #0b0f1a;   /* Page background */
--navy-deep:     #080c14;   /* Mobile menu background */
--navy-surface:  #111827;   /* Card surfaces */
--navy-surface-2:#1a2234;   /* Elevated surfaces */
--red:           #e63946;   /* Accent — buttons, labels, highlights */
--white:         #ffffff;   /* Primary text */
--white-dim:     rgba(255,255,255,0.6);   /* Secondary text */
--white-faint:   rgba(255,255,255,0.2);   /* Muted text */
```

Fonts loaded from Google Fonts:
- **Display / Headings**: Jost
- **Body / UI**: Manrope

---

## 📸 Image Tips
- **Profile photo**: 800×1000px minimum, JPG
- **Design cards**: 1200×800px minimum, JPG
- **App icons**: 200×200px, PNG with transparent background
- Compress images before uploading at [Squoosh](https://squoosh.app)

---

Built with intent. No frameworks, no dependencies, no bloat.
