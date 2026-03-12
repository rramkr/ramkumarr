# How to Deploy ramkumarr.com

## Step 1: Buy the Domain

**Where to buy:** Namecheap, GoDaddy, or Google Domains
- Search for "ramkumarr.com"
- Purchase (typically $10-15/year)
- Set auto-renew to avoid losing it

## Step 2: Choose Hosting

### Option A: Netlify (Recommended - Free & Simple)
**Best for:** Static sites, zero config, automatic HTTPS

1. Go to [netlify.com](https://netlify.com)
2. Sign up with GitHub/email
3. Drag and drop the `index.html` file
4. Site is live instantly at random URL
5. Add custom domain "ramkumarr.com" in settings
6. Netlify provides SSL automatically

**Pros:** Free, fast, automatic HTTPS, easy updates
**Cons:** Static only (but that's all you need)

### Option B: Vercel (Similar to Netlify)
Same process as Netlify, equally good option

### Option C: Traditional Hosting (Bluehost, SiteGround)
If you want traditional cPanel hosting
- More complex setup
- Monthly cost ($5-10/month)
- More features if you expand later

### Option D: GitHub Pages (Free, Tech-Savvy)
If you're comfortable with Git:
1. Create GitHub repo "ramkumarr"
2. Push index.html
3. Enable GitHub Pages in settings
4. Point domain to GitHub

## Step 3: Configure Domain DNS

After buying domain, point it to your hosting:

### For Netlify/Vercel:
In your domain registrar (Namecheap, etc):
- Add A record: `@` → `75.2.60.5` (Netlify's IP)
- Add CNAME: `www` → `your-site.netlify.app`
- Or follow their specific DNS instructions

**Wait time:** 1-24 hours for DNS to propagate

## Step 4: Set Up Email (Google Workspace)

1. **Add ramkumarr.com to Google Workspace**
   - Go to admin.google.com
   - Domains → Add domain
   - Add "ramkumarr.com"
   - Verify ownership (add TXT record to DNS)

2. **Create email alias**
   - Users → Your account → User information
   - Email aliases → Add alias
   - Add "ram@ramkumarr.com"

3. **Start using new email**
   - Update email signature
   - Update LinkedIn, social profiles
   - Both ram@ramsabode.com and ram@ramkumarr.com work

**Cost:** No additional cost if already using Google Workspace

## Step 5: Customize Content

Before going live, update index.html:

1. **Add your professional photo**
   - Replace `[Your professional photo here]` placeholder
   - Upload image, update path

2. **Refine copy**
   - Adjust "About Me" to your voice
   - Update credentials (1000+ clients, 15+ years, etc.)
   - Verify all links work

3. **Test everything**
   - All three venture links work
   - Email link opens correctly
   - Responsive on mobile

## Step 6: Add Analytics (Optional but Recommended)

### Google Analytics
1. Create property at analytics.google.com
2. Add tracking code before `</head>` in HTML
3. Monitor traffic, behavior

### Or use privacy-friendly alternative:
- Plausible Analytics
- Simple Analytics
- Fathom Analytics

## Step 7: Update Other Properties

Once ramkumarr.com is live:

### Social Media
- LinkedIn: Update website to ramkumarr.com
- Twitter: Update bio link
- Instagram: Update bio link

### Email Signatures
Update signature across all ventures:
```
Ramkumar R
ramkumarr.com
ram@ramkumarr.com
```

### Venture Sites (Optional)
Add footer to ramsabode.com, way2top.com, thecrux.ai:
```html
<footer>
  <p>Founded by <a href="https://ramkumarr.com">Ramkumar R</a></p>
</footer>
```

## Step 8: Soft Launch

1. **Test everything** on live site
2. **Share with close friends** for feedback
3. **Update professional network** with new site
4. **Announce on LinkedIn** (optional)

## Maintenance

### Regular Updates
- Keep ventures section current if you launch new platforms
- Update credentials as they grow
- Add media/speaking appearances
- Consider adding blog later

### Domain Renewal
- Set auto-renew to avoid losing domain
- Check annually that DNS/email still working

## Costs Summary

**Minimal setup:**
- Domain: $10-15/year
- Hosting: $0 (Netlify/Vercel free)
- Email: $0 (add to existing Google Workspace)
- **Total: ~$12/year**

**With premium options:**
- Domain: $15/year
- Analytics: $0-9/month
- Email: Already have Google Workspace
- **Total: $15-120/year**

## Quick Start Checklist

- [ ] Buy ramkumarr.com domain
- [ ] Sign up for Netlify (or chosen hosting)
- [ ] Upload index.html
- [ ] Configure DNS to point to hosting
- [ ] Add ramkumarr.com to Google Workspace
- [ ] Create ram@ramkumarr.com email alias
- [ ] Add professional photo to site
- [ ] Customize about section copy
- [ ] Test all links work
- [ ] Set up analytics
- [ ] Update LinkedIn/social profiles
- [ ] Share with network

## Need Help?

If you get stuck:
- Netlify has great docs: docs.netlify.com
- Google Workspace support: support.google.com/a
- DNS usually takes 24hrs, be patient
- Test email after DNS propagates

---

**Time estimate:** 2-3 hours for full setup, mostly waiting for DNS
**Difficulty:** Easy (no coding required beyond what's provided)
