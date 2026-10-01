# Dream Food Restaurant Website

> 🚧 **STATUS: INCOMPLETE / HANDOFF-READY**
>
> This repository is the source of truth for a pro-bono website project for Dream Food Restaurant. The website has **not** been completed or launched yet. The repo is intentionally structured so another AI/developer (for example Replit or Grok) can continue the build cleanly.

## Project goal

Create a **zero-cost, mobile-first, professional restaurant website** that improves discovery, presents the menu clearly, and routes customers to verified ordering/contact channels without unnecessary paid infrastructure.

## Recommended MVP architecture

**Static-first website → Cloudflare Pages (preferred free hosting)**

Use the simplest implementation that works:
- HTML/CSS/JavaScript, or
- a static framework if clearly justified.

Do **not** add Node.js, Express, PostgreSQL, Redis, authentication, or paid services unless a verified business requirement genuinely needs them.

## Start here

Read these files in this order:

1. [HANDOFF.md](HANDOFF.md)
2. [docs/PROJECT_BRIEF.md](docs/PROJECT_BRIEF.md)
3. [docs/AI_HANDOFF.md](docs/AI_HANDOFF.md)
4. [docs/SOURCES.md](docs/SOURCES.md)
5. [docs/MENU_REFERENCE.md](docs/MENU_REFERENCE.md)
6. [docs/ARCHITECTURE.md](docs/ARCHITECTURE.md)
7. [STATUS.md](STATUS.md)

If using Replit or Grok, see:
- [docs/REPLIT_OR_GROK_START_HERE.md](docs/REPLIT_OR_GROK_START_HERE.md)

## MVP scope

- Home
- Menu
- Our Story
- Gallery
- Location & Hours
- Order Online
- Contact / Reserve
- Technical SEO foundations

## Design direction — “Modern Souq”

Derived from the supplied strategy whitepaper:

- Terracotta: `#C1440E`
- Warm gold: `#C89B3C`
- Deep teal-green: `#145A46`
- Warm sand/off-white base
- Clean geometric sans-serif for body copy
- One restrained display/accent face
- Large food photography
- Subtle mashrabiya-inspired geometric texture
- Warm, direct, educational copy
- Avoid stereotypical “Arabian Nights” styling

## Important data rule

The intended Foodpanda listing supplied by the project owner is:

https://www.foodpanda.my/restaurant/ogd7/dream-food-restaurant-marluri

Do **not** substitute data from similarly named restaurants or other locations.

If a restaurant fact cannot be verified, keep a visible `TODO` rather than inventing it.

## Compliance

- Do not claim or display halal certification unless certification status is confirmed.
- If customer personal data is collected, add a simple privacy notice and minimize data collection.
- Do not upload the confidential whitepaper PDF to this public repository.
- Do not invent opening hours, phone numbers, menu prices, owner story, ingredients, certification status, or delivery links.

## Hosting target

Preferred: **Cloudflare Pages**, using a free `*.pages.dev` URL for the MVP.

A paid custom domain is optional and can be configured later by the project owner/client.


## Contribution and approval workflow

**`main` is the approved production branch. AI agents and developers must not work directly on `main`.**

Required workflow:

1. Create a dedicated branch for the assigned task, for example:
   - `replit/homepage`
   - `grok/menu`
   - `cline/mobile-fixes`
   - `qwen/seo`
2. Make and test changes on that branch.
3. Open a Pull Request into `main`.
4. The project owner must review and approve the Pull Request before merge.
5. Only approved changes may be merged into `main`.
6. Delete the feature branch after merge when it is no longer needed.
7. Update `STATUS.md` and the relevant GitHub Issue as part of the Pull Request.

**Do not bypass this workflow by pushing directly to `main`.**

Until GitHub branch protection/rules are enabled in repository settings, this rule is documented policy rather than a hard technical block. Once protection is enabled, direct pushes to `main` should be rejected by GitHub.

See [CONTRIBUTING.md](CONTRIBUTING.md) for the full branch and Pull Request policy.

## Current status

See [STATUS.md](STATUS.md).

## Project owner

GitHub: [@safwanbakarov](https://github.com/safwanbakarov)
