# Krish Gupta — Portfolio

Dark & futuristic portfolio website. Built with pure HTML/CSS/JS. Zero dependencies.

---

## 🚀 Deploy to Render (Step-by-step)

### Step 1 — Push to GitHub

1. Create a new repo on GitHub (e.g. `krish-portfolio`)
2. Inside this folder, run:

```bash
git init
git add .
git commit -m "Initial portfolio"
git remote add origin https://github.com/YOUR_USERNAME/krish-portfolio.git
git push -u origin main
```

### Step 2 — Deploy on Render

1. Go to [render.com](https://render.com) and sign in
2. Click **"New +"** → **"Static Site"**
3. Connect your GitHub account and select the `krish-portfolio` repo
4. Use these settings:
   - **Name:** `krish-portfolio` (or anything you like)
   - **Branch:** `main`
   - **Build Command:** *(leave empty)*
   - **Publish Directory:** `.`
5. Click **"Create Static Site"**
6. Render will give you a free URL like `krish-portfolio.onrender.com` 🎉

---

## ✏️ Personalise Before Deploying

Search for `✏️` comments in `index.html` — those are all the spots to update:

| What | Where in index.html |
|---|---|
| GitHub URL | Nav bar + Contact section |
| Email | Contact section |
| LinkedIn | Contact section |
| Project repo links | Each project card |
| Bio text | About section |
| Stats (years, projects) | About section |
| Experience entries | Experience section |

---

## 📁 Files

```
krish-portfolio/
├── index.html     ← entire site (HTML + CSS + JS)
├── render.yaml    ← Render deployment config
└── README.md      ← this file
```

No npm, no build step, no framework. Just push and it deploys.
