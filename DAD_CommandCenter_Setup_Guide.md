# DAD Command Center — GitHub Pages Setup Guide
## One-time setup. 15 minutes. Free forever.

---

## WHAT YOU'LL GET
- A live URL like: **https://jduzan.github.io/dad-command-center/**
- Works on iPhone, iPad, Mac, any browser
- Install to iPhone home screen — opens fullscreen like a real app
- Your DAD logo as the app icon
- Works offline after first load
- All devices share the same data via Google Drive sync

---

## STEP 1 — Create a Free GitHub Account
1. Go to **github.com**
2. Click **Sign up**
3. Use any email — suggest jduzan@duzanadcm.com
4. Choose the **Free** plan

---

## STEP 2 — Create a New Repository
1. After signing in, click the **+** button (top right) → **New repository**
2. Repository name: `dad-command-center`
3. Set to **Public** *(required for free GitHub Pages)*
4. Check **"Add a README file"**
5. Click **Create repository**

---

## STEP 3 — Upload Your Files
You have a zip file: **DAD_CommandCenter_PWA.zip** — unzip it first.

Inside you'll find a folder called `pwa_upload` with:
```
index.html
manifest.json
sw.js
icons/
  icon-57.png
  icon-60.png
  icon-72.png
  icon-76.png
  icon-114.png
  icon-120.png
  icon-144.png
  icon-152.png
  icon-180.png
  icon-192.png
  icon-512.png
  icon-maskable-512.png
```

**Upload them:**
1. In your new repository, click **"uploading an existing file"** (or drag & drop)
2. Drag ALL files from inside `pwa_upload/` into the upload box
   - index.html, manifest.json, sw.js → drag these in
3. Click **Commit changes**
4. Now click **"Create new file"** → type `icons/icon-192.png`
   - Actually easier: use the **drag and drop** on the repo page
   - Drag the entire `icons` folder into GitHub — it will upload all icons

**Easier method for icons:**
1. Click **Add file → Upload files**
2. Drag the `icons` folder directly into the upload area
3. Commit

---

## STEP 4 — Enable GitHub Pages
1. In your repository, click **Settings** (top tab)
2. Scroll down to **Pages** in the left sidebar
3. Under **Source**, select **Deploy from a branch**
4. Branch: **main** | Folder: **/ (root)**
5. Click **Save**
6. Wait 1-2 minutes, then your URL appears:
   **https://[your-username].github.io/dad-command-center/**

---

## STEP 5 — Install on iPhone
1. Open **Safari** on your iPhone (must be Safari, not Chrome)
2. Go to your GitHub Pages URL
3. Tap the **Share button** (box with arrow pointing up)
4. Scroll down → tap **"Add to Home Screen"**
5. Name it: **DAD Command** → tap **Add**
6. The DAD logo icon appears on your home screen!

**Tap it** — it opens fullscreen, no browser bar, exactly like a native app.

---

## STEP 6 — Install on Other Devices

**iPad:** Same as iPhone — Safari → Share → Add to Home Screen

**Mac (Safari):**
- Go to your URL in Safari
- File menu → **Add to Dock** (macOS Sonoma+)
- Or just bookmark it

**Mac (Chrome):**
- Go to your URL
- Click the install icon in the address bar (looks like a monitor with arrow)

**Android:**
- Chrome → menu (3 dots) → **Add to Home Screen**

---

## STEP 7 — Connect Google Drive Sync (share data across all devices)
All your devices will read/write the same data file in Google Drive.

1. Open the app on any device
2. Tap **More** tab (or Notes → "📋 Proposals, History & Tools")
3. Scroll to **☁ GOOGLE DRIVE SYNC**
4. Paste your Apps Script URL
5. Tap **Save & Connect**

Now every device automatically syncs. When you update data on your iPhone, your Mac sees it (tap Sync Now or it auto-syncs on save).

---

## UPDATING THE APP IN THE FUTURE
When Claude gives you an updated HTML file:
1. Go to your GitHub repository
2. Click on `index.html`
3. Click the **pencil icon** (Edit)
4. Or just drag the new file onto the repository — it will replace the old one
5. Commit — GitHub Pages updates in ~60 seconds

---

## YOUR APP URL
```
https://[your-github-username].github.io/dad-command-center/
```
Bookmark this and share it with anyone who needs access.

---

## TROUBLESHOOTING

**App not updating after I upload new files**
→ Wait 2 minutes, then hard-reload: iPhone Safari → hold reload button → "Reload Without Content Blockers"

**"Add to Home Screen" not appearing**
→ Must use Safari on iPhone/iPad, not Chrome or Firefox

**Data not syncing between devices**
→ Make sure Google Drive sync URL is set on each device
→ Tap "↻ Sync Now" manually to force a pull

**Icons look wrong on home screen**
→ Delete the home screen icon, re-add from Safari

---

*Built by Claude for Duzan Architecture + Design Inc.*
*jduzan@duzanadcm.com | 510-931-9632*
