# Dream Food Static MVP

This branch carries the approved Modern Souq design foundation into the static M03 website implementation.

## Routes

- `index.html` — Home
- `menu.html` — Menu preview with draft categories and verification notice
- `our-story.html` — Story page shell; no founder story is invented
- `gallery.html` — Clearly labelled slots for restaurant-approved photography
- `location.html` — Maluri location context; exact address, hours and directions remain pending
- `order.html` — Foodpanda, phone/WhatsApp and additional ordering routes remain pending verification
- `contact.html` — Contact and reservation process placeholders
- `journal.html` — Draft editorial topics, clearly not published restaurant news
- `article-template.html` — Blank template for future approved journal content

## Design foundation

- Warm sand with terracotta, gold and deep teal accents from `docs/PROJECT_BRIEF.md`.
- Editorial system-serif headings with a legible system sans-serif for body text.
- Mobile-first navigation, a persistent mobile action, visible focus states and reduced-motion support.
- Original abstract CSS illustrations are labelled as placeholders. They do not represent actual dishes or restaurant interiors.
- No font, image, tracking or CMS dependency is loaded from an external service.

## Data and verification boundaries

- `assets/data/business.json` centralizes business facts. Unknown values stay `null` until M04 evidence is available.
- `assets/data/menu.json` records the working draft categories, has no publishable menu items, and states the verification requirement.
- Exact address, opening hours, menu names/prices/availability, phone/WhatsApp, Foodpanda/Grab links, reservation method, certification wording and approved photography remain unverified.
- No map/order/contact action is fabricated or linked to a similarly named location.

## Cloudflare Pages

- Framework preset: None
- Build command: None
- Build output directory: repository root
- Functions or environment variables: None
- Local preview: `python3 -m http.server 8080`

M03 static routes are implemented in this branch. M04 verification, M05 final QA/SEO and M06 deployment remain separate milestones.
