# Architecture Decision

## Decision

Use a **static-first architecture** for the MVP.

```text
Customer browser / mobile
        ↓
Cloudflare Pages
        ↓
Static HTML/CSS/JS (or static framework output)
        ↓
Repository-managed menu/content data
        ↓
External services:
- Foodpanda
- optional GrabFood
- WhatsApp / phone
- Google Maps / Business Profile
```

## Why

The MVP does not require:
- authentication,
- user accounts,
- internal order processing,
- session storage,
- a proprietary reservation database,
- a server-side application layer.

A static architecture is:
- cheaper,
- easier to hand over,
- easier to audit,
- easier to deploy,
- and consistent with the RM0 hosting constraint.

## Future upgrade triggers

A backend may be introduced later only if a verified requirement appears, such as:
- real-time table inventory,
- staff login/admin panel,
- owned order processing,
- payment processing,
- loyalty accounts,
- customer database,
- automated reservation workflow,
- inventory integration.

If that happens, document the decision before adding infrastructure.
