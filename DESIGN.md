---
version: alpha
name: Run The Numbers
description: |
  Specialist paid search agency for ecommerce and lead generation. Voice is straight-talking Yorkshireman;
  visual identity is editorial and data-led — the "Ledger" system.
  Think vintage accountancy ledger meets modern data dashboard: warm
  cream paper, narrow palette, one confident blue accent that earns
  its place. Archetypes: 70% Ruler (authority, control) + 30% Sage
  (evidence, plain speech).
colors:
  bg-canvas: "#FAF7F2"
  bg-surface: "#FFFFFF"
  bg-raised: "#F4EFE6"
  bg-sunken: "#F0EAE0"
  text-primary: "#1B1A17"
  text-secondary: "#5C564B"
  text-tertiary: "#8C8478"
  border-subtle: "#E8E1D3"
  border-strong: "#C9C0AE"
  accent: "#2B4A7C"
  accent-hover: "#1E3A6C"
  accent-soft: "#E6EEF9"
  accent-deep: "#142544"
  on-accent: "#F5F1E8"
typography:
  display:
    fontFamily: Fraunces, Georgia, "Times New Roman", serif
    fontSize: 3.5rem
    fontWeight: 300-400
    lineHeight: 1.1
    letterSpacing: "-0.02em"
    fontOpticalSizing: auto
    fontVariationSettings: "'SOFT' 30-50"
  h1:
    fontFamily: Fraunces, Georgia, "Times New Roman", serif
    fontSize: 2.25rem
    fontWeight: 400
    lineHeight: 1.2
  h2:
    fontFamily: Fraunces, Georgia, "Times New Roman", serif
    fontSize: 1.5rem
    fontWeight: 400
    lineHeight: 1.3
  h3:
    fontFamily: Geist, Inter, -apple-system, sans-serif
    fontSize: 1.25rem
    fontWeight: 600
    lineHeight: 1.4
  body-md:
    fontFamily: Geist, Inter, -apple-system, sans-serif
    fontSize: 1rem
    fontWeight: 400
    lineHeight: 1.7
  body-sm:
    fontFamily: Geist, Inter, -apple-system, sans-serif
    fontSize: 0.875rem
    fontWeight: 400
    lineHeight: 1.6
  caption:
    fontFamily: Geist, Inter, -apple-system, sans-serif
    fontSize: 0.75rem
    fontWeight: 400
    lineHeight: 1.5
  mono:
    fontFamily: "JetBrains Mono", "Fira Code", monospace
    fontSize: 0.875rem
    fontWeight: 400
    lineHeight: 1.6
  data-callout:
    fontFamily: Fraunces, Georgia, "Times New Roman", serif
    fontSize: 4.5rem
    fontWeight: 300
    lineHeight: 1
    letterSpacing: "-0.02em"
rounded:
  none: 0px
  sm: 4px
  md: 8px
  lg: 16px
  pill: 9999px
spacing:
  xs: 4px
  sm: 8px
  md: 16px
  lg: 24px
  xl: 32px
  2xl: 48px
  3xl: 64px
  4xl: 96px
components:
  button-primary:
    backgroundColor: "{colors.accent}"
    textColor: "{colors.on-accent}"
    typography: "{typography.body-md}"
    fontWeight: 500
    rounded: "{rounded.sm}"
    padding: 12px 24px
  button-primary-hover:
    backgroundColor: "{colors.accent-hover}"
    textColor: "{colors.on-accent}"
  button-secondary:
    backgroundColor: transparent
    textColor: "{colors.accent}"
    typography: "{typography.body-md}"
    fontWeight: 500
    rounded: "{rounded.sm}"
    padding: 12px 24px
  button-secondary-hover:
    backgroundColor: "{colors.accent-soft}"
    textColor: "{colors.accent}"
  link:
    textColor: "{colors.accent}"
    typography: "{typography.body-md}"
  card:
    backgroundColor: "{colors.bg-surface}"
    textColor: "{colors.text-primary}"
    rounded: "{rounded.md}"
    padding: 24px
  card-alt:
    backgroundColor: "{colors.bg-raised}"
    textColor: "{colors.text-primary}"
    rounded: "{rounded.md}"
    padding: 24px
  callout:
    backgroundColor: "{colors.bg-raised}"
    textColor: "{colors.text-primary}"
    padding: 16px 20px
  input:
    backgroundColor: "{colors.bg-surface}"
    textColor: "{colors.text-primary}"
    typography: "{typography.body-md}"
    rounded: "{rounded.sm}"
    padding: 12px 16px
  data-highlight:
    backgroundColor: "{colors.bg-canvas}"
    textColor: "{colors.accent}"
    typography: "{typography.data-callout}"
    padding: 0
---

## Overview

Run The Numbers® (RTN) is a UK specialist paid search agency for ecommerce and lead generation. The visual identity — codenamed "Ledger" — is editorial and data-led rather than decorative. Layouts feel like a vintage accountancy ledger reimagined for the screen: warm cream paper, left-aligned text, generous whitespace, and a single confident ledger blue accent used sparingly. Clean over clever. Data leads. Whitespace is authority. One idea per slide or section.

Two archetypes guide every choice: 70% Ruler (authority, structure, control) and 30% Sage (wisdom, evidence, plain speech).

## Colors

The palette is deliberately narrow and warm. Ledger blue carries the brand. Dark ink carries the words. Cream carries the surface.

- **accent (#2B4A7C) — Ledger Blue.** The one hero colour. Used for headlines, CTAs, data callouts, hyperlinks, bullet points, accents, and the logo. Never as a background fill for large areas.
- **accent-hover (#1E3A6C).** Darker state for interactive elements.
- **accent-soft (#E6EEF9).** Light tint for hover backgrounds, selected states, soft tags.
- **accent-deep (#142544).** Used for dark-mode surfaces and section dividers where the old gunmetal (#121212) was used.
- **on-accent (#F5F1E8).** Warm off-white text for use on accent and accent-deep backgrounds.
- **bg-canvas (#FAF7F2) — Warm Cream.** The default page background. Replaces pure white as the primary surface. Gives everything that ledger-paper warmth.
- **bg-surface (#FFFFFF).** Cards, inputs, and elements that sit on top of canvas.
- **bg-raised (#F4EFE6).** Callout boxes, alternate table rows, subtle elevation without shadows.
- **bg-sunken (#F0EAE0).** Inset areas, code blocks, secondary panels.
- **text-primary (#1B1A17).** Headings and body copy. Warm near-black — never pure black (#000000).
- **text-secondary (#5C564B).** Captions, metadata, secondary copy.
- **text-tertiary (#8C8478).** Placeholder text, disabled states, timestamps.
- **border-subtle (#E8E1D3).** Dividers, table borders, card edges on canvas.
- **border-strong (#C9C0AE).** More prominent separation — section dividers, active input borders.

Never mix more than three colours on a single surface.

## Typography

Two typeface families, plus a monospace for data.

**Display and headings: Fraunces** — a variable serif with optical sizing (9-144), weight range 300-400, and a SOFT axis (30-50) that controls the quirkiness of the letterforms. Think editorial broadsheet meets vintage ledger. Fallback stack: Georgia → Times New Roman → serif.

**Body and UI: Geist** — a clean geometric sans-serif from Vercel. Weights used: 400 (regular), 500 (medium for labels/buttons), 600 (semibold for H3 and emphasis). Fallback stack: Inter → -apple-system → sans-serif.

**Mono: JetBrains Mono** — for code snippets, data tables, account IDs, and anything that benefits from tabular alignment. Weights 400 and 500. Fallback: Fira Code → monospace.

Roles:

- **display** — the single biggest line on a page or slide. Fraunces at light weight with generous SOFT axis.
- **h1 / h2** — section hierarchy in Fraunces. H2 is rendered in Ledger Blue in documents to signal a shift in level and reinforce brand.
- **h3** — subheading in Geist SemiBold. The transition point from serif to sans.
- **body-md** — default reading size in Geist; 1rem at 1.7 line-height for generous scan-ability.
- **body-sm** — secondary text, dense tables, in Geist.
- **caption** — footnotes, metadata, disclaimers, in Geist.
- **mono** — code, IDs, numeric data, in JetBrains Mono.
- **data-callout** — the hero number on a data slide. Always Ledger Blue. Always huge. Fraunces at light weight. Pair with one short line of context underneath.

Context-specific sizing (document-native, not tokenised):

- Presentations (.pptx): display titles 44-54pt, slide titles 32-40pt, body 16-20pt, data callouts 48-72pt.
- PDFs (A4): title 28-36pt, H1 22-26pt, body 10-12pt.
- Word (.docx): title 32pt, H1 24pt, H2 16pt (Ledger Blue), body 11pt with 1.15 line-spacing.

Never use ALL CAPS except for the RTN logo mark itself. Fraunces for headings and display, Geist for everything else. Do not mix beyond this pairing.

## Layout

- Left-align text by default. Centre-align only for display titles and single-line callouts.
- Use asymmetric layouts. Centred-everything looks corporate.
- Dark surfaces (accent-deep #142544) for opening slides, closing slides, and section dividers. Warm cream (bg-canvas #FAF7F2) for content, data, detail.
- Content aligns to an invisible grid. No floating elements.
- One idea per slide or section. If you need to explain two things, use two slides.

Spacing follows an 8px progression (xs 4 / sm 8 / md 16 / lg 24 / xl 32 / 2xl 48 / 3xl 64 / 4xl 96). Use these tokens for all margins, padding, and gaps on web or app UI.

## Shapes

Soft corners, not sharp. The favicon container is a rounded rectangle — corners elsewhere follow the same instinct.

- `rounded.sm` (4px) — buttons, inputs, small chips, table corners.
- `rounded.md` (8px) — cards, callout boxes, media frames.
- `rounded.lg` (16px) — hero image masks, large feature blocks.
- `rounded.pill` — tag chips, pill badges.

No drop shadows. No gradients. No inner glows. The brand reads flat and editorial. Depth comes from the warm/cool surface layering (canvas → surface → raised) and whitespace, not from effects.

## Components

- **button-primary** — Ledger Blue background, warm off-white text. The main call-to-action. One primary per view.
- **button-secondary** — transparent background, Ledger Blue text. Lower priority actions. Hover fills with accent-soft.
- **link** — Ledger Blue with a matching underline. Never default browser blue.
- **card** — white background on cream canvas, 8px radius, 24px internal padding. Content blocks.
- **card-alt** — raised warm tone (#F4EFE6), otherwise identical. Used on white surfaces for subtle elevation without shadows.
- **callout** — raised background with a 3px Ledger Blue left border, 16px padding. Used for pull-quotes, asides, warnings. No icon, no "NOTE:" label — the border signals the shift.
- **input** — white background, 4px radius, 12px/16px padding, 1px subtle border. Ledger Blue focus ring.
- **data-highlight** — the hero number treatment. Fraunces at light weight, Ledger Blue, huge (72pt+ in slides / 4.5rem+ on web), paired with one line of dark context underneath in Geist body-md.

Charts and data visualisation: primary series uses `{colors.accent}`, secondary uses `{colors.text-primary}`, gridlines and axes use `{colors.border-subtle}`. No colourful palettes.

Icons: simple line-based only, stroke weight 1.5-2px, in `{colors.accent}` or `{colors.text-primary}`. No filled icons. No multi-colour icons.

## Logo

> **Hard rule — never fake the logo.** Never substitute a hand-built text or CSS approximation of the monogram for the official SVG. Pull the real asset from `logo-redesign/svg/RTN_Logo_{Variant}.svg` (canonical raw URL below) and use it. Composing the full "RUN THE NUMBERS®" lockup live in HTML/CSS is fine and expected; faking the "RTN" mark itself with typed letters is not. A text-placeholder logo on any deliverable is a bug.

The V2 logo is a monogram. "RTN" set in Fraunces variable at weight 700, opsz 144, SOFT 0, WONK 0. The variable axes are pinned so the mark is deterministic across rebuilds. The display cut (opsz 144) is non-negotiable: the body cut (opsz 9) renders chunky and loses the high-contrast strokes that make Fraunces feel like Fraunces. No descriptor baked into the SVG, no border, no container shape.

The full "RUN THE NUMBERS®" descriptor is not exported as a flattened asset. It gets composed live in HTML/CSS using Fraunces and Geist on the surfaces that need it — hero sections, document covers, presentation title slides. Composition rules: "RTN" in Fraunces variable at weight 500, opsz 144, letter-spacing 0.05em. "RUN THE NUMBERS®" underneath in Geist (not Mono), weight 500, uppercase, letter-spacing 0.5em. RTN cap height roughly 5x the descriptor cap height. Optical spacing between the two lines about half the descriptor cap height. The ® lives on the descriptor only — never on the three-letter monogram, because only the full registered string "Run The Numbers®" is protected.

Canonical decision record: the vault note **Brand & Visual System**. The original Notion page went with the workspace decommission, so this file is the source of truth for the mark; the vault holds the decision history behind it.

### Asset structure

Everything lives in `logo-redesign/` of this repo.

**SVGs (5 variants)** — `logo-redesign/svg/`. Monogram-only, no descriptor.

- `RTN_Logo_Warm_Ink.svg` (`#1B1A17`) — Warm Ink. Default for Canvas Cream or other light surfaces. The everyday version.
- `RTN_Logo_Ledger_Blue.svg` (`#2B4A7C`) — Ledger Blue. Brand-forward placement: hero sections, primary marketing surfaces.
- `RTN_Logo_Canvas_Cream.svg` (`#FAF7F2`) — Canvas Cream. Reversed out for use on Ledger Blue, Warm Ink, or photographic backgrounds.
- `RTN_Logo_Black.svg` (`#000000`) — Pure black. For mono print, faxes, situations where colour fidelity isn't guaranteed.
- `RTN_Logo_White.svg` (`#FFFFFF`) — Pure white. For dark backgrounds where Canvas Cream washes out.

**PNG raster fallbacks (9 files)** — `logo-redesign/png/`. Three sizes (X1, X2, X4) for each of the three brand-coloured variants: Ledger Blue, Canvas Cream, Warm Ink. Naming: `RTN_Logo_{Variant}_{Size}.png` (e.g. `RTN_Logo_Ledger_Blue_X2.png`). Black and White PNGs are a known gap, tracked separately.

Use SVG by default. PNGs are for placements that can't take vector: email signatures, some document embeds, social profile pictures, third-party platforms with patchy SVG support.

Canonical raw URL pattern: `https://raw.githubusercontent.com/RTN-Digital/rtn-brand-assets/main/logo-redesign/svg/RTN_Logo_{Variant}.svg`.

### When to use the lockup vs the monogram

Use the live-composed lockup (RTN + descriptor) on hero sections, document covers, presentation title slides, large marketing surfaces — anywhere the descriptor is legible at its rendered size. Implement as live HTML/CSS using Fraunces + Geist webfonts, not as a flattened SVG, so the descriptor stays inside the type system and reflows with context.

Use a monogram SVG alone on nav bars, footers, small interface placements, embroidery, app-icon contexts — anywhere the descriptor would be illegible or visually cluttered. Below roughly 32px wordmark height, always drop the descriptor.

### Favicon

Currently a known gap. The previous `favicon-{display,small}.svg` and PNG pack (16, 32, 48, 64, 128, 180, 256) were deleted in the 2026-05-25 clean replacement. Regeneration is tracked as a separate task.

Spec stays: full "RTN" letters in Canvas Cream on a Ledger Blue rounded square. Not a lone R (reads as any R-brand at favicon scale — Reddit, Roblox, R Studio, Rolls Royce). All three letters pin the brand. Two cuts needed: a display cut (Fraunces opsz 144 weight 500) for 64-180px+ contexts including home-screen icons and PWA install, and a small cut (Fraunces opsz 9 weight 700) for 16-32px where letterforms need extra weight to survive. PNG raster fallbacks at 16/32/48/64/128/180/256 cover browsers with patchy SVG favicon support.

### Placement

- Title/cover slide: upper-third, centred or left-aligned, 1.5-2.5" wide.
- Content slide: bottom-right corner, 0.8-1.2" wide, 100% opacity.
- PDF cover: centred, 2-3" wide.
- PDF header (subsequent pages): top-right, 0.6-0.8" wide.
- Word cover: centred, 50mm wide.
- Word header (subsequent pages): top-left, 25mm wide.
- Web / app: header bar, 140-180px wide.

Never:

- Stretch, distort, skew, or rotate the logo.
- Recolour outside the five approved variants.
- Add shadows, glows, gradients, or any effects.
- Place on a busy or cluttered background.
- Use smaller than 0.5" wide (or 80px on web).
- Reduce opacity below 100%.
- Replace with a text-based placeholder when logo files are accessible.
- Bake the "RUN THE NUMBERS®" descriptor into a fresh SVG. Always compose it live in HTML/CSS.

## Do's and Don'ts

**Do**

- Use Ledger Blue sparingly. One accent per slide or section is enough.
- Lead with the number when presenting data. Make it huge, blue, alone — in Fraunces.
- Use the warm cream canvas (#FAF7F2) as the default background, not pure white.
- Use whitespace generously. Cramped layouts signal desperation.
- Write in fragments on slides. Max 30 words per slide (excluding labels).
- Pair Fraunces (headings) with Geist (body). This is the only approved pairing.
- Anonymise client names unless permission is explicitly given.
- Brand naming. Use the full "Run The Numbers®" (with the registered mark) on first mention per page or document, in the footer copyright, and in high-impact moments where the full name earns its weight (homepage hero, case study titles). After first mention, "RTN" is fine throughout, including on the public site — it reads cleaner and avoids repetition. The ® belongs only to the full "Run The Numbers®" string, never to the RTN monogram. "Free Audit" has no registered mark. "RTN Digital" is the legal entity only and never appears as the public-facing brand.

**Don't**

- Don't use pure black (#000000) anywhere. Always text-primary (#1B1A17).
- Don't use pure white (#FFFFFF) as a page background. Always bg-canvas (#FAF7F2) for the outermost surface. White is for cards and inputs sitting on top of canvas.
- Don't use Ledger Blue (#2B4A7C) as a large background fill. It's an accent. Use accent-deep (#142544) for dark sections.
- Don't use the old V1 green (#1aa260) or gunmetal (#121212) — those are retired.
- Don't use Nourd — it has been replaced by Fraunces + Geist.
- Don't mix more than three colours on a single surface.
- Don't use stock photography of handshakes, pointing at screens, or generic "business people".
- Don't use clip-art, drop shadows, gradients, or skeuomorphic effects.
- Don't use emojis in branded deliverables.
- Don't use any of these phrases: "it's never been easier/harder", "here's the truth", "nobody tells you", "in a world where", "game-changer", "unlock", "leverage" (as a verb), "deep dive", "low-hanging fruit", "synergy", "best-in-class", "seamless", "empower", "cutting-edge", "revolutionise", "holistic".
- Don't mix font families beyond the Fraunces + Geist pairing within a document.
- Don't use default Word or Excel table styling — always Ledger Blue header row, warm raised (#F4EFE6) zebra striping, subtle borders (#E8E1D3).
- Don't stretch, distort, recolour, or add effects to the logo.
