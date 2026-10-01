# Contributing and Approval Policy

## Purpose

This repository may be worked on concurrently by multiple AI coding agents and/or human developers.

To prevent design drift, accidental overwrites, and unreviewed production changes, all implementation work must follow the branch and Pull Request workflow below.

## Protected-branch policy

`main` is the approved integration/production branch.

No AI agent or developer should make implementation changes directly on `main`.

### Required workflow

1. Start from the latest `main`.
2. Create one branch per clearly scoped task.
3. Make changes only within that branch.
4. Keep the branch focused on its assigned scope.
5. Open a Pull Request into `main`.
6. Link the relevant GitHub Issue.
7. Include screenshots or a preview URL for visual changes when possible.
8. Update `STATUS.md` if the PR changes milestone progress.
9. The project owner reviews the PR.
10. Merge only after explicit project-owner approval.
11. Delete the branch after merge unless continued work requires it.

## Branch naming

Use:

```text
<agent-or-person>/<short-scope>
```

Examples:

```text
replit/homepage
grok/menu-layout
cline/mobile-navigation
qwen/seo
aider/accessibility
```

## Concurrent-work rule

Parallel work is allowed only when branches have **non-overlapping ownership**.

Good parallel split:
- one branch: homepage shell and hero
- one branch: menu data/content structure
- one branch: SEO/schema/robots/sitemap
- one branch: QA/accessibility checks

Avoid parallel work when two agents would modify the same core layout, global stylesheet, navigation system, or design tokens at the same time.

## Design consistency

All branches must follow:
- `docs/PROJECT_BRIEF.md`
- `docs/AI_HANDOFF.md`
- `docs/ARCHITECTURE.md`

The Modern Souq design tokens and approved information architecture are shared constraints, not suggestions.

If a branch proposes a change to the design system, global navigation, architecture, or data model, call it out explicitly in the PR and do not merge until reviewed.

## Pull Request checklist

A PR should state:

- What was changed?
- Which issue does it address?
- Which files were changed?
- Does it alter global design or architecture?
- What remains unresolved?
- How was it tested?
- Are screenshots/preview links available?
- Was `STATUS.md` updated if relevant?

## Merge policy

Project-owner approval is required before merge into `main`.

AI agents should never interpret completion of their own task as authorization to merge.

## Conflict policy

If two branches conflict:
1. Do not force merge.
2. Rebase or update the later branch from the latest `main`.
3. Re-test affected pages.
4. Resolve design/content conflicts deliberately.
5. Re-request approval if the resolution materially changes the PR.

## Deployment

Once Cloudflare deployment is connected, `main` should represent the approved production state.

Feature branches may be used for preview deployments where supported.
