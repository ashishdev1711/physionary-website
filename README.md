# Physionary Developer Website

This is the developer website for the Physionary: Learn Physics Android app.

## 📦 Contents

- `index.html` - Landing page for the app
- `app-ads.txt` - AdMob verification file

## 🚀 Deployment Instructions (GitHub Pages)

### Step 1: Create GitHub Repository

1. Go to [GitHub](https://github.com) and sign in (or create an account)
2. Click the **"+"** icon in the top right → **"New repository"**
3. Repository name: `physionary-website`
4. Make it **Public**
5. Click **"Create repository"**

### Step 2: Upload Files

**Option A: Via GitHub Web Interface (Easiest)**

1. In your new repository, click **"uploading an existing file"**
2. Drag and drop these files from `d:/Antigravity/physionary-website/`:
   - `index.html`
   - `app-ads.txt`
   - `README.md`
3. Click **"Commit changes"**

**Option B: Via Git (If you have Git installed)**

```bash
cd d:/Antigravity/physionary-website
git init
git add .
git commit -m "Initial commit"
git branch -M main
git remote add origin https://github.com/YOUR_USERNAME/physionary-website.git
git push -u origin main
```

### Step 3: Enable GitHub Pages

1. In your repository, click **"Settings"**
2. Scroll to **"Pages"** in the left sidebar
3. Under **"Source"**, select **"main"** branch
4. Click **"Save"**
5. Wait 1-2 minutes for deployment

### Step 4: Get Your Website URL

Your website will be available at:
```
https://YOUR_USERNAME.github.io/physionary-website/
```

Your `app-ads.txt` will be at:
```
https://YOUR_USERNAME.github.io/physionary-website/app-ads.txt
```

### Step 5: Update Play Store & AdMob

**Google Play Console:**
1. Go to [Play Console](https://play.google.com/console)
2. Select "Physionary" app
3. Store presence → Store settings
4. Update **"Website"** field to: `https://YOUR_USERNAME.github.io/physionary-website`
5. Save changes

**AdMob Console:**
1. Go to [AdMob](https://admob.google.com/)
2. Apps → Select "Physionary"
3. Add your website URL
4. AdMob will automatically verify `app-ads.txt` within 24 hours

## ✅ Verification

After deployment, verify your `app-ads.txt` is accessible:
1. Visit: `https://YOUR_USERNAME.github.io/physionary-website/app-ads.txt`
2. You should see: `google.com, pub-1453507651789191, DIRECT, f08c47fec0942fa0`

## 📱 App Info

- **Package:** com.physionary.app
- **AdMob Publisher ID:** pub-1453507651789191
- **Play Store:** [Physionary on Google Play](https://play.google.com/store/apps/details?id=com.physionary.app)

## 🔄 Updates

To update the website:
1. Edit the files locally in `d:/Antigravity/physionary-website/`
2. Upload the changed files to GitHub (same as Step 2)
3. Changes will be live within 1-2 minutes

---

**Need help?** Contact: [Your support email]
