# Replit Agent Task: TitanRenovationsNYC

## Goal
Update the TitanRenovationsNYC static site with fresh React-quality content pulled from the titan-renovations-react repo — services, gallery, testimonials, and a quote request flow — while keeping the existing Cloudflare Pages deployment intact.

## Tasks
1. Check if a `titan-renovations-react` repo or branch exists in this codebase — if so, migrate its components and content into this repo
2. Build a bold hero section: "NYC's Premier Renovation Specialists", dark/gold or charcoal/white aesthetic, "Get a Free Estimate" CTA button
3. Create a Services section: Kitchen Remodeling, Bathroom Renovation, Full Apartment Gut, Flooring, Painting, Custom Carpentry — cards with icons, descriptions, and starting price ranges
4. Build a Project Gallery: before/after slider component for 4+ renovation projects; each project has a label (kitchen/bath/etc.) and brief description
5. Add a Why Choose Us section: 5+ differentiators (licensed & insured, 15+ years experience, free estimates, warranty on work, all NYC boroughs)
6. Add Client Testimonials: 6 realistic NYC homeowner reviews with names, boroughs, and project types
7. Build a Free Estimate form: name, email, phone, address, project type, budget range, timeline — submit to Supabase `estimate_requests` table
8. Add local SEO: JSON-LD LocalBusiness with contractor type, serviceArea (all 5 boroughs), address, phone; borough-specific meta description
9. Add a Financing Available section/badge — mention payment plans
10. Open Graph tags, favicon, canonical URL
11. Full mobile responsiveness
12. Ensure `npm run build` succeeds (or HTML is valid if static site)

## Tech Stack
- HTML/CSS/JS (static) OR React 18 + Vite if migrating from titan-renovations-react
- Tailwind CSS
- Supabase (estimate requests)
- Cloudflare Pages (static deploy)

## Deploy Target
Cloudflare Pages — already connected to `Kaoz625/TitanRenovationsNYC`. Push to main to deploy. Never Vercel.

## Done When
- [ ] All sections (Hero, Services, Gallery, Testimonials, Estimate Form) built
- [ ] Before/after slider works on at least 2 projects
- [ ] Estimate form submits to Supabase
- [ ] JSON-LD schema with all 5 NYC boroughs as serviceArea
- [ ] Mobile-responsive at 375px
- [ ] All changes pushed to `Kaoz625/TitanRenovationsNYC` main branch
