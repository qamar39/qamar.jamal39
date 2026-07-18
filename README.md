<div align="center">

# 🏗️ Qamar Jamal — Portfolio

### Senior Techno-Functional Consultant · Project Controls & Enterprise Systems

A single-page, fully responsive portfolio site built with **Tailwind CSS** and **Font Awesome**, styled around an enterprise "project schedule" visual language — deep navy/slate tones, monospace WBS-style labels, and a Gantt-inspired experience timeline.

[![Made with Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-CDN-38BDF8?logo=tailwindcss&logoColor=white)](https://tailwindcss.com)
[![Font Awesome](https://img.shields.io/badge/Icons-Font_Awesome_6-528DD7?logo=fontawesome&logoColor=white)](https://fontawesome.com)
[![Deploy: GitHub Pages](https://img.shields.io/badge/Deploy-GitHub_Pages-222?logo=github)](https://pages.github.com)

</div>

---

## ✨ Preview

| Section | What's inside |
|---|---|
| **Hero** | Headline, professional summary, key stats (8+ yrs · 350+ users · 18 DB schemas), profile photo placeholder |
| **About** | Extended bio, education, certification, languages, core focus areas |
| **Core Competencies** | 6-category skill grid — Project Controls Platforms, Reporting & Analytics, Integration & Migration, Docs & Collaboration, Scheduling Techniques, Other Tools |
| **Experience** | Gantt/WBS-styled vertical timeline across three roles and 9+ landmark engagements (Vantage Data Centre, Red Sea Global, Jeddah Central, Pradeep Phosphate, DHL/TECOM, and more) |
| **Contact** | Email, phone, and location cards with direct `mailto:` / `tel:` links |

---

## 🧱 Tech Stack

| Layer | Choice | Notes |
|---|---|---|
| Markup | HTML5 | Single file, no build step |
| Styling | [Tailwind CSS](https://tailwindcss.com) (CDN) | Custom theme tokens (navy/brand/cyan palette, Space Grotesk + Inter + JetBrains Mono type system) defined inline via `tailwind.config` |
| Icons | [Font Awesome 6](https://fontawesome.com) (CDN) | Solid icon set |
| Fonts | Google Fonts | `Space Grotesk` (display), `Inter` (body), `JetBrains Mono` (labels/data) |
| Interactivity | Vanilla JS | Mobile nav toggle, dynamic footer year — no framework, no dependencies |

No `npm install`, no bundler, no build pipeline — it's a single `index.html` you can open directly in a browser.

---

## 📁 Repository Structure

```
.
├── index.html    # Complete single-page portfolio (HTML + Tailwind + JS)
└── README.md     # You are here
```

---

## 🚀 Getting Started Locally

Clone the repo and open the file — that's it:

```bash
git clone https://github.com/<your-username>/<your-repo>.git
cd <your-repo>
open index.html   # macOS
# or just double-click index.html in Finder / File Explorer
```

For a live-reloading local server (optional), use any static file server, e.g.:

```bash
python3 -m http.server 8000
# then visit http://localhost:8000
```

---

## 🌐 Deploying to GitHub Pages

1. **Create / push the repository**
   ```bash
   git init
   git add index.html README.md
   git commit -m "Initial commit — portfolio site"
   git branch -M main
   git remote add origin https://github.com/<your-username>/<your-repo>.git
   git push -u origin main
   ```

2. **Enable GitHub Pages**
   - Go to your repository on GitHub → **Settings** → **Pages**.
   - Under **Build and deployment → Source**, select **Deploy from a branch**.
   - Set **Branch** to `main` and folder to `/ (root)`, then click **Save**.

3. **Visit your live site**
   - GitHub will publish to:
     ```
     https://<your-username>.github.io/<your-repo>/
     ```
   - The first deploy can take 1–2 minutes — refresh the Pages settings tab to see the live link once it's ready.

4. **(Optional) Custom domain**
   - Add a `CNAME` file to the repo root containing your domain (e.g. `qamarjamal.com`).
   - Point your domain's DNS to GitHub Pages ([see GitHub's custom domain guide](https://docs.github.com/en/pages/configuring-a-custom-domain-for-your-github-pages-site)).
   - Re-enter the domain in **Settings → Pages → Custom domain** and enable **Enforce HTTPS**.

---

## 🎨 Customizing

- **Profile photo** — replace the placeholder box in the Hero section (`<div class="w-64 h-64 ...">`) with an `<img>` tag pointing to your photo.
- **Colors** — edit the `tailwind.config` block at the top of `index.html` (`navy`, `brand`, `cyan` color scales).
- **Fonts** — swap the Google Fonts `<link>` and the `fontFamily` values in `tailwind.config`.
- **Content** — all copy lives directly in `index.html`; search for the section comments (`<!-- ============ HERO ============ -->`, etc.) to jump to a section quickly.

---

## 📬 Contact

- **Email:** [qamar.jamal39@gmail.com](mailto:qamar.jamal39@gmail.com)
- **Phone:** +91 82954 70183
- **Location:** Jaipur, Rajasthan, India

---

<div align="center">
<sub>Built with Tailwind CSS · Deployed on GitHub Pages</sub>
</div>
