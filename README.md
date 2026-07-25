# Milano Cafe - Professional Restaurant Website

**A modern, mobile-first restaurant website built with HTML5, CSS3, and JavaScript**

---

## 📋 PROJECT OVERVIEW

**Milano Cafe** is an authentic Italian restaurant in Austin, Texas. This website provides a complete digital presence with online reservations, ordering, menu viewing, and customer engagement.

### Website Features:
✅ Fully responsive design (mobile, tablet, desktop)
✅ SEO optimized with schema markup
✅ Fast loading times
✅ Accessible (WCAG compliant)
✅ Mobile-first navigation
✅ Smooth animations
✅ Contact forms
✅ Embedded maps
✅ Online ordering integration
✅ Reservation system integration

---

## 📁 PROJECT STRUCTURE

```
milano-cafe-v3/
│
├── index.html                    # Home page
├── about.html                    # About page (story, chef, values)
├── menu.html                     # Full menu with categories
├── reservations.html             # Reservation information
├── ordering.html                 # Online ordering info
├── contact.html                  # Contact form & location
│
├── assets/
│   ├── css/
│   │   └── styles.css           # Main stylesheet (2000+ lines)
│   ├── js/
│   │   └── script.js            # JavaScript functionality
│   ├── images/                  # Add restaurant photos here
│   │   ├── hero-image.jpg
│   │   ├── restaurant-1.jpg
│   │   ├── restaurant-2.jpg
│   │   ├── chef.jpg
│   │   ├── dish-1.jpg
│   │   ├── dish-2.jpg
│   │   ├── dish-3.jpg
│   │   ├── wine-bar.jpg
│   │   ├── event.jpg
│   │   └── favicon.ico
│   └── favicon.ico              # Website icon
│
└── README.md                     # This file
```

---

## 🎨 DESIGN & BRANDING

**Color Palette:**
- Primary Red: `#c41e3a` (Italian red)
- Secondary Green: `#1a472a` (Deep forest green)
- Gold Accent: `#d4af37` (Premium accent)
- Text: `#1a1a1a` (Dark)
- Background: `#f9f7f4` (Warm off-white)

**Typography:**
- Headlines: Georgia (serif) - elegant, traditional
- Body: Segoe UI (sans-serif) - modern, readable

---

## 📄 PAGE DESCRIPTIONS

### 1. Home (index.html)
- **Hero Section**: Eye-catching banner with CTA buttons
- **Featured Dishes**: Showcase 3 signature items
- **Why Choose Us**: 6 key benefits
- **Testimonials**: Customer reviews
- **Location**: Map and contact info
- **Call-to-Action**: Reserve or order buttons

### 2. About (about.html)
- **Restaurant Story**: Company history
- **Chef Introduction**: Executive chef background
- **Core Values**: 6 key values (authenticity, quality, community, etc.)
- **Photo Gallery**: 6 restaurant images
- **Why We're Different**: Competitive advantages

### 3. Menu (menu.html)
- **Antipasti**: 4 appetizers
- **Salads (Insalata)**: 5 salads + add-ons
- **Pasta Entrees**: 11 pasta dishes
- **Veal**: 3 veal dishes
- **Chicken**: 3 chicken dishes
- **Seafood**: 5 seafood dishes
- **Vegetarian**: 2 vegetarian dishes
- **Pizza**: 10 pizza options
- **Panini**: 6 sandwiches
- **Dietary Info**: Gluten-free, vegetarian, allergy notes

### 4. Reservations (reservations.html)
- **Booking Methods**: Online, phone, email options
- **Reservation Policy**: Cancellation, seating, party changes
- **Hours & Location**: Business info
- **Dining Experiences**: 6 experience types
- **Call-to-Action**: Book now button

### 5. Ordering (ordering.html)
- **Delivery & Pickup**: Options and details
- **Why Order from Us**: 6 benefits
- **Popular Items**: Quick menu showcase
- **Delivery Info**: Hours, fees, payment
- **Call-to-Action**: Order now button

### 6. Contact (contact.html)
- **Contact Information**: Address, phone, email, hours
- **Contact Form**: Name, email, phone, subject, message
- **Location Map**: Embedded Google Map
- **Quick Links**: Common actions
- **FAQ**: 6 common questions

---

## 🚀 DEPLOYMENT OPTIONS

### Option A: GitHub Pages (FREE & EASY)

**Step 1: Create GitHub Account**
1. Go to github.com
2. Click "Sign up"
3. Enter email, create password, username
4. Verify email

**Step 2: Create Repository**
1. In GitHub, click "+" → "New repository"
2. Name: `milano-cafe-v3`
3. Description: "Professional Italian Restaurant Website"
4. Choose "Public"
5. Click "Create repository"

**Step 3: Upload Files**
1. Click "Add file" → "Upload files"
2. Drag all project files into the upload area
3. Create folders: `assets/css`, `assets/js`, `assets/images`
4. Upload files to correct folders
5. Commit with message: "Initial website commit"

**Step 4: Enable GitHub Pages**
1. Go to repository "Settings"
2. Scroll to "Pages" section
3. Under "Source", select branch "main"
4. Click "Save"
5. Wait 1-2 minutes
6. Your site is live at: `https://tbarnet2.github.io/milano-cafe-v3/`

**Step 5: Connect Custom Domain**
1. In GitHub Settings → Pages
2. Under "Custom domain", enter: `milanoaustin.com`
3. Go to your domain registrar (GoDaddy, etc.)
4. Edit DNS records:
   - Add CNAME record: `www.milanoaustin.com` → `tbarnet2.github.io`
   - Or use A records (GitHub provides options)
5. Wait 24 hours for DNS to propagate
6. Visit `milanoaustin.com`

**Step 6: Enable HTTPS**
1. In GitHub Settings → Pages
2. Check "Enforce HTTPS"
3. Certificate auto-provisions in 24 hours

**Step 7: Update Site Later**
1. Edit any file in GitHub (click pencil icon)
2. Make changes
3. Commit changes
4. Or upload new files/images
5. Changes live in 1-2 minutes

---

### Option B: Microsoft Azure Static Web Apps (FREE tier available)

**Step 1: Create Azure Account**
1. Go to azure.microsoft.com
2. Click "Start free"
3. Sign in with Microsoft account
4. Get $200 free credits
5. Provide payment info (won't charge)

**Step 2: Create Static Web App**
1. Search "Static Web Apps"
2. Click "Create"
3. Select subscription
4. Resource group: Create new "milano-cafe"
5. Name: "milano-cafe-website"
6. Region: Choose closest to Austin (e.g., South Central US)
7. Hosting plan: Free
8. Click "Next: Deployment details"

**Step 3: Connect GitHub**
1. Click "Sign in with GitHub"
2. Authorize Azure
3. Select organization: Your account
4. Repository: milano-cafe-v3
5. Branch: main
6. Build presets: Custom
7. App location: `/`
8. API location: (leave blank)
9. Output location: `/`

**Step 4: Review & Create**
1. Click "Create"
2. Wait 5 minutes for deployment
3. You'll get a URL: `https://[random-name].azurestaticapps.net`

**Step 5: Connect Custom Domain**
1. In your Static Web App → Custom domains
2. Click "Add"
3. Select "CNAME"
4. Enter domain: `milanoaustin.com`
5. Go to domain registrar
6. Add CNAME record: `milanoaustin.com` → Azure's CNAME target
7. Wait 24 hours

**Step 6: Enable HTTPS**
1. Azure enables HTTPS automatically
2. Certificate provided free

**Step 7: Maintain Website**
1. Edit files in GitHub
2. Commit changes
3. Azure automatically redeploys
4. Live in 2-3 minutes

---

### Option C: GoDaddy Hosting (Paid - $2-5/month)

**Step 1: Purchase Hosting**
1. Go to godaddy.com
2. Click "Hosting"
3. Select "Web Hosting" plan (~$2.99/month)
4. Add to cart
5. Complete checkout

**Step 2: Purchase Domain**
1. If you don't have `milanoaustin.com`
2. Search domain on GoDaddy
3. Add to cart (~$12.99/year)
4. Complete checkout

**Step 3: Access Hosting Dashboard**
1. Go to godaddy.com/account
2. Click "My Products"
3. Find your hosting account
4. Click "Manage"
5. You'll see File Manager

**Step 4: Upload Website Files**
1. In File Manager, navigate to `public_html`
2. Create folder structure:
   - `assets/css/`
   - `assets/js/`
   - `assets/images/`
3. Upload all HTML files to root
4. Upload CSS to `assets/css/`
5. Upload JS to `assets/js/`
6. Upload images to `assets/images/`

**Step 5: Configure DNS**
1. In GoDaddy Dashboard → Domains
2. Click your domain
3. DNS settings already connected to hosting
4. Website automatically live

**Step 6: Test Website**
1. Visit `milanoaustin.com`
2. All pages should load
3. Check all links work

**Step 7: Make Updates**
1. Go to GoDaddy File Manager
2. Edit/upload files
3. Changes live in minutes
4. Can edit HTML directly in File Manager

---

## ⚙️ INSTALLATION & SETUP

### Local Testing (Before Deployment)

**On Windows:**
1. Create folder: `C:\Milano-Cafe\`
2. Extract all files into folder
3. Right-click `index.html`
4. Select "Open with" → Chrome/Firefox
5. Website opens in browser
6. Click links to test
7. Use browser DevTools (F12) to check responsive design

**On Mac:**
1. Create folder: `~/Documents/Milano-Cafe/`
2. Extract all files
3. Double-click `index.html`
4. Automatically opens in default browser
5. Test all pages and links

### What You Need:
- ✅ All HTML files (index.html, about.html, etc.)
- ✅ assets/css/styles.css
- ✅ assets/js/script.js
- ✅ assets/images/ (folder with restaurant photos)
- ✅ No backend server needed!

---

## 📸 IMAGE SETUP

You need to add restaurant photos. Replace placeholder paths:

**Location:** `assets/images/`

**Required Images:**
- `hero-image.jpg` - Main hero banner (1200x600px)
- `restaurant-1.jpg` - Dining room (400x300px)
- `restaurant-2.jpg` - Interior/ambiance (400x300px)
- `chef.jpg` - Chef photo (400x400px)
- `dish-1.jpg` - Signature dish #1 (400x300px)
- `dish-2.jpg` - Signature dish #2 (400x300px)
- `dish-3.jpg` - Signature dish #3 (400x300px)
- `wine-bar.jpg` - Wine/bar area (400x300px)
- `event.jpg` - Private event space (400x300px)
- `favicon.ico` - Website icon (32x32px)

**How to Update Images:**
1. Find image paths in HTML files
2. Replace `src="assets/images/dish-1.jpg"` with your image
3. Use high-quality photos (compressed for web)
4. Recommended tool: TinyPNG.com (free compression)

---

## 🔧 CUSTOMIZATION GUIDE

### Change Restaurant Information

**Edit these files to update info:**

1. **Phone Number:**
   - Search: `512-428-6076`
   - Replace with your number in all HTML files

2. **Email:**
   - Search: `cafemilanoaustin@gmail.com`
   - Replace with your email

3. **Address:**
   - Search: `4601 Southwest Parkway, Austin, TX 78745`
   - Replace with your address

4. **Hours:**
   - Search: `11am - 9pm`
   - Update to your hours

5. **Colors:**
   - In `assets/css/styles.css`, find `:root`
   - Change color codes:
     - `--primary-color: #c41e3a;` (main red)
     - `--secondary-color: #1a472a;` (green)
     - `--accent-color: #d4af37;` (gold)

### Update Menu

1. Open `menu.html`
2. Find the section you want to edit
3. Change prices, descriptions, items
4. Format: Each item should follow the template
5. Save file
6. Re-upload to server

### Update About Page

1. Open `about.html`
2. Edit story, chef bio, values
3. Replace placeholder text
4. Add/change images
5. Save and upload

---

## 🧪 TESTING CHECKLIST

Before going live, test:

- [ ] All pages load (index, about, menu, etc.)
- [ ] Navigation menu works
- [ ] Mobile hamburger menu works
- [ ] All links work (internal and external)
- [ ] Contact form submits
- [ ] Reservation button links to external system
- [ ] Order button links to external system
- [ ] Images load properly
- [ ] Maps load and are interactive
- [ ] Responsive design works on phone/tablet/desktop
- [ ] No broken images or 404 errors
- [ ] Fonts load correctly
- [ ] Colors display correctly
- [ ] Forms are functional

**Test on Devices:**
- Desktop (1920x1080, 1366x768)
- Tablet (iPad, 768x1024)
- Mobile (iPhone, 375x667, 414x896)
- Mobile (Android, 360x640)

**Test Browsers:**
- Chrome
- Firefox
- Safari
- Edge

---

## 🐛 TROUBLESHOOTING

### Website Not Loading
**Problem:** "This site can't be reached"
- **Solution 1:** Check domain DNS settings
- **Solution 2:** Verify files uploaded correctly
- **Solution 3:** Wait 24-48 hours for DNS propagation
- **Solution 4:** Check custom domain CNAME/A records

### Images Not Showing
**Problem:** Broken image icons
- **Solution:** Check file paths match folder structure
- **Solution:** Ensure images in `assets/images/` folder
- **Solution:** Check image file names are correct
- **Solution:** Verify image formats (jpg, png, gif)

### Links Not Working
**Problem:** 404 errors on links
- **Solution:** Check href paths in HTML
- **Solution:** Verify files exist in correct folders
- **Solution:** Check for typos in file names (case-sensitive)

### Contact Form Not Working
**Problem:** Form doesn't submit
- **Solution:** Forms currently show alert (not email-enabled)
- **Solution:** To enable email: Integrate Formspree, Netlify Forms, or backend service

### Mobile Menu Not Opening
**Problem:** Hamburger menu doesn't appear/work
- **Solution:** Check JavaScript loaded (`script.js`)
- **Solution:** Verify browser supports JavaScript
- **Solution:** Check browser console for errors (F12)

### Slow Loading
**Problem:** Website takes too long to load
- **Solution:** Compress images using TinyPNG.com
- **Solution:** Reduce image dimensions
- **Solution:** Minimize CSS/JavaScript files
- **Solution:** Enable browser caching

### SSL/HTTPS Errors
**Problem:** "Not secure" warning
- **Solution (GitHub Pages):** Enable "Enforce HTTPS" in settings
- **Solution (Azure):** Automatic, enable custom domain
- **Solution (GoDaddy):** Enable SSL in hosting panel

---

## 📱 MOBILE OPTIMIZATION

This website is built mobile-first:
- ✅ Responsive breakpoints at 768px and 480px
- ✅ Touch-friendly buttons and links
- ✅ Fast loading on 3G/4G
- ✅ Readable font sizes
- ✅ Optimized images

**Test on Real Phone:**
1. Get your website URL
2. Open on phone browser
3. Test all pages
4. Click all buttons and forms
5. Check image quality
6. Verify text is readable

---

## 🔐 SECURITY & MAINTENANCE

### Security Best Practices:
1. **Keep Files Updated:** Regularly check for outdated code
2. **Use HTTPS:** Always use secure connection
3. **Backup Files:** Save copies locally and on GitHub
4. **Monitor Analytics:** Track visitor behavior
5. **Update Contact Info:** Keep phone/email current

### Monthly Maintenance:
1. ✅ Check all links work
2. ✅ Update menu with current items
3. ✅ Verify contact form works
4. ✅ Check photos load
5. ✅ Test on mobile
6. ✅ Update hours if changed
7. ✅ Review and respond to contact forms

### Annual Tasks:
1. ✅ Renew domain (GoDaddy)
2. ✅ Update SSL certificate
3. ✅ Refresh photos
4. ✅ Review and improve content
5. ✅ Optimize for SEO
6. ✅ Update business info

---

## 📊 SEO OPTIMIZATION

This website includes:
- ✅ Meta descriptions on all pages
- ✅ Meta keywords for search engines
- ✅ Open Graph tags for social media
- ✅ Schema markup for local business
- ✅ Mobile-friendly design
- ✅ Fast loading times
- ✅ Clean URL structure
- ✅ Alt text on images

**Additional SEO Tasks:**
1. Submit sitemap to Google Search Console
2. Add Google Analytics tracking
3. Create Google Business Profile
4. Get listed on Yelp, OpenTable
5. Encourage customer reviews

---

## 📞 SUPPORT & RESOURCES

**Need Help?**
- GitHub Pages Docs: https://pages.github.com/
- Azure Static Web Apps: https://docs.microsoft.com/en-us/azure/static-web-apps/
- GoDaddy Support: https://www.godaddy.com/help
- HTML/CSS/JS Learning: https://www.w3schools.com/

**Community Help:**
- Stack Overflow: https://stackoverflow.com/
- GitHub Discussions: Available in your repo
- Web Development Forums: Reddit r/webdev

---

## 📄 FILE PERMISSIONS

All files should have these permissions:
- **HTML files:** Readable by all (644)
- **CSS/JS files:** Readable by all (644)
- **Images:** Readable by all (644)
- **Folders:** Executable (755)

*GitHub Pages and Azure handle this automatically.*

---

## ✅ PRODUCTION CHECKLIST

Before announcing website to public:

- [ ] Domain name configured
- [ ] HTTPS/SSL enabled
- [ ] All pages tested on mobile
- [ ] All links working
- [ ] Contact form functional
- [ ] Menu up-to-date
- [ ] High-quality images added
- [ ] Hours of operation correct
- [ ] Phone/email verified
- [ ] Google Analytics installed
- [ ] Google Business Profile created
- [ ] Website added to Google Search Console
- [ ] Mobile responsive design verified
- [ ] Performance optimized
- [ ] Accessibility checked
- [ ] Social media links added (if applicable)
- [ ] SEO optimized
- [ ] Backup created

---

## 🎓 LEARNING RESOURCES

To understand and modify this code:

**HTML Basics:**
- W3Schools HTML Tutorial: https://www.w3schools.com/html/
- MDN HTML Guide: https://developer.mozilla.org/en-US/docs/Web/HTML

**CSS Styling:**
- W3Schools CSS Tutorial: https://www.w3schools.com/css/
- CSS Grid Guide: https://css-tricks.com/snippets/css/complete-guide-grid/
- Flexbox Guide: https://css-tricks.com/snippets/css/a-guide-to-flexbox/

**JavaScript:**
- W3Schools JS Tutorial: https://www.w3schools.com/js/
- MDN JavaScript Guide: https://developer.mozilla.org/en-US/docs/Web/JavaScript

---

## 📝 VERSION HISTORY

**Version 1.0 - Initial Launch (2024)**
- 6 complete pages
- Full menu with categories
- Responsive design
- Contact form
- Reservation integration
- SEO optimized

---

## 💡 FUTURE ENHANCEMENTS

Consider adding:
- [ ] Customer review system
- [ ] Photo gallery/lightbox
- [ ] Newsletter signup
- [ ] Blog section
- [ ] Video content
- [ ] Live availability calendar
- [ ] Multi-language support
- [ ] Payment integration
- [ ] CMS admin panel
- [ ] Email notifications

---

## 📄 LICENSE

This website code is provided for Milano Cafe's use. All restaurant photos, menu items, and branding are proprietary to Milano Cafe.

---

## 🎉 CONGRATULATIONS!

You now have a professional, modern restaurant website ready for deployment!

**Next Steps:**
1. Choose deployment option (GitHub Pages, Azure, or GoDaddy)
2. Follow the step-by-step guide for your chosen platform
3. Add your restaurant photos
4. Update contact information
5. Test thoroughly
6. Go live!

For questions or assistance, refer to the troubleshooting section or contact the support resources listed above.

---

**Happy hosting! 🍝**

*Built with ❤️ for authentic Italian dining in Austin, Texas*
