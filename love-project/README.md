# 💛 Love Project — Setup Guide

## 📁 Project Structure

```
love-project/
├── index.html          ← Home page (poetic quotes + timeline)
├── question.html       ← "Will you accept my love?" page
├── video.html          ← "I wanna tell you something" + video
├── final.html          ← "I LOVE YOU IN EVERY UNIVERSE" 🌌
├── vercel.json         ← Vercel config (no 404s!)
├── assets/
│   ├── cartoon.png         ← YOUR cute cartoon image
│   ├── love_video.mp4      ← YOUR video file
│   ├── pinterest1.jpg      ← Pinterest image 1
│   ├── pinterest2.jpg      ← Pinterest image 2
│   ├── pinterest3.jpg      ← Pinterest image 3
│   ├── pinterest4.jpg      ← Pinterest image 4
│   └── pinterest5.jpg      ← Pinterest image 5
└── README.md
```

---

## 🖼️ What images/files to add in `assets/`

| File name         | What it is |
|------------------|------------|
| `cartoon.png`    | A cute cartoon character (the one asking "will you accept my love?") — download a cute chibi/kawaii character from Google or draw one |
| `love_video.mp4` | Your personal video message to her |
| `pinterest1.jpg` | Aesthetic Pinterest image — e.g., cozy friendship vibes |
| `pinterest2.jpg` | Aesthetic Pinterest image — e.g., golden hour, warm tones |
| `pinterest3.jpg` | Aesthetic Pinterest image — e.g., starry night / dreamy |
| `pinterest4.jpg` | Aesthetic Pinterest image — e.g., cute quote art |
| `pinterest5.jpg` | Aesthetic Pinterest image — e.g., flowers / nature |

> 💡 **Tip for Pinterest:** Save images → right click → Save As → rename them to the filenames above and put them in `assets/` folder.

---

## 🖥️ How to run in VS Code

### Step 1 — Open the folder in VS Code
```
File → Open Folder → select the `love-project` folder
```

### Step 2 — Install Live Server extension (one-time)
- Press `Ctrl+Shift+X` (Extensions)
- Search **"Live Server"** by Ritwick Dey
- Click **Install**

### Step 3 — Run it
- Right-click on `index.html` in the file explorer
- Click **"Open with Live Server"**
- It opens at `http://127.0.0.1:5500/index.html` ✅

---

## 🚀 How to deploy on Vercel (step by step)

### Step 1 — Push to GitHub
1. Go to [github.com](https://github.com) → New repository → name it `love-project`
2. In VS Code, open terminal (`Ctrl+`` `) and run:
```bash
git init
git add .
git commit -m "💛 love project"
git branch -M main
git remote add origin https://github.com/YOUR_USERNAME/love-project.git
git push -u origin main
```

### Step 2 — Deploy on Vercel
1. Go to [vercel.com](https://vercel.com) → Sign up/Login with GitHub
2. Click **"Add New Project"**
3. Import your `love-project` repository
4. Settings:
   - **Framework Preset:** `Other`
   - **Root Directory:** `./` (leave default)
   - **Build Command:** (leave empty)
   - **Output Directory:** (leave empty)
5. Click **Deploy** 🚀

### Step 3 — Done!
Vercel gives you a URL like `https://love-project-xyz.vercel.app`
Share that link with her! 💌

---

## 🔄 Page flow

```
index.html  →  question.html  →  video.html  →  final.html
(Home)         (Yes/No?)         (Video 💌)      (🌌 Universe)
```

---

## ❓ Troubleshooting

| Problem | Fix |
|---------|-----|
| Video not playing | Make sure the file is exactly `assets/love_video.mp4` |
| Cartoon not showing | Make sure file is exactly `assets/cartoon.png` |
| Pinterest images missing | Make sure filenames are exactly `pinterest1.jpg` through `pinterest5.jpg` |
| 404 on Vercel | The `vercel.json` handles this — make sure it's in the root folder |

---

Made with 💛 — good luck bro, you got this! 🌸
