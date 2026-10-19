<div align="center">

# 🧾 Anas Farhan (Personal Portfolio)

![Status](https://img.shields.io/badge/Status-Live-2F6B4F?style=for-the-badge)
![HTML5](https://img.shields.io/badge/HTML5-1C2521?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-2F6B4F?style=for-the-badge&logo=css3&logoColor=white)
![Vanilla JS](https://img.shields.io/badge/JavaScript-Vanilla-9C6B2E?style=for-the-badge&logo=javascript&logoColor=white)

<br/>

**A single-file, dependency-free portfolio styled as a bank passbook statement — built with plain HTML, CSS, and JavaScript.**

### 🌐 [Live Demo]() &nbsp;·&nbsp; 📬 [Contact Me](mailto:anasfarhan698@gmail.com) &nbsp;·&nbsp; 💼 [LinkedIn](https://www.linkedin.com/in/anas-farhan-1481372a5/) &nbsp;·&nbsp; 🐙 [GitHub](https://github.com/AnasDeveloper69)

</div>

---

## ✨ Concept

Most engineer portfolios reach for a generic "dev terminal" look. This one leans into what the work actually is: two years building ledgers, statements, and account records for a digital-wallet platform. So the site *is* a statement — a perforated passbook cover, ledger-ruled tables for the tech stack, statement-line entries for each role bullet (description left, pulled-out figure right, like a transaction amount column), and numbered "passbook pages" for projects.

## 🎬 Features

- **Ambient ledger-network background** — a `<canvas>` node graph in the accent green drifts slowly and reaches toward the cursor on hover, like a live distributed-ledger network
- **Letter-by-letter name reveal** — "Anas Farhan" animates in character by character on load
- **Typewriter statement line** — cycles through backend / frontend / domain / location under the role line, styled as a `>` command prompt
- **Perforated passbook header** — a punch-hole tear edge rendered in pure CSS (`radial-gradient`)
- **Statement-line experience entries** — each bullet pairs a description with a pulled figure (e.g. `~130,000`, `~628,000 rows`) or a domain tag (`AUTH`, `REPORTING`, `DATA`…)
- **Light / dark theme** — fully token-driven, follows system preference, no flash of wrong theme
- **Zero build step, zero dependencies** — one HTML file, Google Fonts, no framework, no bundler
- **Accessible & reduced-motion aware** — decorative animation disables cleanly under `prefers-reduced-motion`, the network canvas doesn't render at all

---

## 🗂️ Project Structure

```
anas-portfolio/
├── index.html      # Everything — markup, styles, and script in one file
└── README.md
```

No `src/`, no `node_modules`, no config files. Open `index.html` and it works.

---

## 🛠️ Tech Stack

| Technology | Purpose |
|---|---|
| HTML5 | Semantic structure |
| CSS3 (custom properties) | Theming, layout (flex/grid), animation — no framework |
| Vanilla JavaScript | Letter-split reveal, typewriter, canvas network, no libraries |
| [Fraunces](https://fonts.google.com/specimen/Fraunces) | Display serif — the "statement letterhead" voice |
| [Public Sans](https://fonts.google.com/specimen/Public+Sans) | Body sans — the typeface built for official government/financial forms |
| [IBM Plex Mono](https://fonts.google.com/specimen/IBM+Plex+Mono) | Tabular figures, ledger codes, tags |

---

## 🚀 Getting Started

No install, no build. This is a static file.

**Option 1 — Open directly**

```bash
git clone https://github.com/AnasDeveloper69/anas-portfolio.git
cd anas-portfolio
open index.html   # or just double-click it
```

**Option 2 — Local server** (recommended, since some browsers restrict `file://` fonts/canvas)

```bash
npx serve .
# or
python -m http.server 8000
```

---

## ☁️ Deployment

Any static host works — there's nothing to build.

**GitHub Pages**
1. Push this repo to GitHub
2. Settings → Pages → Deploy from branch → `main` / root
3. Live at `https://<username>.github.io/anas-portfolio/`

**Netlify / Vercel**
Drag-and-drop the folder, or connect the repo — no build command needed (or set it to a no-op).

---

## 🎨 Customization

Everything lives in the one `index.html` file.

| What to change | Where |
|---|---|
| Name, role, contact links | `<header class="masthead">` block |
| Summary & key figures | `<section id="summary">` |
| Tech stack | the `<dl class="ledger">` rows |
| Experience entries | `<div class="entries">` — each `.entry` has a `.desc` and a `.meta` (figure + tag) |
| Projects | `<div class="projects">` — each `.proj` card |
| Color palette | `:root` custom properties at the top of `<style>` (`--paper`, `--ink`, `--accent`, `--brass`…) — dark theme redefines the same tokens under `prefers-color-scheme` and `[data-theme="dark"]` |
| Typewriter lines | the `lines` array inside the `typewriter()` function near the bottom `<script>` |
| Network canvas density/speed | the `ledgerNetwork()` function — `count`, `vx`/`vy`, link distances |

---

## 📸 Sections Overview

| # | Section | Description |
|---|---|---|
| 01 | **Masthead** | Name, role, animated statement line, contact row, perforated header edge |
| 02 | **Summary** | Bio + a 4-tile stat strip (years experience, members migrated, dataset size, tree depth) |
| 03 | **Tech Stack** | Backend / Frontend / Data & Infra / Practices, as ledger rows |
| 04 | **Experience** | FoneApp role — six statement-line entries, each tagged by domain |
| 05 | **Selected Projects** | Hutang Bro, Homestay Seri Hijauan, TabungRia, Receipt Scan & Save |
| 06 | **Education** | Universiti Teknologi MARA (UiTM), Computer Science |
| 07 | **Footer** | Availability status, stamped "OPEN" mark, generated-on date |

---

## 📬 Contact

**Anas Farhan**

- 📧 Email: [anasfarhan698@gmail.com](mailto:anasfarhan698@gmail.com)
- 💼 LinkedIn: [anas-farhan-1481372a5](https://www.linkedin.com/in/anas-farhan-1481372a5/)
- 🐙 GitHub: [AnasDeveloper69](https://github.com/AnasDeveloper69)
- 📍 Location: Shah Alam, Selangor, Malaysia

---

<div align="center">

Built by **Anas Farhan** &nbsp;·&nbsp; Shah Alam, Malaysia

</div>
