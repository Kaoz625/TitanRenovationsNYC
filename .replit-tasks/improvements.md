# Replit Agent Task: TitanRenovationsNYC

## Goal
Transform the current minimal Titan Renovations NYC site (index.html + logo images + privacy/terms pages) into a full contractor marketing site with services, before/after gallery, contact form, and SEO optimized for NYC home renovation searches.

## Tasks
1. Redesign index.html as a multi-section single-page site: Hero → Services → Why Choose Us → Before/After Gallery → Testimonials → Contact Form → Footer
2. **Hero**: full-width dark hero image (construction/renovation aesthetic), Titan logo prominent, headline "NYC's Premier Renovation Contractor — Kitchens, Bathrooms, Full Gut Renovations", two CTAs: "Get Free Estimate" (anchor to form) and "View Our Work" (anchor to gallery); phone number (click-to-call) in top right
3. **Services section**: 6 service cards with icon, title, and 2-sentence description — Kitchen Remodeling, Bathroom Renovation, Basement Finishing, Full Gut Renovations, Flooring & Tile, Exterior & Roofing; each card has a "Learn More" expansion (CSS accordion) with bullet-point details
4. **Why Choose Us**: 4 trust badges (Licensed & Insured, 15+ Years Experience, Free Estimates, Satisfaction Guaranteed) with icon + stat; followed by a short "About Titan" paragraph
5. **Before/After Gallery**: 6 project pairs using a CSS slider (single image, hover or click to reveal "after"); label each project type (Kitchen Bronx, Bathroom Brooklyn, Basement Queens, etc.); use placeholder images in a `images/` folder
6. **Testimonials**: 5 reviews with name, neighborhood, rating (★★★★★), and quote; render as a CSS horizontal scroll carousel on mobile, grid on desktop
7. **Contact / Estimate Form**: fields for name, phone, email, service type (dropdown), project description, preferred call time, zip code; submit via Formspree; add a "We respond within 2 hours" trust note
8. **SEO**: unique title/description per page, LocalBusiness JSON-LD schema (name: Titan Renovations NYC, areaServed: all 5 boroughs, phone, priceRange: $$), OG tags, sitemap.xml, robots.txt
9. **Mobile sticky CTA**: fixed bottom bar on mobile with phone icon + "Call for Free Estimate" — only visible below the hero
10. Add a separate `services.html` page that expands all 6 services with more detail (for SEO), linking back to the main page

## Tech Stack
- Vanilla HTML5 / CSS3 / JavaScript (no build tool — keep it simple and fast)
- Google Fonts: Montserrat (headings) + Inter (body)
- Formspree for estimate form
- JSON-LD structured data
- CSS custom properties for theming

## Deploy Target
Cloudflare Pages (static site, CNAME already at titan.nyctailblazers.com). Never Vercel.

## Done When
- [ ] All 7 sections present and styled on index.html
- [ ] 6 service cards render with CSS accordion "Learn More" expansion
- [ ] Before/After gallery shows 6 project pairs with working reveal
- [ ] Testimonials carousel works on mobile (horizontal scroll or swipe)
- [ ] Estimate form submits via Formspree
- [ ] LocalBusiness JSON-LD present and valid (test with Google Rich Results)
- [ ] Mobile sticky CTA bar visible below hero on 375px viewport
- [ ] services.html exists with expanded service details
- [ ] Lighthouse SEO score ≥ 90
