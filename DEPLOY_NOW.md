# 🚀 DEPLOY NOW - Simplest Method

## **Option 1: Vercel Drag & Drop (RECOMMENDED - 2 minutes)**

### Step 1: Open Vercel
Go to: **https://vercel.com/new**

### Step 2: Drag Folder
**Drag this entire folder** into the upload area:
```
/Users/user/Documents/TAURUS-LOCAL-WORKSPACE/active-projects/TAURUS-AI-OPERATIONS/05-CLIENTS_RESOURCE_VAULT/HTML_Demos
```

### Step 3: Deploy
Click **"Deploy"** → Wait 30-60 seconds

### Step 4: Get Your URLs
- **Landing Page:** https://[your-project].vercel.app/landing-page.html
- **Protected Brief:** https://[your-project].vercel.app/protected-executive-brief.html

### Step 5: Set Index Page (Optional)
After deployment, go to:
1. Vercel Dashboard → Your Project → **Settings**
2. Scroll to **"Build & Development Settings"**
3. Output Directory: Leave blank
4. Go to **"Rewrites and Redirects"**
5. Add rule:
   - Source: `/`
   - Destination: `/landing-page.html`

---

## **Option 2: Netlify Drop (Alternative - 2 minutes)**

### Step 1: Open Netlify Drop
Go to: **https://app.netlify.com/drop**

### Step 2: Drag Folder
Drag the `HTML_Demos` folder into the upload area

### Step 3: Done!
Your site is live at: https://[random-name].netlify.app

### Step 4: Rename (Optional)
1. Go to **Site Settings**
2. **Change site name** → `india-rural-fintech`
3. New URL: https://india-rural-fintech.netlify.app

---

## **Your Files Ready for Deployment:**

✅ **landing-page.html** - Main landing page
✅ **protected-executive-brief.html** - Interactive brief (8 slides)
✅ Analytics already integrated (just add your GA4 ID)

---

## **After Deployment:**

1. **Update Analytics:**
   - Get Google Analytics ID: https://analytics.google.com
   - Replace `G-XXXXXXXXXX` in both HTML files with your ID
   - Re-deploy (drag folder again)

2. **Test Your Site:**
   - Visit landing page
   - Click "View Intelligence Report" button
   - Should go to protected brief
   - Test access request form

3. **Share URLs:**
   - Landing: `https://your-site.vercel.app/landing-page.html`
   - Brief: `https://your-site.vercel.app/protected-executive-brief.html`

---

## **Quick Fixes if Needed:**

### If images don't load:
- They use Unsplash CDN - requires internet connection
- Replace with local images if needed

### If links break:
- Update relative paths in HTML files
- Example: `href="/demo/index.html"` → `href="../demo/index.html"`

### If you want custom domain:
- Vercel: Dashboard → Domains → Add
- Netlify: Site Settings → Domain Management → Add custom domain

---

## **CLI Alternative (If You Want to Try Later):**

```bash
# Install Vercel CLI
npm install -g vercel
# or
sudo npm install -g vercel

# Login
vercel login

# Deploy
cd "/Users/user/Documents/TAURUS-LOCAL-WORKSPACE/active-projects/TAURUS-AI-OPERATIONS/05-CLIENTS_RESOURCE_VAULT/HTML_Demos"
vercel --prod
```

---

🚀 **EASIEST: Just drag the HTML_Demos folder to https://vercel.com/new**

Your site will be live in 60 seconds!
