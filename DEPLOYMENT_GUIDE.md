[DEPLOYMENT_GUIDE.md](https://github.com/user-attachments/files/29580804/DEPLOYMENT_GUIDE.md)
# InvestTrack Pro - Deployment Guide for Squarespace

Complete step-by-step instructions to get your tracker live on your Squarespace domain.

---

## 🚀 Fastest Path: GitHub + Netlify + Squarespace

This approach takes **~10 minutes** and requires no coding.

### Step 1: Create a GitHub Account (2 minutes)

1. Go to [github.com](https://github.com)
2. Click **Sign up**
3. Enter email, password, username
4. Verify email
5. Done!

### Step 2: Create a New Repository (2 minutes)

1. Log into GitHub
2. Click **+** icon (top right) → **New repository**
3. Name it: `investtrack-pro`
4. Leave everything else default
5. Click **Create repository**
6. Click **uploading an existing file** link
7. Drag `index.html` into the box
8. Click **Commit changes**

✅ Your code is now on GitHub!

---

### Step 3: Deploy to Netlify (3 minutes)

1. Go to [netlify.com](https://netlify.com)
2. Click **Sign up**
3. Choose **GitHub** option
4. Authorize Netlify to access GitHub
5. Click **New site from Git**
6. Select your `investtrack-pro` repository
7. Click **Deploy site**

Netlify generates a URL: `https://your-random-name.netlify.app`

✅ Your tracker is now LIVE!

---

### Step 4: Add to Squarespace (3 minutes)

Now embed the live tracker in Squarespace:

1. Log into Squarespace
2. Go to **Pages**
3. Click **+** to create new page
4. Choose **Blank** template
5. Name it: "Investment Tracker"
6. Click **Edit** when page is created
7. Click **+** icon to add content block
8. Search for **Code** block
9. Click to add it
10. Paste this code:

```html
<div style="width: 100%; height: 1400px; border: none; border-radius: 8px; overflow: hidden;">
    <iframe src="https://YOUR-NETLIFY-URL.netlify.app" style="width: 100%; height: 100%; border: none;"></iframe>
</div>
```

11. Replace `YOUR-NETLIFY-URL` with your actual Netlify URL
12. Click **Publish**

✅ Your tracker is embedded in Squarespace!

---

## 📝 Your File Downloads

You have 2 files ready in your outputs folder:

1. **index.html** - The complete tracker application
2. **README.md** - Documentation

That's all you need!

---

## 🔧 Updating Your Tracker

If you ever want to update the tracker (bug fixes, new features):

1. Download new `index.html`
2. Go to GitHub → your `investtrack-pro` repo
3. Click **index.html** file
4. Click edit pencil icon
5. Delete all content
6. Paste new code
7. Click **Commit changes**
8. Netlify auto-deploys in ~30 seconds

Your Squarespace page updates automatically!

---

## ✅ Final Checklist

- [ ] GitHub account created
- [ ] `investtrack-pro` repository created
- [ ] `index.html` uploaded to GitHub
- [ ] Netlify account created
- [ ] Site deployed to Netlify
- [ ] Netlify URL copied
- [ ] Code block added to Squarespace
- [ ] Tracker embedded in Squarespace page
- [ ] Page published
- [ ] Test it works on mobile

---

## 🆘 Troubleshooting

**Tracker not showing in Squarespace?**
- Check your Netlify URL is correct in the iframe code
- Make sure GitHub repo is public
- Wait 30 seconds for Netlify to deploy

**Getting 404 errors?**
- Reload the Squarespace page (Ctrl+Shift+R)
- Check the Netlify URL directly in browser

**Data not persisting?**
- Check browser local storage is enabled
- Try clearing browser cache if using old version

**Need more help?**
- Check the README.md file included
- Visit [netlify.com/support](https://netlify.com/support)
- Visit [github.com/contact](https://github.com/contact)

---

## 📊 What You Get

- Professional portfolio tracker
- Real-time stock prices
- Dark mode
- Mobile responsive
- CSV export
- Completely free hosting
- Auto-updating (push to GitHub)

---

**You're all set! Start with Step 1 above.** ✨
