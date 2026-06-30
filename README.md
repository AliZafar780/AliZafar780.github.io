# AliZafar780.github.io

<p align="center">
  <a href="https://AliZafar780.github.io">
    <img src="https://img.shields.io/badge/Live-Site-00ff88?style=for-the-badge&logo=github&logoColor=white" alt="Live Site">
  </a>
  <img src="https://img.shields.io/badge/Status-Active-success?style=for-the-badge" alt="Status">
  <img src="https://img.shields.io/github/deployments/AliZafar780/AliZafar780.github.io/github-pages?style=for-the-badge&label=Deploy" alt="Deploy Status">
  <img src="https://img.shields.io/github/last-commit/AliZafar780/AliZafar780.github.io?style=for-the-badge&label=Updated" alt="Last Commit">
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5">
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" alt="CSS3">
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript">
  <img src="https://img.shields.io/badge/Bootstrap-5.2.3-7952B3?style=for-the-badge&logo=bootstrap&logoColor=white" alt="Bootstrap">
  <img src="https://img.shields.io/badge/License-MIT-yellow?style=for-the-badge" alt="License MIT">
</p>

---

## 🌐 Live Site

**→ [AliZafar780.github.io](https://AliZafar780.github.io)**

Personal portfolio and professional presence for **Ali Zafar** — Security Researcher, AI Systems Architect, and Photographer.

---

## ✨ Features

- **Dark theme** with cyber-green (`#00ff88`) accent — easy on the eyes, built for extended browsing
- **Fully responsive** — optimized for desktop, tablet, and mobile via Bootstrap 5.2
- **Smooth scroll navigation** with animated section transitions
- **Interactive skill bars** — CSS progress bars with Intersection Observer–based animation
- **Project showcase** — hover-reveal cards with tag metadata
- **Photography gallery** — grid layout with placeholder imagery (ready for real photos)
- **SEO-optimized** — Open Graph, Twitter Cards, JSON-LD structured data, meta keywords/description
- **Accessibility-minded** — ARIA labels, semantic HTML, keyboard-friendly navigation
- **Custom 404 page** — matches the site's dark theme with glitch aesthetics

---

## 🛠️ Tech Stack

| Technology | Purpose |
|:-----------|:--------|
| **HTML5** | Semantic document structure |
| **CSS3** | Custom properties, Flexbox, Grid, animations, responsive design |
| **JavaScript (Vanilla ES6)** | Scroll effects, Intersection Observer, smooth navigation |
| **Bootstrap 5.2.3** | Responsive layout, navbar, grid system |
| **Font Awesome 6.4** | Icon set for skills, contact, and UI elements |
| **GitHub Pages** | Zero-config hosting with automatic HTTPS and custom domain support |

---

## 📂 Project Structure

```
.
├── index.html          # Main portfolio page (single-page application)
├── 404.html            # Custom 404 error page
├── README.md           # You are here
├── LICENSE             # MIT license
├── SECURITY.md         # Vulnerability disclosure policy
├── .gitattributes      # Git line-ending normalization
└── .github/            # GitHub-specific config (workflows, etc.)
```

---

## 🚀 Local Development

```bash
# 1. Clone the repository
git clone https://github.com/AliZafar780/AliZafar780.github.io.git
cd AliZafar780.github.io

# 2. Serve locally (choose one)
# Option A: Python 3
python -m http.server 8000

# Option B: Node.js (npx)
npx serve .

# Option C: VS Code Live Server extension
# Right-click index.html → "Open with Live Server"

# 3. Open in browser
# http://localhost:8000
```

No build step required — this is a static site. Edit, save, and refresh.

---

## 🎨 Customization Guide

### Colors & Theme
Edit CSS custom properties in the `:root` block of `index.html`:

```css
:root {
    --accent: #00ff88;       /* Change to your brand color */
    --bg-primary: #0a0a0a;   /* Background */
    --text-primary: #e0e0e0; /* Text color */
}
```

### Content
- **Personal info**: Update name, tagline, and bio in the Hero and About sections
- **Projects**: Add/remove `.project-card` blocks in the Projects section
- **Skills**: Edit `.skill-item` blocks — change skill names and `width` percentages
- **Contact**: Update email and social links in the Contact section
- **Copyright**: Year auto-updates; change name in the `<footer>` tag

### Adding Real Photos
Replace the `.photo-placeholder` divs with `<img>` tags:

```html
<img src="assets/photos/your-photo.jpg" alt="Photo description" class="img-fluid">
```

---

## 🚢 Deployment

This site is deployed via **GitHub Pages** from the `main` branch:

1. Push changes to `main`:
   ```bash
   git add .
   git commit -m "Update portfolio"
   git push origin main
   ```
2. GitHub Actions (if configured) or GitHub's auto-deploy will publish
3. Changes are live at `https://AliZafar780.github.io` within minutes

### Custom Domain (Optional)
To use a custom domain:
1. Add a `CNAME` file with your domain (e.g., `alizafar.com`)
2. Configure DNS `A` records pointing to GitHub Pages IPs:
   - `185.199.108.153`
   - `185.199.109.153`
   - `185.199.110.153`
   - `185.199.111.153`
3. Or use a `CNAME` record pointing to `AliZafar780.github.io`

---

## 📜 License

This project is licensed under the **MIT License** — see the [LICENSE](LICENSE) file for details.

---

## 🤝 Contributing

Contributions, suggestions, and bug reports are welcome.

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/improvement`)
3. Commit changes (`git commit -m 'Add improvement'`)
4. Push to the branch (`git push origin feature/improvement`)
5. Open a Pull Request

---

<p align="center">
  <sub>Built with depth, not decorators — Ali Zafar</sub>
</p>
