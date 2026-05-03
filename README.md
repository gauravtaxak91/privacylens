# PrivacyLens — AI Privacy Tracker PWA

Track what big tech companies collect about you. AI-powered analysis, policy scanner, and personal exposure calculator.

---

## Deploy to Vercel (Free) — Step by Step

### Step 1 — Create a GitHub account
Go to github.com → Sign Up (free)

### Step 2 — Create a new repository
- Click the "+" icon → New repository
- Name it: `privacylens`
- Set to Public
- Click "Create repository"

### Step 3 — Upload your files
- Click "uploading an existing file"
- Upload everything inside the `privacylens` folder:
  - `public/index.html`
  - `public/manifest.json`
  - `public/sw.js`
  - `public/icon-192.png`
  - `public/icon-512.png`
  - `vercel.json`
- Click "Commit changes"

### Step 4 — Deploy on Vercel
- Go to vercel.com → Sign Up with your GitHub account
- Click "Add New Project"
- Select your `privacylens` repository
- Click "Deploy" — done in ~30 seconds

### Step 5 — Get your URL
Vercel gives you a free URL like: `privacylens.vercel.app`
Share this link and anyone can use your app instantly.

### Step 6 — Add to iPhone Home Screen
- Open your Vercel URL in Safari on iPhone
- Tap the Share button (box with arrow)
- Tap "Add to Home Screen"
- Tap "Add"
- PrivacyLens is now an app on your iPhone!

---

## What works out of the box
- Full PWA — installable on iPhone via Safari
- Works offline (cached via service worker)
- Home screen icon + splash screen
- AI analyst (bottom bar) — powered by Claude
- Policy scanner — paste any privacy policy
- Exposure calculator — personal risk score + AI report
- Company deep dives — AI analysis for all 22 companies

---

## Custom domain (optional, free)
Vercel lets you connect a free `.vercel.app` subdomain or a custom domain you own.
To get a free domain: freenom.com or use your Vercel subdomain.

---

## Sharing tips to get users
1. Post on Reddit: r/privacy, r/degoogle, r/netsec
2. Post on Product Hunt (privacylens.vercel.app)
3. Share on Twitter/X with hashtag #privacy #bigtech
4. Write a blog post: "What data does TikTok collect?" — embed your app link
