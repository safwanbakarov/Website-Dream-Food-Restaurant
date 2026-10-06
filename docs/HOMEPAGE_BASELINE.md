# Dream Food Homepage Baseline

This branch establishes the first reviewable Modern Souq homepage shell before separate M03 implementation work begins.

## Design foundation

- Warm sand background with terracotta, gold and deep teal accents from `docs/PROJECT_BRIEF.md`.
- Editorial serif headings paired with a compact, legible sans-serif UI face.
- Mobile-first navigation, a persistent mobile menu action, visible focus states and reduced-motion support.
- Food and atmosphere areas use original abstract CSS illustrations labelled as placeholders. They do not represent actual restaurant dishes or interiors.
- A single static HTML entry point, one stylesheet and a small navigation script keep the site compatible with static hosting.

## Content boundaries

Confirmed project context shown: Dream Food Restaurant, Maluri, Kuala Lumpur, Middle Eastern dining.

Still shown as pending: menu and prices, opening hours, exact address/directions, ordering link, phone/WhatsApp, and restaurant photography. No halal certification claim is made. The Foodpanda destination is not activated on the page pending M04 verification.

## Scope

This is the homepage design baseline for owner review. It does not complete the separate M03 menu, story, gallery, order and contact pages, nor M04 fact verification, M05 QA/SEO, or M06 deployment.

## Cloudflare Pages preview

- Framework preset: None
- Build command: None
- Build output directory: `/` (repository root)
- Functions or environment variables: None
- Local preview: `python3 -m http.server 8080`
