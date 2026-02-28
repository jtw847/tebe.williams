# Tebe Williams — Personal Website Spec

## Project Overview
Single-page personal website for **James "Tebe" Williams**, a CFO/COO specializing in Physical AI, robotics, and intelligent equipment deployment. The site serves three goals:

1. **Attract board seats and advisory roles** — showcase track record, exits, and operational depth
2. **Sell Physical AI consulting services** — position as fractional CFO/advisor for companies building physical AI products
3. **Maintain professional presence** — serve as a landing page for recruiters, investors, and potential partners

**Target audiences:**
- C-suite / board executives evaluating AI investments
- PE/VC firms doing diligence on Physical AI companies
- Mid-market companies adopting AI into physical products
- Recruiters for CFO/COO roles

---

## File Structure
```
/
├── index.html          # Single-file site (HTML + CSS + JS, all inline)
├── images/
│   ├── headshot.jpg           # Professional portrait photo
│   ├── volley-hero.jpg        # Wide shot of Volley trainer (used as hero background)
│   ├── volley-action.jpg      # Volley trainer on platform tennis court (Volley case study hero)
│   ├── volley-action2.jpg     # Additional Volley action shot
│   ├── volley-cv.jpg          # Computer vision court mapping overlay
│   ├── volley-ai.jpg          # AI player tracking visualization
│   ├── volley-pickleball.jpg  # Volley pickleball trainer
│   ├── volley-padel.jpg       # Volley on padel court with city skyline
│   ├── volley-indoor.jpg      # Indoor facility deployment
│   ├── volley-sunset.jpg      # Trainer at sunset on outdoor court
│   ├── volley-night.jpg       # Night court deployment
│   ├── volley-player.jpg      # Player using Volley system
│   ├── outerwall-kiosks.jpg   # Coinstar/Redbox/ecoATM kiosk family (VS Networks case study hero)
│   ├── redbox.jpg             # Redbox kiosk closeup
│   └── ecoatm.jpg             # ecoATM kiosk
├── SPEC.md             # This file
```

**Important note on images:** All image files are JPEGs regardless of original source format. The originals were `.jfif` files renamed during processing. All extensions must be `.jpg` and all HTML `src` attributes must reference `.jpg`.

---

## Site Sections (in order)

### 1. Navigation (fixed top)
- Logo: `tebe.williams` (dot is cyan accent)
- Links: About, Portfolio, Expertise, Consulting, Insights, Contact
- Blurred backdrop, becomes more opaque on scroll
- Collapses (hidden) on mobile

### 2. Hero
- **Background:** `volley-hero.jpg` with dark gradient overlay + subtle grid pattern
- **Headline:** "Finance leader at the frontier of **Physical AI**" (Physical AI in cyan gradient)
- **Tagline:** "I'm Tebe Williams — a CFO/COO who has deployed 50,000+ intelligent devices coast-to-coast, led two high-value exits, and built the financial and operating systems that turn robotic and AI products into scalable businesses."
- **CTAs:** "Explore Consulting →" (primary) | "Get in Touch" (secondary)
- **Stats row:** 50K+ Devices Deployed | 2 High-Value Exits | 25+ Years Experience | 8.3× Record Sale Multiple
- **Headshot:** Right column, gradient border frame

### 3. About — "Where Finance Meets Intelligent Hardware"
- Left column: Three paragraphs of career narrative
- Right column: Three highlight cards:
  - 🎓 Northwestern Kellogg MBA
  - 🤝 Board & Mentor Experience (EO, Future Founders)
  - 🏗️ Builder-First Operator

### 4. Portfolio — "Products I've Built & Scaled"
Two case studies with hero images, descriptions, metrics, and photo galleries:

**Case Study 1: Volley LLC** (Co-Founder / CFO, 2020–2026)
- Autonomous AI robotic training system for racquet sports
- Computer vision, edge computing, 24/7 autonomous operation
- Metrics: 150+ installations | 10K customers | 24/7 operation | 0 on-site staff
- Gallery: 6 images (cv, pickleball, padel, ai, indoor, sunset)

**Case Study 2: VS Networks LLC** (COO / CFO, 2015–2021)
- In-store digital kiosk network for John Deere, STIHL, Ace Hardware, AGCO
- 20,000+ locations, 700% revenue growth, <1% churn
- Metrics: 8.3× revenue multiple | 44% IRR | 20K+ locations | <1% churn
- Gallery: 3 images (redbox, ecoatm, volley-night)

### 5. Expertise — "What I Bring to the Table"
6-card grid:
1. 🤖 Physical AI Systems
2. 📊 Strategic Financial Leadership
3. 🚀 Scaling Operations
4. 💰 M&A and Exits
5. 🌐 Edge & IoT Deployment
6. 📈 Revenue Growth & Retention

### 6. Career Timeline — "Built for This Moment"
Vertical timeline with dot indicators:
- **2020–2026:** Volley LLC — Co-Founder / CFO → Advisor
- **2020–2021:** Superior Tech Inc — COO / CFO (Acquired · 18% IRR)
- **2015–2021:** VS Networks LLC — COO / CFO (Acquired 2× · 44% IRR · 8.3× Multiple)
- **2011–2015:** Outerwall (Redbox & Coinstar) — Sr. Manager, Strategy & New Ventures
- **2001–2011:** Finance & Advisory Foundation — EY · Lincoln International · Deutsche Bank · Accenture (dimmed/past styling)

### 7. Consulting — "Physical AI Advisory"
4 service cards with gold accent:
1. **Physical AI Due Diligence** — Form factor, power distribution, service accuracy, product-market fit
2. **Strategic Planning & Modeling** — R&D costing, timeline planning, financial modeling, board communication
3. **Equipment Financing** — BOM & unit economics, cashflow modeling, financing packages, lender introductions
4. **Field Ops & Customer Success** — Equipment diagnostics, field support design, customer success, AI bot support

CTA block: "Ready to Build Something Intelligent?" with gold button

### 8. Insights / Thought Leadership
3 article preview cards (placeholder concepts, not linked to real articles yet):
1. "Why Edge Computing Changes the CFO's Playbook" (Physical AI)
2. "Equipment Financing as a Growth Lever" (Scaling)
3. "Building for <1% Churn Before Exit" (Operations)

### 9. Contact — "Let's Talk"
- ✉️ Email: tebe.williams@gmail.com
- 📞 Phone: 630-235-2273
- 💼 LinkedIn: https://linkedin.com/in/tebewilliams (placeholder — verify URL)
- Tagline: "Chicago-based · Open to frequent travel"

### 10. Footer
- Nav links repeated
- © 2026 James Tebe Williams. All rights reserved.

---

## Design System

### Typography
- **Headings:** `Space Grotesk` (Google Fonts) — weights 400–700
- **Body:** `DM Sans` — weights 300–700, italic 400
- **Code/Labels:** `JetBrains Mono` — weights 400–500

### Color Palette
```
--bg:      #070810    (primary background, near-black blue)
--bg2:     #0d0e18    (secondary background, case study cards)
--bg-card: #12131f    (card backgrounds)
--bg-card-h: #191a28  (card hover state)
--cyan:    #00d4ff    (primary accent — stats, labels, links)
--blue:    #4361ee    (gradient partner for cyan)
--gold:    #f0b060    (consulting section accent)
--green:   #00e89d    (timeline badges, success metrics)
--txt:     #eef0f6    (primary text)
--txt2:    #9498a8    (secondary text / body copy)
--muted:   #5c6070    (tertiary text / descriptions)
--border:  #1e2030    (card borders, dividers)
```

### Visual Effects
- Noise texture SVG overlay on `body::before` (very subtle, 3% opacity)
- Subtle grid pattern on hero section (CSS background-image)
- Gradient border on headshot (cyan → blue → gold)
- Scroll-triggered reveal animations via IntersectionObserver (`.reveal` class)
- Nav background opacity change on scroll
- Card hover: translateY(-3px) + border color glow
- Gradient text on stat numbers and hero headline accent

### Responsive Breakpoints
- **> 1024px:** Full layout (2-column hero, 3-col grids, nav links visible)
- **≤ 1024px:** Single column, nav links hidden, smaller headshot
- **≤ 640px:** Tighter padding, stacked stats, single-column grids

---

## Known TODOs / Open Items

### Content
- [ ] **LinkedIn URL** — Currently placeholder `https://linkedin.com/in/tebewilliams`, needs verification
- [ ] **Thought leadership articles** — Currently placeholder concepts; needs real articles/links or removal
- [ ] **Text review** — Owner wants to tweak copy throughout
- [ ] **Image review** — Owner wants to adjust which images appear where

### Dual-URL Strategy
- [ ] **Personal URL** — e.g., `tebewilliams.com` — for the full site (board seats, career, general presence)
- [ ] **Consulting URL** — e.g., separate domain for Physical AI consulting practice
- [ ] Decide: two separate sites, or one site with two domains pointing to it, or one domain with consulting as a subdomain/page

### Deployment
- [ ] **Recommended host:** Netlify (free, drag-and-drop, custom domains) — NOT Squarespace (would require rebuild in their template system)
- [ ] Alternative: GitHub Pages or Vercel (also free)
- [ ] Custom domain purchase and DNS setup
- [ ] Add meta tags for SEO (og:image, description, etc.)
- [ ] Add favicon

### Technical Enhancements to Consider
- [ ] Add a contact form (Netlify Forms, Formspree, or similar)
- [ ] Add Google Analytics or Plausible for visitor tracking
- [ ] Add Open Graph / Twitter card meta tags for social sharing
- [ ] Consider splitting CSS into separate file for cacheability (currently all inline)
- [ ] Add print stylesheet if needed for PDF resume generation
- [ ] Optimize images (compress, add srcset for responsive loading)

---

## Source Materials Available
The following documents were used to build the site content and are available for reference:
- Resume/CV (25+ years, full career history)
- Physical AI Fractional CFO Services document (detailed consulting offerings)
- Strategic CFO Experiences document
- VS Networks scaling summary (40× ARR growth, 8.3× revenue multiple details)
- STIHL account overview (3,462 EDGE systems, 7,779 dealers, 45% penetration)
- Equipment dealers account overview (50,000+ addressable locations, 8 verticals)
- Multiple product photos from Volley, VS Networks/Outerwall deployments

---

## Key Accomplishments Reference (for copy editing)

**Volley LLC:**
- Autonomous AI robotic training for racquet sports (tennis, pickleball, padel, platform tennis)
- 150+ installations operating 24/7 nationwide, 10,000 customers
- Edge computing: redundant high-processing compute, intermittent low-bandwidth cloud
- Zero on-site staff required

**VS Networks:**
- Transformed single-client side business → diversified data platform
- Clients: John Deere, STIHL, Ace Hardware, AGCO + others across 20,000+ locations
- 700% revenue growth, <1% customer churn
- Acquired twice: Bertram Capital → The Jordan Company
- 44% IRR, 8.3× revenue multiple (highest ever paid by acquirer)
- Built sales, customer success, tech support, HR from scratch

**Superior Tech:**
- Robotics-driven agritech, acquired by Agri-Fab
- 18% IRR, exceeded revenue targets at 125%

**Outerwall/Redbox/Coinstar:**
- Led $150M Coinstar expansion across continental Europe
- Coinstar Europe now ~40% of company revenues

**Education:** Northwestern Kellogg MBA (Finance concentration)
**Board/Mentorship:** EO board member, Future Founders mentor & pitch judge, EO Global Student Entrepreneur Awards judge
