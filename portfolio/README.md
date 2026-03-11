# Durgaprasad Akula — Portfolio

A single-file static portfolio website built with HTML, CSS, and vanilla JavaScript.

---

## 🚀 Run Locally

No build tools or server required. Just open the file:

### Option 1 — Direct browser open
Double-click `index.html` — it opens straight in your browser.

### Option 2 — VS Code Live Server (recommended)
1. Install the **Live Server** extension in VS Code
2. Right-click `index.html` → **Open with Live Server**

### Option 3 — Python local server
```bash
# Python 3
python -m http.server 3000
# Then open http://localhost:3000
```

---

## ☁️ Deploy to Vercel

### Option 1 — Vercel CLI (fastest)
```bash
# 1. Install Vercel CLI
npm install -g vercel

# 2. Inside this folder, run:
vercel

# 3. Follow the prompts — your site will be live in seconds!
```

### Option 2 — Vercel Dashboard (no CLI needed)
1. Go to [vercel.com](https://vercel.com) and sign in (use GitHub login)
2. Click **"Add New Project"**
3. Drag and drop this entire **portfolio** folder — OR — push it to a GitHub repo and import it
4. Click **Deploy** — done! Vercel auto-detects static files.

### Option 3 — Deploy via GitHub
1. Create a new GitHub repo (e.g. `my-portfolio`)
2. Push this folder to the repo:
```bash
git init
git add .
git commit -m "Initial portfolio"
git remote add origin https://github.com/YOUR_USERNAME/my-portfolio.git
git push -u origin main
```
3. Go to [vercel.com](https://vercel.com) → **Add New Project** → import your GitHub repo → **Deploy**

---

## 📁 File Structure

```
portfolio/
├── index.html     ← Complete portfolio (all CSS + JS inline)
├── vercel.json    ← Vercel deployment config
└── README.md      ← This file
```

---

## ✏️ Customisation Tips

- **Email / phone** — search for `akuladurgaprasad22@gmail.com` and `+918143600826` to update
- **Social links** — update the `href` values in the Contact section
- **Projects** — each project is a `.project-card` div inside `#projects`
- **Colors** — all colors are CSS variables at the top of `<style>`: change `--accent` to pick a new highlight color

---

Built with pure HTML · CSS · JavaScript — no frameworks, no dependencies.
