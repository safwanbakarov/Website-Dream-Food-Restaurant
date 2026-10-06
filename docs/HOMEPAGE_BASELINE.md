# Dream Food Static Site

The M03 site is a lightweight static restaurant website. It includes the landing page and the supporting menu, story, gallery, location, order, and contact pages. It has no journal, article pages, or active publishing workflow.

## Routes

- `index.html` — Home
- `menu.html` — Menu preview with draft categories and verification notice
- `our-story.html` — Story page shell; no founder story is invented
- `gallery.html` — Clearly labelled slots for restaurant-approved photography
- `location.html` — Maluri context; exact address, hours and directions remain pending
- `order.html` — Foodpanda, phone/WhatsApp and other ordering routes pending verification
- `contact.html` — Contact and reservation placeholders

## Design foundation

- Warm sand with terracotta, gold and deep teal accents from `docs/PROJECT_BRIEF.md`.
- Editorial system-serif headings with a legible system sans-serif for body text.
- Mobile-first navigation, a persistent mobile action, visible focus states and reduced-motion support.
- Original abstract CSS illustrations are labelled as placeholders. They do not represent actual dishes or restaurant interiors.
- No font, image, tracking, CMS, or article-posting dependency is loaded from an external service.

## Data and verification boundaries

- `assets/data/business.json` centralizes business facts. Unknown values stay `null` until M04 evidence is available.
- `assets/data/menu.json` records working draft categories, has no publishable menu items, and states the verification requirement.
- Exact address, opening hours, menu names/prices/availability, phone/WhatsApp, Foodpanda/Grab links, reservation method, certification wording and approved photography remain unverified.
- No map/order/contact action is fabricated or linked to a similarly named location.

## Cloudflare Pages

- Framework preset: None
- Build command: None
- Build output directory: repository root
- Functions or environment variables: None
- Local preview: `python3 -m http.server 8080`

M04 verification, M05 final QA/SEO and M06 deployment remain separate milestones.
