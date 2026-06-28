# ⚡ FlipperEdu — Flipper Zero Visual Signal Education

An interactive educational website that shows exactly how Flipper Zero wireless modules work — with live canvas signal animations for every step.

**Live demo:** `https://YOUR-USERNAME.github.io/flipper-edu/`

---

## 📁 File structure

```
flipper-edu/
├── index.html              ← Full website (all-in-one, no build needed)
├── 404.html                ← Custom 404 page
├── sw.js                   ← Service worker (PWA offline support)
├── README.md               ← This file
├── LICENSE                 ← MIT license
├── .gitignore              ← Git ignore rules
├── _config.yml             ← GitHub Pages config
└── assets/
    ├── site.webmanifest    ← PWA app manifest
    ├── icon-192.svg        ← App icon (small)
    ├── icon-512.svg        ← App icon (large)
    └── og-image.svg        ← Social preview image (WhatsApp/LinkedIn)
```

---

## 🚀 How to deploy on GitHub Pages (step by step)

### Step 1 — Create repository
1. Go to **github.com** → click **New repository**
2. Repository name: `flipper-edu`
3. Set to **Public**
4. Do NOT tick "Add a README file"
5. Click **Create repository**

### Step 2 — Upload all files
1. On your new repository page, click **Add file → Upload files**
2. Extract the zip on your computer
3. Open the `flipper-edu` folder
4. Select **all files and the assets folder** → drag into GitHub upload area
5. Scroll down → Commit message: `Initial commit — FlipperEdu`
6. Click **Commit changes**

### Step 3 — Enable GitHub Pages
1. Go to repository **Settings** (top menu)
2. Scroll down → click **Pages** in the left sidebar
3. Under **Source** → select **Deploy from a branch**
4. Branch: **main** | Folder: **/ (root)**
5. Click **Save**
6. Wait 2–3 minutes

### Step 4 — Your site is live!
```
https://YOUR-USERNAME.github.io/flipper-edu/
```
Replace `YOUR-USERNAME` with your actual GitHub username.

### Step 5 — Update your username in the file (optional)
Open `index.html` and find the two lines with `YOUR-USERNAME` and replace with your actual GitHub username. This fixes the canonical URL and OG tags.

---

## 📚 What this teaches

| Module | Real-world scenario |
|--------|-------------------|
| 📡 Sub-GHz | Person presses garage remote → signal travels → Flipper captures → replays |
| 🪪 RFID/NFC | Employee taps office key fob → EM field powers card → UID sent → cloned |
| 📺 Infrared | Press TV remote → IR LED pulses → light travels → Flipper learns → replays |
| 💾 Bad USB | Plug Flipper into laptop → OS trusts keyboard → script injects keys in 5 sec |
| 📶 Bluetooth | BLE devices broadcast → Flipper scans → packets decoded → spam attack |
| 🏆 Quiz | 10 questions covering all 5 modules with detailed explanations |

---

## ✨ Features

- **Sticky canvas** — animation stays in view, page never scrolls while playing
- **Play All Steps** — auto-animates through all 5 steps with smooth transitions
- **Prev / Next buttons** — go through steps manually at your own pace
- **Real-world scenes** — garage door, office door reader, Samsung TV, laptop, coffee shop
- **Live terminal** — shows what Flipper Zero's screen would actually display
- **PWA installable** — works offline, can be installed as an app on Android/iOS
- **Custom 404 page** — themed error page
- **Social preview** — OG image for WhatsApp and LinkedIn sharing

---

## ⚠️ Legal disclaimer

All simulations are **100% virtual**. No real wireless signals are transmitted.

Using any of these techniques on devices you do not own is **illegal in India** under **IT Act 2000, Section 66** — up to 3 years imprisonment + ₹5 lakh fine.

This website is for educational purposes only. Always get **written permission** before testing any security technique.

---

*Made by [@sudo.learner](https://www.instagram.com/sudo.learner) · MIT License · Educational use only*
