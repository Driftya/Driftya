# Agent Guidelines (driftya-front)

All agents in this repository must follow `CONTRIBUTING.md` in this folder.

## Mission
Support Driftya marketing and growth assets with calm, high-clarity output across:
- Social content
- Ad creative
- Landing/campaign HTML/CSS
- SVG/vector brand assets

## Required references before edits
- `CONTRIBUTING.md`
- `../docs/GUIDLINES.md`
- `../docs/MARKETING.md`
- `../docs/GROWTH_ACTIVATION_PLAYBOOK.md`
- `../docs/INSTAGRAM_GUIDELINES.md`
- `../src/Driftya.Web/ClientApp/src/styles/site.scss`

## Workflow (4 passes)
1. First pass: write a short plan in `../docs/plans` and ask for confirmation.
2. Second pass: implement requested files/changes.
3. Third pass: validate outputs (dimensions, copy tone, links, formatting).
4. Fourth pass: update the plan with `[Done]` suffixes.

## Copy and tone guardrails
- No hype, pressure, or scarcity language.
- No manipulative CTA phrasing.
- Prefer reflective prompts and calm wording.
- Keep channel copy concise and human.

## Growth and marketing guardrails
- Prioritize activation quality over vanity impressions.
- Tie recommendations to funnel outcomes (registration and first meaningful action).
- Avoid broad "post everywhere" advice; prefer focused channel experiments.

## Design and implementation guardrails
- Use Driftya color tokens from `site.scss` as source of truth.
- Prefer one accent color per asset; keep accent coverage low.
- For SVG: keep `viewBox`, semantic group naming, and editable structure.
- For HTML/CSS: semantic markup, responsive layout, accessible contrast, keyboard-visible focus.
- Keep outputs reusable for ads, social posts, and lightweight campaign pages.

## Quality checks before handoff
- Brand and tone alignment checked.
- Palette usage validated against `site.scss`.
- File names and folders are clear and consistent.
- UTF-8 encoding preserved for text assets.
