# Quick Hosting Guide - Marathon Training PWA

## Option 1: GitHub Pages (Recommended - Free & Easy)

### Step-by-Step:

1. **Create a GitHub account** (if you don't have one)
   - Go to https://github.com
   - Sign up for free

2. **Create a new repository**
   - Click the "+" in the top right
   - Select "New repository"
   - Name it: `marathon-trainer`
   - Make it Public
   - Click "Create repository"

3. **Upload the HTML file**
   - Click "uploading an existing file"
   - Drag and drop `marathon-trainer.html`
   - Rename it to `index.html` (important!)
   - Click "Commit changes"

4. **Enable GitHub Pages**
   - Go to Settings → Pages
   - Under "Source", select "main" branch
   - Click "Save"
   - Wait 1-2 minutes

5. **Get your URL**
   - Your app will be at: `https://YOUR-USERNAME.github.io/marathon-trainer/`
   - Open this URL on your iPhone in Safari
   - Add to Home Screen

**That's it!** Your app is now hosted for free forever.

---

## Option 2: Netlify (Also Free & Even Easier)

### Step-by-Step:

1. **Go to Netlify**
   - Visit https://www.netlify.com
   - Sign up for free (use GitHub account)

2. **Drag and Drop**
   - On the dashboard, find "Want to deploy a new site without connecting to Git?"
   - Click the drop zone
   - Drag your `marathon-trainer.html` file
   - Rename it to `index.html` first!

3. **Get your URL**
   - Netlify gives you a URL like: `https://random-name.netlify.app`
   - You can customize this in Settings
   - Open on iPhone and add to home screen

**Done!** Your app is live in under 30 seconds.

---

## Option 3: Local Testing (No Hosting)

### For Testing Only:

**Option A: Python Simple Server**
```bash
# In the folder with your HTML file:
python3 -m http.server 8000

# Then on your phone, visit:
# http://YOUR-COMPUTER-IP:8000/marathon-trainer.html
```

**Option B: Direct File**
- Transfer the HTML file to your iPhone (AirDrop, email, etc.)
- Open in Safari
- Add to Home Screen
- Works but won't auto-update

---

## Recommended Setup

**Best Practice:**
1. Host on GitHub Pages or Netlify (takes 5 minutes)
2. This gives you a permanent URL
3. You can update the app anytime by uploading a new version
4. Share the URL with friends who want to train too!

**Benefits of Hosting:**
- Works on any device
- Easy to update
- Can share with others
- Professional URL
- Always accessible

---

## Updating the App

### If hosted on GitHub Pages:
1. Go to your repository
2. Click on `index.html`
3. Click the pencil icon to edit
4. Paste the new version
5. Commit changes
6. Wait 1-2 minutes for deployment

### If hosted on Netlify:
1. Go to your site dashboard
2. Click "Deploys"
3. Drag and drop the new file
4. Done!

---

## Custom Domain (Optional)

Want `marathon.yourdomain.com`?

**GitHub Pages:**
- Add a CNAME file to your repo
- Point your domain's DNS to GitHub

**Netlify:**
- Go to Domain Settings
- Add your custom domain
- Follow the DNS instructions

Both are free! You just need to own a domain name.

---

## Security Note

This app stores all data locally on the device. No data is ever sent to any server. Even when hosted online, it's just serving the HTML file - all your personal training data stays on your phone.

---

**Need help?** 
- GitHub Pages docs: https://pages.github.com
- Netlify docs: https://docs.netlify.com

Happy training! 🏃‍♂️
