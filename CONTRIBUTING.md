# Contributing (Marketing and Creative)

This repository is for Driftya marketing, social, ad, and brand assets.

Use this guide for copy, visual design, HTML/CSS creative pages, and SVG/vector production.

## Source of truth
- Product and tone: `../docs/GUIDLINES.md`
- Quiet outreach style: `../docs/MARKETING.md`
- Growth and activation goals: `../docs/GROWTH_ACTIVATION_PLAYBOOK.md`
- Social image/ad specifics: `../docs/INSTAGRAM_GUIDELINES.md`
- Brand colors and tokens: `../src/Driftya.Web/ClientApp/src/styles/site.scss`

## Brand principles
- Calm over hype.
- Reflection over promotion.
- Clarity over volume.
- Emotional safety over vanity metrics.

Avoid urgency language, performance claims, or aggressive CTA copy.

## Messaging rules
- Lead with human tension and emotional outcome, not feature lists.
- Prefer "If this resonates, try it" over "Sign up now".
- Do not frame Driftya as a growth hack, feed replacement war, or viral product.
- Keep copy concise and low-pressure.

## Growth focus (practical)
Primary success signals:
- Visit -> hero/login intent
- Register success
- First note action completed in first session
- D1 and D7 return behavior

When proposing content, explain which activation step it should improve.

## Visual system
Use `site.scss` tokens as source of truth.

Core palette:
- `--driftya-accent`: `#4f7cff`
- `--driftya-accent-2`: `#5ee6ff`
- `--driftya-accent-3`: `#ff9ed1`
- Light text/background: `#0f1325` / `#f7f8ff`
- Dark text/background: `#f5f7ff` / `#0b0f28`

Accent usage rules:
- Use one accent per asset.
- Keep accent area under 10 percent of canvas.
- Default to `#4f7cff`; use `#5ee6ff` for softer dark-scene highlights.
- Use `#ff9ed1` only as subtle highlight.

## SVG and vector standards
- Prefer vector-first assets (`.svg`) for logos, icons, and scalable shapes.
- Include a correct `viewBox`; avoid fixed-size-only exports.
- Keep layers and groups named semantically (`logo-mark`, `wordmark`, `bg-shape-1`).
- Minimize unnecessary path points and transforms.
- Do not bake text into paths unless required by distribution constraints.
- Keep source files editable (`.svg` and workspace files like `.pdn` as needed).

## HTML/CSS standards for campaign pages
- Use semantic HTML (`header`, `main`, `section`, `footer`).
- Mobile-first responsive layouts.
- Respect accessibility basics:
  - Color contrast
  - `alt` text
  - keyboard-focus-visible states
- Keep CSS tokenized with the Driftya palette variables.
- Keep animation subtle and purposeful; avoid noisy motion.

## Asset delivery checklist
- Correct dimensions for channel (for example, 1080x1350 or 1080x1920).
- Copy follows calm brand tone.
- Color usage follows accent rules.
- Exported file is optimized and named clearly.
- Editable source is included when possible.

## Localization and encoding
- Keep user-facing copy localization-ready.
- Use UTF-8 encoding.
- Avoid broken character output and verify punctuation after export.

## Pull request checklist
- [ ] Aligns with `../docs/GUIDLINES.md` and `../docs/MARKETING.md`
- [ ] Uses brand colors from `site.scss`
- [ ] Meets SVG/HTML/CSS standards above
- [ ] Keeps messaging calm, clear, and non-hype
- [ ] Includes source file(s) and final export(s)
