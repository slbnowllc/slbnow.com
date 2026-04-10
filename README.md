# SLBNow LLC — Website Deployment Guide

## Files in This Package

| File | Purpose |
|------|---------|
| `index.html` | Homepage — three-lane overview, CMMC banner, past performance |
| `cmmc.html` | CMMC Compliance page — RP positioning, tracks, FAQ, free consult CTA |
| `it-services.html` | IT Managed Services page — three tiers, CMMC boundary messaging |
| `federal-subcontracting.html` | Federal subcontracting page — capabilities, team, vehicles, past performance |
| `sitemap.xml` | XML sitemap for Google Search Console submission |
| `robots.txt` | Search engine crawl directives |

## Image Files You Need to Copy From Your Current Repo

- `slbnow_logo.png` — used in nav on all pages
- `sdvosb_badge.png` — used in hero on homepage and federal page
- `cyberab_rp_badge.png` — **NEW: save the CyberAB RP badge image as this filename**

## GitHub Pages Deployment Steps

1. Copy all files into your GitHub Pages repo root (same location as your current `index.html`)
2. Copy `slbnow_logo.png` and `sdvosb_badge.png` from your current repo
3. Save the CyberAB RP badge image as `cyberab_rp_badge.png` in the root
4. Commit and push — GitHub Pages will auto-deploy

## SEO Post-Launch Checklist (Do These Within 48 Hours)

### Google Search Console
1. Go to https://search.google.com/search-console
2. Add property: `https://www.slbnow.com`
3. Verify via HTML tag or DNS
4. Submit sitemap: `https://www.slbnow.com/sitemap.xml`
5. Request indexing for each page individually

### Google Business Profile
1. Go to https://business.google.com
2. Create or claim "SLBNow LLC" listing
3. Category: "IT Service", "Consulting Firm", or "Cybersecurity Service"
4. Add: address (Hudson FL), phone, website, hours
5. Write a 750-character description using these keywords:
   - CMMC compliance, CyberAB Registered Practitioner, defense contractor, SDVOSB, IT managed services, federal program support
6. Add photos (logo, team if available)
7. This is the #1 driver of local/regional top-5 results

### Bing Webmaster Tools
1. Go to https://www.bing.com/webmasters
2. Add site and submit sitemap
3. Bing indexes GSA and DoD contracting searches heavily

### LinkedIn Company Page
- Ensure slbnow.com is listed as company website
- Post about CMMC services — LinkedIn ranks well for B2B govcon searches

## SEO Keywords This Site Targets (by page)

### Homepage
- slbnow.com, SLBNow LLC, federal compliance SDVOSB Florida
- CMMC compliance Florida, IT managed services defense contractor

### cmmc.html (Highest Priority Page)
- CMMC compliance Florida
- CMMC registered practitioner Florida
- CMMC Level 1 readiness small contractor
- CMMC Level 2 readiness defense contractor
- CyberAB registered practitioner Florida
- DFARS 252.204-7021 compliance help
- free CMMC consultation Florida

### it-services.html
- IT managed services defense contractor Florida
- CMMC compliant MSP Florida
- compliance integrated IT services
- CMMC boundary MSP

### federal-subcontracting.html
- SDVOSB subcontractor Florida
- federal program support subcontractor
- VA subcontractor SDVOSB Florida

## Schema Markup Included

All pages include JSON-LD structured data:
- Organization schema (homepage)
- LocalBusiness / ProfessionalService schema (homepage)
- FAQPage schema (homepage + CMMC page)
- Service schema (CMMC, IT Services, Federal pages)
- BreadcrumbList schema (all interior pages)

## Monthly Maintenance

- Update `<lastmod>` dates in sitemap.xml when content changes
- Add Google Reviews once Google Business Profile is active
- Consider adding a blog/news section — govcon content (CMMC updates, DFARS changes) drives organic search traffic significantly
