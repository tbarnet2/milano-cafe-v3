# DEPLOY MILANO CAFE TO GITHUB PAGES

## Complete Step-by-Step Guide

GitHub Pages is **FREE**, **EASY**, and **PERFECT** for restaurant websites.

---

## ✅ STEP 1: Create a GitHub Account (5 minutes)

### Instructions:

1. Go to **github.com**
2. Click the **"Sign up"** button (top right)
3. Enter your **email address**
4. Create a strong **password**
5. Choose a **username** (e.g., "tbarnet2")
   - This will appear in your website URL
   - Use lowercase, no spaces
   - Keep it professional
6. Click **"Create account"**
7. **Verify your email** - Check your inbox for verification link
8. Complete email verification

### After Setup:
- GitHub will show you the home dashboard
- You're ready to create a repository!

---

## ✅ STEP 2: Create a Repository (3 minutes)

### What is a Repository?
- A folder where all your website files live
- GitHub stores, tracks, and publishes everything

### Instructions:

1. On your GitHub home page, click **"+"** (top right)
2. Select **"New repository"**
3. Fill in these details:

**Repository Name:** `milano-cafe-v3`
- ⚠️ IMPORTANT: Use exact name for GitHub Pages to work
- This affects your website URL

**Description:** (Optional)
```
Professional Italian Restaurant Website
Authentic Italian Cuisine in Austin, Texas
```

**Visibility:** Select **"Public"**
- ✅ Public = Everyone can see your website
- ❌ Private = Only you can see it

**Initialize with:**
- ✅ Check "Add a README file"
- ✅ Check "Add .gitignore" → Select "None"
- ❌ Don't add license

4. Click **"Create repository"**

### Success!
You'll see your new repository page. Continue to Step 3!

---

## ✅ STEP 3: Upload Your Website Files (10 minutes)

### Prepare Your Files:

Make sure you have:
- ✅ index.html
- ✅ about.html
- ✅ menu.html
- ✅ reservations.html
- ✅ ordering.html
- ✅ contact.html
- ✅ assets/css/styles.css
- ✅ assets/js/script.js
- ✅ assets/images/ (folder)

### Upload Instructions:

1. Go to your repository page
2. Click **"Add file"** button (right side)
3. Select **"Upload files"**
4. **Drag and drop** all files into the upload area
   - OR click "choose your files" and select them

### Upload Structure:

Upload files to create this structure:
```
milano-cafe-v3/
├── index.html
├── about.html
├── menu.html
├── reservations.html
├── ordering.html
├── contact.html
├── README.md
└── assets/
    ├── css/
    │   └── styles.css
    ├── js/
    │   └── script.js
    └── images/
        ├── hero-image.jpg
        ├── restaurant-1.jpg
        ├── restaurant-2.jpg
        ├── chef.jpg
        ├── dish-1.jpg
        ├── dish-2.jpg
        ├── dish-3.jpg
        ├── wine-bar.jpg
        ├── event.jpg
        └── favicon.ico
```

### Upload HTML Files:

1. In "Add file" upload box
2. Select all 6 HTML files
3. They go in the **root** folder (no subfolder)
4. Click **"Commit changes"**
5. Message: "Add HTML pages"
6. Click **"Commit changes"**

### Create CSS Folder & Upload:

1. Click **"Add file"** → **"Create new file"**
2. Type filename: `assets/css/styles.css`
   - GitHub auto-creates the folders
3. Paste your CSS content (from styles.css file)
4. Click **"Commit new file"**

### Create JS Folder & Upload:

1. Click **"Add file"** → **"Create new file"**
2. Type filename: `assets/js/script.js`
3. Paste your JavaScript content
4. Click **"Commit new file"**

### Upload Images:

1. Click **"Add file"** → **"Upload files"**
2. Select all image files from your assets/images folder
3. They'll upload to root - that's OK
4. After upload, you'll move them to correct folder
5. Click **"Commit changes"**

#### Move Images to Correct Folder:

1. For each image:
   - Click on the image file
   - Click the edit (pencil) icon
   - Change the path from `image-name.jpg` to `assets/images/image-name.jpg`
   - Click **"Commit changes"**

**Alternative (Easier):**
- Use GitHub Desktop app (free download)
- Or use git command line
- Upload folder structure directly

---

## ✅ STEP 4: Enable GitHub Pages (2 minutes)

### What is GitHub Pages?
- GitHub's free hosting service
- Automatically publishes your website
- No server management needed

### Instructions:

1. Go to your repository
2. Click **"Settings"** (top menu)
3. On the left sidebar, scroll down to find **"Pages"**
4. Click **"Pages"**

### Configure Pages:

Under **"Build and deployment"**:

**Source:**
- Change dropdown from "Deploy from a branch" → **"GitHub Actions"**
- OR select **"Branch"** and choose **"main"**

After selecting "main":
- Click **"Save"**
- GitHub will build your site

### Wait for Build:

- You'll see a message: "GitHub Pages is being built"
- Wait 1-2 minutes
- Page refreshes with:
  ```
  Your site is published at:
  https://tbarnet2.github.io/milano-cafe-v3/
  ```

✅ **YOUR WEBSITE IS NOW LIVE!**

### Test Your Website:

1. Copy the URL: `https://tbarnet2.github.io/milano-cafe-v3/`
2. Paste in browser
3. You should see your Milano Cafe homepage
4. Click around to test all pages
5. Check images load
6. Test mobile view (press F12, click mobile icon)

---

## ✅ STEP 5: Connect Custom Domain (10 minutes)

### Why Custom Domain?
- Look professional: `milanoaustin.com` instead of `github.io/milano-cafe-v3`
- Better branding
- Easier for customers to remember

### If You Don't Have a Domain:

**Where to Buy:**
- GoDaddy.com ($12/year)
- Google Domains ($12/year)
- Namecheap.com ($9/year)
- Any domain registrar

**Search for:** `milanoaustin.com`
- Check if available
- Add to cart
- Checkout ($12-15/year)
- Confirm purchase via email

### If You Already Have a Domain:

Proceed to DNS configuration below.

### DNS Configuration:

**Step 1: GitHub Setup**

1. Go to your repository → Settings → Pages
2. Scroll to **"Custom domain"**
3. Enter your domain: `milanoaustin.com`
4. Click **"Save"**
5. GitHub will start checking DNS

**Step 2: Domain Registrar Setup**

You'll see a message from GitHub asking you to configure DNS. Follow their specific instructions, but generally:

**Option A: CNAME Record (Easiest)**

1. Go to your domain registrar (GoDaddy, Google Domains, etc.)
2. Find DNS settings
3. Add a **CNAME** record:
   - **Name:** `www`
   - **Value:** `tbarnet2.github.io`
4. Save changes

**Option B: A Records (More Complex)**

GitHub provides 4 IP addresses:
```
185.199.108.153
185.199.109.153
185.199.110.153
185.199.111.153
```

1. Go to domain registrar
2. Add 4 **A** records (one for each IP)
3. Point to GitHub's servers

**Step 3: Wait for DNS Propagation**

- Changes take 24-48 hours
- Visit `milanoaustin.com` after waiting
- If it doesn't work, troubleshoot DNS

---

## ✅ STEP 6: Enable HTTPS (1 minute)

### What is HTTPS?
- Secure connection (see the 🔒 lock in browser)
- Required for trust
- Protects customer data

### Instructions:

1. Go to repository → Settings → Pages
2. Find **"HTTPS"** section
3. Check the box: **"Enforce HTTPS"**
4. Click **"Save"**
5. Wait 5-10 minutes for certificate

✅ Your website now has a secure connection!

Visit `https://milanoaustin.com` - you'll see the 🔒 lock icon.

---

## ✅ STEP 7: Test Your Website

### Full Testing Checklist:

**Desktop Browser:**
- [ ] All pages load (Home, About, Menu, Reservations, Ordering, Contact)
- [ ] Navigation menu works
- [ ] All links work (internal and external)
- [ ] Buttons work (Reserve, Order, Contact)
- [ ] Images display properly
- [ ] Maps load and work
- [ ] Contact form submits
- [ ] No 404 errors

**Mobile Browser:**
- [ ] Press F12 to open DevTools
- [ ] Click mobile icon (looks like phone)
- [ ] Select iPhone or Android
- [ ] Website responsive
- [ ] Hamburger menu opens/closes
- [ ] Text readable
- [ ] Buttons clickable
- [ ] Images load

**Mobile Device (iPhone or Android):**
- [ ] Visit on your actual phone
- [ ] Test all functionality
- [ ] Check performance
- [ ] Verify no broken links

**Browsers to Test:**
- [ ] Chrome
- [ ] Firefox
- [ ] Safari
- [ ] Edge

---

## ✅ STEP 8: Update Your Site Later

### Making Changes:

**Simple Text Changes:**

1. Go to your repository
2. Click the file you want to edit (e.g., about.html)
3. Click the **pencil (edit)** icon
4. Make your changes
5. Scroll down and click **"Commit changes"**
6. Add a message like "Update about page"
7. Click **"Commit changes"**
8. Wait 1-2 minutes
9. Visit your site - changes live!

**Adding New Images:**

1. Go to repository
2. Click **"Add file"** → **"Upload files"**
3. Select image files
4. Upload to `assets/images/` folder
5. Update HTML to reference new image
6. Commit
7. Changes live in 1-2 minutes

**Updating Menu:**

1. Click on `menu.html`
2. Click pencil (edit) icon
3. Find the item you want to change
4. Update price, description, or add new item
5. Scroll down and commit changes
6. Changes live immediately

**Updating Hours/Contact:**

1. Click on file that contains the info
2. Edit the text
3. Commit changes
4. Live in 1-2 minutes

### Using GitHub Desktop (Optional):

For more advanced users:

1. Download GitHub Desktop (free)
2. Sign in with your GitHub account
3. Clone your repository
4. Make changes to files on your computer
5. "Commit" and "Push" changes
6. Changes automatically sync to GitHub
7. Website updates in 1-2 minutes

---

## 🐛 TROUBLESHOOTING

### Problem: Website Not Loading

**Cause:** Files not uploaded correctly

**Solution:**
1. Check repository has HTML files
2. Verify folder structure is correct
3. Check Settings → Pages → Branch is "main"
4. Wait 5 minutes and try again

### Problem: Images Not Showing

**Cause:** Image paths incorrect

**Solution:**
1. Verify images in assets/images/ folder
2. Check HTML has correct paths: `src="assets/images/filename.jpg"`
3. Make sure filename matches exactly (case-sensitive)

### Problem: Custom Domain Not Working

**Cause:** DNS not configured correctly

**Solution:**
1. Wait 24-48 hours for DNS to propagate
2. Check DNS records are correct at your registrar
3. Visit GitHub repo → Settings → Pages
4. Verify custom domain field is filled
5. Try clearing browser cache (Ctrl+Shift+Del)

### Problem: Menu Not Opening on Mobile

**Cause:** JavaScript not loading

**Solution:**
1. Check script.js file exists in assets/js/
2. Verify HTML references correct path: `src="assets/js/script.js"`
3. Open browser DevTools (F12)
4. Check Console tab for errors

### Problem: Form Not Working

**Cause:** Contact form requires backend setup

**Solution (for now):**
- Form shows "Thank you" message
- To actually send emails, integrate:
  - Formspree.io (free tier)
  - Netlify Forms
  - Basin.com

### Problem: "Custom Domain Already Taken"

**Cause:** Someone registered milanoaustin.com

**Solution:**
- Use alternative domain:
  - milanoaustin.restaurant
  - milanoinaustin.com
  - austinmilano.com
- Or use GitHub's free domain:
  - tbarnet2.github.io/milano-cafe-v3

---

## 📊 PERFORMANCE TIPS

### Speed Up Your Site:

1. **Compress Images:**
   - Use TinyPNG.com (free)
   - Reduces file size by 50-80%
   - No quality loss

2. **Optimize CSS/JavaScript:**
   - Remove unused code
   - Minify (make smaller)

3. **Use Correct Image Sizes:**
   - Hero image: 1200x600px
   - Menu item: 400x300px
   - Don't use huge files

4. **Enable Caching:**
   - GitHub Pages does this automatically

### Check Speed:
- Visit PageSpeed Insights: pagespeed.web.dev
- Enter your URL
- Get performance score
- Fix any issues

---

## ✅ FINAL CHECKLIST

Before announcing to public:

- [ ] GitHub account created
- [ ] Repository created
- [ ] All files uploaded
- [ ] GitHub Pages enabled
- [ ] Custom domain connected
- [ ] HTTPS enabled
- [ ] Website loads on desktop
- [ ] Website loads on mobile
- [ ] All pages work
- [ ] All links work
- [ ] Images display
- [ ] Forms respond
- [ ] Map loads
- [ ] Contact info correct
- [ ] Menu up to date
- [ ] Hours correct
- [ ] Phone/email verified

✅ **YOU'RE READY TO GO LIVE!**

---

## 🎉 NEXT STEPS

1. **Add Analytics:**
   - Sign up for Google Analytics (free)
   - Track visitors
   - See which pages popular
   - Optimize based on data

2. **Create Google Business Profile:**
   - Go to business.google.com
   - Add Milano Cafe
   - Show up in Google Maps
   - Customers can find you easier

3. **Submit to Search Engines:**
   - Google Search Console (free)
   - Bing Webmaster Tools (free)
   - Help search engines find you

4. **Get Listed on Directories:**
   - Yelp
   - OpenTable
   - TripAdvisor
   - More visibility = more customers

5. **Share on Social Media:**
   - Facebook
   - Instagram
   - Twitter
   - Announce your new website!

---

*Happy publishing! Your Milano Cafe website is now live! 🍝*