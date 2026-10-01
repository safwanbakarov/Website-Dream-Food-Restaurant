# AI / Developer Handoff Instructions

## Read before coding

You are continuing an **incomplete pro-bono restaurant website project**.

Your job is to implement the approved static MVP without inventing business facts.

## Source priority

When sources conflict, use this order:

1. Owner/client-confirmed facts
2. Exact Dream Food Restaurant Maluri Foodpanda listing supplied by the project owner
3. Dream Food Restaurant Digital Growth Whitepaper
4. Arabic Restaurant Web Development Prep (prior AI working document)
5. Your own inference — only for design/engineering choices, never restaurant facts

## Do not

- Do not copy data from another Dream Food Restaurant location.
- Do not claim halal certification unless confirmed.
- Do not publish the confidential whitepaper PDF.
- Do not invent opening hours, phone numbers, prices, owner story, ingredients, or delivery links.
- Do not add a full backend unless a verified requirement needs it.
- Do not describe generic/AI food imagery as the restaurant's actual dish photography.

## Build goal

Create a fast, static website deployable to Cloudflare Pages.

Suggested structure:

```text
/
├── index.html
├── menu.html                # optional if not single-page
├── assets/
│   ├── css/
│   ├── js/
│   └── images/
├── data/
│   └── menu.json
├── robots.txt
├── sitemap.xml
├── README.md
├── HANDOFF.md
├── STATUS.md
└── docs/
```

A framework is acceptable if:
- the output remains static,
- setup stays simple,
- and the framework materially improves maintainability.

## Required UX

- Mobile-first.
- Clear hero and restaurant positioning.
- Prominent Menu, Order, Location, and Contact actions.
- Menu cards support image, name, price, short description.
- Foodpanda CTA uses the exact verified listing URL.
- WhatsApp/call/map links use verified facts only.
- Keep animations subtle.
- Respect reduced-motion preferences if animation is used.
- Optimize and lazy-load images.

## Visual direction

**Modern Souq**

- `#C1440E` terracotta
- `#C89B3C` warm gold
- `#145A46` deep teal-green
- warm sand/off-white base
- geometric pattern at low opacity
- large food imagery
- clean, calm layout

## Handoff discipline

After each build step:
1. Update `STATUS.md`.
2. Keep unresolved facts as TODOs.
3. Explain architecture deviations.
4. Update deployment instructions.
5. Do not mark production-ready until launch blockers are closed.
