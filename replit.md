# Go Green Steam Clean - Static Website

## Overview
Professional, cohesive static HTML website for Go Green Steam Clean, an eco-friendly cleaning business based in Portlaoise, Co. Laois, Ireland. The site features a modern, mobile-responsive design with consistent eco-friendly branding.

## Project Structure
```
/
├── index.html              # Home page
├── about.html              # About Us page
├── contact.html            # Contact page with form
├── carpet-cleaning.html    # Carpet cleaning service page
├── upholstery-cleaning.html # Upholstery cleaning service page
├── mattress-cleaning.html  # Mattress cleaning service page
├── rug-cleaning.html       # Rug cleaning service page
├── commercial-cleaning.html # Commercial cleaning service page
├── water-tank-cleaning.html # Water tank cleaning service page
├── privacy-policy.html     # Privacy policy page
├── assets/
│   ├── css/
│   │   └── custom.css      # Custom eco-friendly branding styles
│   └── images/             # Product and service images
└── package.json            # NPM dependencies
```

## Technology Stack
- Static HTML5/CSS3/JavaScript
- Bootstrap 5.3 (CDN)
- Font Awesome 6.4 (CDN)
- Google Fonts (Inter)
- Custom CSS for eco-friendly branding

## Color Palette
- Primary Green: #2d6a4f
- Secondary Green: #40916c
- Light Green: #74c69d
- Accent Green: #b7e4c7
- Pale Green: #d8f3dc
- Slate Dark: #2d3436
- Slate Medium: #4a5568
- CTA Vibrant Orange: #ff6b35 (for Call Now buttons)

## Running the Site
The site is served using `npx serve` on port 5000.

## Contact Information
- Phone: 085-836 0077
- Email: gogreensteamclean.ie@gmail.com
- Address: Ratheven, Portlaoise, Co. Laois, R32 DY00
- Facebook: https://www.facebook.com/share/18HQcdftXD/
- Instagram: https://www.instagram.com/gogreensteamclean.ie
- Availability: Monday to Friday

## Service Areas
Laois, Kildare, Carlow, Kilkenny, Tipperary, Offaly, and Westmeath

## Services Offered
- Carpet Steam Cleaning
- Upholstery Steam Cleaning
- Mattress Steam Cleaning
- Rug Steam Cleaning
- Commercial Cleaning
- Water Tank Cleaning (Attic tanks, legionella control)

## Image Conventions
- All images are WebP format for performance
- Naming: `{service}-{type}.webp` e.g. `carpet-cleaning-1---before.webp`
- Logo files: `go-green-steam-clean-logo.webp` (130px nav) and `go-green-steam-clean-logo-footer.webp` (128px footer)
- Hero images have `fetchpriority="high"` and a `<link rel="preload">` in `<head>`
- Below-fold/gallery images have `loading="lazy"`
- No unused images should be kept in `assets/images/`

## Recent Changes
- April 2026: Converted all JPG images to WebP (up to 72% file size savings); deleted 19 unused image files; reduced image folder from 19MB to 10MB; renamed all whatsapp-named files to descriptive names; added lazy loading to below-fold images; added fetchpriority="high" and preload hints for hero/LCP images on all pages
- February 2026: Updated footer copyright year to 2026
- February 2026: Replaced car interior cleaning with water tank cleaning service
- February 2026: Added vibrant orange CTA buttons for better visibility on green backgrounds
- February 2026: Updated contact availability from "7 days a week" to "Monday to Friday"
- February 2026: Removed duplicate phone number in CTA section on index page
- January 2025: Complete website overhaul with new design and structure
- Added 6 service sub-pages
- Implemented Services dropdown navigation
- Added About page
- Enhanced SEO with unique titles and meta descriptions
- Added social media integration (Facebook & Instagram)
- Mobile-responsive design implemented
