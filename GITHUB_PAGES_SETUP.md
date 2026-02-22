# 🚀 PhysioTimer PWA - GitHub Pages Setup Guide

## Step-by-Step Setup (5 minutes)

### **Step 1: Create GitHub Account (if you don't have one)**
- Go to https://github.com
- Sign up (free)
- Verify email

---

### **Step 2: Create a New Repository**
1. Click the **+** icon (top right) → **New repository**
2. Repository name: `physio-timer`
3. **Keep it PUBLIC** (required for free GitHub Pages)
4. ✅ Check "Add a README file"
5. Click **Create repository**

---

### **Step 3: Upload Files**
You need to upload 3 files to your repository:
- `index.html` (rename from physio-timer.html)
- `manifest.json`
- `service-worker.js`

**To upload:**
1. In your repo, click **Add file** → **Upload files**
2. Drag & drop the 3 files OR click to select them
3. Scroll down, click **Commit changes**

---

### **Step 4: Enable GitHub Pages**
1. Go to repository **Settings** (top menu)
2. Scroll down to **Pages** (left sidebar)
3. Under "Source", select:
   - Branch: `main`
   - Folder: `/ (root)`
4. Click **Save**
5. Wait 1-2 minutes for deployment

You'll see: **"Your site is published at https://yourusername.github.io/physio-timer"**

---

### **Step 5: Access Your PWA**

#### **On Desktop:**
- Visit: `https://yourusername.github.io/physio-timer`
- Click the **install icon** (address bar, right side)
- Select **Install PhysioTimer**

#### **On Mobile (iPhone/iPad):**
1. Open Safari
2. Visit: `https://yourusername.github.io/physio-timer`
3. Tap **Share** → **Add to Home Screen**
4. Name: PhysioTimer
5. Tap **Add**

#### **On Mobile (Android):**
1. Open Chrome
2. Visit: `https://yourusername.github.io/physio-timer`
3. Tap **⋮** (menu) → **Install app**
4. Tap **Install**

---

## ✅ After Installation

### **On Your Home Screen:**
- PhysioTimer appears as a native app icon
- Tap to open (loads instantly from cache)
- Works **100% offline** after first load
- All your saved routines stay saved

---

## 📝 File Structure in Your Repo

```
physio-timer/
├── index.html          (rename from physio-timer.html)
├── manifest.json       (PWA config)
├── service-worker.js   (offline support)
└── README.md          (auto-generated)
```

---

## 🔄 Update Your App (After Changes)

If you want to update the app:
1. Edit files in GitHub (or upload new versions)
2. Click **Commit changes**
3. GitHub auto-deploys (takes 1-2 minutes)
4. On your phone: Restart the app or refresh

---

## ❓ Troubleshooting

### **"Install button not showing"**
- Make sure you're on HTTPS (GitHub Pages is always HTTPS ✅)
- Wait 2-3 minutes for deployment
- Hard refresh: Ctrl+Shift+R (Windows) or Cmd+Shift+R (Mac)

### **"Service worker not working"**
- This is normal on first load
- Refresh the page once
- Offline support activates on 2nd visit

### **"Can't see my changes"**
- Wait 2 minutes for deployment
- Hard refresh your browser (Ctrl+Shift+R)
- Clear browser cache if needed

---

## 💾 Your Data is Safe

- All routines saved to **browser storage** (stays on your device)
- Not synced to GitHub
- Private to your phone/device

---

## 🎉 You're Done!

Your PhysioTimer PWA is now:
- ✅ Live on the web
- ✅ Installable on mobile
- ✅ Works completely offline
- ✅ Loaded from home screen in 1 second

**Share your URL with others:** `https://yourusername.github.io/physio-timer`

---

## 📞 Need Help?

If GitHub Pages doesn't deploy after 5 minutes:
1. Check **Settings** → **Pages** - shows deployment status
2. Click the failed deployment to see errors
3. Usually just needs file refresh or 1-2 minute wait

---

**Enjoy your PWA! 💪**
