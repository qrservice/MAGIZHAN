# 🎀 Birthday Invitation – GitHub Pages Deployment Guide

## 📁 Files needed
```
your-repo/
└── index.html        ← the invitation page
└── birthday.mp3      ← (optional) background music
└── README.md         ← this file
```

---

## 🚀 Deploy to GitHub Pages (Free)

### Step 1 — Create GitHub Repo
1. Go to https://github.com/new
2. Name it: `birthday-invite` (or anything)
3. Set **Public**
4. Click **Create repository**

### Step 2 — Upload files
```bash
git init
git add index.html
git commit -m "Add birthday invitation"
git branch -M main
git remote add origin https://github.com/YOUR_USERNAME/birthday-invite.git
git push -u origin main
```

### Step 3 — Enable GitHub Pages
1. Repo → **Settings** → **Pages**
2. Source: **Deploy from a branch**
3. Branch: `main` / `root`
4. Save → Your site will be live at:
   `https://YOUR_USERNAME.github.io/birthday-invite/`

---

## ✏️ Customise the invite

| What to change | Where in index.html |
|---|---|
| Baby's name | `Princess Ananya` (3 places) |
| Age / turning | `is turning 1 Year Old` |
| Party date & time | `June 17, 2025` + `18:00:00` in countdown |
| Venue name | `Grand Paradise Hall` |
| Google Maps link | `https://maps.google.com/?q=...` |
| WhatsApp number | `91XXXXXXXXXX` |
| Family message | Inside `<p class="message-text">` |

## 🎵 Adding Background Music

1. Download a free birthday tune (e.g. from pixabay.com/music)
2. Save as `birthday.mp3` in the same folder
3. In `index.html`, uncomment the `<audio>` tag and the music JS block

---

Made with 💛 – Adi
