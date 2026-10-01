# Project Brief — Dream Food Restaurant Website

## Objective

Create a calm, professional, mobile-first website for Dream Food Restaurant with **zero hosting cost for the MVP**.

The website should support awareness and consideration first, then route customers to low-friction actions such as:
- viewing the menu,
- opening Foodpanda,
- contacting the restaurant,
- getting directions,
- and making a reservation only if an approved low-complexity process exists.

## Strategic direction

The supplied whitepaper recommends a **Modern Souq** concept:
- contemporary,
- uncluttered,
- warm,
- culturally grounded,
- but not clichéd.

### Design tokens

- Terracotta — `#C1440E`
- Warm gold — `#C89B3C`
- Deep teal-green — `#145A46`
- Warm sand/off-white background

### Visual rules

- Food photography should be the dominant visual element.
- Geometric/mashrabiya-inspired texture should remain subtle.
- Body typography must be highly legible on mobile.
- Accent typography should be used sparingly.
- Copy should be warm, direct, and educational.

## Proposed information architecture

1. Home
2. Menu
3. Our Story
4. Gallery
5. Location & Hours
6. Order Online
7. Contact / Reserve

A Blog/Journal can be added later as an SEO/content engine.

## Mobile UX requirements

- Maximum 6–7 primary navigation items.
- Persistent Order/Reserve CTA on mobile.
- Major destinations reachable within two taps from Home.
- Above-the-fold content should quickly answer:
  - What cuisine is this?
  - Is the restaurant open?
  - How do I order or visit?
- Menu and location content should not depend on heavy JavaScript.
- Compress and lazy-load images.
- Prefer WebP/AVIF.
- Maintain accessible text contrast.

## SEO requirements

- Unique title/meta description per page.
- One H1 per page.
- `Restaurant` / `LocalBusiness` structured data.
- Consistent NAP (Name, Address, Phone).
- XML sitemap.
- `robots.txt`.
- Descriptive image alt text.
- Internal links between Menu, Location, and educational content.

## Technical decision

### MVP
Static-first:

`Browser → Cloudflare Pages → static site → external order/contact/maps links`

Menu data may live in a structured JSON/JS/Markdown file inside the repository.

### Not required for MVP
A previous AI suggested:
- Next.js
- Node.js / Express
- PostgreSQL
- Redis

Those are not required unless a later verified feature needs server-side state, authentication, or persistent application data.

## Compliance constraints

- Do not claim halal certification unless verified.
- If customer personal data is collected, publish a privacy notice and minimize data collection.
- Avoid creating a new customer database for the MVP unless the restaurant explicitly requires it.

## Definition of done

- Live zero-cost static deployment.
- Restaurant/menu facts verified.
- Ordering/contact routes work.
- Mobile and desktop usable.
- No unverified claims.
- Basic accessibility, SEO, and performance checks completed.
- GitHub contains build/deployment/handoff documentation.
