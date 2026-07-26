# MILANO CAFE WEBSITE - MAINTENANCE GUIDE

## Keep Your Website Fresh & Performing

---

## 📅 MAINTENANCE SCHEDULE

### Weekly Tasks (15 minutes)
- [ ] Check website loads properly
- [ ] Verify all links work
- [ ] Monitor contact form submissions
- [ ] Check for any error messages

### Monthly Tasks (30 minutes)
- [ ] Update menu items/prices if changed
- [ ] Verify business hours are current
- [ ] Check contact information accuracy
- [ ] Review website analytics
- [ ] Test mobile responsiveness
- [ ] Verify images all display
- [ ] Check all buttons function

### Quarterly Tasks (1 hour)
- [ ] Update testimonials/reviews
- [ ] Refresh website photos
- [ ] Optimize for SEO
- [ ] Review and improve copy
- [ ] Check site speed (PageSpeed Insights)
- [ ] Update team/chef info if needed
- [ ] Review analytics trends

### Annual Tasks (2-3 hours)
- [ ] Renew domain registration
- [ ] Update SSL certificate
- [ ] Major content refresh
- [ ] Consider design updates
- [ ] Full security audit
- [ ] Backup all files
- [ ] Update business info

---

## 🔄 COMMON UPDATES

### Update Menu Items

**To Change a Price:**

1. Go to GitHub repository
2. Click `menu.html`
3. Click pencil (edit) icon
4. Find the item (e.g., "Veal Parmesan")
5. Change the price: `<span class="price">$28</span>`
6. Scroll down and click "Commit changes"
7. Add message: "Update Veal Parmesan price"
8. Live in 1-2 minutes

**To Add a New Item:**

1. Go to `menu.html`
2. Click pencil (edit) icon
3. Find the right category section
4. Copy an existing item:
   ```html
   <div class="menu-item">
       <div class="item-header">
           <h3>New Item Name</h3>
           <span class="price">$XX</span>
       </div>
       <p class="item-description">Item description here</p>
   </div>
   ```
5. Paste below existing items
6. Update name, price, description
7. Commit changes

**To Remove an Item:**

1. Go to `menu.html`
2. Click pencil
3. Find the item
4. Delete the entire `<div class="menu-item">` block
5. Commit changes

### Update Hours

**Find all instances of:**
```
Mon - Sat: 11am - 9pm
Sunday: Closed
```

**Update in these files:**
- index.html
- about.html
- menu.html
- reservations.html
- ordering.html
- contact.html
- README.md

**Process:**
1. Open each file
2. Use browser Find (Ctrl+F) to locate hours
3. Click pencil, edit time
4. Commit changes
5. Repeat for all files

### Update Contact Information

**Phone Number:**

Search for: `(512) 428-6076`

Replace in all HTML files:
1. index.html
2. about.html
3. menu.html
4. reservations.html
5. ordering.html
6. contact.html

**Email Address:**

Search for: `cafemilanoaustin@gmail.com`

Replace in all files

**Address:**

Search for: `4601 Southwest Parkway, Austin, TX 78745`

Replace in all files

**Map Update:**

If address changes:
1. Go to Google Maps
2. Search new address
3. Get the embed code
4. Replace in contact.html

### Update About Page

**Chef Bio:**

1. Open about.html
2. Click pencil
3. Find "Meet Our Chef" section
4. Update bio text
5. Change chef image path if needed
6. Commit

**Restaurant Story:**

1. Open about.html
2. Find "Our Story" section
3. Update text as needed
4. Commit

**Values:**

1. Find "Our Core Values" section
2. Update any value descriptions
3. Add/remove values if needed
4. Keep formatting consistent
5. Commit

### Update Photos

**Replace Hero Image:**

1. Prepare new image (1200x600px, optimized)
2. Go to repository → assets → images
3. Click `hero-image.jpg`
4. Click pencil, delete content
5. Click "Upload file" icon
6. Select new image
7. Commit changes

**Add Gallery Photo:**

1. Prepare new image (400x300px, optimized)
2. Go to repository → Add file → Upload files
3. Drag new image to upload area
4. Make sure it goes to assets/images/
5. Commit
6. Update gallery section in about.html

**Replace Any Image:**

1. Get new image file
2. Compress with TinyPNG.com
3. Go to file in GitHub
4. Click pencil, delete
5. Upload new image
6. Use same filename
7. Commit

---

## 📊 ANALYTICS & MONITORING

### Google Analytics Setup (If Not Done)

1. Go to google.com/analytics
2. Sign in with Google account
3. Click "Start measuring"
4. Enter your website URL
5. Create property
6. Get tracking ID
7. Add to index.html:
   ```html
   <script async src="https://www.googletagmanager.com/gtag/js?id=GA_ID"></script>
   <script>
   window.dataLayer = window.dataLayer || [];
   function gtag(){dataLayer.push(arguments);}
   gtag('js', new Date());
   gtag('config', 'GA_ID');
   </script>
   ```
   Replace GA_ID with your tracking ID
8. Commit changes

### What to Monitor

**Monthly Metrics:**
- Total visitors
- Pages viewed
- Average time on site
- Bounce rate
- Traffic sources
- Mobile vs desktop

**Quarterly Review:**
- Most viewed pages
- Least viewed pages
- Traffic trends
- User behavior patterns
- Form submissions
- Link clicks

**Actionable Insights:**
- If menu viewed 1000x/month → menu working!
- If reservation button low clicks → check CTA
- If mobile traffic high → ensure mobile perfect
- If bounce rate high → improve content

---

## 🎯 SEO MAINTENANCE

### Google Search Console Setup

1. Go to search.google.com/search-console
2. Click "Add property"
3. Enter your domain: milanoaustin.com
4. Add verification code to site
5. Monitor search performance

### Monthly SEO Checks

- [ ] Check search keywords in Search Console
- [ ] Verify site indexed in Google
- [ ] Review mobile usability
- [ ] Check for broken links
- [ ] Verify meta tags present
- [ ] Update schema markup if needed

### Improve Rankings

**For "Italian restaurant Austin":**
1. Make sure phrase in title
2. Include in descriptions
3. Include in headings
4. Natural mentions in content
5. Local keywords throughout

**Get Local Links:**
- Submit to business directories
- Get listed on Yelp, Google Maps
- Local news mentions
- Chamber of Commerce
- Local business associations

**Encourage Reviews:**
- Add "Review us" link to website
- Include in email receipts
- Mention in restaurant
- Respond to all reviews

---

## ⚡ PERFORMANCE OPTIMIZATION

### Page Speed Test (Quarterly)

1. Visit pagespeed.web.dev
2. Enter your domain
3. Get overall score
4. Review recommendations
5. Implement improvements

### Optimization Tips

**Reduce Image Size:**
```
Use TinyPNG.com
- Upload image
- Download compressed version
- Reduces file by 50-80%
- No visible quality loss
```

**Image Dimensions:**
- Hero: 1200x600px (max)
- Gallery: 400x300px (max)
- Menu items: 300x200px (max)
- Don't upload huge files

**Minimize CSS/JavaScript:**
- Remove unused code
- Use minifiers (cssminifier.com)
- Keep external requests low

**Browser Caching:**
- Already enabled on GitHub Pages
- Static files cached 10 minutes
- Nothing to do!

**Content Delivery:**
- GitHub Pages uses CDN
- Content served from closest server
- Already optimized!

---

## 🔒 SECURITY MAINTENANCE

### Monthly Security Checks

- [ ] HTTPS enabled (check 🔒 icon)
- [ ] No security warnings in browser
- [ ] Contact form handling secure
- [ ] No outdated code
- [ ] Links to trusted services only

### Annual Security Audit

1. Check SSL certificate validity
2. Verify HTTPS status
3. Review code for vulnerabilities
4. Check for outdated libraries
5. Update any deprecated code
6. Test contact form security

### Best Practices

- ✅ Keep backups of all files
- ✅ Use strong passwords
- ✅ Enable two-factor auth on GitHub
- ✅ Verify external links (reservation, ordering systems)
- ✅ Monitor for phishing attempts
- ✅ Regular backups to local drive

---

## 💾 BACKUP PROCEDURES

### Weekly Backup (Automated)

GitHub automatically keeps version history:
- Every change is tracked
- Can revert to any previous version
- Data redundancy built-in

### Monthly Manual Backup

**On Windows:**
1. Go to your Milano Cafe folder
2. Right-click → "Copy"
3. Navigate to external hard drive or cloud
4. Right-click → "Paste"
5. Folder backed up!

**On Mac:**
1. Open Milano Cafe folder
2. Cmd+C to copy
3. Open external drive
4. Cmd+V to paste
5. Backed up!

**To Cloud (Google Drive/OneDrive):**
1. Open Google Drive
2. Click "New" → "Folder upload"
3. Select Milano Cafe folder
4. Upload completes
5. Backed to cloud!

### Restore from Backup

If something goes wrong:
1. Download backup folder
2. Re-upload to GitHub
3. Website back to that state
4. Easy recovery!

---

## 🐛 TROUBLESHOOTING COMMON ISSUES

### Page Not Updating After Changes

**Cause:** Browser cache showing old version

**Solution:**
1. Hard refresh: Ctrl+Shift+R (Windows) or Cmd+Shift+R (Mac)
2. Or clear browser cache
3. Or open in incognito/private window
4. Wait 2 minutes and try again

### Images Broken After Upload

**Cause:** Incorrect file paths

**Solution:**
1. Check image in assets/images/ folder
2. Verify filename exactly matches in HTML
3. Check case (JPG vs jpg matters)
4. File size under 500KB
5. Format supported (jpg, png, gif)

### Mobile Menu Not Working

**Cause:** JavaScript not loaded

**Solution:**
1. Check script.js exists
2. Path correct in HTML: `assets/js/script.js`
3. Open DevTools (F12)
4. Check Console for errors
5. Try different browser

### Forms Not Responding

**Cause:** JavaScript issues or no backend

**Solution:**
1. Check script.js loads
2. Open DevTools Console (F12)
3. Look for JavaScript errors
4. Forms show "thank you" but don't email
5. To enable email, add form service:
   - Formspree.io
   - Basin.com
   - Netlify Forms

### Site Slow to Load

**Cause:** Large images or network issue

**Solution:**
1. Compress all images with TinyPNG.com
2. Check PageSpeed Insights for bottlenecks
3. Reduce image count
4. Use correct image sizes
5. Check internet connection

### Domain Not Pointing to Site

**Cause:** DNS not configured or not propagated

**Solution:**
1. Wait 24-48 hours for propagation
2. Verify DNS records at registrar
3. Check CNAME record correct
4. Clear DNS cache:
   - Windows: `ipconfig /flushdns` in command prompt
   - Mac: `sudo dscacheutil -flushcache` in terminal
5. Try different browser

---

## 📈 GROWTH OPTIMIZATION

### Increase Website Traffic

1. **SEO Optimization:**
   - Target keywords
   - Add local content
   - Get listed in directories
   - Build backlinks

2. **Social Media:**
   - Share on Facebook, Instagram
   - Post menu highlights
   - Share customer photos
   - Announce specials

3. **Email Marketing:**
   - Add newsletter signup
   - Send updates to list
   - Promote special events
   - Share menu changes

4. **Local Partnerships:**
   - Partner with local influencers
   - Get featured in local media
   - Cross-promote with other restaurants
   - Sponsor community events

5. **Google My Business:**
   - Keep profile updated
   - Post regularly
   - Respond to reviews
   - Add photos/videos

### Increase Conversions

**From Visitor to Customer:**
1. Clear CTAs (buttons visible)
2. Easy reservation process
3. Simple ordering
4. Mobile optimized
5. Fast load times
6. Trust signals (reviews, ratings)
7. Contact info prominent

---

## 📝 CONTENT CALENDAR

### Monthly Content Ideas

**January:**
- New Year specials
- Health-conscious menu options
- Resolution motivation

**February:**
- Valentine's Day promotions
- Romantic dinner packages
- Couple testimonials

**March:**
- Spring menu updates
- Easter preparations
- Chef features

**April-May:**
- Spring ingredients
- Outdoor dining (if available)
- Mother's Day/Father's Day

**June-August:**
- Summer events
- Seasonal specials
- Wine pairings
- Chef interviews

**September-October:**
- Fall ingredients
- Harvest specials
- Event hosting

**November-December:**
- Holiday specials
- Gift cards
- Year-end gratitude
- New Year previews

---

## ✅ MAINTENANCE CHECKLIST TEMPLATE

### Weekly
- [ ] Site loads properly
- [ ] All links work
- [ ] No error messages
- [ ] Check contact submissions

### Monthly
- [ ] Menu current
- [ ] Hours correct
- [ ] Contact info verified
- [ ] Review analytics
- [ ] Test mobile
- [ ] Images display
- [ ] All buttons work

### Quarterly
- [ ] Update testimonials
- [ ] Refresh photos
- [ ] SEO check
- [ ] Copy review
- [ ] Speed test
- [ ] Team info current
- [ ] Analytics review

### Annual
- [ ] Domain renewal
- [ ] SSL renewal
- [ ] Content refresh
- [ ] Design review
- [ ] Security audit
- [ ] Full backup
- [ ] Business info update

---

## 📞 WHEN TO CONTACT HELP

**Technical Issues:**
- GitHub Pages not working → GitHub Support
- Domain DNS issues → Domain registrar support
- Security concerns → GitHub security team

**Web Development Questions:**
- Stack Overflow (stackoverflow.com)
- Web Dev communities (Reddit r/webdev)
- MDN Web Docs

**Restaurant Marketing:**
- Local marketing consultant
- Social media expert
- SEO specialist

---

*Keep your Milano Cafe website fresh, fast, and successful! 🍝*
