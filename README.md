# Ale Fabrik — Website

## Files
- index.html — Homepage
- services.html — Services & pricing
- about.html — About page
- contact.html — Contact form
- impressum.html — Legal notice (German law)
- privacy.html — Privacy policy
- terms.html — Terms & conditions
- style.css — Shared stylesheet
- sitemap.xml — For Google indexing
- CNAME — GitHub Pages custom domain
- robots.txt — Search engine instructions

## Before going live — checklist
- [ ] Replace all [BRACKETED] placeholders in every HTML file
- [ ] Add your Formspree form ID in contact.html (search: YOUR_FORM_ID)
- [ ] Update CNAME if using a different domain
- [ ] Register domain on Namecheap
- [ ] Create GitHub repo, push all files
- [ ] Enable GitHub Pages on main branch
- [ ] Add CNAME DNS record pointing to yourusername.github.io
- [ ] Wait for SSL to provision (usually <30 minutes)
- [ ] Test contact form end-to-end
- [ ] Submit sitemap.xml to Google Search Console

## Deploy commands
git init
git add .
git commit -m "Initial launch"
git remote add origin https://github.com/[USERNAME]/alefabrik.com.git
git push -u origin main
