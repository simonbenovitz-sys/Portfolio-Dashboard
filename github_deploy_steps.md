# GitHub Pages Deployment Steps 🚀

## Step 1: Create GitHub Repository

1. Go to [github.com](https://github.com) and log in
2. Click the green "New" button (or go to github.com/new)
3. Repository name: `portfolio-dashboard`
4. Make it **Public** (required for free GitHub Pages)
5. ✅ Check "Add a README file"
6. Click "Create repository"

## Step 2: Upload Files

**Option A: Web Interface (Easiest)**
1. In your new repo, click "uploading an existing file"
2. Drag these files from your computer:
   - `index.html`
   - `README.md`
3. Scroll down, add commit message: "Initial dashboard setup 🔥"
4. Click "Commit changes"

**Option B: Git Commands (if you have git installed)**
```bash
git clone https://github.com/YOUR-USERNAME/portfolio-dashboard.git
cd portfolio-dashboard
# Copy your index.html and README.md to this folder
git add .
git commit -m "Initial dashboard setup 🔥"
git push origin main
```

## Step 3: Enable GitHub Pages

1. In your repo, go to **Settings** tab (far right)
2. Scroll down to **Pages** section (left sidebar)
3. Under "Source": Select **Deploy from a branch**
4. Branch: Select **main**
5. Folder: Select **/ (root)**
6. Click **Save**

## Step 4: Access Your Dashboard

After 2-3 minutes, your dashboard will be live at:
**https://YOUR-USERNAME.github.io/portfolio-dashboard**

## Files Ready for Upload

Your workspace now contains:
- ✅ `index.html` - Your dashboard
- ✅ `README.md` - Project description  
- ✅ This instruction file

## Next Steps

Once live, we can:
- Add real-time stock price APIs
- Set up automatic daily updates
- Add mobile app bookmarking
- Integrate with your actual account balances

---

Need help with any step? Just ask! 🔥